<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir Detail Pelanggaran Siswa - SMAN 1 Natal</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 py-8">

    <div class="w-full max-w-lg mx-auto p-6 md:p-8 bg-white rounded-xl shadow-lg">
        <div class="text-center mb-8">
            <h1 class="text-2xl font-bold text-gray-800">Formulir Laporan Pelanggaran</h1>
            <p class="text-gray-500 mt-1">Lengkapi semua data pelanggaran dengan detail.</p>
        </div>

        <form action="#" method="POST" class="space-y-6">
            
            <fieldset class="border-t border-gray-200 pt-6">
                <legend class="text-lg font-semibold text-gray-900">1. Identitas Siswa</legend>
                
                <div class="mt-4 grid grid-cols-1 gap-y-6 sm:grid-cols-2 sm:gap-x-4">
                    <div>
                        <label for="nama-siswa" class="block text-sm font-medium text-gray-700">Nama Siswa</label>
                        <input type="text" name="nama-siswa" id="nama-siswa" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" placeholder="Nama lengkap siswa">
                    </div>
                    <div>
                        <label for="kelas" class="block text-sm font-medium text-gray-700">Kelas</label>
                        <input type="text" name="kelas" id="kelas" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" placeholder="Contoh: XII IPA 1">
                    </div>
                    <div class="sm:col-span-2">
                        <label for="nisn" class="block text-sm font-medium text-gray-700">NIS / NISN</label>
                        <input type="text" name="nisn" id="nisn" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" placeholder="Nomor Induk Siswa">
                    </div>
                </div>
            </fieldset>

            <fieldset class="border-t border-gray-200 pt-6">
                <legend class="text-lg font-semibold text-gray-900">2. Detail Pelanggaran</legend>
                <div class="mt-4 grid grid-cols-1 gap-y-6 sm:grid-cols-2 sm:gap-x-4">
                    <div>
                        <label for="tanggal-kejadian" class="block text-sm font-medium text-gray-700">Tanggal Kejadian</label>
                        <input type="date" name="tanggal-kejadian" id="tanggal-kejadian" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500">
                    </div>
                     <div>
                        <label for="waktu-kejadian" class="block text-sm font-medium text-gray-700">Waktu Kejadian (Kira-kira)</label>
                        <input type="time" name="waktu-kejadian" id="waktu-kejadian" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500">
                    </div>
                    <div class="sm:col-span-2">
                        <label for="jenis-pelanggaran" class="block text-sm font-medium text-gray-700">Jenis Pelanggaran</label>
                        <select id="jenis-pelanggaran" name="jenis-pelanggaran" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500">
                            <option value="" disabled selected>-- Pilih Jenis Pelanggaran --</option>
                            <optgroup label="Pelanggaran Ringan (5 Poin)">
                                <option value="Terlambat">Terlambat Masuk</option>
                                <option value="Seragam Tidak Lengkap">Seragam/Atribut Tidak Lengkap</option>
                                <option value="Rambut Tidak Rapi">Rambut Tidak Rapi / Diwarnai</option>
                            </optgroup>
                            <optgroup label="Pelanggaran Sedang (15 Poin)">
                                <option value="Tidak Mengerjakan Tugas">Tidak Mengerjakan Tugas</option>
                                <option value="Mengganggu KBM">Mengganggu Proses Belajar Mengajar</option>
                                <option value="Membuang Sampah Sembarangan">Membuang Sampah Sembarangan</option>
                            </optgroup>
                             <optgroup label="Pelanggaran Berat (25-50 Poin)">
                                <option value="Merokok di Sekolah">Merokok di Area Sekolah</option>
                                <option value="Absen Tanpa Keterangan">Absen Tanpa Keterangan (Bolos)</option>
                                <option value="Vandalisme">Vandalisme (Mencoret/Merusak Fasilitas)</option>
                                <option value="Berkelahi">Berkelahi</option>
                            </optgroup>
                            <option value="Lainnya">Lainnya</option>
                        </select>
                    </div>
                     <div class="sm:col-span-2">
                        <label for="catatan" class="block text-sm font-medium text-gray-700">Deskripsi / Kronologi Kejadian</label>
                        <textarea id="catatan" name="catatan" rows="4" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" placeholder="Jelaskan secara singkat apa yang terjadi, siapa saja yang terlibat, dan di mana lokasinya."></textarea>
                    </div>
                </div>
            </fieldset>

             <fieldset class="border-t border-gray-200 pt-6">
                <legend class="text-lg font-semibold text-gray-900">3. Pelapor & Tindak Lanjut</legend>
                 <div class="mt-4 grid grid-cols-1 gap-y-6">
                    <div>
                        <label for="nama-guru" class="block text-sm font-medium text-gray-700">Nama Guru Pelapor</label>
                        <input type="text" name="nama-guru" id="nama-guru" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" placeholder="Tulis nama lengkap Anda">
                    </div>
                    <div>
                        <label for="tindakan" class="block text-sm font-medium text-gray-700">Tindakan yang Sudah Diambil (Jika Ada)</label>
                        <input type="text" name="tindakan" id="tindakan" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" placeholder="Contoh: Diberi teguran lisan, diminta push-up, dll.">
                    </div>
                    <div>
                        <label for="bukti-foto" class="block text-sm font-medium text-gray-700">Upload Bukti (Opsional)</label>
                        <input type="file" name="bukti-foto" id="bukti-foto" class="mt-1 block w-full text-sm text-gray-500 file:mr-4 file:py-2 file:px-4 file:rounded-md file:border-0 file:text-sm file:font-semibold file:bg-blue-50 file:text-blue-700 hover:file:bg-blue-100">
                    </div>
                </div>
            </fieldset>


            <div class="pt-6">
                <button type="submit" class="w-full flex justify-center py-3 px-4 border border-transparent rounded-lg shadow-sm text-base font-medium text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500">
                    Kirim Laporan Pelanggaran
                </button>
            </div>
        </form>

         <div class="text-center mt-6">
            <a href="index.html" class="text-sm text-blue-600 hover:text-blue-500">
                &larr; Kembali ke Portal Utama
            </a>
        </div>
    </div>

</body>
</html>
