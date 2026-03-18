# System Design Fundamentals
> Materi lengkap system design dari dasar sampai praktik, cocok untuk interview prep maupun real-world project.

---

## 1. Introduction
- 1.1 What is System Design
- 1.2 Why It Matters
- 1.3 History and Evolution

## 2. Requirements
- 2.1 Functional Requirements
- 2.2 Non-Functional Requirements
- 2.3 Estimating Scale

## 3. High-Level Design
- 3.1 System Overview
- 3.2 Components & Data Flow
- 3.3 Tech Stack Basics

## 4. API Design
- 4.1 REST Basics
- 4.2 Endpoints & Structure
- 4.3 Versioning & Rate Limiting

## 5. Data Design
- 5.1 SQL vs NoSQL
- 5.2 Schema Design
- 5.3 Indexing & Partitioning

## 6. Scalability
- 6.1 Vertical vs Horizontal Scaling
- 6.2 Load Balancing
- 6.3 Stateless Systems

## 7. Caching
- 7.1 Purpose of Caching
- 7.2 Cache Strategies
- 7.3 Cache Invalidation

## 8. Asynchronous Systems
- 8.1 Sync vs Async
- 8.2 Message Queues
- 8.3 Background Jobs

## 9. Reliability
- 9.1 Fault Tolerance
- 9.2 Failover
- 9.3 Retry & Circuit Breaker

## 10. Performance
- 10.1 Latency & Throughput
- 10.2 Query Optimization

## 11. Security
- 11.1 Authentication & Authorization
- 11.2 Data Protection

## 12. Monitoring
- 12.1 Logging
- 12.2 Metrics & Alerts

## 13. Deployment
- 13.1 CI/CD Basics
- 13.2 Containers & Cloud

## 14. Trade-offs
- 14.1 CAP Theorem
- 14.2 Consistency vs Availability
- 14.3 Cost vs Performance

## 15. Real Examples
- 15.1 URL Shortener
- 15.2 Chat System
- 15.3 E-commerce System

---

## 16. Summary
- Key Takeaways

---

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
