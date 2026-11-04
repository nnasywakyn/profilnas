<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profil Mahasiswa - Eldaniz Yazzid Hatrawijaya</title>
  <!-- Mengambil Font & Ikon Modern -->
  <link rel="stylesheet" href="https://cloudflare.com">
  <style>
    /* Latar Belakang Soft Yellow Pastel dengan Animasi Halus */
    body { 
      font-family: 'Segoe UI', Roboto, sans-serif; 
      background: linear-gradient(-45deg, #fef9e7, #fcf3cf, #fcd116, #fef9e7);
      background-size: 400% 400%;
      animation: gradientBg 12s ease infinite;
      display: flex; 
      justify-content: center; 
      align-items: center; 
      min-height: 100vh; 
      margin: 0; 
      padding: 20px; 
      box-sizing: border-box; 
    }
    {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
     {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    { 
      background: white; 
      width: 100%; 
      max-width: 500px; 
      padding: 40px 30px; 
      border-radius: 24px; 
      box-shadow: 0 15px 35px rgba(0,0,0,0.08); 
      text-align: center;
      animation: fadeInUp 0.8s ease-out;
    }
    .profile-img { 
      width: 130px; 
      height: 130px; 
      border-radius: 50%; 
      object-fit: cover; 
      border: 4px solid #d4ac0d; 
      margin-bottom: 15px; 
      transition: transform 0.4s ease;
    }
    .profile-img:hover {
      transform: scale(1.08) rotate(3deg);
    }
    { color: #2c3e50; margin: 10px 0 5px 0; font-size: 26px; font-weight: 700; }
    .subtitle { color: #b7950b; font-size: 15px; margin-bottom: 20px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px; }
    .bio { color: #627d98; line-height: 1.6; font-size: 15px; margin-bottom: 25px; }
    h3 { color: #2c3e50; text-align: left; border-bottom: 2px solid #f0f4f8; padding-bottom: 8px; margin: 25px 0 15px 0; font-size: 16px; text-transform: uppercase; letter-spacing: 0.5px; }
    h3 i { color: #d4ac0d; margin-right: 5px; }
    .tag-container { display: flex; flex-wrap: wrap; gap: 8px; }
    .tag { 
      background: #f0f4f8; 
      color: #4b6584; 
      padding: 6px 14px; 
      border-radius: 20px; 
      font-size: 13px; 
      font-weight: 500; 
      transition: all 0.3s ease;
    }
    .tag:hover {
      background: #d4ac0d;
      color: white;
      transform: translateY(-2px);
    }
.contact-info { text-align: left; font-size: 14px; color: #4b6584; line-height: 2; }
    .contact-info i { color: #d4ac0d; margin-right: 8px; width: 16px; }
 .social-links { display: flex; justify-content: center; gap: 15px; margin-top: 30px; }
    .social-btn { 
      text-decoration: none; 
      color: white; 
      width: 45px; 
      height: 45px; 
      border-radius: 50%; 
      display: flex; 
      justify-content: center; 
      align-items: center; 
      font-size: 18px; 
      transition: all 0.3s ease; 
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }
    .social-btn:hover { transform: translateY(-5px); box-shadow: 0 8px 15px rgba(0,0,0,0.15); }
    
    .btn-email { background: #d4ac0d; }
    .btn-instagram { background: #e1306c; }
    .btn-github { background: #2f3640; }
  </style>
</head>
<body>
 <div class="card">
    <!-- PENTING: Ganti foto-profil.jpg dengan nama file foto asli Anda di komputer -->
    <img src="foto-profil.jpg" alt="Foto Eldaniz" class="profile-img">
    
    <h1>Eldaniz Yazzid Hatrawijaya</h1>
    <div class="subtitle">Manajemen Informasi dan Komunikasi</div>
    <p class="bio">Halo! Saya mahasigma yang antusias di dunia informasi dan teknologi. Saat ini sedang mendalami Cloud Computing dan senang mengubah ide menjadi karya digital yang bermanfaat.</p>
    
    <h3><i class="fa-solid fa-heart"></i> Hobi & Minat</h3>
    <div class="tag-container">
      <span class="tag">Cloud Computing</span>
      <span class="tag">Web Development</span>
      <span class="tag">Musik</span>
      <span class="tag">Nonton Sepakbola</span>
    </div>

    <h3><i class="fa-solid fa-code"></i> Kemampuan</h3>
    <div class="tag-container">
      <span class="tag">Cloud Computing</span>
      <span class="tag">HTML & CSS</span>
      <span class="tag">Komunikasi & Presentasi</span>
    </div>

    <h3><i class="fa-solid fa-address-book"></i> Kontak</h3>
    <div class="contact-info">
      <div><i class="fa-solid fa-envelope"></i> eldanizyazzid@gmail.com</div>
      <div><i class="fa-solid fa-location-dot"></i> Yogyakarta, Indonesia</div>
    </div>

    <div class="social-links">
      <a href="mailto:eldanizyazzid@gmail.com" class="social-btn btn-email" title="Email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://instagram.com" target="_blank" class="social-btn btn-instagram" title="Instagram"><i class="fa-brands fa-instagram"></i></a>
      <a href="https://github.com" target="_blank" class="social-btn btn-github" title="GitHub"><i class="fa-brands fa-github"></i></a>
  </div>
</body>
</html>
