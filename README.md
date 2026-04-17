<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARMANEAR | OFFICIAL</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&family=Syne:wght@800&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background-color: #000000;
            color: #ffffff;
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        /* Custom Font for Band Name */
        .carmanear-font {
            font-family: 'Syne', sans-serif;
            font-weight: 800;
            text-transform: uppercase;
        }

        /* Custom Gritty Link Style */
        .raw-link {
            border-bottom: 2px solid #ffffff;
            transition: all 0.3s ease;
        }
        .raw-link:hover {
            color: #888888;
            border-bottom-color: #888888;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-center items-center text-center p-6">

    <h1 class="text-6xl md:text-9xl carmanear-font tracking-tighter mb-8 -ml-3 md:-ml-8 z-10">
        CARMANEAR
    </h1>

    <main class="w-full max-w-xl aspect-square mb-12">
        <img src="carmanear_albumart.jpg" alt="CARMANEAR ALBUM ART" class="w-full h-full object-cover rounded-sm shadow-2xl transition hover:scale-105 duration-500">
    </main>

    <div class="space-y-12 w-full max-w-sm">
        
        <div>
            <p class="text-sm uppercase tracking-widest text-gray-500 mb-2">New Release</p>
            <a href="YOUR_SPOTIFY_URL_HERE" target="_blank" class="text-3xl font-bold tracking-tight raw-link">
                Listen on Spotify
            </a>
        </div>

        <div>
            <p class="text-sm uppercase tracking-widest text-gray-500 mb-1">Booking & Inquiries</p>
            <a href="mailto:contact@carmanear.com" class="text-xl text-gray-200 hover:text-white transition">contact@carmanear.com</a>
        </div>

        <div class="flex justify-center space-x-10 text-xs text-gray-500 uppercase tracking-widest pt-8 border-t border-zinc-900">
            <a href="#" class="hover:text-white transition">Instagram</a>
            <a href="#" class="hover:text-white transition">TikTok</a>
        </div>

    </div>

</body>
</html>
