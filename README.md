# SkyReserve
Java 17 + Spring Boot + JPA/Hibernate + MySQL airline reservation system.

Features: Home, Login/Signup, flight search, available flights, flight selection, dynamic seat availability, passenger details, booking summary, demo payment/confirmation, PNR/Booking ID, and admin dashboard.

Database defaults: jdbc:mysql://localhost:3306/skyreserve, user root, password root. Override DB_URL, DB_USER, DB_PASSWORD environment variables if needed.

Run: `mvn spring-boot:run` then open http://localhost:8080

Admin: admin@skyreserve.com / admin123

Payment is a working demo confirmation stored in MySQL; it does not charge real money. For real payments, connect Razorpay/Stripe/etc. and keep API secrets server-side.
