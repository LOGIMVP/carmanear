<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARMANEAR</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Syne:wght@800&display=swap');
        body { background-color: #000000; color: #ffffff; margin: 0; }
        .font-syne { font-family: 'Syne', sans-serif; }
    </style>
</head>
<body class="bg-black min-h-screen flex flex-col items-center justify-center p-6">

    <div class="w-full max-w-lg flex flex-col items-center">
        
        <h1 class="font-syne text-5xl md:text-8xl mb-8 tracking-tighter uppercase text-center">
            CARMANEAR
        </h1>

        <div class="w-full mb-10 flex justify-center">
            <img src="carmanear_albumart.jpg" alt="CARMANEAR" class="max-w-full h-auto max-h-[70vh] shadow-[0_0_60px_rgba(255,255,255,0.1)] border border-zinc-900 rounded-sm">
        </div>

        <div class="flex flex-col items-center space-y-8 w-full">
            <div class="text-center">
                <p class="text-[10px] tracking-[0.4em] text-zinc-500 uppercase mb-2">New Release</p>
                <a href="YOUR_SPOTIFY_LINK" target="_blank" class="text-2xl font-bold uppercase tracking-widest border-b-2 border-white pb-1 hover:text-zinc-400 hover:border-zinc-400 transition-all">
                    Spotify
                </a>
            </div>

            <div class="text-center pt-4">
                <p class="text-[10px] tracking-[0.4em] text-zinc-500 uppercase mb-2">Contact</p>
                <a href="mailto:contact@carmanear.com" class="text-sm tracking-widest text-zinc-400 hover:text-white transition uppercase">
                    contact@carmanear.com
                </a>
            </div>
        </div>

    </div>

</body>
</html>
