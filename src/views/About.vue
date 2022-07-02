<script setup></script>

<template>
  <div>
    <div
      class="mx-auto max-w-screen-xl px-4 py-12 sm:px-6 lg:flex lg:items-center lg:justify-between lg:py-16 lg:px-8"
    >
      <h2
        class="text-3xl font-extrabold leading-9 tracking-tight text-gray-900 sm:text-4xl sm:leading-10"
      >
        关于榕实夕阳红
        <br />
        <span class="text-3xl text-gray-400">榕实毕业生创建的组织</span>
      </h2>
      <div class="mt-8 flex lg:mt-0 lg:flex-shrink-0">
        <div class="inline-flex rounded-md shadow">
          <router-link
            to="/"
            class="mt-2 md:mt-5 p-3 px-5 bg-black text-white font-bold text-sm hover:bg-blue-600"
            >回到主页</router-link
          >
        </div>
      </div>
    </div>
  </div>
  <section class="container mx-auto py-10 md:py-20 antialiased">
    <section class="grid lg:grid-cols-2 2xl:grid-cols-4 grid-cols-1 gap-8">
      <article
        class="mx-auto max-w-sm pb-8 bg-cover bg-center cursor-pointer transform duration-500 hover:-translate-y-1 shadow-2xl rounded-xl"
      >
        <div class="mx-auto mb-20 mt-10 w-40">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            aria-hidden="true"
            role="img"
            class="iconify iconify--carbon"
            width="150"
            height="150"
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 32 32"
          >
            <path
              fill="currentColor"
              d="M12 4a5 5 0 1 1-5 5a5 5 0 0 1 5-5m0-2a7 7 0 1 0 7 7a7 7 0 0 0-7-7zm10 28h-2v-5a5 5 0 0 0-5-5H9a5 5 0 0 0-5 5v5H2v-5a7 7 0 0 1 7-7h6a7 7 0 0 1 7 7zm0-26h10v2H22zm0 5h10v2H22zm0 5h7v2h-7z"
            ></path>
          </svg>
        </div>
        <h2 class="text-center text-3xl mt-8 font-bold min-h-18 px-12">人员组成</h2>
        <p class="m-4 text-lg p-4 leading-relaxed text-center">
          榕实夕阳红是一个由榕实毕业生创立的非官方组织。
          <br />
          <br />
          由pi-dal于2022年六月创立，目前拥有六位成员。
        </p>
      </article>

      <article
        class="mx-auto max-w-sm pb-8 bg-cover bg-center cursor-pointer transform duration-500 hover:-translate-y-1 shadow-2xl rounded-xl"
      >
        <div class="mx-auto mb-20 mt-10 w-40">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            aria-hidden="true"
            role="img"
            class="iconify iconify--bx"
            width="150"
            height="150"
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
          >
            <path
              fill="currentColor"
              d="M5 22h14c1.103 0 2-.897 2-2V5c0-1.103-.897-2-2-2h-2a1 1 0 0 0-1-1H8a1 1 0 0 0-1 1H5c-1.103 0-2 .897-2 2v15c0 1.103.897 2 2 2zM5 5h2v2h10V5h2v15H5V5z"
            ></path>
            <path
              fill="currentColor"
              d="m11 13.586l-1.793-1.793l-1.414 1.414L11 16.414l5.207-5.207l-1.414-1.414z"
            ></path>
          </svg>
          </div>
          <h2 class="text-center text-3xl mt-8 font-bold min-h-18 px-12">宗旨</h2>
          <p class="m-4 text-lg p-4 leading-relaxed text-center">
            通过这个组织使榕实毕业生能够增进友谊，提高交流，提升自我。
          </p>
      </article>
    </section>
  </section>
</template>
