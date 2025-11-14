<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Golda - Life Inspiration</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ffcf33, #ff66c4, #6ecbff, #a2ff6e);
            background-size: 300% 300%;
            animation: gradientShift 12s ease infinite;
            color: #222;
        }@keyframes gradientShift {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    header {
        text-align: center;
        padding: 50px 20px;
        color: #fff;
        text-shadow: 2px 2px 6px rgba(0,0,0,0.4);
    }

    header h1 {
        font-size: 3rem;
        margin: 0;
        font-weight: bold;
    }

    header p {
        font-size: 1.3rem;
        margin-top: 10px;
    }

    .gallery-section {
        padding: 40px 20px;
        max-width: 1100px;
        margin: auto;
    }

    .gallery-title {
        text-align: center;
        font-size: 2rem;
        margin-bottom: 30px;
        font-weight: bold;
    }

    .gallery-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
    }

    .gallery-grid img {
        width: 100%;
        height: 250px;
        object-fit: cover;
        border-radius: 12px;
        box-shadow: 0 4px 12px rgba(0,0,0,0.3);
        transition:
