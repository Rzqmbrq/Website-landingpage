<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Baju Kami - Jual Baju & Kaos Berkualitas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow: hidden; /* Mencegah animasi meluap */
        }
        h1 {
            background-color: #ff6f61;
            color: #fff;
            padding: 20px;
            margin: -20px -20px 20px -20px;
            border-radius: 10px 10px 0 0;
            animation: fadeInDown 1s ease-in-out; /* Animasi fade in dari atas */
        }
        h2 {
            color: #333;
            margin-top: 20px;
        }
        a {
            color: #ff6f61;
            text-decoration: none;
            transition: color 0.3s ease; /* Transisi warna saat hover */
        }
        a:hover {
            text-decoration: underline;
            color: #e65a50;
        }
        .cta-button {
            display: inline-block;
            background-color: #ff6f61;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-align: center;
            margin: 20px 0;
            text-decoration: none;
            transition: background-color 0.3s ease; /* Transisi warna latar saat hover */
            animation: pulse 1.5s infinite; /* Animasi berdenyut */
        }
        .cta-button:hover {
            background-color: #e65a50;
        }
        .footer {
            text-align: center;
            margin-top: 30px;
            font-size: 14px;
            color: #777;
            animation: fadeInUp 1s ease-in-out; /* Animasi fade in dari bawah */
        }
        .product-image {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 20px 0;
            opacity: 0; /* Awalnya transparan */
            animation: fadeIn 1s ease-in-out forwards; /* Animasi fade in */
        }

        /* Animasi CSS */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🌺 SELAMAT DATANG DI TOKO BAJU KAMI! 🌺</h1>
        <p>Temukan gaya terbaikmu dengan koleksi baju dan kaos kami yang nyaman dan stylish!</p>

        <h2>✨ MENGAPA MEMILIH KAMI?</h2>
        <ul style="list-style: none; padding: 0;">
            <li>✅ <strong>Bahan Berkualitas Tinggi</strong></li>
            <li>✅ <strong>Desain Trendy & Unik</strong></li>
            <li>✅ <strong>Harga Terjangkau</strong></li>
            <li>✅ <strong>Pengiriman Cepat</strong></li>
        </ul>

        <h2>🛍️ PRODUK KAMI</h2>
        <img src="D:\JUAL BAJU\Palestine black.jpg" alt="Kaos Ramadhan Berkah" class="product-image">
        <img src="D:\JUAL BAJU\Jaga lisan.jpg" alt="Kaos Jaga Lisan" class="product-image">
        <img src="D:\JUAL BAJU\Ramadhan design.jpg" alt="Kaos Jaga Lisan" class="product-image">
        <ul style="list-style: none; padding: 0;">
            <li style="animation: pulse 1.5s infinite;"><strong>Kaos Basic</strong> - Mulai dari Rp 60.000</li>
            <li style="animation: pulse 1.5s infinite;"><strong>Kaos Custom Desain</strong> - Mulai dari Rp 150.000</li>
        </ul>

        <h2>📦 CARA PEMESANAN</h2>
        <ol style="text-align: left; display: inline-block; text-align: left;">
            <li>Pilih produk yang Anda inginkan.</li>
            <li>Kirim pesan ke nomor WhatsApp kami: <a href="https://wa.me/6285283222402" target="_blank">+62 852-8322-2402</a> dengan format:
                <ul>
                    <li>Nama:</li>
                    <li>Alamat:</li>
                    <li>Kode Produk:</li>
                    <li>Jumlah:</li>
                </ul>
            </li>
            <li>Konfirmasi pembayaran dan tunggu pesanan Anda dikirim!</li>
        </ol>

        <h2>📞 HUBUNGI KAMI</h2>
        <p>Untuk info lebih lanjut atau bantuan, hubungi kami di:</p>
        <a href="https://wa.me/6285283222402" class="cta-button" target="_blank">+62 852-8322-2402</a>

        <p><strong>🚀 GRATIS ONGKIR</strong> untuk pembelian di atas Rp 300.000!</p>
        <p>Jangan lewatkan promo menarik lainnya!</p>

        <div class="footer">
            <p>© 2025 Toko Baju Kami. All Rights Reserved.</p>
        </div>
    </div>
</body>
</html>
