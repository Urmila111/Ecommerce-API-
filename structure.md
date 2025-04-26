Here’s a detailed folder and file structure for an Ecommerce API using the MVC (Model-View-Controller) pattern with Express and Mongoose, based on all the features you provided:

📁 ecommerce-api/

├── 📁 config/                       # Configuration files
│   ├── db.js                       # Mongoose connection
│   ├── cloudinary.js              # Media storage (e.g., for product images)
│   ├── paymentGateways.js         # Stripe/PayPal config
│   └── env.js                     # Environment variable setup
│
├── 📁 controllers/                 # Controllers handle business logic
│   ├── authController.js
│   ├── userController.js
│   ├── productController.js
│   ├── categoryController.js
│   ├── brandController.js
│   ├── couponController.js
│   ├── paymentController.js
│   ├── reviewController.js
│   ├── orderController.js
│   ├── cartController.js
│   ├── wishlistController.js
│   └── shippingController.js
│
├── 📁 models/                      # Mongoose models (MongoDB schemas)
│   ├── User.js
│   ├── Product.js
│   ├── Category.js
│   ├── Brand.js
│   ├── Coupon.js
│   ├── Review.js
│   ├── Order.js
│   ├── Cart.js
│   ├── Wishlist.js
│   └── ShippingMethod.js
│
├── 📁 routes/                      # Express routes
│   ├── authRoutes.js
│   ├── userRoutes.js
│   ├── productRoutes.js
│   ├── categoryRoutes.js
│   ├── brandRoutes.js
│   ├── couponRoutes.js
│   ├── paymentRoutes.js
│   ├── reviewRoutes.js
│   ├── orderRoutes.js
│   ├── cartRoutes.js
│   ├── wishlistRoutes.js
│   └── shippingRoutes.js
│
├── 📁 middlewares/                # Middleware functions
│   ├── authMiddleware.js          # Authentication and role-based access
│   ├── errorMiddleware.js         # Error handling
│   ├── validateMiddleware.js      # Input validation
│   └── uploadMiddleware.js        # For uploading images/files
│
├── 📁 utils/                       # Utility/helper functions
│   ├── generateToken.js           # JWT generation
│   ├── sendEmail.js               # For password reset or notifications
│   ├── couponUtils.js             # Discount calculations
│   └── paymentUtils.js            # Payment processing logic
│
├── 📁 services/                   # Business logic or 3rd party APIs
│   ├── paymentService.js          # Integration with Stripe/PayPal
│   ├── shippingService.js         # Logic for shipping calculations
│   └── refundService.js           # Refund operations
│
├── 📁 views/                      # (Optional for APIs) Swagger or API documentation
│   └── docs.ejs
│
├── 📁 tests/                      # Unit and integration tests
│   ├── product.test.js
│   ├── user.test.js
│   ├── order.test.js
│   └── ...
│
├── .env
├── .gitignore
├── app.js                         # Main Express app
├── server.js                      # Entry point
├── package.json
└── README.md
