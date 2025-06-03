<template>
  <!-- SECTION 1 -->
  <section class="min-h-screen bg-[#800000] text-white flex flex-col items-center justify-center py-8">
    <!-- Logo & Title -->
    <div class="text-center space-y-4">
      <h2 class="tracking-widest text-sm font-semibold">UNDANGAN</h2>
      <img
        src=""
        alt="Kwong Moy Heritage Logo"
        class="mx-auto w-48"
      />
      <p class="text-xs font-bold uppercase text-yellow-500">No Pork No Lard</p>
      <p class="text-sm italic">Chinese Cuisine, Noodle Specialist & Dimsum</p>
      <h1 class="text-4xl font-serif italic mt-4">Soft Opening</h1>
    </div>

    <!-- Guest Name -->
    <div class="mt-8 text-center">
      <p>Kepada Yth</p>
      <p>Bapak/Ibu/Saudara/i</p>
      <p>Di Tempat</p>
    </div>

    <!-- Contact & Time -->
    <div class="mt-10 space-y-4 text-center">
      <div>
        <p class="text-sm tracking-wide uppercase">Untuk reservasi hubungi:</p>
        <p class="font-bold">0815-778-8567</p>
      </div>
      <div>
        <p class="text-sm tracking-wide uppercase">Jam Layanan:</p>
        <p class="font-bold">07.00 - 22.00 WIB</p>
      </div>
    </div>

    <!-- Date Banner -->
    <div class="w-full flex items-center justify-center relative h-16 mt-10">
      <div class="w-full h-4 bg-[#cdb577] text-black font-semibold px-4 py-1 shadow"></div>
      <div class="flex items-center absolute top-0 bg-[#cdb577] p-4 h-full">
        <p class="font-bold text-[#800000]">9 - 16 JUNE 2025</p>
      </div>
    </div>
  </section>

  <!-- SECTION 2 -->
  <section class="min-h-screen bg-[#800000] text-white flex items-center justify-end py-8">
    <div class="bg-[#cdb577] h-fit py-10 w-[90%] text-[#800000] flex flex-col items-start justify-center gap-5">
      <!-- Judul Menu -->
      <div class="text-center relative mb-6 w-full">
        <img src="/231194.jpg" alt="Menu header" class="w-full h-32" />
        <h2 class="text-white font-bold text-4xl absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2">MENU</h2>
      </div>
  
      <div class="grid grid-cols-2 gap-6 text-sm px-2">
        <!-- Kolom 1 -->
        <div>
          <h3 class="font-bold mb-1">YAMIEN</h3>
          <ul class="space-y-0.5">
            <li class="text-xs flex flex-wrap">Yamien Asin/Manis <span class="float-right">Rp 30.000</span></li>
            <li class="text-xs flex flex-wrap">Yamien Asin/Manis Baso <span class="float-right">Rp 35.000</span></li>
            <li class="text-xs">Yamien Asin/Pangsit <span class="float-right">Rp 40.000</span></li>
            <li class="text-xs">Yamien Asin/Manis Baso Pangsit <span class="float-right">Rp 45.000</span></li>
          </ul>
  
          <h3 class="font-bold mt-4 mb-1">DIMSUM STEAM</h3>
          <ul class="space-y-0.5">
            <li class="text-xs">Ceker Ayam <span class="float-right">Rp 25.000</span></li>
            <li class="text-xs">Char Siu Pao <span class="float-right">Rp 25.000</span></li>
            <li class="text-xs">Cheongfan Udang Kering <span class="float-right">Rp 25.000</span></li>
            <li class="text-xs">Hakau <span class="float-right">Rp 25.000</span></li>
            <li class="text-xs">Siomay Ayam <span class="float-right">Rp 25.000</span></li>
            <li class="text-xs">Telur Asin Hongkong <span class="float-right">Rp 25.000</span></li>
          </ul>
  
          <h3 class="font-bold mt-4 mb-1">DIMSUM GORENG</h3>
          <ul class="space-y-0.5">
            <li class="text-xs">Bola Udang Kumis Naga <span class="float-right">Rp 22.000</span></li>
            <li class="text-xs">Cakue Goreng Seafood <span class="float-right">Rp 25.000</span></li>
            <li class="text-xs">Gyoza <span class="float-right">Rp 25.000</span></li>
            <li class="text-xs">Talas Goreng <span class="float-right">Rp 22.000</span></li>
          </ul>
        </div>
  
        <!-- Kolom 2 -->
        <div>
          <h3 class="font-bold mb-1">MENU PAKET</h3>
          <ul class="space-y-0.5">
            <li class="text-xs">Nasi Ayam Cah Brokoli <span class="float-right">Rp 32.500</span></li>
            <li class="text-xs">Nasi Ayam Cah Jamur <span class="float-right">Rp 32.500</span></li>
            <li class="text-xs">Nasi Ayam Cah Kapri <span class="float-right">Rp 32.500</span></li>
            <li class="text-xs">Nasi Ayam Goreng Lada Hitam <span class="float-right">Rp 32.500</span></li>
            <li class="text-xs">Nasi Ayam Kuluyuk <span class="float-right">Rp 32.500</span></li>
            <li class="text-xs">Nasi Ayam Teriyaki <span class="float-right">Rp 32.500</span></li>
            <li class="text-xs">Nasi Bistik Ayam <span class="float-right">Rp 32.500</span></li>
            <li class="text-xs">Nasi Sapi Cah Jamur <span class="float-right">Rp 37.000</span></li>
            <li class="text-xs">Nasi Sapi Kuluyuk <span class="float-right">Rp 37.000</span></li>
            <li class="text-xs">Nasi Sapi Lada Hitam <span class="float-right">Rp 37.000</span></li>
            <li class="text-xs">Nasi Udang Asam Manis <span class="float-right">Rp 40.000</span></li>
            <li class="text-xs">Nasi Udang Goreng Tepung <span class="float-right">Rp 40.000</span></li>
          </ul>
        </div>
      </div>
  
      <!-- Footer teks -->
      <p class="mt-6 italic text-center text-[#7b1c1c] text-sm leading-relaxed px-2">
        Menu yang kami tampilkan belum mewakili semuanya. <br />
        <span class="font-semibold">Ada banyak kejutan rasa di Kwongmoy yang menanti kamu di meja makan!</span>
      </p>
    </div>
  </section>

  <!-- SECTION 3 -->

  <!-- SECTION 4 -->
  <section class="min-h-screen bg-[#800000] text-white flex items-center justify-start py-8">
    <!-- Logo & Title -->
    <div class="bg-[#cdb577] h-fit py-10 w-[90%] text-[#800000] flex flex-col items-start justify-center gap-5">
      <div class="flex flex-col space-y-2 mx-auto pb-4 px-6">
        <h5 class="text-2xl">Undangan ini berlaku sebagai:</h5>
        <h1 class="font-bold text-4xl">Voucher Senilai Rp250.000</h1>
        <span class="text-2xl">Dan langsung terdaftar sebagai Silver Member</span>
        <p class="font-bold mb-2 mt-8">Catatan Penting:</p>
        <ul class="list-disc pl-5 space-y-1 text-sm leading-relaxed">
          <li>Tidak dapat digabungkan dengan promo lain dan tidak dapat diuangkan</li>
          <li>Voucher ini hanya berlaku untuk 1 kali kunjungan selama periode soft opening</li>
          <li>Harap tunjukkan undangan ini kepada petugas saat kedatangan</li>
          <li>Promo berlaku untuk makan di tempat (dine-in)</li>
          <li>Berlaku 10 - 16 Juni 2025</li>
        </ul>
      </div>
      <img src="/231194.jpg" class="w-[90%] h-32 object-cover" />
    </div>
  </section>

  <!-- History Section 1 -->
  <section class="min-h-screen bg-[#f5f2ea] text-black px-8 py-10">
    <div class="max-w-[480px] mx-auto">
      <h2 class="text-center text-2xl italic font-serif">
        The History of <span class="font-bold text-yellow-800">Kwong Moy Heritage</span> <span class="italic text-sm">since 1948</span>
      </h2>

      <!-- Pendiri -->
      <div class="flex justify-evenly items-center gap-4 relative h-ful mt-6">
        <div class="absolute left-0 top-1/2 h-1/2 border-l-2 border-dashed border-black"></div>
        <div class="absolute w-3 h-3 rounded-full bg-black -left-1 top-1/2"></div>
        <div class="text-center">
          <img src="/231194.jpg" class="rounded-full mx-auto w-24 h-36 object-cover border-4 border-[#7b5540]" />
          <p class="font-semibold mt-2">Tjoeng Kim Yin</p>
          <p class="text-xs">張金賢</p>
          <p class="text-xs">1919 - 2016</p>
        </div>
        <div class="text-center">
          <img src="/231194.jpg" class="rounded-full mx-auto w-24 h-36 object-cover border-4 border-[#7b5540]" />
          <p class="font-semibold mt-2">Xiong Yu Xiu</p>
          <p class="text-xs">熊秀秀</p>
          <p class="text-xs">1929 - 2012</p>
        </div>
      </div>

      <!-- Cerita Tahun 1946 -->
      <div class="flex flex-col justify-evenly items-center gap-4 relative h-full">
        <div class="absolute left-0 top-0 h-full border-l-2 border-dashed border-black"></div>
        <div class="absolute w-3 h-3 rounded-full bg-black -left-1 top-1/4"></div>
        <div class="absolute w-3 h-3 rounded-full bg-black -left-1 bottom-1/4"></div>

        <div class="bg-[#cdb577] border border-[#5a3e36] text-black py-4 px-6 rounded-md shadow mx-5 mt-6">
          <p class="text-center text-sm"><span class="font-bold">1946</span> – Awal Sebuah Perjalanan<br />
          <strong>Tjoeng Kim Yin</strong> tiba di Indonesia. Sesampainya, ia bertemu dengan <strong>Xiong Yu Xiu</strong>, yang menjadi pasangan hidupnya.</p>
        </div>
  
        <!-- Cerita Tahun 1948 -->
        <div class="bg-[#cdb577] border border-[#5a3e36] text-black py-4 px-6 rounded-md shadow mx-5">
          <p class="text-center text-sm"><span class="font-bold">1948 – Berdirinya Kedai KwongMoy Pertama Kali</span>,<br />
          <strong>Tjoeng Kim Yin</strong> bersama <strong>Xiong Yu Xiu</strong> mendirikan usaha rumah makan di Cianjur, yang diberi nama kwongmoy.</p>
        </div>
      </div>

      <!-- Foto Tahun 1969 -->
      <div class="flex flex-col justify-evenly items-center gap-4 relative h-full">
        <div class="absolute left-0 top-0 h-1/2 border-l-2 border-dashed border-black"></div>
        <div class="absolute w-3 h-3 rounded-full bg-black -left-1 top-1/2"></div>
        <div class="grid grid-cols-3 gap-2 mx-5 mt-6">
          <img src="/231194.jpg" class="object-cover rounded shadow" />
          <img src="/231194.jpg" class="object-cover rounded shadow" />
          <img src="/231194.jpg" class="object-cover rounded shadow" />
        </div>
      </div>
    </div>
  </section>

  <!-- History Section 2 -->
  <section class="min-h-screen bg-[#f5f2ea] text-black px-8 py-10">
    <div class="max-w-[480px] mx-auto">
      <h2 class="text-center text-2xl italic font-serif">
        The History of <span class="font-bold text-yellow-800">Kwong Moy Heritage</span> <span class="italic text-sm">since 1948</span>
      </h2>

      <!-- Pendiri -->
      <div class="flex justify-evenly items-center gap-4 relative h-ful mt-6">
        <div class="absolute left-0 top-1/2 h-1/2 border-l-2 border-dashed border-black"></div>
        <div class="absolute w-3 h-3 rounded-full bg-black -left-1 top-1/2"></div>
        <div class="text-center">
          <img src="/231194.jpg" class="mx-auto w-24 h-36 object-cover" />
          <p class="text-xs">1969</p>
        </div>
        <div class="text-center">
          <img src="/231194.jpg" class="mx-auto w-24 h-36 object-cover" />
          <p class="text-xs">1969</p>
        </div>
      </div>

      <!-- Cerita Tahun 1980 -->
      <div class="flex flex-col justify-evenly items-center gap-4 relative h-full">
        <div class="absolute left-0 top-0 h-full border-l-2 border-dashed border-black"></div>
        <div class="absolute w-3 h-3 rounded-full bg-black -left-1 top-1/4"></div>

        <div class="bg-[#cdb577] border border-[#5a3e36] text-black py-4 px-6 rounded-md shadow mx-5 mt-2">
          <p class="text-center text-sm"><span class="font-bold">1980</span> – Generasi Kedua Melanjutkan Warisan
 Dengan dedikasi dan inovasi, generasi kedua mengambil alih. Resep warisan tetap dipertahankan, sambil menyesuaikan dengan zaman yang terus berubah.</p>
        </div>
  
        <div class="flex justify-center mt-1">
          <div class="text-center">
            <img src="/231194.jpg" class="mx-auto w-24 h-36 object-cover rounded shadow" />
            <p class="text-xs">1982</p>
          </div>
        </div>
      </div>

      <!-- Cerita Tahun 2025 -->
      <div class="flex flex-col justify-evenly items-center gap-4 relative h-full">
        <div class="absolute left-0 top-0 h-3/4 border-l-2 border-dashed border-black"></div>
        <div class="absolute w-3 h-3 rounded-full bg-black -left-1 top-1/4"></div>
        <div class="absolute w-3 h-3 rounded-full bg-black -left-1 top-3/4"></div>

        <div class="bg-[#cdb577] border border-[#5a3e36] text-black py-4 px-6 rounded-md shadow mx-5 mt-2">
          <p class="text-center text-sm"><span class="font-bold">2025</span> – Melampaui Waktu, Menjadi Lebih Kuat
 Setiap resep, setiap bumbu, dan setiap cerita telah melewati waktu. Kini, generasi ketiga melanjutkan jejak, bukan hanya menjaga rasa, tapi juga membawa warisan ini ke era baru. Dengan semangat yang sama, mereka merawat tradisi sekaligus berinovasi, memastikan bahwa kehangatan dan cita rasa khas tetap hidup untuk generasi berikutnya.</p>
        </div>
  
        <div class="flex justify-center mt-1">
          <div class="text-center">
            <img src="/231194.jpg" class="mx-auto w-24 h-36 object-cover rounded shadow" />
            <p class="text-xs">2025</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- SECTION 7 -->
  <section class="min-h-screen bg-[#800000] text-white flex flex-col items-center justify-center py-8">
    <!-- Logo & Title -->
    <div class="text-center">
      <h2 class="tracking-widest text-sm font-semibold">UNDANGAN</h2>
    </div>
  </section>
</template>

<script setup>
// You can later import dynamic guest name or reservation features here
</script>

<style scoped>
/* You can add floral Chinese-style decorations with background image or animation */
</style>
