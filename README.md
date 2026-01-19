<html lang="id">

    <meta charset="UTF-8">
      <style>
        :root {
            --primary: #0f172a;
            --accent: #2563eb;
            --whatsapp: #25d366;
            --bg-gradient: linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%);
            --white: #ffffff;
            --text-muted: #64748b;
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
            padding: 20px 0;
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

        .badge {
            background: #dbeafe;
            color: var(--accent);
            padding: 8px 16px;
            border-radius: 50px;
            font-size: 14px;
            font-weight: 700;
            display: inline-block;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 36px;
            margin: 0 0 10px 0;
            letter-spacing: -1px;
        }

        .tagline {
            font-size: 16px;
            color: var(--text-muted);
            margin-bottom: 30px;
        }

        .section-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            text-align: left;
            margin: 30px 0;
        }

        .box {
            background: #f8fafc;
            padding: 20px;
            border-radius: 16px;
            border: 1px solid #e2e8f0;
        }

        h3 {
            margin-top: 0;
            font-size: 14px;
            color: var(--accent);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* VISUAL SKILLS */
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin: 20px 0;
        }

        .skill-item {
            background: #f1f5f9;
            padding: 6px 14px;
            border-radius: 8px;
            font-size: 13px;
            font-weight: 600;
            color: var(--secondary);
            border: 1px solid #cbd5e1;
        }

        /* BUTTONS */
        .btn-group {
            display: flex;
            flex-direction: column;
            gap: 15px;
            align-items: center;
            margin-top: 30px;
        }

        .btn {
            width: 280px;
            padding: 16px;
            border-radius: 12px;
            text-decoration: none;
            font-weight: 700;
            font-size: 16px;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn-download {
            background: var(--accent);
            color: white;
            box-shadow: 0 8px 20px rgba(37, 99, 235, 0.2);
        }

        .btn-whatsapp {
            background: var(--whatsapp);
            color: white;
            box-shadow: 0 8px 20px rgba(37, 211, 102, 0.2);
        }

        .btn:hover {
            transform: translateY(-3px);
            filter: brightness(1.1);
        }

        @media (max-width: 768px) {
            .section-grid { grid-template-columns: 1fr; }
            .hero-card { padding: 30px 20px; }
            h1 { font-size: 26px; }
        }
    </style>
</head>
<body>

    <div class="hero-card">
        <div class="badge">F&B Operations & Store Management</div>
        <h1>Migi Setyo Sugiarto Adi</h1>
        <div class="tagline">Semarang, Indonesia | migisetyosa@gmail.com</div>

        <div class="section-grid">
            <div class="box">
                <h3>Tentang Saya</h3>
                <p style="font-size: 14px; margin: 0;">Profesional F&B dengan lebih dari 5 tahun pengalaman. Ahli dalam operasional toko, manajemen inventory (Cost Control), dan kepemimpinan tim.</p>
            </div>
            <div class="box">
                <h3>Tujuan Karir</h3>
                <p style="font-size: 14px; margin: 0;">Meningkatkan efisiensi operasional dan pertumbuhan bisnis melalui peran strategis di bidang Production atau Management.</p>
            </div>
        </div>

        <h3 style="text-align: center; margin-bottom: 10px;">Keahlian Utama</h3>
        <div class="skills-list">
            <div class="skill-item">Inventory Management</div>
            <div class="skill-item">Cost Control</div>
            <div class="skill-item">Microsoft Excel</div>
            <div class="skill-item">Leadership</div>
            <div class="skill-item">Purchasing</div>
            <div class="skill-item">Food Safety</div>
        </div>

        <div class="btn-group">
            <a href="Migi Setyo Sugiarto Adi (9).pdf" class="btn btn-download" download>
                📄 DOWNLOAD CV LENGKAP
            </a>

            <a href="https://wa.me/628112683668?text=Halo%20Migi,%20saya%20tertarik%20dengan%20profil%20Anda%20setelah%20melihat%20website%20portofolio%20Anda." 
               target="_blank" 
               class="btn btn-whatsapp">
                💬 HUBUNGI VIA WHATSAPP
            </a>
        </div>

        <p style="margin-top: 30px; font-size: 12px; color: #94a3b8;">
            Siap berkontribusi untuk kemajuan perusahaan Anda.
        </p>
    </div>

</body>
</html>
