# -ibrahim-os-
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>İbrahim Proje Merkezi</title>
    <style>
        /* Genel sayfa tasarımı */
        body {
            background-color: #0f172a;
            color: #f8fafc;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            margin: 0;
            padding: 20px;
        }

        h1 {
            color: #38bdf8;
            font-size: 2.5rem;
            margin-top: 30px;
            margin-bottom: 5px;
        }

        .subtitle {
            color: #94a3b8;
            font-size: 1.2rem;
            margin-bottom: 40px;
        }

        /* Proje kartlarının dizileceği alan */
        .projects-grid {
            display: flex;
            flex-direction: column;
            gap: 25px;
            max-width: 600px;
            margin: 0 auto;
        }

        /* Her bir proje kutusunun (kartının) stili */
        .project-card {
            background-color: #1e293b;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.4);
            border: 1px solid #334155;
            text-align: left;
            transition: 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
            border-color: #38bdf8;
        }

        .project-title {
            font-size: 1.5rem;
            color: #38bdf8;
            margin-top: 0;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .project-desc {
            color: #94a3b8;
            font-size: 1rem;
            line-height: 1.5;
            margin-bottom: 20px;
        }

        /* Projelere özel butonların tasarımı */
        .project-btn {
            display: inline-block;
            padding: 10px 20px;
            color: #0f172a;
            text-decoration: none;
            font-weight: bold;
            border-radius: 8px;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            transition: 0.3s;
        }

        /* Her buton için farklı havalı renkler */
        .btn-blue {
            background-color: #38bdf8;
            box-shadow: 0 4px 12px rgba(56, 189, 248, 0.3);
        }
        .btn-blue:hover { background-color: #0ea5e9; }

        .btn-green {
            background-color: #4ade80;
            box-shadow: 0 4px 12px rgba(74, 222, 128, 0.3);
        }
        .btn-green:hover { background-color: #22c55e; }

        .btn-purple {
            background-color: #c084fc;
            box-shadow: 0 4px 12px rgba(192, 132, 252, 0.3);
        }
        .btn-purple:hover { background-color: #a855f7; }
    </style>
</head>
<body>

    <h1>İbrahim Proje Merkezi</h1>
    <p class="subtitle">Geliştirdiğim tüm yazılım, donanım ve robotik projeleri</p>

    <div class="projects-grid">

        <!-- 1. PROJE: İBRAHİM OS -->
        <div class="project-card">
            <div class="project-title">🖥️ İbrahim OS</div>
            <p class="project-desc">Küçük ekranlar ve mikrokontrolcüler için özel olarak tasarladığım, hafif ve modüler kullanıcı arayüzü ve işletim sistemi simülasyonu yazılımı.</p>
            <button class="project-btn btn-blue" onclick="aksiyon('İbrahim OS')">Yazılımı İndir</button>
        </div>

        <!-- 2. PROJE: IGS GÜVENLİK SİSTEMİ -->
        <div class="project-card">
            <div class="project-title">🚨 IGS (İbrahim Güvenlik Sistemi)</div>
            <p class="project-desc">Mesafe sensörleri ve alarmlar kullanarak odaları veya özel eşyaları korumak amacıyla geliştirdiğim akıllı güvenlik sistemi projesi.</p>
            <button class="project-btn btn-green" onclick="aksiyon('IGS Güvenlik Sistemi')">Sistemi Başlat</button>
        </div>

        <!-- 3. PROJE: AKILLI ÇÖP KOVASI -->
        <div class="project-card">
            <div class="project-title">🗑️ Akıllı Çöp Kovası</div>
            <p class="project-desc">Tinkercad ile 3D modellendi ve servo motor ile mesafe sensörü entegre edildi. Elinizi uzattığınızda kapağı otomatik olarak açılır.</p>
            <button class="project-btn btn-purple" onclick="aksiyon('Akıllı Çöp Kovası')">3D Modeli İncele</button>
        </div>

    </div>

    <script>
        // Butonlara tıklandığında çalışacak fonksiyon
        function aksiyon(projeAdi) {
            alert(projeAdi + " projesi başarıyla tetiklendi! (Simülasyon)");
        }
    </script>

</body>
</html>
