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
<img width="376" height="431" alt="Screenshot_3" src="https://github.com/user-attachments/assets/12798248-55dd-47b6-a4d9-4e2469fcc55c" />

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
