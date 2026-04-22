




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stitch & Deco | Crochet Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
    <style>
        :root {
            --gold: #c5a059;
            --dark-slate: #1a1a1a;
            --cream: #f9f7f2;
            --border-style: 2px solid var(--gold);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--cream);
            color: var(--dark-slate);
            font-family: 'Montserrat', sans-serif;
            line-height: 1.6;
        }

        /* Art Deco Border Frame */
        body::before {
            content: "";
            position: fixed;
            top: 10px; left: 10px; right: 10px; bottom: 10px;
            border: 1px solid var(--gold);
            pointer-events: none;
            z-index: 999;
        }

        header {
            text-align: center;
            padding: 4rem 1rem;
            border-bottom: var(--border-style);
            margin: 0 2rem;
        }

        h1 {
            font-family: 'Cinzel', serif;
            font-size: 3rem;
            letter-spacing: 8px;
            text-transform: uppercase;
            color: var(--dark-slate);
        }

        .subtitle {
            letter-spacing: 4px;
            text-transform: uppercase;
            font-size: 0.9rem;
            margin-top: 10px;
            color: var(--gold);
        }

        /* Project Grid */
        .container {
            max-width: 1000px;
            margin: 3rem auto;
            padding: 0 2rem;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 3rem;
        }

        .project-card {
            border: 1px solid rgba(197, 160, 89, 0.3);
            padding: 15px;
            transition: all 0.4s ease;
            background: white;
        }

        .project-card:hover {
            border: 1px solid var(--gold);
            transform: translateY(-5px);
        }

        .img-placeholder {
            width: 100%;
            height: 250px;
            background-color: #eee;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Cinzel', serif;
            color: #ccc;
            border: 1px solid #eee;
        }

        h2 {
            font-family: 'Cinzel', serif;
            font-size: 1.4rem;
            margin-bottom: 0.5rem;
            border-bottom: 1px solid var(--gold);
            display: inline-block;
        }

        .date {
            font-size: 0.7rem;
            color: var(--gold);
            display: block;
            margin-bottom: 1rem;
            letter-spacing: 2px;
        }

        footer {
            text-align: center;
            padding: 4rem 1rem;
            font-size: 0.8rem;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        /* Decorative Element */
        .deco-divider {
            width: 100px;
            height: 2px;
            background: var(--gold);
            margin: 2rem auto;
            position: relative;
        }

        .deco-divider::after {
            content: "◆";
            position: absolute;
            top: -10px;
            left: 42%;
            background: var(--cream);
            padding: 0 5px;
            color: var(--gold);
        }
    </style>
</head>
<body>

    <header>
        <h1>Stitch & Deco</h1>
        <p class="subtitle">Handcrafted Crochet • Minimalist Aesthetic</p>
    </header>

    <div class="container">
        <div class="grid">
