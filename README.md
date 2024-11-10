<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shashin Shamal D | Personal Brand</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

    <!-- Navigation -->
    <nav class="bg-blue-600 text-white shadow-md py-4">
        <div class="container mx-auto flex justify-between items-center px-6">
            <h1 class="text-2xl font-bold">Shashin Shamal D</h1>
            <div class="space-x-6">
                <a href="#home" class="hover:text-yellow-400">Home</a>
                <a href="#about" class="hover:text-yellow-400">About</a>
                <a href="#portfolio" class="hover:text-yellow-400">Portfolio</a>
                <a href="#contact" class="hover:text-yellow-400">Contact</a>
                <a href="#login" class="hover:text-yellow-400">Login</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative py-24 bg-cover bg-center fade-in" style="background-image: url('https://example.com/your-background.jpg');">
        <div class="absolute inset-0 bg-black opacity-50"></div>
        <div class="container mx-auto text-center relative z-10">
            <h1 class="text-4xl font-bold text-white animate_animated animate_fadeIn">Welcome to Shashin's World</h1>
            <p class="mt-4 text-xl text-white">Innovative Thinker | Tech Enthusiast | Creative Visionary</p>
            <a href="#about" class="inline-block mt-8 bg-yellow-500 text-white px-6 py-3 rounded-lg shadow-lg hover:bg-yellow-400">Learn More</a>
        </div>
    </section>

    <!-- Social Media Links -->
    <section class="py-10 text-center bg-gray-100">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-6">Connect with Me</h2>
            <div class="space-x-6">
                <!-- WhatsApp -->
                <a href="https://wa.me/1234567890" target="_blank" class="text-3xl text-green-500 hover:text-green-400">
                    <i class="fab fa-whatsapp"></i>
                </a>
                <!-- Facebook -->
                <a href="https://facebook.com/yourfacebook" target="_blank" class="text-3xl text-blue-600 hover:text-blue-400">
                    <i class="fab fa-facebook-f"></i>
                </a>
                <!-- TikTok -->
                <a href="https://www.tiktok.com/@yourtiktok" target="_blank" class="text-3xl text-black hover:text-gray-800">
                    <i class="fab fa-tiktok"></i>
                </a>
                <!-- Instagram -->
                <a href="https://instagram.com/yourinstagram" target="_blank" class="text-3xl text-pink-500 hover:text-pink-400">
                    <i class="fab fa-instagram"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-100 text-center">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-6">About Me</h2>
            <p class="text-lg mb-8">
                Hello, I'm Shashin Shamal D. A passionate developer and tech enthusiast. I believe in leveraging technology for innovative solutions, enhancing user experiences, and solving complex problems with creativity and expertise.
            </p>
            <img src="https://example.com/your-image.jpg" alt="Shashin Shamal D" class="w-32 h-32 rounded-full mx-auto mb-6 shadow-lg">
        </div>
    </section>

    <!-- Login Section -->
    <section id="login" class="py-20 bg-gray-900 text-white text-center">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-6">Login</h2>
            <form id="login-form" class="mx-auto max-w-md">
                <input type="email" id="email" placeholder="Enter your email" class="w-full p-3 mb-4 rounded-lg shadow-md" required>
                <input type="password" id="password" placeholder="Enter your password" class="w-full p-3 mb-4 rounded-lg shadow-md" required>
                <button type="submit" class="bg-yellow-500 text-white px-6 py-3 rounded-lg shadow-lg hover:bg-yellow-400">Login</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-600 text-white text-center py-6">
        <p>&copy; 2024 Shashin Shamal D. All Rights Reserved.</p>
    </footer>

    <!-- Font Awesome for Social Icons -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
