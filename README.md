# 💸 FinMate – Personal Finance Companion

**FinMate** is a full-featured Laravel-based personal finance management web application that empowers users to track expenses, boost their financial literacy, and receive personalized insights with the help of AI.

## 🚀 Features

### ✅ Financial Quiz Module
- Daily financial literacy quiz with:
  - 10 auto-generated questions via **Google Gemini API**
  - Real-time feedback and scoring
  - AI-powered suggestions for concepts to learn based on wrong answers
  - Ability to share score to feed

### 📊 Expense Tracker
- Add income or expenses manually
- Choose from predefined categories (Food, Rent, Entertainment, etc.)
- See total balance with visual feedback (green for income, red for expense)
- Mock API import functionality simulating card transactions
- Edit or delete transactions with ease

### 📈 AI Financial Insights
- Smart analysis of your financial behavior
- Visual pie charts for expenses & income by category
- Savings rate progress bar
- Natural language insights generated via Gemini API

### 🧵 Social Feed
- Post status updates with or without images
- Like system 
- Feed shows user avatar and time since post

### 👤 Profile
- Upload a profile picture
- View and delete your own posts
- Change profile information

### ✉️ Private Messaging
- Direct messaging system between users
- Conversation list with latest messages
- Fully styled chat interface with timestamps and delivery indicators

## 🛠️ Tech Stack

- **Backend**: Laravel 10, PHP 8+
- **Frontend**: Blade, Alpine.js, Tailwind CSS, Chart.js
- **AI Integration**: Google Gemini API
- **Auth**: Laravel Breeze (Sanctum, Blade-based auth)
- **Database**: MySQL (or any Laravel-supported DB)
- **Storage**: Local storage for profile photos and feed images
- **APIs**: Mock API for card transaction import

## 🧠 AI Features Powered By Gemini API
- Quiz question generation
- Personalized feedback after quiz completion
- Financial insights based on real expenses

## 📦 Installation

```bash
git clone https://github.com/yourusername/finmate.git
cd finmate
composer install
npm install && npm run build
php artisan key:generate
php artisan migrate
php artisan storage:link
php artisan serve
```

> Don't forget to set your `GEMINI_API_KEY` in `.env` to enable AI features.

For a short time(I guess) it can be accessed at finmate.hackathon.aico.dev
