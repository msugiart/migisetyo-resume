<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Profesional - Migi Setyo Sugiarto Adi</title>
    <style>
        :root {
            --primary: #0f172a;
            --accent: #2563eb;
            --bg-gradient: linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%);
            --white: #ffffff;
        }

        body {
            font-family: 'Inter', -apple-system, sans-serif;
            margin: 0;
            background: var(--bg-gradient);
            color: var(--primary);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .hero-card {
            background: var(--white);
            max-width: 800px;
            width: 90%;
            padding: 50px;
            border-radius: 24px;
            box-shadow: 0 20px 50px rgba(0,0,0,0.1);
            text-align: center;
            position: relative;
        }

        /* Penanda Profesional */
        .hero-card::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 10px;
            background: var(--accent);
            border-radius: 24px 24px 0 0;
        }

        h1 { font-size: 32px; margin: 10px 0; letter-spacing: -1px; }
        .tagline { color: #64748b; margin-bottom: 30px; font-weight: 500; }

        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            text-align: left;
            margin: 30px 0;
        }

        .info-box {
            background: #f1f5f9;
            padding: 20px;
            border-radius: 12px;
            border-left: 4px solid var(--accent);
        }

        h3 { font-size: 14px; text-transform: uppercase; color: var(--accent); margin-bottom: 10px; }
        p { font-size: 14px; line-height: 1.6; margin: 0; }

        .btn-download {
            background: var(--accent);
            color: white;
            padding: 16px 32px;
            border-radius: 12px;
            text-decoration: none;
            font-weight: 700;
            display: inline-block;
            transition: 0.3s;
            box-shadow: 0 8px 15px rgba(37, 99, 235, 0.2);
        }

        .btn-download:hover { transform: translateY(-3px); background: #1d4ed8; }

        @media (max-width: 600px) { .grid { grid-template-columns: 1fr; } }
    </style>
</head>
<body>

    <div class="hero-card">
        <h1>Migi Setyo Sugiarto Adi</h1>
        <div class="tagline">F&B Operations Specialist | Semarang, Indonesia</div>

        <div class="grid">
            <div class="info-box">
                <h3>Tentang Saya</h3>
                <p>Profesional F&B dengan pengalaman lebih dari 5 tahun di operasional restoran, bar, dan manajemen toko. Ahli dalam pengelolaan inventaris, kontrol biaya (Cost Control), dan kepemimpinan tim.</p>
            </div>
            <div class="info-box">
                <h3>Tujuan Karier</h3>
                <p>Berkontribusi dalam peningkatan efisiensi operasional dan pertumbuhan bisnis melalui peran strategis di bidang Production atau Management.</p>
            </div>
        </div>

        <div style="margin-top: 40px;">
            <a href="Migi Setyo Sugiarto Adi (9).pdf" class="btn-download" download>
                UNDUH CV LENGKAP (PDF)
            </a>
        </div>
    </div>

</body>
</html>
