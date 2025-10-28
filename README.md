# Multi-Framework Ticket Web App

Complete ticket management system implementations in React, Vue.js, and Twig.

## 📁 Project Structure

```
PRACTICAL PROJECT/
├── Static UI/              # Original static HTML/CSS prototype  
├── ticket-app-react/       # React implementation ✅
├── ticket-app-vue/         # Vue.js implementation ✅
├── ticket-app-twig/        # Twig implementation ✅
└── README.md              # This file
```

## 🚀 Quick Start

### React Version
```bash
cd ticket-app-react
npm install
npm run dev
```
Visit 

### Vue.js Version
```bash
cd ticket-app-vue
npm install
npm run dev
```
Visit `http://localhost:5174`

### Twig Version
```bash
cd ticket-app-twig
composer install
php -S localhost:8000 -t public
```
Visit `http://localhost:8000`

## ✨ Features (All Implementations)

- ✅ Landing page with animated SVG waves
- ✅ Login & Signup with validation
- ✅ Protected dashboard with statistics
- ✅ Full CRUD ticket management
- ✅ LocalStorage/session persistence
- ✅ Toast notifications
- ✅ Responsive design (max-width: 1440px)
- ✅ Status color coding (Open/In Progress/Closed)

## 🔐 Test Credentials

- **Email:** admin@ticketapp.com  
  **Password:** admin123

- **Email:** user@test.com  
  **Password:** password123

## 📋 Task Requirements Checklist

### ✅ Core Features
- [x] Landing page with wavy background
- [x] Decorative circles and box sections
- [x] Authentication (Login/Signup)
- [x] Dashboard with statistics
- [x] Ticket CRUD operations
- [x] Form validation
- [x] Error handling
- [x] Protected routes
- [x] Session management (localStorage: `ticketapp_session`)

### ✅ Design Consistency
- [x] Max-width: 1440px centered
- [x] Responsive layout
- [x] Status colors (green/amber/gray)
- [x] Card-style boxes
- [x] Circular decorative elements

### ✅ Validation Rules
- [x] Title: Required
- [x] Status: Required (open/in_progress/closed only)
- [x] Inline error messages
- [x] Toast notifications

### 📝 Documentation
- [x] React README with setup instructions
- [x] Vue README
- [x] Twig README
- [x] Root README (this file)

## 🛠️ Technologies

### React Implementation
- React 19 + React Router
- Vite build tool
- CSS3 with variables
- LocalStorage API

### Vue.js Implementation  
- Vue 3 + Vue Router
- Vite build tool
- Composition API
- Pinia state management

### Twig Implementation
- PHP 7.4+ with Twig 3.0
- Simple PHP routing
- LocalStorage auth (client-side)
- Component-based templates

## 📧 Submission

- Task deadline: Sunday, 26th October 2025 – 11:59 PM (GMT +1)
- Submission form: https://forms.gle/FZ1MXos9xdH9arZdA

## 👤 Author

Built for HNG12 Frontend Stage 2 Task

---

**Note:** Each framework implementation is completely independent and can run standalone.
