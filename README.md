<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARMANEAR</title>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@1,600&family=Inter:wght@300&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body, html { margin: 0; padding: 0; height: 100%; width: 100%; overflow: hidden; background-color: #000; }
        
        .bg-image {
            background-image: linear-gradient(rgba(0,0,0,0.1), rgba(0,0,0,0.2)), url('carmanear_albumart.jpg');
            background-size: cover;
            background-position: center;
            height: 100vh;
            width: 100vw;
            position: fixed;
            top: 0;
            left: 0;
            z-index: -1;
        }

        .serif-font { font-family: 'Cormorant Garamond', serif; }
        .sans-font { font-family: 'Inter', sans-serif; }

        /* This creates the exact stacked/overlapping logo look */
        .logo-stack {
            display: flex;
            flex-direction: column;
            align-items: center;
            line-height: 0.6; /* Critical for the overlap */
        }
        .logo-second-word {
            margin-top: -5px; /* Adjusts the vertical overlap */
            margin-left: 40px; /* Offsets 'near' to the right like the example */
        }
    </style>
</head>
<body class="flex flex-col justify-between items-center h-screen w-screen text-white py-12 px-6">

    <div class="bg-image"></div>

    <div class="flex space-x-8 text-lg opacity-90">
        <a href="#" class="hover:opacity-50 transition"><i class="fa-brands fa-instagram"></i></a>
        <a href="#" class="hover:opacity-50 transition"><i class="fa-brands fa-spotify"></i></a>
        <a href="#" class="hover:opacity-50 transition"><i class="fa-brands fa-tiktok"></i></a>
        <a href="#" class="hover:opacity-50 transition"><i class="fa-brands fa-youtube"></i></a>
    </div>

    <div class="logo-stack serif-font italic select-none">
        <span class="text-7xl md:text-[130px] tracking-tighter">Carma</span>
        <span class="logo-second-word text-7xl md:text-[130px] tracking-tighter">near</span>
    </div>

    <nav class="sans-font text-[10px] md:text-xs tracking-[0.5em] uppercase opacity-90">
        <a href="mailto:contact@carmanear.com" class="hover:opacity-40 transition border-b border-transparent hover:border-white pb-1">
            Contact Us
        </a>
    </nav>

</body>
</html>
