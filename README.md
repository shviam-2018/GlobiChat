# GlobiChat  

A **Next.js-powered** global communication platform integrating **real-time messaging, social media, payments, and mini-programs**—designed as a WeChat alternative for the international market.  

---

## 🚀 Tech Stack  

- **Frontend:** Next.js (App Router), TypeScript  
- **Backend:** Prisma (PostgreSQL), Server Actions, API Route Handlers  
- **Authentication:** Clerk for user authentication & authorization  
- **Styling:** Tailwind CSS, Shadcn  
- **File Storage:** UploadThing for file uploads  
- **Optimizations:** Data Fetching, Caching, Optimistic Updates  

---

## 📌 Mini Tasks  

### 🔹 **Project Setup**  
- Initialize a Next.js project with TypeScript  
- Set up folder structure: `pages/`, `components/`, `styles/`, `utils/`  
- Configure **Tailwind CSS & Shadcn** for styling  

### 🔹 **Authentication & Security**  
- Integrate **Clerk** for authentication & authorization  
- Implement **JWT-based authentication** for API security  
- Set up **OAuth login** (Google, Apple, etc.)  
- Create **user profile & settings page**  

### 🔹 **Messaging System**  
- Build **real-time chat** using Server Actions  
- Implement **group chats** (up to 500 users)  
- Add support for **voice & video calls**  
- Encrypt **end-to-end messaging**  

### 🔹 **Social Features (Moments & Status Updates)**  
- Develop **social feed** (post images, videos, and status updates)  
- Implement **likes, comments, and shares**  
- Add **privacy controls** for posts  

### 🔹 **QR Code System**  
- Implement **QR code login & user authentication**  
- Create **QR-based friend requests**  
- Develop **QR code payments & transactions**  

### 🔹 **Payments & GlobiPay System**  
- Implement **fake currency transactions (for now)**  
- Support **real-time currency conversion**  
- Design **animated transaction confirmations**  
- Integrate **QR code-based payments & requests**  

### 🔹 **Database & API Setup**  
- Set up **PostgreSQL with Prisma ORM**  
- Implement **Server Actions for API integration**  
- Optimize **data fetching, caching & revalidation**  

### 🔹 **Error Handling & UX Enhancements**  
- Configure `loading.tsx`, `error.tsx`, and `not-found.tsx` pages  
- Implement **optimistic UI updates**  
- Ensure **seamless navigation with dynamic & static routes**  

---

## 📜 How to Run Locally  

```sh
git clone https://github.com/your-repo/globichat.git
cd globichat
npm install
npm run dev
