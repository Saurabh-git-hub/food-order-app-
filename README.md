# 🍽️ Food Order App

A **Full Stack Food Ordering Web App** built with **Next.js**, **Tailwind CSS**, **Clerk**, and **HyGraph**. This project enables users to explore dishes, authenticate securely, and place orders with real-time feedback.

---

## [🚀 Live Demo](https://food-order-app-2-saurabh-git-hubs-projects.vercel.app/) 


## 📸 Cover Image

![Home Page](./Image%20Food%20Order/home%20.png)

---

## ✨ Features (Step-by-Step Guide)

A walkthrough of the entire food ordering journey with screenshots for each step.

---
### 🏠 1. Home Page – Explore Dishes

Users land on the homepage where they can browse through delicious food items.
- Browse a variety of delicious food items.
- Clean and responsive UI powered by Tailwind CSS.
- Food items loaded from Headless CMS (HyGraph).

![Home Page](./Image%20Food%20Order/home%20.png)

### 🔐 2. Login Page

Users authenticate securely via Clerk.
- Auth handled by **Clerk** with secure login/signup.
- Google Sign-In for fast onboarding.
- Redirects to home after successful login.

![Login](./Image%20Food%20Order/login%20.png)

![Home Page Extended](./Image%20Food%20Order/home%202%20.png)

---

### 👤 3. User Profile

Users can manage their personal profile.
- Displays user profile info and profile picture.
- Shows order history (optional expansion).
- Managed by Clerk authentication session.

![Profile](./Image%20Food%20Order/profile%20.png)

---

### 🛍️ 4. Place Your Order

Users add items to the cart and proceed to order placement.
- Add/remove items with real-time cart updates.
- Displays price, quantity, and total amount.
- User-friendly layout for faster checkout.

![Order Page](./Image%20Food%20Order/order.png)

---

### 📝 5. Submit Review

Users can rate and review food items after ordering.
- Add star-based ratings and write reviews.
- Helps improve trust and engagement.

![Review 1](./Image%20Food%20Order/review%20.png)
![Review 2](./Image%20Food%20Order/review%202.png)
![Review 3](./Image%20Food%20Order/review%203.png)

---

### 💳 6. Payment Page

User sees detailed payment information and chooses the payment method.
- Shows breakdown of items and delivery charges.
- Secure payment flow ensures order reliability.

![Payment Page](./Image%20Food%20Order/payment.png)

---

### 🎯 7. Final Payment Confirmation

Confirmation page shown after successful payment.
- Confirmation of successful order placement.
- Order summary and thank you message.
- Guides user back to homepage or order history.

![Final Payment](./Image%20Food%20Order/final%20payment.png)

---

### 🎬 Demo Video

Watch the app in action with a full video walkthrough:

https://github.com/user-attachments/assets/880696fa-5bea-4737-8339-35e9334b1966

---

## ✨ Key Features (Step-by-Step)

1. **🔐 Authentication with Clerk**
   - Secure login/signup.
   - Session management using Clerk.
   - Personalized user dashboard.

2. **🍱 Browse and Select Food**
   - Displays categories and food items.
   - Filter and explore popular dishes.
   - Fully responsive UI.

3. **🛒 Add to Cart & Order**
   - Users can add items to cart.
   - Seamless checkout flow.
   - Loading state feedback and error validation.

4. **📧 Email Notifications**
   - Users receive email confirmation for orders.
   - Integrated email template support.

5. **📊 Real-time Feedback**
   - Loading indicators and validation using **Zod**.
   - Queries managed using **React Query** for performance.

---

## 🛠️ Technologies Used

| Tech             | Description                                |
|------------------|--------------------------------------------|
| ![Next.js](https://img.shields.io/badge/Next.js-000?logo=next.js&logoColor=white) | React Framework for SSR & routing |
| ![Tailwind](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwindcss&logoColor=white) | Utility-first CSS framework       |
| ![Clerk](https://img.shields.io/badge/Clerk-3A0CA3?logo=clerk&logoColor=white) | Authentication & user management |
| ![HyGraph](https://img.shields.io/badge/HyGraph-000000?logo=graphql&logoColor=white) | Headless CMS                      |
| ![React Query](https://img.shields.io/badge/React%20Query-FF4154?logo=reactquery&logoColor=white) | Data fetching & caching           |
---


**Food Order App** solves this by offering:

- Secure login and real-time cart updates.
- Smooth UX with loading states and form validation.
- API-based, serverless infrastructure to reduce latency.

---

## 🖥️ Project Structure

```bash
food-order-app/
├── (auth)/                  # Authentication using Clerk
├── (routes)/                # App routes
├── _components/             # UI components
├── _context/                # Context API for state
├── _utils/                  # Utility functions
├── api/send-email/          # API endpoint to send emails
├── components/              # Custom components
├── emails/                  # Email templates
├── lib/                     # Logic & DB handlers
├── public/                  # Static files (images, icons)
│   └── home.png             # Homepage screenshot
├── .env                     # Environment variables
├── .gitignore
├── README.md
├── middleware.js
├── next.config.mjs
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.js

---
```

---
## ⚙️ Installation & Setup
✅ Prerequisites
- Node.js & npm installed

- Git installed

- .env file configured
--
# 🚀 Setup Instructions

1. Clone the repository
git clone https://github.com/Saurabh-git-hub/food-order-app-.git

2. Navigate into the project directory
cd food-order-app-

3. Install dependencies
npm install

4. Run the development server
npm run dev

---

## 🧑‍💻 Usage Instructions
Visit the app at http://localhost:3000/.

- Sign up or log in using Clerk authentication.

- Browse dishes and add to your cart.

- Place an order to see checkout confirmation and email notification.

---
• [📁 GitHub Repo](https://github.com/Saurabh-git-hub/food-order-app-)
--

## 👨‍💻 Contributors

| Name | GitHub Profile |
|------|--------------|
| Saurabh | [GitHub](https://github.com/Saurabh-git-hub) |

---

## 📜 License
This project is licensed under the **MIT License**.

---
  ## 📧 **Contact**  

Feel free to reach out for any queries or suggestions:  
- **Developer:** Saurabh  
- **Email:** saurabh20002004@gmail.com  

---
Thanks 🙂
---

### ⭐ Don't forget to **star** the repo if you like it! ⭐

