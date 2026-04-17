<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARMANEAR</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Syne:wght@800&family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { 
            background-color: #000000; 
            color: #ffffff; 
            font-family: 'Inter', sans-serif; 
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
        }
        .carmanear-font { font-family: 'Syne', sans-serif; }
        .fade-in { animation: fadeIn 1.5s ease-in-out; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
    </style>
</head>
<body>

    <div class="flex flex-col items-center text-center w-full max-w-md px-6 fade-in">
        
        <h1 class="text-5xl md:text-7xl carmanear-font tracking-tighter mb-8 uppercase">
            CARMANEAR
        </h1>

        <div class="w-full shadow-[0_0_50px_rgba(255,255,255,0.05)] mb-10">
            <img src="_MG_1349.jpg" alt="CARMANEAR" class="w-full h-auto rounded-sm border border-zinc-900">
        </div>

        <div class="space-y-8">
            <div class="group">
                <p class="text-[10px] uppercase tracking-[0.3em] text-zinc-500 mb-2">New Release</p>
                <a href="YOUR_SPOTIFY_LINK" target="_blank" class="text-2xl font-bold border-b-2 border-white hover:text-zinc-400 hover:border-zinc-400 transition-all pb-1 uppercase tracking-wider">
                    Listen on Spotify
                </a>
            </div>
            
            <div class="pt-4">
                <p class="text-[10px] uppercase tracking-[0.3em] text-zinc-500 mb-2">Booking & Inquiries</p>
                <a href="mailto:contact@carmanear.com" class="text-sm text-zinc-300 hover:text-white transition tracking-widest border-b border-transparent hover:border-zinc-500">
                    contact@carmanear.com
                </a>
            </div>
        </div>

    </div>

</body>
</html>
