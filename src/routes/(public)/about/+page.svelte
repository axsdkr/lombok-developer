<script lang="ts">
  // import Iconify from '@iconify/svelte'
  // import { businessDecisions, devProductivity } from '$lib/images'
</script>

<section class="container py-32">
  <div class="py-20">
    <div class="flex-col md:flex lg:flex-row-reverse">
      <img
        class=" rounded-sm border-r-4 border-emerald-500 shadow-2xl"
        src="https://images.unsplash.com/photo-1606857521015-7f9fcf423740?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTB8fG9mZmljZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=400&q=60"
        alt="" />
      <div class=" pl-2">
        <!-- <iconify class=" text-4xl mb-5 mr-2 text-sky-900" icon="material-symbols:home-app-logo"></iconify> -->
        <h1 class="mb-2 mt-10 text-4xl font-semibold lg:mt-2">ABOUT US</h1>
        <hr />
        <p class="py-5">
          We are a web design and digital marketing company based in Lombok, Indonesia. We have been
          designing many websites since 2004.
        </p>
        <button class="btn-outline btn-success btn">Read More</button>
      </div>
    </div>
  </div>
</section>

<section class=" container mb-20 bg-gray-700 py-20">
  <h1 class="text-center text-3xl font-semibold text-white">VISIONS & MISIONS</h1>
  <p class="text-center text-white">Lombok Developer</p>
  <div class="mt-5 flex-col md:flex lg:flex-row">
    <p class=" border-l-4 border-emerald-500 bg-white p-16">
      <span class="text-2xl font-semibold">Vision</span>
      Menjadi perusahaan Teknologi Informasi terkemuka di Indonesia pada umumnya dan Bali khususnya.
    </p>

    <p class="max-w-lg border-r-4 border-white bg-emerald-500 p-16 text-white">
      <span class="text-2xl font-semibold">Misions</span>
      Menjadi perusahaan Teknologi Informasi terdepan dalam mengembangkan kualitas layanan, kreativitas,
      peningkatan kualitas layanan, cepat, akurat dan tepat dalam aspek teknologi informasi.
    </p>
  </div>
</section>

<section class="mb-20 text-center">
  <div class="stats">
    <div class="flex-col md:flex lg:flex-row">
      <div class="stat place-items-center">
        <div class="stat-title">Downloads</div>
        <div class="stat-value">31K</div>
        <div class="stat-desc">From January 1st to February 1st</div>
      </div>

      <div class="stat place-items-center">
        <div class="stat-title">Users</div>
        <div class="stat-value text-primary">4,200</div>
        <div class="stat-desc text-primary">↗︎ 40 (2%)</div>
      </div>

      <div class="stat place-items-center">
        <div class="stat-title">New Registers</div>
        <div class="stat-value">1,200</div>
        <div class="stat-desc">↘︎ 90 (14%)</div>
      </div>
    </div>
  </div>
</section>

<section class="container mb-32 grid py-20">
  <p class="my-10 text-center text-4xl font-semibold">Our Creative Team.</p>

  <div class=" grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3">
    <div>
      <div class="card m-auto mb-5 w-64 bg-base-100 shadow-xl">
        <figure>
          <img
            src="https://images.unsplash.com/photo-1600486913747-55e5470d6f40?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTh8fG1hbnxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=400&q=60"
            alt="Man" />
        </figure>
        <div class="card-body">
          <h2 class="card-title">UI UX Developer</h2>
          <p>Hulami Haekal</p>
          <div class="card-actions justify-end" />
        </div>
      </div>
    </div>

    <div>
      <div class="card m-auto mb-5 w-64 bg-base-100 shadow-xl">
        <figure>
          <img
            src="https://images.unsplash.com/photo-1600486913747-55e5470d6f40?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTh8fG1hbnxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=400&q=60"
            alt="Man" />
        </figure>
        <div class="card-body">
          <h2 class="card-title">Frontend developer</h2>
          <p>Bani Taufik</p>
          <div class="card-actions justify-end" />
        </div>
      </div>
    </div>

    <div>
      <div class="card m-auto w-64 bg-base-100 shadow-xl">
        <figure>
          <img
            src="https://images.unsplash.com/photo-1600486913747-55e5470d6f40?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTh8fG1hbnxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=400&q=60"
            alt="Man" />
        </figure>
        <div class="card-body">
          <h2 class="card-title">Backend developer</h2>
          <p>M sukrillah</p>
          <div class="card-actions justify-end" />
        </div>
      </div>
    </div>
  </div>
</section>
