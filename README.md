# 🌟 Sage

**Sage** is a full-stack platform where users can create, organize, and share meaningful life lessons, personal growth insights, and wisdom. The platform allows users to save lessons, explore public wisdom, and upgrade to premium for exclusive content.

---

## 🔗 Live Website

[Visit Sage]()
[Live Server]()

---

## 🖥️ Features

- **User Authentication:** Secure email/password and Google login.
- **Premium Access:** Upgrade via Stripe to unlock premium lessons and features.
- **Lesson Management:** Create, update, delete, and save lessons with visibility control (Public / Private) and access level (Free / Premium).
- **Public Lessons Browser:** Explore wisdom from the community with search, filter, and sort options.
- **Favorites & Reactions:** Save lessons to favorites and react to others’ lessons in real-time.
- **Dashboard:** Personal dashboard showing stats, recent lessons, and quick actions.
- **Admin Panel:** Manage users, moderate lessons, and track platform-wide analytics.
- **Responsive Design:** Fully optimized for mobile, tablet, and desktop views.
- **Beautiful UI:** Modern, visually appealing design with consistent typography, spacing, and buttons.

---

## 📚 Key Pages

- **Home:** Hero banner, featured lessons, top contributors, and popular lessons.
- **Login / Register:** Secure authentication with Google login option.
- **Add Lesson / My Lessons / Update Lesson:** Full CRUD operations for lessons (Protected routes).
- **Public Lessons:** Browse community lessons with filters, sorting, and premium access handling.
- **Lesson Details:** Full lesson view with likes, comments, and save functionality.
- **Pricing / Upgrade:** Compare Free vs Premium plans and checkout via Stripe.
- **Payment Success / Cancel Pages**
- **Favorites:** Personalized collection of saved lessons.
- **Dashboard (User + Admin):** Analytics, quick actions, and admin moderation tools.
- **404 / Not Found:** Friendly error page with navigation options.

---

## ⚡ Highlights

- **Premium Badge:** Shows instantly after successful upgrade.
- **Real-time UI Updates:** Likes, favorites, and premium content update without page reload.
- **Token Verification:** Secure backend using Firebase Admin SDK.
- **Search, Filter, and Sort:** Dynamic filtering of public lessons by category, emotional tone, and keywords.
- **Pagination:** Efficient navigation of public lessons.
- **Lottie Animations:** Engaging visual feedback when adding lessons or performing actions.

---

## 💡 Tech Stack

- **Frontend:** React, React Router, Tailwind CSS, Lucide Icons
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** Firebase Auth, JWT
- **Payments:** Stripe (Test Mode)
- **State Management:** React hooks & Context API
- **Hosting / Deployment:** Netlify (Frontend), Vercel (Backend)

---

## 🏆 Achievements

- Fully dynamic premium subscription system with Stripe integration
- Real-time UI updates for lesson interactions
- Admin moderation dashboard for lessons and users
- Beautiful, consistent, and professional UI design
- Responsive layout across devices

---

## 📂 Repository Structure

sage-client/
├── README.md
├── package.json
├── .env
├── .gitignore
├── public/
│ ├── index.html
│ ├── favicon.ico
│ └── assets/
│ ├── images/
│ └── icons/
├── src/
│ ├── index.jsx
│ ├── App.jsx
│ ├── setupTests.js
│ ├── styles/
│ │ ├── globals.css
│ │ └── theme.css
│ ├── components/
│ │ ├── Navbar.jsx
│ │ ├── Footer.jsx
│ │ ├── Loader.jsx
│ │ ├── LessonCard.jsx
│ │ ├── CommentBox.jsx
│ │ └── ...
│ ├── hooks/
│ │ ├── useAuth.js
│ │ ├── useAxios.js
│ │ ├── useAxiosSecure.js
│ │ ├── usePremium.js
│ │ └── ...
│ ├── contexts/
│ │ ├── AuthContext.jsx
│ │ └── PremiumContext.jsx
│ ├── layouts/
│ │ ├── MainLayout.jsx
│ │ └── DashboardLayout.jsx
│ ├── pages/
│ │ ├── Home/
│ │ │ ├── Home.jsx
│ │ │ └── HeroSection.jsx
│ │ ├── Auth/
│ │ │ ├── Login.jsx
│ │ │ └── Register.jsx
│ │ ├── Lessons/
│ │ │ ├── AddLesson.jsx
│ │ │ ├── MyLessons.jsx
│ │ │ ├── UpdateLesson.jsx
│ │ │ ├── PublicLessons.jsx
│ │ │ └── LessonDetails.jsx
│ │ ├── Favorites/
│ │ │ └── Favorites.jsx
│ │ ├── Pricing/
│ │ │ ├── Pricing.jsx
│ │ │ ├── PaymentSuccess.jsx
│ │ │ └── PaymentCancel.jsx
│ │ ├── Dashboard/
│ │ │ ├── DashboardHome.jsx
│ │ │ ├── Profile.jsx
│ │ │ └── user-specific pages…
│ │ ├── Admin/
│ │ │ ├── ManageUsers.jsx
│ │ │ ├── ManageLessons.jsx
│ │ │ ├── ReportedLessons.jsx
│ │ │ └── ...
│ │ ├── Contact.jsx
│ │ ├── NotFound.jsx
│ │ └── Loading.jsx
│ ├── services/
│ │ ├── authService.js
│ │ ├── lessonService.js
│ │ └── paymentService.js
│ ├── utils/
│ │ ├── formatDate.js
│ │ └── constants.js
│ ├── assets/
│ │ ├── images/
│ │ └── lottie/
│ └── routes/
│ └── AppRoutes.jsx
└── tailwind.config.js

---

## ✅ Notes

- No Lorem Ipsum was used; all content is meaningful.
- Error and success messages are implemented with SweetAlert & React Hot Toast.
- Credentials are secured using environment variables.
- All frontend routes are reload-safe, and protected routes are secure.
- Minimum commit counts achieved: 20 on client-side, 12 on server-side.

---

## 📌 Future Enhancements (Optional)

- Dark/Light theme toggle
- Export lessons as PDF
- Social sharing of lessons (Facebook, LinkedIn)
- Enhanced analytics and charts for admin dashboard

---

## 🎯 Conclusion

Digital Life Lessons empowers users to **preserve their wisdom**, **learn from others**, and **grow together**. With premium content, interactive dashboards, and community moderation, it provides a modern and engaging experience for personal growth enthusiasts.

---

> Developed by: **Raiyan Sohel**
> GitHub: [My GitHub](https://github.com/RaiyanSohel-byte)
