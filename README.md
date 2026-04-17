<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARMANEAR | OFFICIAL</title>
    <link href="https://fonts.googleapis.com/css2?family=Syne:wght@700&display=swap" rel="stylesheet">
    <style>
        /* Reset default browser margins */
        body {
            margin: 0;
            padding: 0;
            background-color: #000; /* Keep the top border black */
            font-family: sans-serif;
            overflow-x: hidden; /* Prevent horizontal scroll */
        }

        /* --- Section 1: Band Name Header (Matches original) --- */
        .top-header {
            background-color: #000;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100px;
            text-transform: uppercase;
            font-size: 1.2rem;
            letter-spacing: 0.1em;
            margin: 0;
        }

        /* --- Section 2: White Background, Wide Image Container --- */
        /* This section spans full width, removing the "red area" */
        .image-section {
            background-color: #fff;
            width: 100vw; /* Spans full viewport width */
            display: flex;
            justify-content: center;
            align-items: center;
            /* Adjust padding to control spacing around the image */
            padding: 40px 0;
        }

        /* Container to keep content centered on large screens */
        .content-container {
            width: 100%;
            max-width: 1200px; /* Maximum content width to look good on desktops */
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* --- Band Name inside White Area (Large, bold, centers) --- */
        .band-title {
            font-family: 'Syne', sans-serif;
            font-weight: 700;
            font-size: 3rem; /* Increase as desired for impact */
            text-transform: uppercase;
            letter-spacing: 0.05em;
            margin-bottom: 30px;
            color: #000;
            text-align: center;
        }

        /* --- Vertical Image (Centers and fits max possible area) --- */
        .artist-image {
            width: 100%;
            max-width: 500px; /* Limits portrait image from being *too* large on big screens */
            height: auto;
            object-fit: contain; /* Shows entire portrait image without cutting it off */
            display: block; /* Removes any default inline-block spacing */
        }

        /* --- MOBILE/TABLET STYLES --- */
        @media (max-width: 768px) {
            .band-title {
                font-size: 2rem;
            }
            .artist-image {
                max-width: 90%; /* On phones, image fills almost the whole width */
            }
        }
    </style>
</head>
<body>

    <div class="top-header">
        <h1>carmanear</h1>
    </div>

    <div class="image-section">
        <div class="content-container">
            <h2 class="band-title">CARMANEAR</h2>
            
            <img src="carmanear_albumart.jpg" alt="CARMANEAR" class="artist-image">
        </div>
    </div>

</body>
</html>
