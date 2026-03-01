# PBW-Minpro-1-Portofolio

# Portfolio Jihan

### Nama: Jihan Alya Naflah
### NIM:  2409116082



## Tampilan Website
Website portofolio yang menampilkan profil, skill, pengalaman, dan sertifikat.

### 1. Home (Hero Section)
Berisi perkenalan singkat dan foto.
<img width="1353" height="644" alt="image" src="https://github.com/user-attachments/assets/88264ecd-e4bd-4342-be95-2a916fbcee5f" />



### 2. About Me
Deskripsi diri singkat, Skills dengan progress bar, dan Hobbies.
<img width="1360" height="641" alt="image" src="https://github.com/user-attachments/assets/462429e0-2df2-481d-94c6-32127432d197" />



### 3. Experience
Daftar pengalaman dalam bentuk card.
<img width="1362" height="627" alt="image" src="https://github.com/user-attachments/assets/61566951-2f70-4bbf-8eb2-cd49548626ef" />


### 4. Certificates
Daftar sertifikat dalam bentuk card grid.
<img width="1366" height="638" alt="image" src="https://github.com/user-attachments/assets/453e86b1-47de-40e8-ad4a-ccee98e71b25" />




## Penjelasan Code

- **Navbar**
  Navigasi ke setiap section (Home, About, Experience, Certificates).
  
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Portfolio JihanAly</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>

<body>


    <nav>
        <div class="logo">Jihanly</div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#certificates">Certificates</a></li>
        </ul>
    </nav>

Navbar berisi logo ‘Jihanly’ di kiri dan menu navigasi ke section Home, About, Experience, dan Certificates yang tetap terlihat saat halaman di-scroll.


- **Home Section**  
 <img width="559" height="292" alt="image" src="https://github.com/user-attachments/assets/938a52fb-e6e3-42b7-88e2-06b71c19e433" />


 Home section menampilkan perkenalan singkat Jihan Alya Naflah dengan teks, foto, dan elemen dekoratif lingkaran mengambang di samping foto.

 
- **About Me Section**  
 <section id="about" class="about">
        <h2>About Me</h2>
        <p>
        Saya merupakan mahasiswa aktif Program Studi Sistem Informasi semester 4 di Universitas Mulawarman. Saya menikmati proses belajar dan mengeksplorasi hal baru, terutama dalam bidang teknologi. Bagi saya, setiap proses pembelajaran adalah kesempatan untuk berkembang dan meningkatkan kemampuan diri. 
        </p>

        <h3>Skills</h3>

        <div class="skill">
            <span>HTML</span>
            <div class="progress"><div style="width: 70%"></div></div>
        </div>

About Me menampilkan deskripsi diri, daftar skills, serta hobi yang dilengkapi ikon visual.


- **Experience Section**  
   <section id="experience" class="experience">
    <h2>Experience</h2>

    <div class="card-container">

        <div class="card">
            <h4>Kepengurusan INFORSA</h4>
            <p>Anggota Departemen ADWEL – 2025</p>
            <small>
                Berperan dalam mendukung pelaksanaan program kerja organisasi.
            </small>
        </div>

        <div class="card">
            <h4>Akselerasi Pengenalan Lingkungan Kampus Sistem Informasi</h4>
            <p>Anggota Divisi Kesehatan & Konsumsi – 2025</p>
        </div>

        <div class="card">
            <h4>Desain X-Banner Kegiatan Mahasiswa</h4>
            <p>Project Design – 2025</p>
            <small>
                Mendesain media publikasi kegiatan menggunakan Canva.
            </small>
        </div>

    </div>
</section>


Experience menampilkan daftar pengalaman dalam organisasi, disajikan dalam bentuk card yang memuat judul, posisi, dan deskripsi singkat.


- **Certificates Section**  
 <section id="certificates" class="certificates">
    <h2>Certificates</h2>

    <div class="card-container">
        <div class="card">
            <img src="Sertifikasi Aplikasi.jpeg" alt="Sertifikat 1">
            <h4>Akselerasi Pengenalan Lingkungan Kampus</h4>
            <p>Anggota Divisi Kesehatan & Konsumsi – INFORSA – 2025</p>
        </div>

        <div class="card">
            <img src="Sertifikat Insevent.jpg" alt="Sertifikat 2">
            <h4>INSEVENT</h4>
            <p>Panitia – INFORSA – 2025</p>
        </div>

        <div class="card">
            <img src="Sertifikat Kuliah Umum.jpg" alt="Sertifikat 3">
            <h4>Kuliah Umum</h4>
            <p>Peserta – Universitas Mulawarman – 2024</p>
        </div>
    </div>
</section>

Certificates menampilkan daftar sertifikat dalam bentuk card yang memuat gambar sertifikat, judul, dan keterangan singkat.


- **Skills & Hobbies**
          <h3>Skills</h3>

        <div class="skill">
            <span>HTML</span>
            <div class="progress"><div style="width: 70%"></div></div>
        </div>


        <div class="skill">
            <span>MySQL</span>
            <div class="progress"><div style="width:75%"></div></div>
        </div>

        <div class="skill">
            <span>Python</span>
            <div class="progress"><div style="width:75%"></div></div>
        </div>

        <h3>Tools</h3>

        <div class="skill">
            <span>Microsoft Word</span>
            <div class="progress"><div style="width:85%"></div></div>
        </div>


        <div class="hobbies">
    <h3>Hobbies</h3>

    <div class="hobby-list">

        <div class="hobby-item">
            <i class="fas fa-book"></i>
            <span>Membaca Buku</span>
        </div>

        <div class="hobby-item">
            <i class="fas fa-film"></i>
            <span>Menonton Film</span>
        </div>

        <div class="hobby-item">
            <i class="fas fa-music"></i>
            <span>Mendengarkan Musik</span>
        </div>

    </div>
</div>


 Skills menampilkan kemampuan dalam berbagai bidang, sedangkan Hobbies menampilkan kegiatan favorit menggunakan ikon Font Awesome.


## Teknologi yang Digunakan

- HTML5  
- CSS3  
- Google Fonts  
- Font Awesome (ikon)  



