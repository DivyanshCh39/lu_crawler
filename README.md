# 🕷️ LU Crawler — Resource Sharing Platform

A full-stack web platform for students of University of Lucknow to share and access academic resources including notes, question papers, and books.

🌐 **Live Demo:** [lucrawler.vercel.app](https://lucrawler.vercel.app)

---

## 📌 Features

- 📤 Upload and share notes, question papers, and books
- 📥 Download and preview resources
- 🔍 Search and filter by category or keyword
- 🔐 User authentication (Sign up / Login)
- 📱 Fully responsive UI across all devices
- ☁️ Cloud storage for all uploaded files

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js, React.js, TailwindCSS |
| Backend | Supabase (Auth, Database, Storage) |
| Deployment | Vercel |

---

## 🧪 Testing

A complete **Functional Test Plan** has been created for this project covering 25+ test cases across all major modules.

📁 Available in the [`testing/`](./testing/) folder:
- ✅ 25 Functional Test Cases — login, upload, download, search, UI
- ✅ Requirement Traceability Matrix (RTM)
- ✅ Bug Report Log
- ✅ Entry/Exit Criteria
- ✅ Test Summary Dashboard

---

## 📁 Project Structure

```
lu_crawler/
├── src/                  # Application source code
│   ├── app/              # Next.js app router pages
│   └── components/       # Reusable React components
├── public/               # Static assets
├── testing/
│   └── LU_Crawler_Test_Plan.xlsx   # Functional test plan
└── README.md
```

---

## 🚀 Run Locally

```bash
# Clone the repo
git clone https://github.com/DivyanshCh39/lu_crawler.git
cd lu_crawler

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Add your Supabase URL and anon key

# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🔑 Environment Variables

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

---

## 👨‍💻 Author

**Divyansh Chaurasia**
- GitHub: [@DivyanshCh39](https://github.com/DivyanshCh39)
- LinkedIn: [divyanshch](https://linkedin.com/in/divyanshch)
