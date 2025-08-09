<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal Pelanggaran Siswa - SMAN 1 Natal</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-gray-900 to-gray-800 min-h-screen flex items-center justify-center p-4">

    <div class="w-full max-w-md mx-auto bg-white/10 backdrop-blur-lg rounded-2xl shadow-2xl p-8 text-white border border-white/20">
        <div class="text-center">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/Logo_tut_wuri_handayani.svg/1200px-Logo_tut_wuri_handayani.svg.png" alt="Logo Sekolah" class="mx-auto mb-6 w-28 h-28 p-2 bg-white/20 rounded-full shadow-lg">
            <h1 class="text-3xl font-extrabold">Portal Pelanggaran Siswa</h1>
            <p class="text-gray-300 mt-2 text-lg">SMA Negeri 1 Natal</p>
        </div>

        <div class="mt-10 space-y-5">
            <a href="form-pelanggaran.html" class="group block w-full text-center bg-yellow-400 text-gray-900 font-bold py-4 px-4 rounded-xl shadow-lg hover:bg-yellow-300 focus:outline-none focus:ring-4 focus:ring-yellow-400/50 transition-all duration-300 transform hover:-translate-y-1">
                <div class="flex items-center justify-center">
                    <i data-lucide="file-plus-2" class="mr-3 h-6 w-6"></i>
                    Catat Pelanggaran Baru
                </div>
            </a>

            <a href="https://docs.google.com/spreadsheets/d/1ANxe4deZFKAmMNSUhwzx0QVzJfZzgX1bqefxU0AmPJ4/edit#gid=157047955" target="_blank" class="group block w-full text-center bg-white/20 text-white font-bold py-4 px-4 rounded-xl shadow-lg hover:bg-white/30 focus:outline-none focus:ring-4 focus:ring-white/50 transition-all duration-300 transform hover:-translate-y-1">
                <div class="flex items-center justify-center">
                    <i data-lucide="bar-chart-3" class="mr-3 h-6 w-6"></i>
                    Lihat Rekap Pelanggaran
                </div>
            </a>
        </div>
    </div>
    <script>
      lucide.createIcons();
    </script>
</body>
</html>
