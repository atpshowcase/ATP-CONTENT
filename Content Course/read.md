# 📘 Next.js Fundamentals – Learning Roadmap

## 🟢 1. Introduction to Next.js
- What is Next.js?
- Why use Next.js over React?
- Key features:
  - File-based routing
  - Server-side rendering (SSR)
  - Static site generation (SSG)
  - API routes
- When to use Next.js

---

## 🟢 2. Project Setup
- Creating Next.js app (`create-next-app`)
- Project structure overview
- Running development server
- Build & production

---

## 🟢 3. File-Based Routing
> ⭐ Core Feature

- Pages & routing system
- Dynamic routes (`[id].js`)
- Nested routes
- Linking between pages (`Link`)

---

## 🟢 4. Layouts & Structure
- Layout pattern
- Shared UI (Navbar, Footer)
- App Router vs Pages Router (intro)

---

## 🟢 5. Components in Next.js
- Reusing React components
- Server vs Client Components (intro)
- Component organization

---

## 🟢 6. Styling in Next.js
- Global CSS
- CSS Modules
- Tailwind CSS (common usage)
- Styled components (optional)

---

## 🟢 7. Data Fetching
> 🔥 Very Important

- `getStaticProps` (SSG)
- `getServerSideProps` (SSR)
- Client-side fetching
- When to use each method

---

## 🟢 8. API Routes (Backend inside Next.js)
> ⭐ Fullstack feature

- Creating API routes
- Handling requests & responses
- Basic CRUD operations

---

## 🟢 9. Rendering Strategies
> 🔥 Core Concept

- CSR (Client-Side Rendering)
- SSR (Server-Side Rendering)
- SSG (Static Site Generation)
- ISR (Incremental Static Regeneration)

---

## 🟢 10. Dynamic Routing & Params
- Route parameters
- Catch-all routes
- Using params in pages

---

## 🟢 11. Middleware (Basic)
- What is middleware?
- Request interception
- Authentication basics

---

## 🟢 12. Image Optimization
- `next/image`
- Automatic optimization
- Lazy loading

---

## 🟢 13. SEO Optimization
- Meta tags
- `next/head`
- Open Graph
- Why SEO matters

---

## 🟢 14. Authentication (Basic)
- Login system concept
- Session vs token
- Intro to auth libraries (e.g., NextAuth)

---

## 🟢 15. Environment Variables
- `.env.local`
- Managing secrets
- Using env variables in app

---

## 🟢 16. Deployment
- Build process
- Deploy to Vercel
- Environment setup

---

## 🟢 17. Performance Optimization
- Code splitting
- Lazy loading
- Caching strategies

---

## 🟢 18. Error Handling
- Custom error pages
- Handling API errors
- Fallback UI

---

## 🟢 19. Advanced Concepts (Optional)
- App Router (deep dive)
- Server Actions
- Streaming & Suspense
- Edge functions

---

# 🧠 Suggested Learning Path

1. Basics → (1–3) ⭐  
2. Layout & Components → (4–5)  
3. Data Fetching → (7–9) 🔥  
4. API Routes → (8) ⭐  
5. SEO & Optimization → (12–13)  
6. Deployment → (16)

---

# 💡 Practice Ideas

- Blog Website (SSG + SEO)
- Dashboard App (SSR)
- Fullstack CRUD App (API routes)
- Portfolio Website (Next.js + SEO)

---

# 🚀 Tips

- Understand rendering strategies deeply (CSR vs SSR vs SSG)
- Use Next.js for real-world projects
- Practice API routes (this is where you become fullstack)
- Combine with React knowledge (Next.js = React + features)

## Prompt Final (Siap Pakai)
Baca file `read.md`, lalu kerjakan ini:

1. Jelaskan semua materi dengan gaya tongkrongan Indonesia, tapi tetap jelas, runut, dan informatif.
2. Buat file HTML baru dengan template visual yang sama seperti `Docker-for-Developers-Complete.html`.
3. Gunakan struktur heading berjenjang:
   - Judul besar: `BAB A`, `BAB B`, `BAB C`, dst.
   - Subjudul: `A.1`, `A.2`, `B.1`, `B.2`, dst.
4. Tambahkan bagian `Map Cepat Section` di awal artikel.
5. Untuk setiap subbab, sertakan analogi sederhana (tongkrongan/kehidupan sehari-hari).
6. Gunakan bahasa santai tapi tetap profesional; jangan terlalu formal.
7. Pertahankan fitur copy ke Tiptap:
   - Tombol `Copy Rich HTML for Tiptap`
   - Tombol `Copy Tiptap-Safe HTML`
   - Sanitizer aman untuk: heading, paragraph, list, bold, italic, quote, pre/code.
8. Pasang fitur copy button otomatis di setiap BAB dan setiap subheader.
9. Untuk setiap subheader (`A.1`, `H.2`, dst), sediakan 3 tombol:
   - Tombol kode level (copy plain text: mis. `H.1`)
   - Tombol `Judul H.1` (copy judul tanpa prefix level)
   - Tombol `Isi H.1` (copy isi subbab tanpa judul, termasuk paragraf/list/analogi/code block)
10. Tombol copy BAB tetap tersedia untuk copy seluruh isi satu BAB.
11. Pastikan elemen tombol copy tidak ikut tercopy di output HTML/Tiptap.
12. Semua contoh kode wajib rapi dalam blok `pre/code`, bukan satu baris panjang.
13. Jangan pakai tabel, jangan pakai emoji/icon.
14. Output final: langsung buat file HTML baru dengan nama yang relevan, lalu pastikan `no errors`.

Jika ada bagian ambigu, lanjut dengan asumsi paling masuk akal dan jelaskan keputusan secara runut.
