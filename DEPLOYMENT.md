# 🎓 Student Wellness Hub - Complete Documentation

## Project Overview

The **Student Wellness Hub** is a complete frontend web application built with React and Vite that provides comprehensive wellness and health management for students.

## Repository Structure

```
Front-1/
├── front/fedfp22/student-wellness-hub/    ← Main project folder
│   ├── src/                               ← Source code
│   ├── public/                            ← Static assets
│   ├── package.json                       ← Dependencies
│   ├── vite.config.js                    ← Vite configuration
│   ├── README.md                         ← Project documentation
│   └── index.html                        ← HTML entry point
└── (Other project files)
```

## Quick Start

### Clone and Setup
```bash
git clone https://github.com/Lekha1657/Front-1.git
cd Front-1/front/fedfp22/student-wellness-hub
npm install
npm run dev
```

### Access the Application
- **URL**: http://localhost:5173
- **Admin Demo**: Email: `admin@school.edu` | Password: `admin123`

## Key Components

| Component | Purpose |
|-----------|---------|
| **App.jsx** | Main application shell, state management |
| **Home.jsx** | Dashboard, program browsing, resources |
| **Calendar.jsx** | Month view calendar, reminders |
| **Appointments.jsx** | List and manage booked sessions |
| **Profile.jsx** | User information and participation history |
| **AdminDashboard.jsx** | Program management interface |
| **Login.jsx / Signin.jsx** | Authentication pages |

## Features at a Glance

✅ **15+ Wellness Programs**
- Mental Health (meditation, counseling, stress management)
- Fitness Programs (running, yoga, strength training)
- Nutrition Advice (meal planning, cooking workshops, dietary guidance)

✅ **Calendar with Reminders**
- Full month view calendar
- Create custom reminders
- Upcoming events list
- Visual indicators for appointments and reminders

✅ **Appointment Booking**
- 9 professional session types
- Schedule with doctors, therapists, coaches, nutritionists
- Date/time selection
- Appointment tracking

✅ **User Authentication**
- Sign up and login
- Admin-only access control
- Persistent sessions (localStorage)
- Client-side password hashing

✅ **Responsive Design**
- Mobile-first approach
- Dark mode support
- Smooth animations
- Touch-friendly interface

## Technology Stack

- **React 19.x** - UI Framework
- **Vite 7.x** - Build tool & dev server
- **CSS3** - Styling with CSS variables
- **localStorage** - Data persistence
- **SHA-256** - Client-side password hashing

## Data & Storage

### Mock Data Included
- 15+ pre-loaded wellness programs
- 9 professional sessions (doctors, therapists, coaches, nutritionists)
- 1 seeded admin account

### localStorage Keys
```javascript
swh_programs      // Wellness programs
swh_users         // User accounts
swh_current_user  // Active user
swh_user          // User profile
swh_calendar      // Calendar events
swh_appointments  // Booked appointments
swh_reminders     // User reminders
swh_dark          // Theme preference
```

## Important Notes

⚠️ **Security Notice**
- This is a **frontend demo** application
- Password hashing is **client-side only** (not production-safe)
- No backend server or database
- For production, implement:
  - Backend authentication server
  - Server-side password hashing
  - Database integration
  - HTTPS/TLS encryption
  - Session management (JWT/OAuth)

## Available Scripts

```bash
npm run dev       # Start development server
npm run build     # Create production build
npm run preview   # Preview production build
npm run lint      # Run ESLint
```

## Workflows

### 🎯 Join a Program
1. Navigate to Home tab
2. Click "Explore" on any category
3. Click "Join" on a program
4. Button changes to "Joined ✓"
5. Event appears on calendar

### 📅 Book an Appointment
1. Go to Appointments tab
2. Select category and provider
3. Choose date and time
4. Add notes (optional)
5. Click "Book Appointment"

### 🔔 Set a Reminder
1. Navigate to Calendar tab
2. Click "+ Reminder"
3. Enter title, date, time, and type
4. Click "Save Reminder"
5. Reminder appears on calendar

## Color Scheme

### Light Mode
- Background: #f7f9fc (Light Blue Gray)
- Panel: #ffffff (White)
- Text: #0f1724 (Dark Navy)
- Accent: #6366f1 (Indigo)

### Dark Mode
- Background: #0b1220 (Dark Navy)
- Panel: #0f1724 (Dark Slate)
- Text: #e6eef8 (Light Blue)
- Accent: #8b5cf6 (Purple)

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## File Size

- Build size: ~47 KB (gzipped)
- Development size: ~4.6 MB (26 files)

## GitHub Repository

**URL**: https://github.com/Lekha1657/Front-1

**Latest Release**: Main branch - Version 1.0

## Commit History

```
fa702cb - docs: Add comprehensive README
79365d8 - feat: Complete Student Wellness Hub application
```

## Next Steps / Future Enhancements

- [ ] Backend API integration
- [ ] Database (MongoDB/PostgreSQL)
- [ ] Email notifications
- [ ] User profile images
- [ ] Program ratings/reviews
- [ ] Wellness metrics dashboard
- [ ] Calendar export (iCal)
- [ ] Push notifications
- [ ] Mobile app (React Native)

## Support & Contact

- **Developer**: Lekha1657
- **Repository**: https://github.com/Lekha1657/Front-1
- **Issues**: Report via GitHub Issues
- **Discussions**: GitHub Discussions

---

**Version**: 1.0.0  
**Last Updated**: November 30, 2025  
**Status**: ✅ Complete & Deployed to GitHub
