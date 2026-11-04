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
  </style>
</head>
<body>
  <div class="card">
    <h1>Profil Mahasiswa</h1>
    <h2>Nama:nasywa kayana</h2>
    <p>Program Studi: Manajemen Informasi Komunikasi</p>
    <p>Saya sedang belajar Cloud Computing.</p>
    <p>Instagram:@nnasywakyn.</p>
    <p>Email: mahasiswa@email.com</p>
  </div>
</body>
</html>
