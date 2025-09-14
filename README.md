# 🚗 CampusCruz - College Ride Sharing Platform

> A modern ride-sharing platform designed specifically for college students. Connect with fellow students, share rides, and build your campus community while saving money on transportation.

## 📖 What is CampusCruz?

CampusCruz is a comprehensive ride-sharing application that helps college students coordinate transportation to and from campus. Whether you're a driver looking to earn points by offering rides or a student needing a lift, CampusCruz makes campus commuting easier, more affordable, and more social.

## ✨ Key Features

🚗 **Offer Rides** - Share your journey with fellow students and earn points  
🎒 **Find Rides** - Search for available rides that match your schedule  
⭐ **Rating System** - Build trust through user ratings and reviews  
🏆 **Points System** - Earn points for completed rides and maintaining good ratings  
📱 **Real-time Notifications** - Stay updated on ride requests and confirmations  
🔒 **College Verification** - Secure platform limited to verified .edu email addresses  
📍 **GPS Integration** - Easy location sharing with current position detection  

## 🛠️ Tech Stack

### Frontend
- **React.js 18** - Modern UI framework
- **Vite** - Fast build tool and development server
- **Material-UI (MUI)** - Component library for consistent design
- **React Router** - Client-side routing
- **Axios** - HTTP client for API requests
- **Formik & Yup** - Form handling and validation
- **Date-fns** - Date formatting and manipulation

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - Authentication tokens
- **bcryptjs** - Password hashing
- **Express Validator** - Input validation

## 🚀 Getting Started

### Prerequisites
- **Node.js** (version 16 or higher)
- **MongoDB** (local installation or cloud instance)
- **Git** for version control

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/campuscruz.git
   cd campuscruz
   ```

2. **Setup Backend**
   ```bash
   cd backend
   npm install
   # Create .env file with your MongoDB connection string
   echo "MONGODB_URI=your_mongodb_connection_string" > .env
   echo "JWT_SECRET=your_jwt_secret" >> .env
   npm run dev
   ```

3. **Setup Frontend**
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

4. **Access the application**
   - Frontend: `http://localhost:5173`
   - Backend: `http://localhost:5000`

## 🎯 How It Works

### For Drivers
1. **Create an account** with your college email (.edu required)
2. **Offer a ride** by setting your route, time, and available seats
3. **Accept passengers** from incoming requests
4. **Complete the ride** and earn points based on passengers carried
5. **Build your reputation** through passenger ratings

### For Passengers
1. **Sign up** with your verified college email
2. **Search for rides** based on your destination and timing
3. **Request to join** rides that match your needs
4. **Provide pickup location** for driver coordination
5. **Rate your experience** after the ride completion

## 💡 Benefits

### For Students
- **Save Money** - Split transportation costs with other students
- **Reduce Carbon Footprint** - Fewer cars on the road means less emissions
- **Build Connections** - Meet new people and expand your campus network
- **Earn Rewards** - Points system incentivizes good behavior
- **Safe & Secure** - College-only platform with verified users

### For Campus Community
- **Reduced Parking Demand** - Fewer individual cars on campus
- **Enhanced Student Experience** - Easier access to campus events and activities
- **Environmental Impact** - Promotes sustainable transportation choices

## 👨‍💻 Creator

This project was developed by **Ayaan Usmani** and  by **Akshi Dhiman** as a solution to common transportation challenges faced by college students. 

📧 Contact: ayaanusmani2005@gmail.com

## 🔧 Development Scripts

### Frontend
```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
npm run lint     # Run ESLint
```

### Backend
```bash
npm start        # Start production server
npm run dev      # Start development server with nodemon
```

## 🤝 Contributing

Contributions are welcome! If you'd like to improve CampusCruz:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📋 Future Enhancements

- [ ] Mobile app development (React Native)
- [ ] Integration with campus shuttle schedules
- [ ] Advanced matching algorithms
- [ ] In-app messaging system
- [ ] Rewards to be claimed from the points earned
- [ ] Route optimization features

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

Special thanks to the college community for inspiring this project and providing valuable feedback during development.

---

<p align="center">
  <strong>Making campus transportation smarter, one ride at a time</strong> 🎓
</p>


