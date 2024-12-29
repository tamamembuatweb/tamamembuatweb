<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Panduan Tata Tertib Lalu Lintas</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Panduan Tata Tertib Lalu Lintas</h1>
        <nav>
            <ul>
                <li><a href="#home">Beranda</a></li>
                <li><a href="#guidelines">Panduan</a></li>
                <li><a href="#tips">Tips Aman</a></li>
                <li><a href="#about">Tentang Penulis</a></li>
                <li><a href="#contact">Kontak</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Selamat Datang</h2>
            <p>Web ini bertujuan memberikan informasi penting tentang tata tertib berlalu lintas di Indonesia.</p>
        </section>
        <section id="guidelines">
            <h2>Panduan Tata Tertib</h2>
            <ul>
                <li>Mematuhi rambu lalu lintas.</li>
                <li>Menggunakan helm SNI saat mengendarai motor.</li>
                <li>Memiliki SIM dan STNK yang berlaku.</li>
                <!-- Tambahkan poin lainnya -->
            </ul>
        </section>
        <section id="tips">
            <h2>Tips Aman di Jalan</h2>
            <ul>
                <li>Selalu cek kondisi kendaraan sebelum berkendara.</li>
                <li>Jaga jarak aman dengan kendaraan lain.</li>
                <li>Jangan gunakan ponsel saat berkendara.</li>
            </ul>
        </section>
        <section id="about">
            <h2>Tentang Penulis</h2>
            <p>Halo! Saya [Nama Anda], seorang penggiat keselamatan berkendara. Saya membuat web ini untuk meningkatkan kesadaran akan pentingnya tata tertib lalu lintas.</p>
        </section>
        <section id="contact">
            <h2>Kontak</h2>
            <form>
                <label for="name">Nama:</label><br>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br><br>
                <label for="message">Pesan:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>
                <button type="submit">Kirim</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Panduan Tata Tertib Lalu Lintas. Semua Hak Dilindungi.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background: #0047ab;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

header ul {
    list-style: none;
    padding: 0;
}

header ul li {
    display: inline;
    margin: 0 10px;
}

header ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 2rem;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}

form input, form textarea, form button {
    width: 100%;
    padding: 0.5rem;
    margin: 0.5rem 0;
}

