# 🧠 MindClouds

> A mindful MERN stack web app where you can **rain your thoughts**, **capture emotions**, and **reflect** — in your own private cloud.

---

### ✨ Highlights

- 🧱 **Full-Stack App** built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js)
- 🧠 **Purpose-Driven UI** to help users **vent their thoughts** and keep track of emotional patterns
- 📝 Create, update, and delete entries with a **Title & Thought**
- 🛠️ Fully functional **REST API** with custom routes, controllers, and error handling
- ⚙️ Integrated **Rate Limiting** using **Upstash Redis**
- 📱 **Fully Responsive** design
- 🚀 **Ready for Deployment** with environment variable support and deployment guide included
- 🌐 Learn key web dev concepts: HTTP methods, status codes, REST APIs, NoSQL vs SQL
- 🔐 Secure `.env` config with MongoDB Atlas + Upstash Redis keys

---

## 🌈 Why MindClouds?

MindClouds isn’t just a note-taking app — it’s your **personal mental space**.  
Use it to:

- **Vent your thoughts freely** — no filter, no judgment.
- Track emotional states and recurring thoughts over time.
- Reflect on what's been troubling you.
- Share your journal with a professional — or keep it just for you.

> Because writing it down is the first step to feeling better.

---

## 🗂️ Folder Structure

```

MindClouds/
├── backend/      # Express + MongoDB + Redis API
├── frontend/     # React + Tailwind frontend
├── .env          # Environment variables (see below)
├── README.md     # You’re reading it!

````

---

## 🔧 .env Setup

Create a `.env` file inside `/backend` with the following:

```env
MONGO_URI=<your_mongo_uri>
UPSTASH_REDIS_REST_URL=<your_redis_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_token>
NODE_ENV=development
````

---

## 🚀 Getting Started

### 📦 Run the Backend

```bash
cd backend
npm install
npm run dev
```

### 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```

> The app will be live on `http://localhost:5173` by default.

---

## 🧪 Key Features

* **Create Cloud (Thought)** — Vent what’s on your mind
* **Edit / Update Cloud** — Refine or reflect later
* **Delete Cloud** — Clean out old thoughts
* **Rate Limiting** — Protect your mental space and server traffic
* **Responsive UI** — Works across devices

---

## 🌍 Deployment Guide

Coming soon! *(or link your live project once deployed)*

You can deploy the **backend to Render or Railway** and the **frontend to Vercel or Netlify**.

---

## 🙋‍♀️ Author

**Karishma Santani**
Student @ IIT BHU | Web Dev Enthusiast | Mental Health Advocate
GitHub: [@codingkarishma](https://github.com/codingkarishma)

---

## 📄 License

This project is open-source under the MIT License.
Feel free to build, modify, or contribute — just don’t forget to **be kind to your mind.** ☁️

---

```
💭 “MindClouds is your space to think, vent, reflect, and grow.”
```

```
