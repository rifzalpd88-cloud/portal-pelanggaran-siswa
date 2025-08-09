<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir Pencatatan Pelanggaran - SMAN 1 Natal</title>
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
<body class="bg-gradient-to-br from-gray-900 to-gray-800 min-h-screen py-10 px-4">

    <div class="w-full max-w-3xl mx-auto bg-white/10 backdrop-blur-lg rounded-2xl shadow-2xl p-6 md:p-8 text-white border border-white/20">
        <div class="text-center mb-6">
            <h1 class="text-3xl font-extrabold">Catat Pelanggaran Baru</h1>
            <p class="text-gray-300 mt-2">Formulir ini terhubung langsung ke rekap data.</p>
        </div>

        <div class="aspect-w-1 aspect-h-1 md:aspect-w-4 md:aspect-h-3 lg:aspect-w-3 lg:aspect-h-2 overflow-hidden rounded-xl border border-white/10 shadow-inner">
             <iframe 
                src="https://docs.google.com/forms/d/e/1FAIpQLSfSAmPIsCHGX0ShpYFK8gzd8sn1AmYT5ftImKSHZdsoh7CSlg/viewform?embedded=true" 
                class="w-full h-full"
                frameborder="0" 
                marginheight="0" 
                marginwidth="0">
                Memuat…
            </iframe>
        </div>

        <div class="text-center mt-8">
            <a href="index.html" class="inline-flex items-center gap-2 text-yellow-400 hover:text-yellow-300 font-semibold transition-colors duration-300">
                <i data-lucide="arrow-left-circle" class="h-5 w-5"></i>
                Kembali ke Portal Utama
            </a>
        </div>
    </div>

    <script>
      lucide.createIcons();
    </script>
</body>
</html>
