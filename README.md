<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARMANEAR</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;1,600&family=Inter:wght@300&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body, html { margin: 0; padding: 0; height: 100%; overflow: hidden; background-color: #000; }
        
        .bg-image {
            background-image: linear-gradient(rgba(0,0,0,0.1), rgba(0,0,0,0.4)), url('carmanear_albumart.jpg');
            background-size: cover;
            background-position: center;
            height: 100vh;
            width: 100vw;
            position: fixed;
            top: 0;
            left: 0;
            z-index: -1;
        }

        .serif-font { font-family: 'Playfair Display', serif; }
        .sans-font { font-family: 'Inter', sans-serif; }

        /* Subtle fade-in for that cinematic feel */
        .fade-in { animation: fadeIn 2.5s ease-out forwards; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
    </style>
</head>
<body class="flex flex-col justify-between items-center min-h-screen text-white py-12 px-6 fade-in">

    <div class="bg-image"></div>

    <div class="flex space-x-8 text-[10px] tracking-[0.4em] sans-font opacity-70">
        <a href="#" class="hover:opacity-100 transition">INSTAGRAM</a>
        <a href="#" class="hover:opacity-100 transition">TIKTOK</a>
    </div>

    <div class="text-center">
        <h1 class="serif-font text-6xl md:text-9xl tracking-tight leading-none italic">
            Carmanear
        </h1>
    </div>

    <nav class="flex flex-wrap justify-center gap-x-10 gap-y-4 text-[10px] md:text-xs tracking-[0.5em] uppercase sans-font opacity-70">
        <a href="YOUR_SPOTIFY_LINK" target="_blank" class="hover:opacity-100 transition">Spotify</a>
        <a href="mailto:contact@carmanear.com" class="hover:opacity-100 transition">Contact</a>
    </nav>

</body>
</html>
