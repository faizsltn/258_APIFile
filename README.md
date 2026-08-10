# Praktikum 9 - API File Management (Komik & Genre)

Repository ini berisi implementasi RESTful API menggunakan Express.js, Sequelize (PostgreSQL), JWT Authentication, dan Multer untuk penanganan upload file gambar.

---

## 🛠️ Informasi Modul
* **Mata Kuliah**: Pemrograman Web Service (PWS)
* **Praktikum**: 9 (API File Management)

---

## 🚀 Fitur API
1. **Autentikasi Penulis**: Register & Login (dengan Token JWT)
2. **Manajemen Genre**: Create, Read, Update, Delete (Protected Route)
3. **Manajemen Komik**: Create, Read, Update, Delete + Upload Cover Gambar (Protected Route)

---

## ⚙️ Cara Menjalankan Project

1. **Install Dependencies**
   ```bash
   npm install

   📸 Bukti Pengujian API (Postman Screenshots)
1. Register Penulis
Endpoint: POST /api/register
Deskripsi: Mendaftarkan akun penulis baru.
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/c064635c-a1c9-4c53-8711-34e80ac185d7" />

2. Login Penulis
Endpoint: POST /api/login
Deskripsi: Autentikasi penulis dan mendapatkan JWT Token.
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/7e98a0db-d048-40fa-b407-a1ea48a51db5" />

3. CRUD Genre
A. Post Genre
Endpoint: POST /api/genre
Deskripsi: Menambahkan data genre baru.
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/8b0982c8-33c2-48c2-a05f-b18707fa24a5" />

B. Get Genre
Endpoint: GET /api/genre
Deskripsi: Menampilkan semua daftar genre.
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/90cf75fa-bb11-4927-94fc-005c3c6e29c5" />

C. Put Genre
Endpoint: PUT /api/genre/:id
Deskripsi: Mengubah data genre berdasarkan ID.
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/8ab475c8-21ea-48b2-a970-e5c19e846720" />

D. Delete Genre
Endpoint: DELETE /api/genre/:id
Deskripsi: Menghapus data genre berdasarkan ID.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e958dd50-5ec3-4a5c-bb64-972facdc3019" />

4. CRUD Komik
A. Post Komik (Upload Gambar)
Endpoint: POST /api/komik
Deskripsi: Menambahkan data komik beserta file gambar sampul (Multer).
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c5238567-b51f-419b-b485-84390798520d" />

B. Get Komik
Endpoint: GET /api/komik
Deskripsi: Menampilkan semua daftar komik.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b1e1594e-3bfc-4571-90c0-8b120eca74c2" />

C. Put Komik
Endpoint: PUT /api/komik/:id
Deskripsi: Mengubah data komik / gambar berdasarkan ID.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c45da224-7a0c-4dbd-bf18-303ef49ef431" />

D. Delete Komik
Endpoint: DELETE /api/komik/:id
Deskripsi: Menghapus data komik berdasarkan ID.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ceb23f3d-b2d0-4103-95cd-2a6e4485efe5" />
