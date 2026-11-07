# Materi Workshop

## Building with AI, Managing Change with GitHub

### 1. Prompt Engineering

Prompt Engineering merupakan cara merancang instruksi agar AI dapat memberikan jawaban yang tepat, relevan, dan sesuai dengan kebutuhan.

Prompt adalah instruksi atau masukan yang diberikan kepada model untuk mendapatkan hasil tertentu.

### 2. Context dalam Prompt

Context atau konteks diperlukan agar AI dapat memahami kebutuhan dari instruksi yang diberikan.

Prompt yang memiliki konteks yang jelas dapat menghasilkan output yang lebih sesuai dibandingkan prompt yang terlalu umum.

### 3. Struktur Prompt

Struktur prompt yang dipelajari terdiri dari:

- **Role** — menentukan peran AI.
- **Task** — menentukan tugas yang harus dilakukan.
- **Context** — memberikan konteks atau informasi pendukung.
- **Format** — menentukan bentuk output yang diinginkan.

### 4. Git

Git merupakan version control system yang digunakan untuk melacak dan mengelola perubahan pada suatu project.

### 5. GitHub

GitHub merupakan platform berbasis web yang digunakan untuk menyimpan repository Git secara online dan mendukung kolaborasi.

### 6. Perbedaan Git dan GitHub

**Git** digunakan untuk version control dan mengelola perubahan project.

**GitHub** digunakan sebagai platform online untuk menyimpan repository Git dan mendukung kolaborasi.

### 7. Git Workflow

Git memiliki beberapa bagian penting:

- **Working Directory** — tempat file project yang sedang dikerjakan.
- **Staging Area** — tempat perubahan yang akan dimasukkan ke commit.
- **Repository** — tempat Git menyimpan riwayat dan data project.

### 8. Git Command Dasar

```bash
git init
```

Digunakan untuk memulai repository Git.

```bash
git add .
```

Digunakan untuk menambahkan perubahan ke staging area.

```bash
git commit -m "message"
```

Digunakan untuk menyimpan perubahan ke repository.

```bash
git push origin main
```

Digunakan untuk mengirim perubahan ke repository GitHub.

```bash
git pull origin main
```

Digunakan untuk mengambil perubahan dari repository.

### 9. Git Setup

Untuk mengecek versi Git:

```bash
git --version
```

Konfigurasi identitas Git:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### 10. VS Code

VS Code digunakan sebagai salah satu lingkungan untuk mengerjakan project.

Versi VS Code dapat dicek melalui terminal dengan:

```bash
code --version
```

### 11. Repository dan GitHub

Repository lokal dapat dihubungkan dengan repository GitHub menggunakan remote.

Contoh:

```bash
git remote add origin <url>
```

Kemudian perubahan dapat dikirim menggunakan:

```bash
git push origin main
```

### 12. SSH Key

SSH Key dapat digunakan untuk menghubungkan komputer dengan GitHub.

Contoh pembuatan SSH key:

```bash
ssh-keygen -t ed25519 -C "email@domain.com"
```

Koneksi SSH dapat dicek dengan:

```bash
ssh -T git@github.com
```

### 13. Student Task Planner

Pada bagian praktik workshop, peserta membuat project **Student Task Planner**.

Project ini digunakan untuk membantu mahasiswa mengelola tugas dan deadline.

Alur praktik meliputi:

1. Menggunakan AI-assisted platform.
2. Membuat prompt untuk project.
3. Menggunakan `git init`.
4. Melakukan commit.
5. Melakukan push ke GitHub.
6. Melakukan perubahan pada project.
7. Melakukan commit dan push kembali.  
