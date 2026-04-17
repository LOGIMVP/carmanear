<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARMANEAR</title>
    <link href="https://fonts.googleapis.com/css2?family=Syne:wght@800&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #000; color: #fff; margin: 0; padding: 0; }
        .font-syne { font-family: 'Syne', sans-serif; }
        /* This ensures your vertical image doesn't get too tall on big screens */
        .art-container img { max-height: 65vh; width: auto; margin: 0 auto; }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-center p-6 text-center">

    <h1 class="font-syne text-5xl md:text-8xl tracking-tighter uppercase mb-10">
        CARMANEAR
    </h1>

    <div class="art-container mb-12 shadow-2xl">
        <img src="carmanear_albumart.jpg" alt="CARMANEAR" class="border border-zinc-800 rounded-sm">
    </div>

    <div class="flex flex-col items-center gap-10">
        <a href="YOUR_SPOTIFY_LINK" target="_blank" class="text-2xl font-bold uppercase tracking-[0.2em] border-b-2 border-white pb-1 hover:text-zinc-400 hover:border-zinc-400 transition-all">
            Spotify
        </a>

        <a href="mailto:contact@carmanear.com" class="text-sm tracking-[0.3em] text-zinc-500 hover:text-white transition uppercase">
            contact@carmanear.com
        </a>
    </div>

</body>
</html>
