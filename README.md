<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Program Jum'at Berkat</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.7/dist/tailwind.min.css" rel="stylesheet">
</head>

<body>
  <!-- Tombol dengan Background Gambar -->
  <div class="bg-cover bg-center bg-blue-400 py-24">
    <div class="container mx-auto px-4">
      <div class="max-w-xxl mx-auto text-center">
        <h1 class="text-5xl font-bold text-white mb-4">Selamat Datang di Program Jum'at Berkat</h1>
        <p class="text-lg text-white mb-8">Bersedekah dengan memberikan makanan kepada yang memerlukan di hari Jum'at
        </p>
        <a href="#" class="px-6 py-3 bg-white text-blue-600 font-bold rounded focus:outline-none focus:shadow-outline"
          type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false"
          aria-controls="collapseExample">Selengkapnya</a>
        <div class="collapse hidden mt-2" id="collapseExample">
          <div class="p-4 bg-gray-100 mx-auto rounded-lg text-blue-600">
            <p>Mari ikut membantu sesama kita dengan menyediakan keperluan asas yaitu makanan kepada mereka yang
              memerlukan. Bantuan kita akan sangat membantu mereka.
            </p> 
          </div>
        </div>
      </div>
    </div>
  </div>

  <section class="overflow-hidden bg-gray-50 sm:grid sm:grid-cols-2">
    <div class="p-8 md:p-12 lg:px-16 lg:py-24">
      <div class="mx-auto max-w-xl text-center ltr:sm:text-left rtl:sm:text-right">
        <h2 class="text-2xl font-bold text-gray-900 md:text-3xl">
          Mari bersama
        </h2>
        <p class="text-gray-500 md:mt-4 md:block">
          Mari ikut membantu sesama kita dengan menyediakan keperluan asas yaitu makanan kepada mereka yang memerlukan.
          Bantuan kita akan sangat membantu mereka
        </p>

        <div class="mt-4 md:mt-8">
          <a href="#" class="inline-block bg-white text-blue-600 font-bold py-3 px-6 rounded-lg shadow-lg">
            Ikut Berpartisipasi
          </a>
        </div>
      </div>
    </div>

    <img alt="Student" src="PJBS1.png" class="h-56 w-full object-cover sm:h-full" />
  </section>

  <section class="bg-white">
    <div class="mx-auto max-w-screen-xl px-4 py-12 sm:px-6 md:py-16 lg:px-8">
      <div class="mx-auto max-w-3xl text-center">
        <h2 class="text-3xl font-bold text-blue-600 sm:text-4xl">
          STATISTIK
        </h2>

        <p class="mt-4 text-gray-500 sm:text-xl">
          Program berbagi bersama "Jum'at Berkat sudah dimulai sejak 2017, sejak itu ribuan orang telah mendapatkan
          manfaatnya"
        </p>
      </div>

      <div class="mt-8 sm:mt-12">
        <dl class="grid grid-cols-1 gap-4 sm:grid-cols-2 sm:divide-x sm:divide-gray-100">
          <div class="flex flex-col px-4 py-8 text-center">
            <dt class="order-last text-lg font-medium text-gray-500">
              Jumlah Nilai
            </dt>

            <dd class="text-4xl font-extrabold text-blue-600 md:text-4xl">
              Rp.500.000.000
            </dd>
          </div>

          <div class="flex flex-col px-4 py-8 text-center">
            <dt class="order-last text-lg font-medium text-gray-500">
              Orang yang memerlukan
            </dt>

            <dd class="text-4xl font-extrabold text-blue-600 md:text-5xl">10.000</dd>
          </div>

          <!-- <div class="flex flex-col px-4 py-8 text-center">
            <dt class="order-last text-lg font-medium text-gray-500">
              Total Addons
            </dt>

            <dd class="text-4xl font-extrabold text-blue-600 md:text-5xl">86</dd> -->
      </div>
      </dl>
    </div>
    </div>
  </section>

  <section class="bg-gray-50">
    <div class="mx-auto max-w-screen-xl px-4 py-20 lg:flex lg:items-center">
      <div class="mx-auto max-w-xl text-center">
        <h1 class="text-3xl font-extrabold sm:text-5xl">
          Hubungi Kami
          <!-- <strong class="font-extrabold text-red-700 sm:block">
            Untuk Informasi Lebih Lanjut
          </strong> -->
        </h1>

        <!-- <p class="mt-4 sm:text-xl/relaxed">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nesciunt illo
          tenetur fuga ducimus numquam ea!
        </p> -->

        <div class="mt-8 flex flex-wrap justify-center gap-4">
          <a class="block w-full rounded bg-red-600 px-12 py-3 text-sm font-medium text-white shadow hover:bg-red-700 focus:outline-none focus:ring active:bg-red-500 sm:w-auto"
            href="/get-started">
            Whatsapp
          </a>
          <a class="block w-full rounded px-12 py-3 text-sm font-medium text-red-600 shadow hover:text-red-700 focus:outline-none focus:ring active:text-red-500 sm:w-auto"
            href="/about">
            Email
          </a>
        </div>
      </div>
    </div>
  </section>

  <script>
    const toggleButton = document.querySelector('[data-toggle="collapse"]');
    const collapseElement = document.querySelector(toggleButton.getAttribute('data-target'));
    toggleButton.addEventListener('click', () => {
      collapseElement.classList.toggle('hidden');
    });
  </script>

  <!-- Footer -->
  <footer class="bg-gray-800 py-8">
    <div class="container mx-auto px-4">
      <div class="text-center text-white">
        <p>&copy; 2023 Program Jum'at Berkat. All rights reserved.</p>
        <p>Jl. Harapan Utama RT 001/011, Kec. Babakan Madang, Kab. Bogor, Jawa Barat 16810</p>
      </div>
    </div>
  </footer>

</body>

</html>
