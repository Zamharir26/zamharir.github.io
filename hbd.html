<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesanku untuk orang yang kusukai</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            padding: 20px;
            transition: background-color 0.3s;
            position: relative; /* Tambahkan posisi relatif untuk body */
        }

        .page {
            display: none;
            flex-direction: column;
            align-items: center; /* Perbaiki struktur CSS di sini */
            width: 100%; /* Mengatur lebar halaman */
            max-width: 600px; /* Batas maksimal lebar halaman */
        }

        .page.active {
            display: flex;
        }

        .cool { background-color: #cce7ff; color: #003366; }
        .happy { background-color: #ffff99; color: #333; }
        .romance { background-color: #ffcccb; color: #600; }
        .sad { background-color: #a9a9a9; color: #fff; }
        .positive { background-color: #98fb98; color: #005500; }
        .spirit { background-color: #fff3e0; color: #ff6f20; }

        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .error-message {
            color: red;
        }

        button, a {
            padding: 10px 20px;
            text-decoration: none;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            color: #fff;
        }

        /* Tombol dengan warna sesuai tema */
        .happy button, .happy a { background-color: #ffeb3b; color: #333; }
        .romance button, .romance a { background-color: #ff8a80; color: #fff; }
        .sad button, .sad a { background-color: #757575; color: #fff; }
        .positive button, .positive a { background-color: #4caf50; color: #fff; }
        .spirit button, .spirit a { background-color: #ffcc80; color: #fff; }
        
        /* Tombol keluar */
        .exit-button {
            background-color: #d32f2f;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            position: absolute; /* Ganti ke posisi absolut */
            bottom: 20px; /* Jarak dari bawah */
            right: 20px; /* Jarak dari kanan */
        }

        /* Tombol Kembali dan Lanjut */
        .nav-buttons {
            display: flex;
            justify-content: space-between;
            width: 100%;
            margin-top: auto; /* Membuat tombol berada di bagian bawah halaman */
            gap: 20px; /* Jarak antara tombol Kembali dan Lanjut */
        }

        .nav-buttons a {
            width: 48%; /* Mengatur lebar tombol */
            text-align: center; /* Pusatkan teks */
        }
    </style>
</head>
<body class="cool">

    <!-- Halaman 1 - Cool -->
    <div id="page1" class="page active cool">
        <h1>Selamat Datang</h1>
        <form id="loginForm">
            <label for="name">Nama Penerima (satu kata):</label>
            <input type="text" id="name" name="name" required>
            
            <label for="nickname">Nama Panggilan (satu kata):</label>
            <input type="text" id="nickname" name="nickname" required>

            <label for="sender">Nama Pengirim (satu kata):</label>
            <input type="text" id="sender" name="sender" required>

            <button type="submit">Lanjut</button>
        </form>
        <p id="error" class="error-message"></p>
        <a href="#" class="exit-button" onclick="exitPage()">Exit</a>
    </div>

    <!-- Halaman 2 - Happy -->
    <div id="page2" class="page happy">
        <h1>Untuk orang yang kusukai</h1>
        <p>Ini adalah halaman penuh kebahagiaan yang ingin aku bagi bersamamu.</p>
        <div class="nav-buttons">
            <a href="#" onclick="goToPage(1)">Back</a>
            <a href="#" onclick="goToPage(3)">Next</a>
        </div>
    </div>

    <!-- Halaman 3 - Romance -->
    <div id="page3" class="page romance">
        <h1>Cinta</h1>
        <p>Aku ingin kamu tahu betapa berharganya dirimu bagiku.</p>
        <div class="nav-buttons">
            <a href="#" onclick="goToPage(2)">Back</a>
            <a href="#" onclick="goToPage(4)">Next</a>
        </div>
    </div>

    <!-- Halaman 4 - Sad -->
    <div id="page4" class="page sad">
        <h1>Kesedihan</h1>
        <p>Ada saatnya aku merasa sedih, namun aku tahu kita bisa menghadapinya bersama.</p>
        <div class="nav-buttons">
            <a href="#" onclick="goToPage(3)">Back</a>
            <a href="#" onclick="goToPage(5)">Next</a>
        </div>
    </div>

    <!-- Halaman 5 - Positive -->
    <div id="page5" class="page positive">
        <h1>Halaman Positif</h1>
        <p>Kita bisa melalui semua rintangan ini. Teruslah semangat!</p>
        <div class="nav-buttons">
            <a href="#" onclick="goToPage(4)">Back</a>
            <a href="#" onclick="goToPage(6)">Next</a>
        </div>
    </div>

    <!-- Halaman 6 - Semangat -->
    <div id="page6" class="page spirit">
        <h1>Semangat!</h1>
        <p>Selalu ingat untuk tetap semangat dalam setiap langkah hidupmu!</p>
        <div class="nav-buttons">
            <a href="#" onclick="goToPage(5)">Back</a>
            <a href="#" onclick="goToPage(1)">Exit</a>
        </div>
    </div>

    <script>
        // Fungsi untuk validasi dan navigasi halaman
        document.getElementById('loginForm').addEventListener('submit', function(event) {
            event.preventDefault();

            const nameInput = document.getElementById('name').value.toLowerCase().trim();
            const nicknameInput = document.getElementById('nickname').value.toLowerCase().trim();
            const senderInput = document.getElementById('sender').value.toLowerCase().trim();

            const validNames = ["asyifa"];
            const validNickname = "ipaa";
            const validSender = "ridwan";  // Ganti ini dengan nama pengirim yang valid

            if (validNames.includes(nameInput) && nicknameInput === validNickname && senderInput === validSender) {
                goToPage(2);
            } else {
                document.getElementById('error').textContent = "Nama, panggilan, atau pengirim salah. Coba lagi atau kamu bukan orang yang dituju!";
                // Reset nilai input setelah gagal
                document.getElementById('loginForm').reset(); 
            }
        });

        // Fungsi untuk navigasi antar halaman
        function goToPage(pageNumber) {
            // Hilangkan kelas 'active' dari semua halaman
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
            });

            // Tampilkan halaman yang dipilih
            const selectedPage = document.getElementById('page' + pageNumber);
            selectedPage.classList.add('active');

            // Ubah latar belakang body sesuai dengan kelas halaman
            document.body.className = selectedPage.classList[1];
        }

        // Fungsi untuk keluar dari halaman pertama
        function exitPage() {
            alert("Terima kasih telah berkunjung!");
            window.location.href = "https://google.com"; // Ganti dengan URL lain jika diperlukan
        }
    </script>
</body>
</html>
