<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DDANZZ - Toko dan Portofolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .hero-bg {
            background-color: #f8fafc;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="bg-white text-gray-800">

    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center">
                <img src="http://googleusercontent.com/file_content/1" alt="Logo DDANZZ" class="h-10 w-auto">
            </a>
            <div class="hidden md:flex space-x-8">
                <a href="#beranda" class="text-gray-600 hover:text-blue-600">Beranda</a>
                <a href="#produk" class="text-gray-600 hover:text-blue-600">Produk</a>
                <a href="#tentang" class="text-gray-600 hover:text-blue-600">Tentang Saya</a>
                <a href="#kontak" class="text-gray-600 hover:text-blue-600">Kontak</a>
            </div>
            <div class="md:hidden">
                <button id="menu-btn" class="text-gray-600 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <a href="#beranda" class="block py-2 px-4 text-sm hover:bg-gray-100">Beranda</a>
            <a href="#produk" class="block py-2 px-4 text-sm hover:bg-gray-100">Produk</a>
            <a href="#tentang" class="block py-2 px-4 text-sm hover:bg-gray-100">Tentang Saya</a>
            <a href="#kontak" class="block py-2 px-4 text-sm hover:bg-gray-100">Kontak</a>
        </div>
    </header>

    <main>
        <!-- Bagian Beranda (Hero) -->
        <section id="beranda" class="hero-bg">
            <div class="container mx-auto px-6 py-24 text-center">
                <h1 class="text-4xl md:text-6xl font-bold text-gray-900 leading-tight">Selamat Datang di Toko DDANZZ</h1>
                <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">Temukan produk-produk berkualitas dan kenali saya lebih dekat. Tempat di mana kreativitas dan kualitas bertemu.</p>
                <a href="#produk" class="mt-8 inline-block bg-blue-600 text-white font-semibold px-8 py-3 rounded-lg shadow-lg hover:bg-blue-700 transition duration-300">Lihat Produk</a>
            </div>
        </section>

        <!-- Bagian Produk -->
        <section id="produk" class="py-20">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-12">Produk Unggulan</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-10">
                    
                    <!-- Produk 1: E-Book -->
                    <div class="bg-white rounded-lg shadow-lg overflow-hidden card-hover transition duration-300 flex flex-col">
                        <img src="http://googleusercontent.com/file_content/2" alt="Cover E-book Misteri Kebun Karet" class="w-full h-56 object-cover">
                        <div class="p-6 flex flex-col flex-grow">
                            <h3 class="text-xl font-semibold mb-2 product-name">Misteri Kebun Karet di Cibuluh</h3>
                            <p class="text-gray-600 mb-4 flex-grow">Sebuah e-book misteri yang akan membawa Anda ke dalam cerita penuh teka-teki di sebuah kebun karet yang kelam.</p>
                            <div class="text-2xl font-bold text-blue-600">Rp 15.000</div>
                            <button class="mt-4 w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700 transition duration-300">Unduh Sekarang</button>
                        </div>
                    </div>

                    <!-- Contoh Produk 2 -->
                    <div class="bg-white rounded-lg shadow-lg overflow-hidden card-hover transition duration-300 flex flex-col">
                        <img src="https://placehold.co/600x400/9CA3AF/FFFFFF?text=Segera+Hadir" alt="Gambar Produk 2" class="w-full h-56 object-cover">
                        <div class="p-6 flex flex-col flex-grow">
                            <h3 class="text-xl font-semibold mb-2 product-name">Dalam Masa Proses</h3>
                            <p class="text-gray-600 mb-4 flex-grow">Produk baru akan segera hadir di sini. Nantikan pembaruannya!</p>
                            <div class="text-2xl font-bold text-gray-500">Segera Hadir</div>
                            <button class="mt-4 w-full bg-gray-400 text-white py-2 rounded-lg cursor-not-allowed" disabled>Segera Hadir</button>
                        </div>
                    </div>

                    <!-- Contoh Produk 3 -->
                    <div class="bg-white rounded-lg shadow-lg overflow-hidden card-hover transition duration-300 flex flex-col">
                        <img src="https://placehold.co/600x400/9CA3AF/FFFFFF?text=Segera+Hadir" alt="Gambar Produk 3" class="w-full h-56 object-cover">
                        <div class="p-6 flex flex-col flex-grow">
                            <h3 class="text-xl font-semibold mb-2 product-name">Dalam Masa Proses</h3>
                            <p class="text-gray-600 mb-4 flex-grow">Produk baru akan segera hadir di sini. Nantikan pembaruannya!</p>
                            <div class="text-2xl font-bold text-gray-500">Segera Hadir</div>
                            <button class="mt-4 w-full bg-gray-400 text-white py-2 rounded-lg cursor-not-allowed" disabled>Segera Hadir</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Bagian Tentang Saya -->
        <section id="tentang" class="bg-gray-50 py-20">
            <div class="container mx-auto px-6">
                <div class="flex flex-col md:flex-row items-center gap-12">
                    <div class="md:w-1/3">
                        <img src="http://googleusercontent.com/file_content/1" alt="Foto Diri" class="rounded-full w-64 h-64 object-cover shadow-lg mx-auto">
                    </div>
                    <div class="md:w-2/3 text-center md:text-left">
                        <h2 class="text-3xl font-bold mb-4">Tentang Saya</h2>
                        <div id="bio-content">
                            <p class="text-gray-600 leading-relaxed mb-4">
                                Halo! Nama saya Ramdan Iskandar. Saya adalah seorang pelajar. Saya memulai toko ini untuk berbagi produk-produk e-book berkualitas yang saya kurasi dan buat sendiri. Saya percaya bahwa setiap produk memiliki cerita dan saya ingin membagikannya dengan Anda.
                            </p>
                            <p class="text-gray-600 leading-relaxed">
                                Di luar pekerjaan, saya suka membaca dan mencari ilmu yang saya belum ketahui. Jangan ragu untuk terhubung dengan saya melalui media sosial!
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Bagian Kontak -->
        <section id="kontak" class="py-20">
            <div class="container mx-auto px-6 max-w-xl text-center">
                <h2 class="text-3xl font-bold mb-4">Hubungi Saya</h2>
                <p class="text-gray-600 mb-8">Punya pertanyaan atau ingin bekerja sama? Kirimkan saya pesan!</p>
                <form id="contact-form">
                    <div class="mb-4"><input type="text" placeholder="Nama Anda" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required></div>
                    <div class="mb-4"><input type="email" placeholder="Email Anda" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required></div>
                    <div class="mb-4"><textarea placeholder="Pesan Anda" rows="5" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required></textarea></div>
                    <button type="submit" class="w-full bg-blue-600 text-white font-semibold py-3 rounded-lg hover:bg-blue-700 transition duration-300">Kirim Pesan</button>
                </form>
                <div id="form-message" class="mt-4 text-green-600"></div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-10">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2024 DDANZZ. Hak Cipta Dilindungi.</p>
            <div class="flex justify-center space-x-6 mt-4">
                <a href="#" class="hover:text-blue-400">Instagram</a>
                <a href="#" class="hover:text-blue-400">Facebook</a>
                <a href="#" class="hover:text-blue-400">Twitter</a>
            </div>
        </div>
    </footer>

    <script>
        // --- SCRIPT UTAMA ---
        document.addEventListener('DOMContentLoaded', () => {
            // Script untuk menu mobile
            const menuBtn = document.getElementById('menu-btn');
            const mobileMenu = document.getElementById('mobile-menu');
            menuBtn.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });

            // Script untuk navigasi smooth scroll
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                    document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
                });
            });
            
            // Script untuk pesan konfirmasi form kontak
            const contactForm = document.getElementById('contact-form');
            const formMessage = document.getElementById('form-message');
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                formMessage.textContent = 'Terima kasih! Pesan Anda telah terkirim.';
                contactForm.reset();
                setTimeout(() => { formMessage.textContent = ''; }, 5000);
            });
        });
    </script>git init
</body>
</html>
