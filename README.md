<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARMANEAR | OFFICIAL</title>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@600&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* This prevents the page from having black bars on the sides on desktops */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow-x: hidden;
            background-color: #f8f8f8; /* A light off-white, matching the header */
        }

        /* --- Global Font Setup --- */
        .sans-font { font-family: sans-serif; }
        .serif-font { font-family: 'Cormorant Garamond', serif; }

        /* --- THE LOGO CHALLENGE (Overlapping two-line design) --- */
        /* We place the "Carmanear" word in two separate containers to force them to overlap */
        .central-logo {
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
            z-index: 10;
        }

        .overlapping-logo-text {
            display: inline-block;
            position: relative;
            line-height: 0.1; /* This is the key that forces the lines to cross */
        }

        .logo-word {
            display: block;
            position: relative;
        }

        /* Adjust the negative margin of the bottom word to control the exact overlap */
        .logo-bottom-word {
            margin-top: -10px; /* Play with this number until the 'W' overlaps the text above */
        }
    </style>
</head>
<body class="sans-font text-[10px] tracking-[0.4em] uppercase text-black">

    <div class="page-wrap flex flex-col min-h-screen">
        
        <header class="w-full bg-[#f8f8f8] border-b border-zinc-200 h-[70px] flex justify-center items-center">
            <div class="flex space-x-10 text-xs">
                <a href="#" class="hover:opacity-50 transition">INSTAGRAM</a>
                <a href="#" class="hover:opacity-50 transition">TIKTOK</a>
                <a href="#" class="hover:opacity-50 transition">SPOTIFY</a>
            </div>
        </header>

        <main class="main-content flex-grow flex justify-center items-center relative overflow-hidden bg-black">
            <img src="carmanear_albumart.jpg" alt="CARMANEAR" class="w-full h-full object-cover">
        </main>

        <div class="absolute inset-0 flexjustify-center items-center h-full pt-[70px] pb-[70px]">
            <div class="central-logo">
                <div class="overlapping-logo-text serif-font text-white text-7xl md:text-[140px] tracking-tight leading-none text-center">
                    
                    <span class="logo-word logo-top-word">Carma</span>
                    
                    <span class="logo-word logo-bottom-word">near</span>
                </div>
            </div>
        </div>

        <footer class="w-full bg-[#f8f8f8] border-t border-zinc-200 h-[70px] flex justify-center items-center">
            <nav class="flex space-x-10 md:space-x-16 text-xs text-black">
                <a href="YOUR_SPOTIFY_LINK" target="_blank" class="hover:opacity-50 transition">Listen</a>
                <a href="mailto:contact@carmanear.com" class="hover:opacity-50 transition">Contact</a>
            </nav>
        </footer>

    </div>

</body>
</html>
