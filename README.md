API Testing – Reqres.in
Proyek ini berisi automated API testing menggunakan Katalon Studio untuk menguji beberapa endpoint pada Reqres.in.
Struktur proyek dibuat dengan pemisahan Object Repository, Test Cases, dan Test Suite

🚀 Teknologi yang Digunakan
Katalon Studio – untuk membuat dan menjalankan automation testing.
Groovy – bahasa scripting yang digunakan Katalon.
Reqres.in – API dummy untuk simulasi.
GitHub – version control dan kolaborasi.

API_Testing_Reqres/
│
├── Object Repository/
│   ├── Get_List_User.rs
│   ├── Registrasi.rs
│   ├── Single_User.rs
│   └── Update.rs
│
├── Test Cases/
│   ├── Get_List_User.tc
│   ├── Registrasi.tc
│   ├── Single_User.tc
│   └── Update.tc
│
├── Scripts/
│   └── Testing_Automation.groovy
│
├── Test Suites/
│   └── Testing_Automation.ts
│
└── README.md

📑 Test Case yang Dibuat
No	Nama Test Case	Endpoint	Method
1	Get List User	/api/users?page=1	GET
2	Registrasi	/api/register	POST
3	Single User	/api/users/2	GET
4	Update User	/api/users/2	PUT

📊 Hasil Testing
Semua test case berjalan sukses.
Response body sesuai dengan ekspektasi berdasarkan dokumentasi API.

