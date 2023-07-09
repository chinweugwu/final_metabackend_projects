    path('menu-items/', views.MenuItems.as_view()),
    path('menu-items/<int:pk>', views.SingleMenuItemView.as_view()),
    path('bookings/', views.BookingItemsView.as_view()),
    path('bookings/<int:pk>', views.SingleBookingItemView.as_view()),
