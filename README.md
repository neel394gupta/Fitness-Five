# 🏋️ THE FITNESS FIVE – Gym Website
THE FITNESS FIVE is a modern gym website built with React and Tailwind CSS, featuring membership plans, trainer profiles, galleries, Google Sheets CMS, WhatsApp integration, and lead generation forms.

## 🚀 Features

### Frontend

* Modern Gym Landing Page
* Responsive Design (Mobile, Tablet, Desktop)
* Animated Hero Section
* Membership Plans
* Trainer Showcase
* Transformation Gallery
* Testimonials Section
* Contact Page
* WhatsApp Integration

### CMS Integration

* Google Sheets powered content management
* Dynamic Membership Plans
* Dynamic Trainer Profiles
* Dynamic Testimonials
* Dynamic Gallery Images

### Lead Generation

* Free Trial Form
* Membership Enquiry Form
* Google Forms Integration
* WhatsApp Click-to-Chat

### SEO

* React Helmet SEO
* Meta Tags
* Sitemap Support
* Robots.txt

### Deployment

* Vercel Ready
* Environment Variables Support
* Production Build Configuration

---

## 🛠 Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS
* React Router
* React Helmet Async
* Lucide React Icons

### Integrations

* Google Sheets API
* Google Forms
* Google Drive
* Google Maps Embed
* WhatsApp API

---

## 📂 Project Structure

```text
src/
│
├── components/
│   ├── Navbar.jsx
│   ├── Hero.jsx
│   ├── MembershipCards.jsx
│   ├── Trainers.jsx
│   ├── Gallery.jsx
│   ├── Transformations.jsx
│   ├── FreeTrialForm.jsx
│   ├── ContactSection.jsx
│   ├── WhatsAppButton.jsx
│   └── SEO.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── About.jsx
│   ├── Programs.jsx
│   └── Contact.jsx
│
├── services/
│   ├── googleSheets.js
│   └── googleForms.js
│
└── App.jsx
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/fitness-five.git
cd fitness-five
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
VITE_GOOGLE_SHEET_ID=YOUR_GOOGLE_SHEET_ID
VITE_GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
```

---

## 📊 Google Sheets CMS Setup

Create the following sheets:

### Membership

| Plan | Price | Duration |
| ---- | ----- | -------- |

### Trainers

| Name | Specialization | Experience | Image |
| ---- | -------------- | ---------- | ----- |

### Gallery

| Image |
| ----- |

### Testimonials

| Name | Review | Rating |
| ---- | ------ | ------ |

### Transformations

| Name | Before | After | Result |
| ---- | ------ | ----- | ------ |

Publish the sheet and connect it using the Google Sheets API.

---

## 📍 Gym Information

**THE FITNESS FIVE**

Address:
D-73, Above IDBI Bank, Near Sai Mandir,
Kamla Nagar, Agra, Uttar Pradesh 282005

Phone:
+91 72539 42000

Hours:
Monday – Saturday

* 6:00 AM – 10:00 AM
* 5:00 PM – 10:00 PM

---

## 🌐 Deployment

### Vercel

```bash
npm install -g vercel
vercel
```

Production Build:

```bash
npm run build
```

---

## 📈 Future Enhancements

* Admin Dashboard
* Google Reviews API
* Instagram Feed Integration
* Online Membership Payments
* Attendance Tracking
* AI Workout Recommendation System
* Nutrition Planner
* Analytics Dashboard

---

## 📄 License

This project is intended for educational and commercial use by THE FITNESS FIVE.

---

### Developed with ❤️ using React + Tailwind CSS
