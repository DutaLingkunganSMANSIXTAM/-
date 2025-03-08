GPBLHS SMAN 6 Tambun Selatan Present
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Duta Lingkungan & Adiwiyata Creative SMAN 6 Tambun Selatan</title>
    <style>
        :root {
            --primary: #2e7d32;
            --primary-light: #60ad5e;
            --primary-dark: #005005;
            --text-on-primary: #ffffff;
            --text-primary: #212121;
            --text-secondary: #757575;
            --background: #f9f9f9;
            --accent: #66bb6a;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--background);
            color: var(--text-primary);
            line-height: 1.6;
        }
        
        header {
            background-color: var(--primary);
            color: var(--text-on-primary);
            padding: 1.5rem;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        nav {
            background-color: var(--primary-dark);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 0.8rem 1rem;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: var(--text-on-primary);
            text-decoration: none;
            font-weight: 500;
            padding: 0.5rem 0.8rem;
            border-radius: 4px;
            transition: background-color 0.3s;
        }
        
        nav ul li a:hover {
            background-color: rgba(255,255,255,0.2);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }
        
        section {
            margin-bottom: 3rem;
        }
        
        h1 {
            font-size: 2.2rem;
            margin-bottom: 0.5rem;
        }
        
        h2 {
            font-size: 1.8rem;
            color: var(--primary-dark);
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--primary-light);
        }
        
        h3 {
            font-size: 1.4rem;
            color: var(--primary);
            margin: 1.2rem 0 0.8rem;
        }
        
        p {
            margin-bottom: 1rem;
        }
        
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            height: 100%;
            display: flex;
            flex-direction: column;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }
        
        .card-content {
            padding: 1.5rem;
            flex-grow: 1;
        }
        
        .card-title {
            font-size: 1.3rem;
            font-weight: 600;
            color: var(--primary-dark);
            margin-bottom: 0.8rem;
        }
        
        .card-description {
            color: var(--text-secondary);
            margin-bottom: 1rem;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--accent);
            color: var(--text-on-primary);
            padding: 0.6rem 1.2rem;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 500;
            transition: background-color 0.3s;
            text-align: center;
            margin-top: auto;
        }
        
        .btn:hover {
            background-color: var(--primary);
        }
        
        .duta-card {
            background-color: white;
            border-radius: 8px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        
        .duta-periode {
            font-weight: 600;
            color: var(--primary);
            margin-bottom: 0.8rem;
        }
        
        .duta-list {
            list-style: none;
        }
        
        .duta-list li {
            margin-bottom: 0.5rem;
        }
        
        .medsos {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 1rem;
        }
        
        .medsos a {
            color: var(--primary);
            text-decoration: none;
            display: flex;
            align-items: center;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .medsos a:hover {
            color: var(--primary-dark);
        }
        
        .medsos i {
            margin-right: 0.5rem;
            font-size: 1.2rem;
        }
        
        footer {
            background-color: var(--primary-dark);
            color: var(--text-on-primary);
            text-align: center;
            padding: 1.5rem;
            margin-top: 2rem;
        }
        
        .contact-info {
            margin-top: 1rem;
            font-size: 0.9rem;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                padding: 0;
            }
            
            nav ul li {
                margin: 0;
                text-align: center;
            }
            
            nav ul li a {
                display: block;
                padding: 0.8rem;
                border-radius: 0;
            }
            
            .grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Duta Lingkungan & Adiwiyata Creative</h1>
        <p>SMAN 6 Tambun Selatan</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#beranda">Beranda</a></li>
            <li><a href="#green-project">Green Project</a></li>
            <li><a href="#profil">Profil Sekolah</a></li>
            <li><a href="#duta">Duta Lingkungan</a></li>
            <li><a href="#kontak">Kontak</a></li>
        </ul>
    </nav>
    
    <main class="container">
        <section id="beranda">
            <h2>Selamat Datang</h2>
            <p>Selamat datang di website resmi Duta Lingkungan dan Adiwiyata Creative SMAN 6 Tambun Selatan. Kami berkomitmen untuk mengedukasi dan mengajak seluruh warga sekolah untuk peduli terhadap lingkungan hidup melalui berbagai kegiatan dan program berkelanjutan.</p>
            <p>Duta Lingkungan merupakan perwakilan siswa yang bertugas sebagai agen perubahan dalam menyebarkan kesadaran peduli lingkungan, sementara Tim Adiwiyata Creative fokus pada pengembangan kreativitas dan inovasi dalam program lingkungan hidup sekolah.</p>
        </section>
        
        <section id="green-project">
            <h2>Green Project 🌿</h2>
            <p>Green Project adalah inisiatif digital dan media sosial yang dikembangkan oleh Tim Adiwiyata Creative dan Duta Lingkungan SMAN 6 Tambun Selatan. Melalui project ini, kami berbagi informasi, tips, dan kegiatan terkait pengelolaan lingkungan hidup yang bisa diterapkan dalam kehidupan sehari-hari.</p>
            <div class="grid">
                <div class="card">
                    <div class="card-content">
                        <div class="card-title">Green Project Digital</div>
                        <div class="card-description">
                            Kumpulan konten edukatif dan informatif tentang lingkungan hidup yang dipublikasikan melalui berbagai platform digital. Kami membagikan tips sederhana, fakta menarik, dan ajakan untuk bersama-sama merawat lingkungan.
                        </div>
                        <a href="http://bit.ly/4icFdFg" class="btn" target="_blank">Lihat Green Project</a>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="profil">
            <h2>Profil Sekolah Adiwiyata</h2>
            <p>SMAN 6 Tambun Selatan telah menerapkan program Adiwiyata yang berfokus pada pembentukan karakter peduli lingkungan. Melalui berbagai program dan kegiatan, kami berusaha menciptakan lingkungan sekolah yang hijau, bersih, dan berkelanjutan.</p>
            <div class="grid">
                <div class="card">
                    <div class="card-content">
                        <div class="card-title">Video Profil Sekolah Adiwiyata</div>
                        <div class="card-description">
                            Mengenal lebih dekat SMAN 6 Tambun Selatan sebagai sekolah Adiwiyata yang memiliki komitmen kuat dalam pengelolaan lingkungan hidup. Video ini menampilkan berbagai program dan fasilitas pendukung program Adiwiyata di sekolah kami.
                        </div>
                        <a href="https://youtu.be/Q7H7QpRoF8U?si=PEtp1gWiC-ncEfTC" class="btn" target="_blank">Tonton Video</a>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="duta">
            <h2>Duta Lingkungan</h2>
            <p>Duta Lingkungan adalah siswa terpilih yang berperan sebagai teladan dan penggerak dalam upaya pelestarian lingkungan di sekolah. Mereka bertugas mengedukasi dan mengajak seluruh warga sekolah untuk aktif terlibat dalam program-program lingkungan hidup.</p>
            
            <div class="duta-card">
                <div class="duta-periode">Duta Lingkungan Periode 2024/2025</div>
                <ul class="duta-list">
                    <li>Adhi Kurnia Nugraha - XI.3</li>
                    <li>Siregar, Tiara Anastasia Enjelika - XI.5</li>
                </ul>
            </div>
            
            <div class="duta-card">
                <div class="duta-periode">Duta Lingkungan Periode 2023/2024</div>
                <ul class="duta-list">
                    <li>Raafi Febrian - XI.4</li>
                    <li>Kayla Putri Zafira - XII IPS 4</li>
                </ul>
            </div>
            
            <div class="duta-card">
                <div class="duta-periode">Duta Lingkungan Periode 2021/2022</div>
                <ul class="duta-list">
                    <li>Rizki Maulana - XII IPS 4</li>
                    <li>Vareza Maylina - XII IPA 5</li>
                </ul>
            </div>
            
            <h3>Media Sosial Duta Lingkungan</h3>
            <p>Ikuti kami di media sosial untuk mendapatkan update terbaru tentang kegiatan dan program Duta Lingkungan SMAN 6 Tambun Selatan:</p>
            
            <div class="medsos">
                <a href="https://www.instagram.com/dutalingkungan.smansix?igsh=cHVibnpyY3p4Y3Z2" target="_blank">
                    Instagram: @dutalingkungan.smansix
                </a>
                <a href="https://www.tiktok.com/@dutalingkungan.smansix?_t=ZS-8uWG2s" target="_blank">
                    TikTok: @dutalingkungan.smansix
                </a>
            </div>
        </section>
    </main>
    
    <footer id="kontak">
        <h3>Kontak Kami</h3>
        <p>Email: dutalingkungansmansix@gmail.com</p>
        <div class="contact-info">
            <p>SMAN 6 Tambun Selatan</p>
            <p>Jl. Raya Jatimulya, RT.001/RW.013, Jatimulya, Kec. Tambun Sel., Kota Bks, Jawa Barat 17510</p>
        </div>
    </footer>
</body>
</html>
