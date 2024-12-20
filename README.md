<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio M. Holil</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .gradient-bg {
            background: linear-gradient(90deg, #4f46e5, #3b82f6);
        }
    </style>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Header -->
    <header class="gradient-bg text-white p-4 md:p-6 shadow-lg sticky top-0 z-50">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl md:text-3xl font-extrabold">M. Holil Portfolio</h1>
        </div>
        <nav class="overflow-x-auto whitespace-nowrap bg-opacity-90 backdrop-blur p-2 md:p-4">
            <ul class="flex space-x-4 justify-center">
                <li><a href="#about" class="hover:underline text-white font-semibold">Tentang</a></li>
                <li><a href="#skills" class="hover:underline text-white font-semibold">Keahlian</a></li>
                <li><a href="#education" class="hover:underline text-white font-semibold">Pendidikan</a></li>
                <li><a href="#projects" class="hover:underline text-white font-semibold">Proyek</a></li>
                <li><a href="#contact" class="hover:underline text-white font-semibold">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <!-- Tentang -->
    <section id="about" class="bg-white py-10 md:py-20" data-aos="fade-up">
        <div class="container mx-auto px-4 md:px-6 text-center">
            <div class="mb-6">
                <img src="https://via.placeholder.com/150" alt="Foto Profil M. Holil" class="w-32 h-32 md:w-48 md:h-48 rounded-full mx-auto shadow-lg">
            </div>
            <h2 class="text-3xl md:text-4xl font-extrabold text-gray-800 mb-4">Tentang Saya</h2>
            <p class="text-gray-600 leading-loose text-base md:text-lg">Halo! Nama saya <strong>M. Holil</strong>. Saat ini saya sedang menempuh pendidikan di Universitas Yatsi Madani. Saya sedang mempelajari teknologi web seperti PHP dan MySQLi, serta tertarik untuk mengembangkan aplikasi berbasis web yang modern dan efisien.</p>
        </div>
    </section>

    <!-- Keahlian -->
    <section id="skills" class="bg-gray-100 py-10 md:py-20" data-aos="fade-up">
        <div class="container mx-auto px-4 md:px-6">
            <h2 class="text-3xl md:text-4xl font-extrabold text-center text-gray-800 mb-8">Keahlian</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 md:gap-6">
                <div class="bg-white p-4 rounded-lg shadow-md text-center">
                    <i class="fas fa-code text-3xl md:text-4xl text-blue-500 mb-2"></i>
                    <h3 class="text-lg md:text-xl font-bold">PHP</h3>
                    <p class="text-gray-600 text-sm md:text-base">Pengembangan aplikasi berbasis server menggunakan PHP.</p>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md text-center">
                    <i class="fas fa-database text-3xl md:text-4xl text-blue-500 mb-2"></i>
                    <h3 class="text-lg md:text-xl font -bold">MySQLi</h3>
                    <p class="text-gray-600 text-sm md:text-base">Mengelola database relasional dengan MySQLi.</p>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md text-center">
                    <i class="fas fa-desktop text-3xl md:text-4xl text-blue-500 mb-2"></i>
                    <h3 class="text-lg md:text-xl font-bold">HTML & CSS</h3>
                    <p class="text-gray-600 text-sm md:text-base">Membuat tampilan web responsif dan modern.</p>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-md text-center">
                    <i class="fas fa-tools text-3xl md:text-4xl text-blue-500 mb-2"></i>
                    <h3 class="text-lg md:text-xl font-bold">Tailwind CSS</h3>
                    <p class="text-gray-600 text-sm md:text-base">Mendesain antarmuka pengguna dengan framework Tailwind CSS.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Riwayat Pendidikan -->
    <section id="education" class="bg-white py-10 md:py-20" data-aos="fade-up">
        <div class="container mx-auto px-4 md:px-6">
            <h2 class="text-3xl md:text-4xl font-extrabold text-center text-gray-800 mb-8">Riwayat Pendidikan</h2>
            <ul class="space-y-4">
                <li class="bg-gray-50 p-4 rounded-lg shadow-lg flex items-center">
                    <i class="fas fa-school text-3xl md:text-4xl text-blue-500 mr-4"></i>
                    <div>
                        <h3 class="text-xl md:text-2xl font-bold">Universitas Yatsi Madani</h3>
                        <p class="text-gray-600">Sarjana Teknik Informatika - 2021 - Sekarang</p>
                    </div>
                </li>
                <li class="bg-gray-50 p-4 rounded-lg shadow-lg flex items-center">
                    <i class="fas fa-school text-3xl md:text-4xl text-blue-500 mr-4"></i>
                    <div>
                        <h3 class="text-xl md:text-2xl font-bold">SMA Negeri 1 [Nama Kota]</h3>
                        <p class="text-gray-600">Jurusan IPA - 2018 - 2021</p>
                    </div>
                </li>
            </ul>
        </div>
    </section>

    <!-- Proyek -->
    <section id="projects" class="bg-gray-100 py-10 md:py-20" data-aos="fade-up">
        <div class="container mx-auto px-4 md:px-6">
            <h2 class="text-3xl md:text-4xl font-extrabold text-center text-gray-800 mb-8">Proyek</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-6">
                <div class="bg-white p-4 rounded-lg shadow-lg">
                    <i class="fas fa-laptop-code text-3xl md:text-4xl text-blue-500 mb-2"></i>
                    <h3 class="text-xl md:text-2xl font-bold">Aplikasi Manajemen Data</h3>
                    <p class="text-gray-600">Sistem manajemen data berbasis web menggunakan PHP dan MySQLi.</p>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-lg">
                    <i class="fas fa-laptop-code text-3xl md:text-4xl text-blue-500 mb-2"></i>
                    <h3 class="text-xl md:text-2xl font-bold">Website Portofolio</h3>
                    <p class="text-gray-600">Website pribadi untuk menampilkan keahlian dan proyek.</p>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-lg">
                    <i class="fas fa-laptop-code text-3xl md:text-4xl text-blue-500 mb-2"></i>
                    <h3 class="text-xl md:text-2xl font-bold">Sistem Reservasi</h3>
                    <p class="text-gray-600">Aplikasi reservasi sederhana untuk pengelolaan tempat duduk.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Kontak -->
    <section ```html
    id="contact" class="bg-white py-10 md:py-20" data-aos="fade-up">
        <div class="container mx-auto px-4 md:px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-extrabold text-gray-800 mb-4">Kontak</h2>
            
            <div class="flex flex-col md:flex-row justify-center space-y-4 md:space-y-0 md:space-x-8">
                <div>
                    <a href="mailto:mholil@example.com" class="text-blue-500 text-lg md:text-xl font-bold"><i class="fas fa-envelope"></i> mholil@example.com</a>
                </div>
                <div>
                    <a href="https://linkedin.com/in/mholil" class="text-blue-500 text-lg md:text-xl font-bold"><i class="fab fa-linkedin"></i> LinkedIn</a>
                </div>
                <div>
                    <a href="https://instagram.com/username" class="text-blue-500 text-lg md:text-xl font-bold"><i class="fab fa-instagram"></i> Instagram</a>
                </div>
                <div>
                    <a href="https://wa.me/1234567890" class="text-blue-500 text-lg md:text-xl font-bold"><i class="fab fa-whatsapp"></i> WhatsApp</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="gradient-bg text-white p-4 md:p-6 text-center">
        <p class="font-semibold">&copy; 2024 Portfolio M. Holil. All rights reserved.</p>
    </footer>

    <script>
        AOS.init();
    </script>
</body>
</html>
