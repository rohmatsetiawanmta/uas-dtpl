# 📚 Catatan Belajar UAS — Dinamika Tim Perangkat Lunak (DTPL)
**Topik Utama: Software Craftsmanship, Agile, CMMI, dan Scaling Agile**

---

## 🗂️ Daftar Isi
1. [Software Engineering & Software Craftsmanship](#1-software-engineering--software-craftsmanship)
2. [Agile Software Development & Agile Hangover](#2-agile-software-development--agile-hangover)
3. [Software Craftsmanship Manifesto vs Agile Manifesto](#3-software-craftsmanship-manifesto-vs-agile-manifesto)
4. [CMMI: Pengantar, Maturity Levels, dan Representasi](#4-cmmi-pengantar-maturity-levels-dan-representasi)
5. [CMMI & Agile (Scrum): Project Planning (PP)](#5-cmmi--agile-scrum-project-planning-pp)
6. [CMMI & Agile (Scrum): Project Monitoring & Control (PMC)](#6-cmmi--agile-scrum-project-monitoring--control-pmc)
7. [CMMI & Agile (Scrum): Requirements Management (REQM)](#7-cmmi--agile-scrum-requirements-management-reqm)
8. [CMMI & Agile (Scrum): Requirements Development (RD)](#8-cmmi--agile-scrum-requirements-development-rd)
9. [Verification & Validation (VER & VAL) + Software Inspection](#9-verification--validation-ver--val--software-inspection)
10. [The Essence of SE & Agnostic Scaling Agile (ASA) Model](#10-the-essence-of-se--agnostic-scaling-agile-asa-model)

---

## 1. Software Engineering & Software Craftsmanship

### 🎯 The Ultimate Goal of Software Development
> **"Deliver QUALITY products ON TIME and ON BUDGET which meet the customer's REAL NEEDS"**

Ini adalah tujuan utama yang menjadi landasan seluruh mata kuliah ini. Semua framework dan pendekatan yang dipelajari (Agile, CMMI, Craftsmanship) bermuara ke sini.

### 🔧 Engineering Mindset
Mengutip Guru Madhava dalam "Think Like An Engineer": pesawat terbang sudah ada sebelum ilmu aeronautika formal. Artinya, *praktik sering mendahului teori*.

Engineering berarti **"Producing under Constraint"**. Ada tiga hal yang selalu dihadapi:
- **Structure** — ada struktur yang harus dipahami
- **Constraints** — batasan waktu, biaya, sumber daya
- **Trade-offs** — tidak ada solusi sempurna, selalu ada pilihan antara opsi-opsi

> "There is not enough time to make a perfect product, but we always have limitless time to make it better."

### 📐 Software Engineering Process Life Cycle
Siklus hidup proses pengembangan perangkat lunak melibatkan:
- Software Development Planning
- Requirements Analysis
- Software Architecture Design
- Coding
- Software Testing
- Software Product Distribution and Deployment

**Trilogy of Software Engineering Process Focus** (3 hal yang harus seimbang):
1. **Process Life Cycle** — tahapan-tahapan pengembangan
2. **Skilled & Talented Software Team** — tim yang kompeten
3. **Software Dev. & Productivity Tools** — alat bantu yang tepat

### 📚 SWEBOK (Software Engineering Body of Knowledge)
Area pengetahuan utama dalam Software Engineering:
- Software Requirements, Software Design, Software Construction, Software Testing
- Software Maintenance, Software Configuration Management
- Software Engineering Management, Software Engineering Process
- Software Engineering Models and Methods, Software Quality
- Software Engineering Professional Practice, Software Engineering Economics

### 🏗️ Software Engineering Framework Hierarchy
Dari yang paling luas ke paling spesifik:
1. **Framework** — misal: CMMI-Dev, Essence/SEMAT
2. **Methodology** — misal: Waterfall, RUP, XP, Scrum
3. **Process Method** — misal: OOA, OOD, Black Box Testing
4. **Management Procedures** — Rules & Policy: Change Request, Inspection, Release

**Framework standar internasional yang relevan:**
- ISO-12207: Software Engineering
- ISO-15288: System Engineering
- ISO-9001: Quality
- CMMI for System and Software Engineering

---

## 2. Agile Software Development & Agile Hangover

### ✅ Apa itu Agility?
- Effective (rapid and adaptive) **response to change**
- Effective **communication** among all stakeholders
- **Drawing the customer onto the team**
- Organizing a team so that it is **in control of the work** performed
- **Rapid, incremental delivery** of software

### 📋 Scrum Framework (Metodologi Agile utama)
Scrum adalah metodologi agile yang paling populer. Komponen utamanya:
- **Product Backlog** — daftar semua fitur/kebutuhan produk
- **Sprint** — iterasi pengembangan berdurasi tetap (biasanya 2–4 minggu)
- **Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective**
- **Product Owner, Scrum Master, Development Team**

### 😵 The Agile Hangover
Sejak 2001, banyak perusahaan beralih ke Agile. Namun banyak yang tetap mengalami masalah lama:
- Kualitas perangkat lunak yang rendah
- Banyak bugs
- Technical debt yang tinggi
- Basis kode yang berantakan
- Biaya maintenance yang besar
- Pengguna yang kecewa

**Mengapa?** Banyak perusahaan hanya mengganti *ritual* (stand-up meeting, sticky notes, post-its berwarna) tanpa mengubah kualitas teknis secara fundamental.

**Definisi Agile Hangover:** Kelelahan, kekecewaan, dan birokratisasi yang muncul setelah penerapan Agile yang berlebihan, kaku, atau buruk — di mana tim lebih fokus pada ritual daripada memberikan nilai. Ditandai dengan *"zombie Scrum"* — tim menjalankan Scrum secara mekanis tanpa jiwa.

**Kondisi yang sering terjadi:**
- Hanya memaksimalkan peningkatan *proses* tapi mengabaikan *keunggulan teknis*
- Lupa bahwa hasil terpenting adalah (kualitas) perangkat lunak itu sendiri

**Solusi:** Inilah kenapa **Software Craftsmanship** hadir — untuk melengkapi Agile dengan keunggulan teknis.

---

## 3. Software Craftsmanship Manifesto vs Agile Manifesto

### 📜 Agile Manifesto (2001, Kent Beck et al.)
| Lebih dihargai | Dibandingkan |
|---|---|
| Individuals and interactions | Processes and tools |
| Working software | Comprehensive documentation |
| Customer collaboration | Contract negotiation |
| Responding to change | Following a plan |

### 🛠️ Apa itu Software Craftsmanship?
- Ideologi tentang **profesionalisme** dalam pengembangan perangkat lunak
- Pengembang mengadopsinya untuk menjadi lebih baik
- Mempromosikan banyak **praktik teknis** agar tim bisa menulis *well-crafted code*
- Menekankan pemahaman domain bisnis pengguna, bukan hanya fokus menulis kode

**Analogi:** Seperti perbedaan *batik tulis* (craftsmanship) vs *batik cap* (industrial/engineered). Craftsmanship mementingkan kualitas dan keahlian individual yang mendalam.

### 📜 Software Craftsmanship Manifesto
| Craftsmanship values | Dibandingkan dengan nilai Agile |
|---|---|
| **Not only** working software, **but also** well-crafted software | Working software |
| **Not only** responding to change, **but also** steadily adding value | Responding to change |
| **Not only** individuals and interactions, **but also** a community of professionals | Individuals and interactions |
| **Not only** customer collaboration, **but also** productive partnerships | Customer collaboration |

### 🔍 Penjelasan Detail Tiap Poin Manifesto

**1. Well-crafted software vs Working software**
Working software saja tidak cukup. Perangkat lunak harus:
- Mudah dipahami
- Mudah diubah
- Teruji (tested)
- Memiliki rancangan yang sederhana
- Bisnis prosesnya tergambar dengan baik dalam source code
- Praktik seperti **Test-Driven Development (TDD)** dan **simple design** sangat ditekankan

**2. Steadily adding value vs Responding to change**
Menanggapi perubahan saja tidak cukup. Harus ada:
- Peningkatan struktur kode secara berkala
- Kode yang tetap rapi, mudah dikembangkan, dapat diuji, dan mudah dirawat
- Prinsip: **"always leave the code cleaner than we found it"**

**3. Community of professionals vs Individuals and interactions**
- Pengembang harus menerapkan **kode etik** profesionalisme
- Kode etik melindungi tim dari tekanan eksternal yang merugikan
- Tim tidak boleh terintimidasi untuk mengubah praktik teknis yang bermanfaat
- Selalu belajar dan tidak malu untuk belajar dari orang lain

**4. Productive partnerships vs Customer collaboration**
Tujuannya adalah membangun hubungan yang produktif dengan membantu klien:
- Meningkatkan proses
- Menyajikan pilihan dan menghapus birokrasi yang tidak perlu
- Memahami domain bisnis
- Menyajikan informasi dan pengetahuan yang baik
- Membantu merencanakan dan memprioritaskan pekerjaan

### 🤝 Bagaimana Mengadopsi Software Craftsmanship?
- Software craftsmanship adalah ideologi **pelengkap** Agile, bukan pengganti
- Dapat diadopsi dengan metodologi Agile apapun
- Komunitas Software Craftsmanship merekomendasikan **Extreme Programming (XP)** karena XP sangat fokus pada praktik teknis

**Extreme Programming (XP):** Metodologi Agile yang memfokuskan pada teknik pemrograman yang baik, komunikasi yang jelas, dan kerjasama tim. XP memiliki praktik-praktik yang mendukung Software Craftsmanship seperti:
- Test-Driven Development (TDD)
- Pair Programming
- Refactoring
- Continuous Integration

---

## 4. CMMI: Pengantar, Maturity Levels, dan Representasi

### 💡 Mengapa CMMI?
Analogi sepak bola: Tim Little League vs Tim Profesional. Perbedaannya bukan pada usia, tapi pada **kematangan proses**.

- Tim profesional memiliki **self-perpetuating quality**: membuat permainan yang baik, mengembangkan pemain baru seperti diri mereka, dan mencari cara untuk bermain lebih baik.
- CMMI mencoba **menangkap dan mendeskripsikan** perbedaan antara organisasi pengembang perangkat lunak berkualitas tinggi dan rendah.

**Keyakinan dasar CMMI:** Penggunaan teknik perangkat lunak baru tidak akan dengan sendirinya meningkatkan produktivitas, karena masalah sebenarnya adalah **bagaimana kita mengelola proses perangkat lunak**.

### 📊 5 Maturity Levels (CMMI-DEV)

| Level | Nama | Karakteristik |
|---|---|---|
| **1** | Initial | Ad hoc dan chaotic. Keberhasilan bergantung pada individu, bukan proses. |
| **2** | Managed | Proses direncanakan dan dijalankan sesuai kebijakan. Stabil dan dapat diulang di level proyek. |
| **3** | Defined | Proses terdokumentasi dengan baik dalam standar organisasi. Proaktif, bukan reaktif. |
| **4** | Quantitatively Managed | Proses diukur secara statistik. Ada target kuantitatif untuk kualitas dan performa. |
| **5** | Optimizing | Perbaikan proses berkelanjutan berdasarkan pemahaman kuantitatif. |

**Data Perbandingan Performa per Level (Rifkin, 1993)**
Untuk program 200.000 baris kode dari 1.300 proyek:

| CMM Level | Durasi (Calendar Months) | Effort (Person Months) | Faults Delivered | Total Cost |
|---|---|---|---|---|
| Level 1 | 29.8 | 593.5 | 61 | $5,440,000 |
| Level 2 | 18.5 | 143.0 | 12 | $1,311,000 |
| Level 3 | 15.2 | 79.5 | 7 | $728,000 |
| Level 4 | 12.5 | 42.8 | 5 | $392,000 |
| Level 5 | 9.0 | 16.0 | 1 | $146,000 |

> **Defect rate kira-kira berkurang setengah setiap naik satu maturity level.**

**Waktu rata-rata untuk naik level:**
- Level 1 → 2: ~25 bulan
- Level 2 → 3: ~22 bulan
- Level 3 → 4: ~36.5 bulan

### 🗂️ Process Areas (PA) di CMMI-DEV v1.3

**22 Process Area, diorganisir ke 4 kategori:**

| Maturity Level | Project Management | Process Management | Engineering | Support |
|---|---|---|---|---|
| 5 | | OPM | | CAR |
| 4 | QPM | OPP | | |
| 3 | IPM, RSKM | OPD, OPF, OT | PI, RD, TS, VAL, VER | DAR |
| 2 | PMC, PP, REQM, SAM | | | CM, MA, PPQA |

**Keterangan singkatan:**
- PP = Project Planning, PMC = Project Monitoring and Control
- REQM = Requirements Management, SAM = Supplier Agreement Management
- RD = Requirements Development, TS = Technical Solution
- PI = Product Integration, VER = Verification, VAL = Validation
- IPM = Integrated Project Management, RSKM = Risk Management
- OPD = Organizational Process Definition, OPF = Organizational Process Focus
- OT = Organizational Training, OPP = Organizational Process Performance
- QPM = Quantitative Project Management, OPM = Organizational Performance Management
- CAR = Causal Analysis and Resolution, DAR = Decision Analysis and Resolution
- CM = Configuration Management, MA = Measurement and Analysis, PPQA = Process and Product Quality Assurance

### ⚖️ Staged vs Continuous Representation

| | Staged Representation | Continuous Representation |
|---|---|---|
| **Satuan ukur** | Maturity Level (1–5) | Capability Level (0–3) |
| **Pendekatan** | Semua PA naik bersama per level | Tiap PA bisa naik capability level-nya secara mandiri |
| **Keunggulan** | Sistematis, ada panduan urutan | Fleksibel, fokus pada area masalah tertentu |
| **Penggunaan** | Sertifikasi formal, benchmark umum | Perbaikan internal yang fleksibel |

**Capability Levels (Continuous):**
- CL 0: Incomplete
- CL 1: Performed — melakukan specific practices
- CL 2: Managed — direncanakan, dipantau, dan dikontrol
- CL 3: Defined — di-*tailor* dari standard process organisasi

### 🔄 CMMI v1.3 vs CMMI v2.0
Perubahan utama di CMMI v2.0 (dirilis Maret 2018):
- "Process Area" → "**Practice Area**": menekankan bahwa ini bukan kumpulan proses kaku, melainkan praktik-praktik
- Practices diorganisir per level (bukan per Specific Goals)
- Generic Practices diganti oleh dua Practice Area baru: **Governance (GOV)** dan **Implementation Infrastructure (II)**
- CMMI Dev 1.3: 22 PA, 168 Practices → CMMI Dev 2.0: 4 Category, 12 Capability Area, 29 PA, 198 Practices

---

## 5. CMMI & Agile (Scrum): Project Planning (PP)

### 🤝 CMMI + Scrum: Dua Perspektif
- **CMMI** memberikan peta tentang **"WHAT"** yang harus dilakukan organisasi berkinerja tinggi
- **Agile/Scrum** menentukan **"HOW"** melakukannya
- Keduanya bekerja bersama: 18 common business problems teridentifikasi yang bisa diselesaikan dengan kombinasi keduanya

### 📋 Project Planning (PP) — Maturity Level 2
**Tujuan:** Menetapkan dan memelihara rencana yang mendefinisikan aktivitas proyek.

**Output utama:** Project Plan — sebagai dasar untuk menjalankan dan mengontrol proyek.

**Project Plan menjawab:**
- Why? — Apa masalah/value proposition proyek ini?
- What? — Apa pekerjaan yang akan dilakukan?
- Who? — Siapa yang terlibat dan perannya?
- When? — Timeline dan milestone-nya?

#### SG 1: Establish Estimates
Membuat perkiraan untuk parameter perencanaan proyek.

**SP 1.1 Estimate the Scope of the Project**
- Buat Work Breakdown Structure (WBS) top-level
- Dalam Scrum, WBS setara dengan **Epics/Stories yang tersusun dalam prioritized backlog** dengan metadata (Definition of Done, sizing)
- Diperkuat oleh: Backlog Grooming, Definition of Done, Release Planning, Sprint Planning, Team Estimating Game

**SP 1.2 Establish Estimates of Work Product and Task Attributes**
- Identifikasi deliverables standar (Requirements Doc, Project Plan, Source Code) dan custom (Prototype, Mockups)
- Break down tasks untuk setiap deliverable
- Dalam Scrum: parent dan children user stories di-*size* menggunakan story sizing saat Backlog Grooming

**SP 1.3 Define Project Lifecycle Phases**
- Pilih lifecycle yang paling sesuai: Waterfall, Agile, dll.
- Dalam Scrum: Release Planning yang menstrukturisasi Sprints di dalamnya dengan durasi dan konten yang terdefinisi

**SP 1.4 Estimate Effort and Cost**
- Kutip dalam *man-days* per task
- Dalam Scrum: sizing of stories digunakan untuk memperkirakan durasi sprint

#### SG 2: Develop a Project Plan
**SP 2.1 Establish the Budget and Schedule**
- Tetapkan Key Milestone: titik kritis di mana progress dapat diukur (misal: Release v1, UAT)
- Buat Schedule Baseline menggunakan WBS (biasanya di MS Project)
- Dalam Scrum: Release Planning (SP 2.2, 2.6, 2.1, 2.7)

**SP 2.2 Identify Project Risks**
- Dokumentasikan risiko yang diketahui: perubahan staf, kebutuhan bisnis yang berkembang, kebijakan yang berubah
- Beri nilai setiap risiko: urgensi, kemungkinan terjadi, dampak
- Buat mitigation plan dan assign owner untuk setiap risiko
- Dalam Scrum: Release Planning, Technical Debt (SP 2.2)

**SP 2.3 Plan Data Management**
- Identifikasi data yang perlu dikelola: Plans, reports, schedules, test cases, dll.
- Atur access level, version control, backup/archiving
- Dalam Scrum: ini dikuatkan oleh Configuration Management

**SP 2.4 Plan the Project's Resources**
- Identifikasi semua resource: orang, fasilitas, tools, perangkat
- Rencanakan ukuran tim dan peran (kalau belum bisa nama, setidaknya job role)
- Dalam Scrum: ini tercakup dalam Release Planning

**SP 2.5 Plan Needed Knowledge and Skills**
- Technical skills: BA, System Architect, Programmer, QA
- Management skills: PM, Change Mgmt, Configuration Mgmt
- Dalam Scrum: Team Agreements dapat mencakup ini

**SP 2.6 Plan Stakeholder Involvement**
- Identifikasi siapa saja stakeholder dan kapan keterlibatan mereka diperlukan
- Pastikan Senior Management terlibat dan ter-inform
- Dalam Scrum: Release Planning (SP 2.6)

**SP 2.7 Establish the Project Plan**
- Publikasikan draft plan yang profesional
- Tampilan plan mencerminkan tingkat komitmen
- Dalam Scrum: **Product Backlog** adalah setara dengan Project Plan. Product Owner + Scrum Team berkolaborasi saat Release Planning, Sprint Planning, dan Backlog Grooming

#### SG 3: Obtain Commitment to the Plan
**SP 3.1 Review Plans that Affect the Project** → dikuatkan oleh Sprint Planning
**SP 3.2 Reconcile Work and Resource Levels** → Sprint Planning
**SP 3.3 Obtain Plan Commitment** → Sprint Planning, Release Planning, Technical Debt

**Kata kunci Commitment:**
- **Agreement** — semua pihak setuju dengan atribut proyek
- **Alignment** — bergerak bersama ke arah yang sama
- **Cooperation** — mengakui pentingnya bekerja sama

#### Mapping PP ke Scrum Ceremonies

| Scrum Ceremony/Technique | CMMI PP Practices |
|---|---|
| Backlog Grooming | SP 1.1, 1.2, 1.4 |
| Definition of Done | SP 1.1, 1.2 |
| Release Planning | SP 1.1–1.4, 2.1, 2.2, 2.6, 2.7, 3.3 |
| Sprint Planning | SP 1.1, 1.2, 1.4, 3.1, 3.2, 3.3 |
| Sprint/Iteration | SP 1.3 |
| Team Estimating Game & Planning Poker | SP 1.1, 1.4 |
| Product Backlog | SP 2.7 |
| Technical Debt | SP 1.4, 2.2, 3.3 |

---

## 6. CMMI & Agile (Scrum): Project Monitoring & Control (PMC)

### 🎯 Tujuan PMC
Memberikan pemahaman tentang kemajuan proyek agar **corrective action** yang tepat dapat diambil ketika performance menyimpang secara signifikan dari rencana.

PMC adalah inti dari Project Management:
- Guide of Work: memastikan semua pekerjaan terkoordinasi sesuai rencana
- Protect Commitment: memastikan komitmen (jadwal, anggaran, kualitas) terealisasi
- Promote Communication: komunikasi yang buruk menyebabkan false perception
- Facilitate Correction, Adjustment, and Focus: perubahan yang tidak terkontrol bisa menyebabkan kegagalan proyek

### SG 1: Monitor the Project Against the Plan

**SP 1.1 Monitor Project Planning Parameters**
Monitor: scope, schedule, budget, resources
- Schedule selalu diperbaharui dan jelas — bisa menjadi communication tool
- Budget: track konsumsi agar selalu sejajar dengan aktivitas proyek
- Dalam Scrum: dikuatkan oleh Daily Standup dan Release Burn-Down Chart

**SP 1.2 Monitor Commitments**
Monitor komitmen terkait deliverables, kualitas, dan komunikasi.
- Dalam Scrum: Daily Standup (format "what I did, what I'm doing, what's blocking me"), Release Burn-Down Chart

**SP 1.3 Monitor Project Risks**
Risiko yang sudah didokumentasikan di PP harus terus dipantau.
- Dalam Scrum: Daily Standup — risiko harus diangkat sebagai agenda spesifik, bukan hanya saat ada blocker

**SP 1.4 Monitor Data Management**
Pastikan work products terpelihara dan tersedia dengan baik.

**SP 1.5 Monitor Stakeholder Involvement**
Stakeholder bisa keluar-masuk proyek; pastikan keterlibatan mereka terencana.
- Dalam Scrum: Release Burn-Down Chart digunakan dan di-review dengan stakeholder saat Sprint Demo dan Retrospective

**SP 1.6 Conduct Progress Reviews**
Review berkala untuk progress, performance, dan issues. PM membandingkan aktual dengan estimasi.
- Dalam Scrum: **Daily Standup**, **Release Burn-Down Chart**, **Sprint Burn-Down Chart**

**SP 1.7 Conduct Milestone Reviews**
- Critical path dates: milestone pada fase proyek (misal: Deployment)
- Critical path work products: Release 1, Prototype, dll.
- Dalam Scrum: **Sprint Demo/Sprint Review** (akhir setiap sprint = milestone review)

### SG 2: Manage Corrective Action to Closure

**SP 2.1 Analyze Issues** — identifikasi dan analisis issues untuk menilai dampak dan urgensi

**SP 2.2 Take Corrective Action:**
- Remove the Issue — eliminasi jika ternyata bukan masalah nyata
- Change Project Activities — misal: tambah resource, kerja overtime untuk schedule issue
- Change the Plan — jika realita tidak bisa dihindari, realign ekspektasi dan modifikasi plan

**SP 2.3 Manage Corrective Actions** — pastikan semua actions ditindaklanjuti hingga tuntas (closure)

### 📊 Scrum Ceremonies yang Memperkuat PMC

**Daily Standup/Daily Scrum**
- Mengidentifikasi issues dan risiko lebih awal ("fail fast")
- Meningkatkan kolaborasi antar anggota tim
- Memperkuat: SP 1.1 (Monitor Parameters), SP 1.2 (Monitor Commitments), SP 1.3 (Monitor Risks), SP 1.6 (Progress Reviews), SP 1.7 (Milestone Reviews)

**Release Burn-Down Chart**
- Menggambarkan trajectory keseluruhan release berdasarkan sprint
- Berdasarkan **velocity** (story points yang bisa di-"burn down" per sprint)
- Membantu Product Owner dan tim memahami apakah functionality akan terdelivery sesuai rencana
- Memperkuat: SP 1.1, 1.2, 1.5, 1.6

**Sprint Burn-Down Chart**
- Menggambarkan effort yang tersisa untuk menyelesaikan sprint
- *Burn-Up chart* adalah kebalikannya: melacak seberapa banyak pekerjaan yang sudah selesai (kurva naik)
- Memperkuat: SP 1.5, 1.6

**Sprint Demo / Sprint Review**
- Teknik kolaboratif iteratif dan inkremental memastikan stakeholder aware terhadap value yang delivered
- Memperkuat: SP 1.2, 1.5, 1.6, 1.7 (SG 1) dan SP 2.3 (SG 2)

#### Mapping PMC ke Scrum Ceremonies

| Scrum Ceremony | PMC Practices |
|---|---|
| Daily Standup | SP 1.1, 1.2, 1.3, 1.6, 1.7 |
| Release Burn-Down Chart | SP 1.1, 1.2, 1.5, 1.6 |
| Sprint Burn-Down Chart | SP 1.5, 1.6 |
| Sprint Demo/Sprint Review | SP 1.2, 1.5, 1.6, 1.7 (SG1); SP 2.3 (SG2) |

---

## 7. CMMI & Agile (Scrum): Requirements Management (REQM)

### 📌 Apa itu Requirements?
Requirements adalah ekspektasi umum tentang:
- Apa yang akan dibangun
- Apa yang harus dilakukan setelah dibangun
- Apa yang diperlukan untuk membangunnya

Requirements adalah **kontrak saling pengertian** antara developer dan customer. Mereka berfungsi sebagai:
1. **Basis for Agreement** — dasar kesepakatan developer-customer-tim
2. **Scope Definition** — menentukan jumlah/jenis pekerjaan, resource, waktu, biaya
3. **Performance Obligation** — tanggung jawab legal (untuk beberapa jenis klien)
4. **Success Criteria** — benchmark keberhasilan proyek
5. **Naturally Subject to Change** — oleh karena itu harus dikelola dengan baik

### 🎯 Tujuan REQM
Mengelola requirements produk dan memastikan alignment antara requirements dengan plans dan work products proyek.

### SG 1: Manage Requirements (5 Specific Practices)

**SP 1.1 Understand Requirements**
- Kembangkan pemahaman dengan requirements providers tentang makna requirements
- Dalam Scrum: **Backlog Grooming** — product owner, Scrum master, dan tim membahas clarifying questions hingga size dan complexity user story dipahami
- Bisa didemonstrasikan: attend backlog grooming session, lihat story points ter-assign, backlog terdokumentasi di board/tool

**SP 1.2 Obtain Commitment to Requirements**
- Dapatkan komitmen dari peserta proyek terhadap requirements
- Dalam Scrum: Backlog Grooming — semua anggota review user stories baru/yang dimodifikasi/yang dihapus
- Penting: CMMI menekankan dialog dengan **extended stakeholders** untuk menghindari misunderstanding

**SP 1.3 Manage Requirements Changes**
- Kelola perubahan requirements seiring berkembangnya proyek
- Dalam Scrum: Epics dan user stories terhubung ke tasks dan Definition of Done di tool seperti Jira atau Version One
- CMMI fokus pada **capture of change purpose and history** — tanpa ini, bisa mendekati chaos

**SP 1.4 Maintain Bidirectional Traceability of Requirements**
- Maintain traceability dua arah antara requirements dan work products
- Dalam Scrum: mapping dari Epics → Parent User Stories → Child User Stories
- Bidirectional traceability membantu memvalidasi bahwa stories terimplementasi dan mengidentifikasi gaps

**SP 1.5 Ensure Alignment Between Project Work and Requirements**
- Pastikan project plans dan work products tetap aligned dengan requirements
- Dalam Scrum: Backlog grooming memastikan user stories aligned dengan kebutuhan, skills, environments, dan architecture yang diperlukan

### ⚡ Tips Menghadapi Requirements yang Selalu Berubah (dalam Scrum)
1. Ada **Product Backlog** untuk track semua user stories
2. **Product Owner** bertanggung jawab menjaga backlog up-to-date
3. **Sprint Backlog di-freeze** setelah Sprint Planning selesai
4. Perubahan yang datang saat Sprint berjalan → masuk ke Product Backlog
5. Lakukan **Backlog Grooming** secara reguler untuk menguraikan user stories untuk sprint berikutnya

### 🔄 REQM v1.3 vs RDM v2.0
Di CMMI v2.0, REQM dan Requirements Development (RD) digabung menjadi satu Practice Area: **Requirements Development & Management (RDM)**.

**RDM Level 1:** RDM 1.1 Record requirements
**RDM Level 2:** RDM 2.1–2.6 (elicit, transform, understand, commit, traceability, alignment)
**RDM Level 3:** RDM 3.1–3.7 (develop & update, operational concepts, allocate, interface, necessary & sufficient, balance, validate)

---

## 8. CMMI & Agile (Scrum): Requirements Development (RD)

### 🎯 Tujuan RD
**Elicit, analyze, and establish** customer, product, dan product component requirements.

RD mendeskripsikan tiga tipe requirements:
1. **Customer requirements** — kebutuhan dari perspektif customer
2. **Product requirements** — kebutuhan produk keseluruhan
3. **Product component requirements** — kebutuhan komponen-komponen produk

Dalam konteks Agile, kebutuhan customer di-elicit, diuraikan, dianalisis, dan divalidasi secara **iteratif**. Requirements didokumentasikan sebagai: user stories, scenarios, use cases, product backlogs.

### SG 1: Develop Customer Requirements

**SP 1.1 Elicit Needs**
- Elicit kebutuhan, ekspektasi, constraints, dan interfaces stakeholder untuk semua fase lifecycle produk
- *Eliciting* lebih dari sekadar mengumpulkan requirements — proactively mengidentifikasi requirements tambahan yang tidak dinyatakan eksplisit
- Teknik: technology demonstrations, questionnaires, interviews, scenarios, Interface Control Working Groups
- Dalam Scrum: Backlog Grooming, Epics, User Stories

**SP 1.2 Transform Stakeholder Needs into Customer Requirements**
- Terjemahkan kebutuhan stakeholder menjadi prioritized customer requirements
- Establis prioritasi customer functional dan quality attribute requirements
- Dalam Scrum: Epic dipecah menjadi User Story yang lebih kecil saat Backlog Grooming

### SG 2: Develop Product Requirements

**SP 2.1 Establish Product and Product Component Requirements**
- Tetapkan product dan product component requirements berdasarkan customer requirements
- Dalam Scrum: modifikasi user stories oleh PO = aspek "maintained"; parent/children user stories = lebih specific data

**SP 2.2 Allocate Product Component Requirements**
- Alokasikan requirements ke setiap product component
- Dalam Scrum: requirements dialokasikan ke delivery increment untuk feed sprint planning

**SP 2.3 Identify Interface Requirements**
- Identifikasi interface antara fungsi-fungsi (atau objek-objek atau entitas logis lainnya)
- Dalam Scrum: interface requirements diidentifikasi dan diaddress melalui user stories

### SG 3: Analyze and Validate Requirements

**SP 3.1 Establish Operational Concepts and Scenarios**
- Kembangkan konsep operasional dan skenario penggunaan produk
- Dalam Scrum: user stories dalam format "As an XXX, I need to XXX so that I can XXX"
- Dikuatkan oleh: Backlog Grooming, Test Driven Development

**SP 3.2 Establish a Definition of Required Functionality and Quality Attributes**
- Definisikan functionality yang dibutuhkan dan quality attributes
- Dalam Scrum: acceptance criteria dan quality attributes dalam user story mendefinisikan "what success looks like"

**SP 3.3 Analyze Requirements**
- Pastikan requirements necessary dan sufficient
- Hapus konflik, pastikan setiap requirement satisfy higher-level requirements
- Dalam Scrum: PO dan tim menganalisis epics dan user stories saat Backlog Grooming

**SP 3.4 Analyze Requirements to Achieve Balance**
- Gunakan proven models, simulations, dan prototyping untuk analisis keseimbangan
- Dalam Scrum: stories diprioritaskan 1 to n untuk memastikan stories paling critical diimplementasikan pertama

**SP 3.5 Validate Requirements**
- Pastikan produk yang dihasilkan akan berfungsi sebagaimana dimaksud di environment pengguna
- Teknik: analysis, simulations, prototyping, demonstrations
- Dalam Scrum: Backlog Grooming membuat stories untuk prototype/simulasi/demonstrasi; TDD memastikan continuous validation

### 📋 Beberapa Teknik/Ceremony Scrum yang Diperkuat oleh RD

**Epics:** Dikuatkan oleh RD SP 1.1 dan SP 1.2. Epic merupakan large user story yang nantinya dipecah menjadi user stories yang bisa diselesaikan dalam satu sprint.

**User Stories:** Format: "As a [user role], I want to [goal] so that [benefit]." Dikuatkan oleh hampir semua SP di SG 1, 2, dan 3. Ketika TDD dan DOD yang robust digunakan, user stories adalah bentuk Requirements Development yang kuat.

**Pair Programming:** Dua developer bekerja bersama di satu workstation. Satu sebagai "driver" (menulis kode), satu sebagai "navigator" (review kode). Meskipun meningkatkan biaya awal, terbayar lewat peningkatan kualitas kode.

**Test Driven Development (TDD):**
1. Developer menulis test case sederhana → akan gagal dulu
2. Tulis minimum code untuk lulus test
3. Bersihkan kode agar memenuhi standar performa dan coding
- Ini adalah teknik Verification DAN Validation sekaligus
- Hubungan kuat dengan RD (SP 3.1, 3.4, 3.5), Validation, dan Verification

**Refactoring:** Memperbaiki internal structure kode tanpa mengubah external functionality. Tujuannya: meningkatkan kualitas kode secara berkelanjutan.

---

## 9. Verification & Validation (VER & VAL) + Software Inspection

### 🔑 Perbedaan Kunci: Verification vs Validation

| Verification | Validation |
|---|---|
| "Did we **build the product right**?" | "Did we **build the right product**?" |
| Apakah memenuhi spesifikasi/requirements? | Apakah memenuhi kebutuhan pengguna sesungguhnya? |
| Pastikan kita membangun dengan benar | Pastikan kita membangun yang benar |
| Focus: requirements & design | Focus: user needs & intended environment |

> Keduanya menggunakan teknik yang serupa, keduanya berlaku di seluruh product lifecycle, dan bisa dilakukan concurrently. Bahkan satu aktivitas review bisa memenuhi Verification DAN Validation sekaligus.

### 🔵 VERIFICATION (VER) — Maturity Level 3

**Tujuan:** Memastikan selected work products memenuhi specified requirements.

#### SG 1: Prepare for Verification
**SP 1.1 Select Work Products for Verification**
Identifikasi work products yang akan diverifikasi dan metode yang akan digunakan:
- Work products: Software Requirement Document, Software Design, Source Code
- Methods: Peer Reviews/Inspections, Static Analysis (SonarQube, Coverity), Traceability Audits, Testing, Demonstrations

**SP 1.2 Establish the Verification Environment**
Siapkan environment untuk verifikasi:
- Static Analysis Setup: server dengan automated tools dan specific rule sets
- Dedicated Test Lab: isolated environment dengan berbagai OS/browser/hardware
- Peer Review Infrastructure: shared digital workspaces dan checklists (Gerrit, GitHub PRs)
- Unit Testing Frameworks: pre-configured environments dengan mocking libraries

**SP 1.3 Establish Verification Procedures and Criteria**
Tentukan kriteria "verified" untuk setiap work product:
- *Software Requirements (SRS):* Traceability, Testability, Unambiguity, Consistency
- *Software Design:* Interface Integrity, Adherence to Architecture, Feasibility
- *Source Code:* Coding Standards, Cyclomatic Complexity, Compiler Warning Level

#### SG 2: Perform Peer Reviews
**SP 2.1 Prepare for Peer Reviews** — kirim dokumen dan checklist 48 jam sebelum meeting
**SP 2.2 Conduct Peer Reviews** — "Code Walkthrough": developer menjelaskan logikanya sementara peers menunjukkan potensi edge-case failures atau violations
**SP 2.3 Analyze Peer Review Data** — catat jumlah defects yang ditemukan, tipenya ("logic error" vs "typo"), waktu review → goldmine untuk process improvement

#### SG 3: Verify Selected Work Products
**SP 3.1 Perform Verification** — gunakan metode dan kriteria yang sudah ditetapkan
**SP 3.2 Analyze Verification Results** — analisis data untuk melihat di mana produk gagal memenuhi requirements; cari trends (misal: "60% defects berhubungan dengan database connection strings")
**SP 3.3 Perform Corrective Action** — track defects ke closure (log di Jira, assign ke developer, re-verify fix)

### 🟢 VALIDATION (VAL) — Maturity Level 3

**Tujuan:** Mendemonstrasikan bahwa produk atau product component memenuhi intended use ketika ditempatkan di intended environment.

#### SG 1: Prepare for Validation
**SP 1.1 Select Products for Validation** — produk dan product component requirements/designs, system, HW/SW, service documentation
**SP 1.2 Establish the Validation Environment** — automated testing environment, dedicated computing/network, production environment, QA Engineer dan Testers
**SP 1.3 Establish Validation Procedures and Criteria** — acceptance criteria customer, environmental performance thresholds (response time, availability)

**Teknik Validasi:**
- Static: design reviews, program inspections, mathematical proofs
- Dynamic: statistical testing, scenario-based testing, run-time checking
- Process validation: SE processes meminimalisir chances of introducing defects

#### SG 2: Validate Product or Product Components
**SP 2.1 Perform Validation** — prototype demonstrations, pilots, tests by end users
**SP 2.2 Analyze Validation Results** — analisis apakah produk memenuhi intended use

**Validation Perspectives:**
- Reliability validation: apakah measured reliability memenuhi specification?
- Safety validation: apakah sistem beroperasi tanpa accidents?
- Security validation: apakah sistem aman dari external attack?

### 🔎 Software Review & Inspection

Reviews adalah cara ampuh mendeteksi dan mengoreksi defects **lebih awal** dalam development, sebelum makin mahal untuk diperbaiki.

**Definisi:**
- **Defect (Error):** Masalah kualitas yang ditemukan sebelum software dirilis ke end users
- **Bug/Defect (post-release):** Masalah kualitas yang ditemukan setelah software dirilis ke end users

**Tipe-tipe Review (dari informal ke formal):**

| Tipe | Karakteristik |
|---|---|
| **Buddy Checking** | Informal, tidak ada checklist, tidak ada data collection, sulit dikontrol |
| **Walkthrough** | Author "walk through" dokumen ke audiens peers. Sedikit persiapan, sedikit dokumentasi |
| **Review by Circulation** | Artifact beredar ke peers untuk dikomentari. Ada dokumentasi issues, minimal data collection |
| **Inspection (Fagan 1976)** | Formal dan terstruktur, ada roles yang jelas, data dikumpulkan, ada quantitative goals, menggunakan inspection criteria yang jelas |

### 📋 Proses Inspection (Fagan Inspection)
Tahapan lengkap berdasarkan Gilb & Graham:

1. **Entry** — Author meminta artifact untuk di-inspect. Moderator memverifikasi entry criteria terpenuhi.
2. **Planning** — Moderator menentukan ukuran dan komposisi tim, goals, timing.
3. **Kickoff Meeting** — Roles di-assign, dokumen didistribusikan, checklist dibagikan.
4. **Individual Checking** — **Mayoritas defects ditemukan di sini.** Setiap reviewer membaca artifact dengan panduan checklist, mencatat issues dan severity.
5. **Logging Meeting** — Meeting terencana untuk mencatat issues yang ditemukan. Setiap issue dicatat satu kali saja.
6. **Edit** — Editor (biasanya author) mengatasi semua logged issues. Semua defects harus diperbaiki.
7. **Follow Up dan Exit** — Moderator memverifikasi semua defects ditangani. Hitung metrics.

**Roles dalam Inspection:**
- **Moderator/Leader** — memimpin keseluruhan proses
- **Author/Producer** — pencipta artifact yang di-inspect
- **Reviewer/Reader** — membaca dan menemukan defects
- **Scribe** — mencatat issues

**Defect Classification:**
- **Severity:** Major (akan menyebabkan masalah jika tidak diperbaiki) atau Minor
- **Type:** Missing, Extra, Wrong

**Inspection Metrics:**
- Total Defects Found = A + B - C (A dan B adalah jumlah yang ditemukan masing-masing reviewer, C adalah yang ditemukan keduanya)
- Estimated Total Defects = AB/C
- **Yield** = Total Defects Found / Estimated Total Defects × 100%
- **Defect Density** = Total Defects Found / Size
- **Inspection Rate** = Size / Total Inspection Hours

**Agile dan Reviews:**
- Dalam Scrum: ada Sprint Review setelah setiap iterasi selesai
- XP: pair programming = proses inspeksi berkelanjutan — dua orang melihat setiap baris kode
- Agile biasanya menggunakan review **informal**, tidak menggunakan formal inspection

### Scrum Ceremonies yang Diperkuat VER & VAL

| Ceremony | VER/VAL Practices |
|---|---|
| Continuous Build/Integration | VER SG1, VAL SG1 |
| Definition of Done | VER SG1, VAL SG1 |
| Pair Programming | VER SG2 (peer review), VAL SG2 |
| Sprint Demo/Sprint Review | VER SG3, VAL SG2 |
| Test Driven Development | VER SG3, VAL SG2 |
| User Stories | VER SG1, VAL SG1 |
| Refactoring | VER SG2, VAL SG2 |

---

## 10. The Essence of SE & Agnostic Scaling Agile (ASA) Model

### 🧩 The Essence of Software Engineering

**Konteks:** Software Engineering tidak kekurangan teori. Setiap beberapa tahun muncul tren baru (OO → UML/RUP → CMMI → XP → Scrum/Kanban). Semua bagus, tapi tidak ada yang memiliki segalanya.

**The Essence** dibuat pada 2014 oleh SEMAT (Software Engineering Method and Theory) dan OMG (Object Management Group):
- Mendeskripsikan **common ground** pengembangan software → disebut **"the kernel"**
- Merupakan standar internasional OMG
- Agnostik terhadap metode — bisa mendeskripsikan metode pengembangan apapun
- Membantu orang belajar tentang software dan praktiknya

### 📐 The Essence Kernel
Kernel mendefinisikan konsep-konsep penting yang umum bagi semua yang bekerja di domain software engineering. Ini adalah skeletal practice framework di mana berbagai Practice bisa berhasil digunakan bersama.

### 🔑 Elemen-Elemen Essence

| Elemen | Definisi | Contoh dalam Scrum |
|---|---|---|
| **Activity** | Pelaksanaan pekerjaan oleh satu orang atau lebih | Coding, Daily Stand-Up, Backlog Refinement |
| **Alpha** | Aspek utama/elemen kunci yang diperlukan untuk progress. Alpha state = indikator progress. | Sprint Alpha: "scheduled" → "planned" → "reviewed" |
| **Work Product** | Artefak atau hasil kerja yang memiliki nilai | Source Code, Project Plan, Kanban Board, Burndown Chart |
| **Competency** | Kemampuan, pengetahuan, dan keterampilan yang diperlukan | Leadership, Testing Skill, Development Skill |
| **Pattern** | Panduan umum (Role, Milestone, Game, Technique) | Product Owner, Scrum Master, Milestones, Brainstorming |

**Kegunaan Essence:**
- Memberikan *common understanding* dan vocabulary untuk mendeskripsikan metode
- Memungkinkan metode lebih mudah dipahami, direvisi, dibandingkan, dievaluasi
- **Scrum Essentials Cards**: Ivar Jacobson (penggagas Essence) + Jeff Sutherland (penggagas Scrum) membuat gambaran Scrum dalam bahasa Essence

### 📈 Scaling Agile

**Tiga Level Agile:**
1. **Team Level Agility** — 1–2 tim, proyek skala kecil
2. **Enterprise Agility (Scaled Agile)** — 3–10+ tim, 24–100+ anggota. Framework: SAFe, Nexus, Scrum@Scale, Spotify Agile
3. **Business Level Agility** — Agile terintegrasi ke seluruh aspek bisnis (HR, finance, marketing, dll.)

**Tantangan Scaling Agile (17th State of Agile Report, 2023):**
- Mendefinisikan Large Scaled Agile framework yang sesuai organisasi
- Membandingkan dan memilih framework yang paling sesuai
- Agile tailoring untuk menyesuaikan keadaan dan karakteristik organisasi

### 🔑 The Essence of Scaling Agile
Elemen-elemen esensial yang harus ada agar Scaling Agile dapat berjalan dengan baik, **tanpa terikat ke framework manapun**:

| Elemen | Tipe | Definisi | Contoh |
|---|---|---|---|
| Product Owner | Pattern | Menentukan fitur dan value | SAFe PO, Nexus PO, Scrum@Scale PO |
| Agile Master | Pattern | Coach & process leader | SAFe Scrum Master, Nexus SM |
| Development Team | Pattern | Tim self-organized cross-functional | — |
| Integration | Activity | Aktivitas integrasi komponen | Nexus NIT, SAFe ART/RTE, LeSS CI |
| System Architect | Pattern | Mendefinisikan dan maintain arsitektur | SAFe System Architect |
| Scaled Product Owner | Pattern | PO skala besar, koordinasi antar sub-PO | SAFe Product Management, Spotify Trio |
| Scaled Agile Master | Pattern | Koordinasi lintas tim | Nexus IT, Spotify Tribe Leader |
| Team Backlog | Work Product | Daftar pekerjaan tim | SAFe Team Backlog, Scrum Sprint Backlog |
| Scaled Backlog | Work Product | Backlog lintas tim | SAFe Program Backlog, Nexus Sprint Backlog |
| Cycle | Alpha | Iterasi Agile | Sprint, Iteration (SAFe) |
| Cycle Planning | Activity | Perencanaan siklus | Sprint Planning |
| Scaled Cycle Planning | Activity | Perencanaan lintas tim, manage interdependencies | PI Planning (SAFe), Nexus Sprint Planning |
| Team Coordination Meeting | Activity | Sinkronisasi internal tim | Daily Scrum |
| Scaled Coordination Meeting | Activity | Sinkronisasi lintas tim | Nexus Daily Scrum, Scrum@Scale SDS |
| User Review | Activity | Review hasil iterasi terintegrasi | System Demo, Sprint Review |
| Requirement Management | Activity | Elicitation, refinement, prioritizing, dll. | Backlog Refinement |
| Success Criteria | Work Product | Kriteria keberhasilan berbagai level | Definition of Done, Acceptance Criteria |
| Release Management | Activity | Pengelolaan release | Release on Demand, Continuous Release |
| Cycle Goal | Work Product | Tujuan dalam satu iterasi | Sprint Goal, PI Objectives |
| Scaled Cycle Goal | Work Product | Tujuan siklus lintas tim | Nexus Sprint Goal, PI Objectives |
| Cycle Output | Work Product | Increment terintegrasi | Increment, Solution |
| Continuous Improvement | Alpha | Peningkatan cara kerja | Retrospective, SAFe IP Iteration |
| Team Retrospective | Activity | Retrospektif tim | Sprint Retrospective |
| Scaled Retrospective | Activity | Retrospektif lintas tim | Inspect & Adapt, Nexus Sprint Retro |
| Value Management | Activity | Menjaga value bisnis | SAFe Product Management |
| Configuration Management | Alpha | Version control & audit | Git, CI/CD pipelines |
| Management Ownership | Competency | Dukungan manajemen | SAFe Lean-Agile Leadership |
| Metrics and Standards | Work Product | Mengukur performa proses/kualitas | — |

### 🏗️ Agnostic Scaling Agile (ASA) Model

**ASA Model** adalah model yang menggambarkan Scaling Agile secara agnostik — tanpa bias ke salah satu framework Scaling Agile yang ada. Terdiri dari:
1. **The Essence of Scaling Agile** — elemen-elemen esensial
2. **Mapping** ke Practice Area (PA) pada CMMI v2 yang relevan

**Kegunaan ASA Model:**
- Assessment Capability Level / Maturity Level proses Scaling Agile
- Membantu mengukur **readiness** organisasi dalam implementasi Scaling Agile
- Proses pemilihan framework scaling agile tertentu
- Tailoring framework atau proses scaling agile
- Panduan implementasi dan adopsi scaling agile secara bertahap

### 📊 Scaling Agile Maturity Level (Berdasarkan ASA Model)

| Maturity Level | Syarat |
|---|---|
| ML 1 | Capability Level 1 pada semua elemen the Essence of Scaling Agile |
| ML 2 | Capability Level 2 pada semua elemen |
| ML 3 | Capability Level 3 pada semua elemen (kecuali PA CM yang maksimum hanya bisa CL 2) |

### 🌐 Hybrid Approach
Kombinasi Waterfall + Agile semakin populer:
- 71% organisasi menggunakan Agile methodologies (Digital.ai survey)
- 42% menggunakan hybrid approach
- PMI 2024: adopsi Agile dan hybrid meningkat 43% dari 2020–2023, mencapai 56.1%

The Essence dan ASA Model dapat digunakan sebagai tools untuk **tailoring** metodologi yang telah ada (baik Agile, konvensional, maupun campuran).

---

## 💡 Ringkasan Konsep Kunci untuk UAS

| Konsep | Inti yang Harus Dipahami |
|---|---|
| **Agile Hangover** | Agile tanpa keunggulan teknis = produksi perangkat lunak berkualitas rendah dengan lebih cepat |
| **Software Craftsmanship** | Ideologi profesionalisme pelengkap Agile — bukan pengganti. Fokus pada well-crafted code |
| **TDD** | Tulis test dulu (gagal), baru tulis minimum code, lalu bersihkan. Simultaneously Verification & Validation |
| **CMMI Maturity Levels** | 1=Chaotic, 2=Managed/Repeatable, 3=Defined, 4=Quantitatively Managed, 5=Optimizing |
| **Verification vs Validation** | VER: "Build it right?" (sesuai spec). VAL: "Build the right thing?" (sesuai kebutuhan user) |
| **Staged vs Continuous** | Staged: naik level bersama-sama. Continuous: tiap PA naik sendiri-sendiri |
| **The Essence** | Common ground, agnostik metode, kernel yang mendeskripsikan elemen esensial SE |
| **ASA Model** | Model Scaling Agile agnostik yang memapping Essence + CMMI v2 |
| **Backlog Grooming** | Merupakan salah satu ceremony yang paling kaya diperkuat oleh CMMI: REQM, RD, dan PP |
| **Technical Debt** | Solusi less-optimal yang sengaja dipilih karena constraints. Harus dikelola agar tidak menumpuk |

---

*Catatan belajar ini disusun berdasarkan slide materi UAS DTPL — Magister Teknologi Informasi, Universitas Indonesia*
