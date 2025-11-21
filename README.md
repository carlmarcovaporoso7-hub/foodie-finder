# 🍔 Foodie Finder

A modern Django-powered web application designed to help people discover the best restaurants, meals, snacks, and drinks in Naval Proper. Built with a focus on user experience, responsive design, and efficient food discovery.

## ✨ Features

### 🎨 User Experience
- **Professional Landing Page** with animated preloader and smooth transitions
- **Responsive Design** that works perfectly on all devices
- **Toast Notifications** for user feedback and interactions
- **Logout Confirmation Modal** with professional styling
- **Back-to-Top Button** for easy navigation

### 🔍 Smart Search & Discovery
- **Live Search Suggestions** with A-Z food recommendations
- **Category Filters** with icons (🍔 Fast Food, 🍤 Seafood, 🍰 Dessert, etc.)
- **Price Tier Badges** (₱ - Affordable, ₱₱ - Moderate, ₱₱₱ - Expensive)
- **Real-time Status** indicators (Open/Closed with color coding)

### 🏪 Restaurant Management
- **Image Carousel** for browsing restaurant photos
- **Complete Menu System** with prices and categories
- **Operating Hours** display
- **Category Tags** and status badges

### 👥 Role-Based Access Control
- **User Registration** with profile creation
- **Secure Authentication** with automatic role-based redirection
- **Three Dashboard Types:**
  - **Admin Dashboard**: Professional sidebar for system management
  - **Restaurant Dashboard**: For restaurant owners to manage their listings
  - **User Dashboard**: Main Foodie Finder interface for customers

## 🚀 Tech Stack

- **Backend**: Django 5.2.7
- **Database**: SQLite (development) / PostgreSQL (production)
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Custom CSS with Poppins font
- **Icons**: Font Awesome 6.5.0
- **Image Processing**: Pillow
- **Deployment**: Render with WhiteNoise for static files

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8+
- pip package manager

### Local Development
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/foodie-finder.git
cd foodie-finder

# Create virtual environment
python -m venv .venv
.venv\Scripts\activate  # Windows
# source .venv/bin/activate  # macOS/Linux

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser (optional)
python manage.py createsuperuser

# Start development server
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` to access the application.

## 🎯 Usage

### For Users
1. **Register** or **Login** to access the platform
2. **Search** for restaurants using the smart search bar
3. **Filter** by categories, price range, and status
4. **Browse** restaurant details, menus, and photos
5. **Discover** new dining experiences in Naval Proper

### For Restaurant Owners
1. **Login** with restaurant role
2. **Manage** restaurant information and photos
3. **Update** menu items and prices
4. **Set** operating hours and status

### For Administrators
1. **Access** admin dashboard with full system control
2. **Manage** users, restaurants, and content
3. **Monitor** platform activity and statistics
4. **Configure** system settings

## 📱 Key Pages

- **Landing Page**: Modern hero section with call-to-action buttons
- **Main Dashboard**: Search interface with featured restaurants
- **Restaurant Detail**: Complete restaurant information with image carousel
- **About Page**: Platform information and additional resources
- **Admin Console**: Professional management interface

## 🎨 Design Highlights

- **Modern UI/UX** with gradient backgrounds and smooth animations
- **Professional Color Scheme** with consistent branding
- **Mobile-First Approach** ensuring perfect mobile experience
- **Interactive Elements** with hover effects and transitions
- **Professional Typography** using Poppins font family

## 🔧 Configuration

### Admin Access
- **Admin Dashboard**: `/console/`
- **Django Admin**: `/admin/`
- **Default Credentials**: admin / adminpass123

### Environment Variables
- `DEBUG`: Set to `False` in production
- `DATABASE_URL`: PostgreSQL connection string for production

## 🚀 Deployment

The application is configured for easy deployment on Render:

1. **Push** code to GitHub
2. **Connect** repository to Render
3. **Configure** build and start commands
4. **Deploy** automatically with PostgreSQL database

## 📄 License

This project was created for educational purposes and local community use.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues and enhancement requests.

## 📞 Contact

For questions or support, please reach out through the repository issues page.

---

**Made with ❤️ for the Naval Proper food community**