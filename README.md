# API Testing – Reqres.in

Proyek ini berisi **automated API testing** menggunakan **Katalon Studio** untuk menguji beberapa endpoint pada [Reqres.in](https://reqres.in/).  
Struktur proyek dibuat dengan pemisahan **Object Repository**, **Test Cases**, dan **Test Suite**.

---

## 🚀 Teknologi yang Digunakan
- **Katalon Studio** – untuk membuat dan menjalankan automation testing.
- **Groovy** – bahasa scripting yang digunakan Katalon.
- **Reqres.in** – API dummy untuk simulasi.
- **GitHub** – version control dan kolaborasi.

---

## 📂 Struktur Project
<img width="526" height="425" alt="Screenshot_5" src="https://github.com/user-attachments/assets/b9bacef4-7843-4795-a495-38b256c0f05e" />


## 📑 Test Case yang Dibuat
| No | Nama Test Case  | Endpoint                 | Method |
|----|-------------------|------------------------|--------|
| 1  | Get List User     | `/api/users?page=1`    | GET    |
| 2  | Get Single User   | `/api/users/3`         | GET    |
| 3  | Put Update        | `/api/users/3`         | PUT    |
| 4  | Post Registrasi   | `/api/register`        | POST   |

---

## 📊 Hasil Testing
- ✅ Semua test case berjalan sukses.
- 📄 Response body sesuai dengan ekspektasi berdasarkan dokumentasi API.
