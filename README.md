# Hari Jewelers Online Store 🛍️

![Hari Jewelers Logo](https://via.placeholder.com/150x50?text=Hari+Jewelers) <!-- Add your logo here -->

A modern and secure e-commerce platform for Hari Jewelers, offering a complete online shopping experience for jewelry enthusiasts.

## ✨ Features

### 👨‍💼 Customer Side
- 🔐 Secure user registration and login system
- 🔄 Password recovery functionality
- 🔍 Advanced product search and filtering
- 📸 High-quality product images with zoom functionality
- 🛒 Smart shopping cart with real-time updates
- 💳 Multiple payment options (Zelle, Stripe, PayPal)
- 📦 Order tracking and status updates
- 📱 Mobile-responsive design
- ⭐ Product reviews and ratings
- 💝 Wishlist functionality

### 👨‍💻 Admin Side
- 🔒 Secure admin dashboard
- 📊 Real-time sales analytics
- 📦 Inventory management
- 👥 Customer management
- 💰 Discount and coupon system
- 📈 Sales reports and statistics
- 📝 Order management system

## 🛠️ Tech Stack

- **Frontend:** React.js, Redux, Material-UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **Payment Processing:** Stripe, Zelle
- **Email Service:** Nodemailer
- **Image Storage:** Cloudinary
- **Deployment:** Heroku, Netlify

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/hari-jewelers.git
cd hari-jewelers
```

2. Install dependencies:
```bash
# Install backend dependencies
npm install

# Install frontend dependencies
cd client
npm install
cd ..
```

3. Set up environment variables:
Create a `.env` file in the root directory with the following variables:
```env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/hari-jewelers
JWT_SECRET=your_jwt_secret_key
STRIPE_PUBLIC_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
FRONTEND_URL=http://localhost:3000
```

4. Start the development servers:
```bash
# Start backend server
npm run dev

# Start frontend server (in a new terminal)
cd client
npm start
```

## 📚 API Documentation

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login
- `POST /api/auth/forgot-password` - Password recovery
- `POST /api/auth/reset-password/:token` - Reset password

### Products
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get single product
- `POST /api/products` - Create product (admin)
- `PUT /api/products/:id` - Update product (admin)
- `DELETE /api/products/:id` - Delete product (admin)

### Orders
- `POST /api/orders` - Create order
- `GET /api/orders/my-orders` - Get user orders
- `GET /api/orders/:id` - Get single order
- `PUT /api/orders/:id/status` - Update order status (admin)

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

- 📧 Email: support@harijewelers.com
- 💬 Live Chat: Available on website
- 📱 Phone: [Your Contact Number]
- 🕒 Support Hours: Monday-Friday, 9AM-5PM EST

## 🙏 Acknowledgments

- Thanks to all contributors
- Special thanks to our beta testers
- Inspired by modern e-commerce solutions

---

Made with ❤️ by Hari Jewelers Team
