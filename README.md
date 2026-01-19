<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Migi Setyo Sugiarto Adi | F&B Operations Specialist</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #0f172a;
            --accent: #2563eb;
            --whatsapp: #22c55e;
            --text-main: #1e293b;
            --text-muted: #64748b;
            --bg: #f8fafc;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg);
            color: var(--text-main);
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .brand-card {
            background: #ffffff;
            max-width: 750px;
            width: 92%;
            padding: 50px;
            border-radius: 32px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.05);
            position: relative;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .badge {
            background: #eff6ff;
            color: var(--accent);
            padding: 6px 16px;
            border-radius: 100px;
            font-size: 13px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            display: inline-block;
            margin-bottom: 16px;
        }

        h1 {
            font-size: 36px;
            font-weight: 700;
            margin: 0;
            color: var(--primary);
            letter-spacing: -0.02em;
        }

        .location {
            color: var(--text-muted);
            font-size: 15px;
            margin-top: 8px;
        }

        .content-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 24px;
            margin-top: 40px;
        }

        .info-card {
            background: #ffffff;
            border: 1px solid #f1f5f9;
            padding: 24px;
            border-radius: 20px;
            transition: all 0.3s ease;
        }

        .info-card:hover {
            border-color: #e2e8f0;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.04);
        }

        h3 {
            font-size: 14px;
            color: var(--accent);
            text-transform: uppercase;
            letter-spacing: 0.1em;
            margin-top: 0;
            margin-bottom: 12px;
        }

        p {
            font-size: 15px;
            line-height: 1.6;
            margin: 0;
            color: var(--text-main);
        }

        .actions {
            margin-top: 48px;
            display: flex;
            flex-direction: column;
            gap: 16px;
        }

        .btn {
            padding: 18px 32px;
            border-radius: 16px;
            text-decoration: none;
            font-weight: 700;
            font-size: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
        }

        .btn-download {
            background-color: var(--primary);
            color: white;
        }

        .btn-download:hover {
            background-color: #000;
            transform: translateY(-2px);
        }

        .btn-whatsapp {
            background-color: transparent;
            color: var(--whatsapp);
            border: 2px solid var(--whatsapp);
        }

        .btn-whatsapp:hover {
            background-color: var(--whatsapp);
            color: white;
            transform: translateY(-2px);
        }

        @media (max-width: 640px) {
            .brand-card { padding: 30px 20px; }
            .content-grid { grid-template-columns: 1fr; }
            h1 { font-size: 28px; }
        }
    </style>
</head>
<body>

    <div class="brand-card">
        <div class="header">
            <span class="badge">Professional Portfolio</span>
            <h1>Migi Setyo Sugiarto Adi</h1>
            <div class="location">Semarang, Indonesia | migisetyosa@gmail.com</div>
        </div>

        <div class="content-grid">
            <div class="info-card">
                <h3>Executive Summary</h3>
                <p>
                    Profesional F&B dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko. Ahli dalam manajemen inventaris, kontrol biaya, serta kepemimpinan tim berbasis data[cite: 4, 5].
                </p>
            </div>
            <div class="info-card">
                <h3>Professional Objective</h3>
                <p>
                    Bertekad meningkatkan efisiensi operasional dan pertumbuhan bisnis melalui posisi Food & Beverage Operations atau Store Management yang strategis.
                </p>
            </div>
        </div>

        <div class="actions">
            <a href="Migi Setyo Sugiarto Adi (9).pdf" class="btn btn-download" download>
                Unduh Resume Lengkap (PDF)
            </a>
            
            <a href="https://wa.me/628112683668?text=Halo%20Migi,%20saya%20melihat%20profil%20Anda%20dan%20tertarik%20untuk%20berdiskusi%20lebih%20lanjut." 
               class="btn btn-whatsapp" 
               target="_blank">
                Hubungi via WhatsApp
            </a>
        </div>
    </div>

</body>
</html>
