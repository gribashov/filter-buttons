<template>
  <body class="bg-gray-100 font-sans">
    <header class="bg-white border-b">
      <div class="container mx-auto" style="max-width: 970px">
        <div class="flex h-12 items-center justify-between">
          <!-- left side -->
          <div class="flex items-center">
            <!-- logo -->
            <a href="#" class="mr-2 w-40 flex-shrink-0"
              ><svg
                class="w-36"
                fill="none"
                viewBox="0 0 274 48"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="m0 23c0-10.8423 0-16.26346 3.36827-19.63173s8.78943-3.36827 19.63173-3.36827h2c10.8423 0 16.2635 0 19.6317 3.36827 3.3683 3.36827 3.3683 8.78943 3.3683 19.63173v2c0 10.8423 0 16.2635-3.3683 19.6317-3.3682 3.3683-8.7894 3.3683-19.6317 3.3683h-2c-10.8423 0-16.26346 0-19.63173-3.3683-3.36827-3.3682-3.36827-8.7894-3.36827-19.6317z"
                  fill="#2787f5"
                />
                <path
                  clip-rule="evenodd"
                  d="m13.0009 15h-3.5008c-1.00024 0-1.2003.4708-1.2003.9898 0 .9271 1.18686 5.525 5.5262 11.6061 2.8929 4.1529 6.9687 6.4041 10.6776 6.4041 2.2253 0 2.5006-.5 2.5006-1.3612v-3.1388c0-1 .2108-1.1996.9154-1.1996.5193 0 1.4094.2596 3.4864 2.2619 2.3737 2.3731 2.765 3.4377 4.1001 3.4377h3.5008c1.0003 0 1.5004-.5 1.2119-1.4867-.3157-.9834-1.449-2.4103-2.9528-4.1016-.816-.9641-2.0399-2.0023-2.4108-2.5215-.5192-.6674-.3709-.9641 0-1.5573 0 0 4.2652-6.007 4.7103-8.0463.2225-.7417 0-1.2866-1.0587-1.2866h-3.5008c-.8901 0-1.3005.4708-1.5231.9898 0 0-1.7802 4.3384-4.3022 7.1565-.816.8157-1.1869 1.0753-1.632 1.0753-.2225 0-.5446-.2596-.5446-1.0011v-6.9339c0-.89-.2583-1.2866-1.0002-1.2866h-5.5013c-.5562 0-.8908.413-.8908.8045 0 .8436 1.261 1.0382 1.391 3.4113v5.1542c0 1.13-.2042 1.3349-.6492 1.3349-1.1868 0-4.0737-4.3578-5.7859-9.3442-.3355-.9692-.6721-1.3607-1.5668-1.3607z"
                  fill="#fff"
                  fill-rule="evenodd"
                />
                <g fill="#000">
                  <path
                    d="m81.8929 23.5791c1.9035-.8883 3.1302-2.3688 3.1302-4.653 0-3.4686-3.1725-5.922-7.7409-5.922h-10.5327v21.996h10.998c4.7376 0 8.037-2.5803 8.037-6.0912 0-2.6649-1.7343-4.653-3.8916-5.3298zm-10.2789-6.5565h5.6682c1.692 0 2.8764 1.0152 2.8764 2.4111s-1.1844 2.3688-2.8764 2.3688h-5.6682zm6.1335 13.959h-6.1335v-5.3721h6.1335c1.9035 0 3.1725 1.0998 3.1725 2.7072s-1.269 2.6649-3.1725 2.6649z"
                  />
                  <path
                    d="m103.876 35.0001h6.387l-10.11-11.421 9.264-10.575h-5.795l-7.3603 8.5446h-1.1844v-8.5446h-4.8645v21.996h4.8645v-8.7561h1.1844z"
                  />
                  <path
                    d="m122.679 35.4231c6.895 0 11.76-4.7376 11.76-11.421s-4.865-11.421-11.76-11.421-11.759 4.7376-11.759 11.421 4.864 11.421 11.759 11.421zm0-4.4415c-3.976 0-6.683-2.8341-6.683-6.9795s2.707-6.9795 6.683-6.9795c3.977 0 6.684 2.8341 6.684 6.9795s-2.707 6.9795-6.684 6.9795z"
                  />
                  <path
                    d="m153.388 13.0041v8.6715h-9.856v-8.6715h-4.864v21.996h4.864v-8.883h9.856v8.883h4.865v-21.996z"
                  />
                  <path
                    d="m169.241 35.0001h4.865v-17.5545h7.614v-4.4415h-20.093v4.4415h7.614z"
                  />
                  <path
                    d="m193.24 12.5811c-4.272 0-8.037 2.1996-9.137 6.0066l4.484.7614c.677-1.3536 2.2-2.6226 4.399-2.6226 2.665 0 4.23 1.9035 4.442 4.7799h-4.738c-6.472 0-9.687 2.8341-9.687 6.8949 0 4.1031 3.173 7.0218 7.657 7.0218 3.595 0 6.006-2.0727 7.064-3.8916l1.015 3.4686h3.596v-12.3516c0-6.3873-3.469-10.0674-9.095-10.0674zm-1.438 18.7389c-2.369 0-3.892-1.2267-3.892-3.1302 0-1.692 1.227-2.8764 4.949-2.8764h4.611c0 3.5955-2.284 6.0066-5.668 6.0066z"
                  />
                  <path
                    d="m221.275 35.0001h6.387l-10.11-11.421 9.264-10.575h-5.795l-7.36 8.5446h-1.185v-8.5446h-4.864v21.996h4.864v-8.7561h1.185z"
                  />
                  <path
                    d="m235.913 35.0001h4.865v-17.5545h7.614v-4.4415h-20.093v4.4415h7.614z"
                  />
                  <path
                    d="m272.518 23.7483c0-6.345-4.738-11.1672-11.421-11.1672-6.684 0-11.421 4.7799-11.421 11.421s4.737 11.421 11.421 11.421c4.568 0 8.883-2.1573 10.532-6.345l-4.568-.7614c-1.058 1.5651-3.088 2.6649-5.668 2.6649-3.723 0-6.176-2.2842-6.641-5.6682h17.681c.042-.4653.085-.9729.085-1.5651zm-11.421-6.9372c3.045 0 5.329 1.9458 6.133 4.6953h-12.182c.803-2.8341 3.088-4.6953 6.049-4.6953z"
                  />
                </g></svg
            ></a>
            <!-- search -->
            <div class="mr-4">
              <div class="relative">
                <div
                  class="
                    absolute
                    left-0
                    top-0
                    items-center
                    justify-center
                    flex
                    h-full
                    pl-2
                    w-8
                    flex-shrink-0
                  "
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
                    />
                  </svg>
                </div>
                <input
                  type="text"
                  placeholder="Поиск"
                  class="
                    outline-none
                    bg-gray-100
                    placeholder-gray-400
                    rounded-lg
                    h-8
                    w-56
                    pl-8
                    pr-4
                    select-none
                  "
                />

                <!-- search list -->
                <div
                  class="absolute right-0 top-full mt-2 bg-white w-56 border"
                >
                  <!-- user card -->
                  <a
                    href="#"
                    class="
                      cursor-pointer
                      flex
                      items-center
                      px-2
                      hover:bg-gray-100
                      group
                      py-2
                      relative
                    "
                  >
                    <div class="flex-shrink-0">
                      <img
                        src="https://sun2-3.userapi.com/s/v1/ig2/XxjnkyiYnohAUSKbOOlLecTlmOivndUpMMlAOG6vx0pZcdGp4suarGF3LsqLOT6Mpc6v5_iIWbZQ57twM8PEo-CT.jpg?size=50x0&quality=96&crop=0,0,750,750&ava=1"
                        class="rounded-full w-8 mr-2 select-none"
                        alt="Masha Kambucha"
                      />
                    </div>
                    <div>
                      <div
                        class="
                          text-xs
                          font-medium
                          text-default-blue
                          truncate
                          pr-8
                        "
                        style="max-width: 175px"
                      >
                        Masha Kambucha
                      </div>
                      <div class="text-xs text-gray-400 opacity-0">Empty</div>
                    </div>

                    <div
                      class="
                        absolute
                        right-0
                        top-0
                        p-3
                        opacity-0
                        group-hover:opacity-100
                      "
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-5 text-custom-blue hover:text-custom-dark-blue"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
                        />
                        <path
                          d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
                        />
                      </svg>
                    </div>
                  </a>
                  <a
                    href="#"
                    class="
                      cursor-pointer
                      flex
                      items-center
                      px-2
                      hover:bg-gray-100
                      group
                      py-2
                      relative
                    "
                  >
                    <div class="flex-shrink-0">
                      <img
                        src="https://sun2-9.userapi.com/s/v1/ig2/t5pGtm8Yr_KFL5imBZhRu8Wv1unEeuXvVmTFrK3Ik4FZ2egXVg1G-OynJeoPcTlpm_F70zeY5GYBcAbZ4KoeWRCG.jpg?size=50x0&quality=95&crop=0,0,1069,1069&ava=1"
                        class="rounded-full w-8 mr-2 select-none"
                        alt="Алексей Ярошенко"
                      />
                    </div>
                    <div>
                      <div
                        class="
                          text-xs
                          font-medium
                          text-default-blue
                          truncate
                          pr-8
                        "
                        style="max-width: 175px"
                      >
                        Алексей Ярошенко
                      </div>
                      <div class="text-xs text-gray-400">Украина</div>
                    </div>

                    <div
                      class="
                        absolute
                        right-0
                        top-0
                        p-3
                        opacity-0
                        group-hover:opacity-100
                      "
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-5 text-custom-blue hover:text-custom-dark-blue"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
                        />
                        <path
                          d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
                        />
                      </svg>
                    </div>
                  </a>
                  <a
                    href="#"
                    class="
                      cursor-pointer
                      flex
                      items-center
                      px-2
                      hover:bg-gray-100
                      group
                      py-2
                      relative
                    "
                  >
                    <div class="flex-shrink-0">
                      <img
                        src="https://vk.com/images/camera_400.png"
                        class="rounded-full w-8 mr-2 select-none"
                        alt="Андрей Грибашов"
                      />
                    </div>
                    <div>
                      <div
                        class="
                          text-xs
                          font-medium
                          text-default-blue
                          truncate
                          pr-8
                        "
                        style="max-width: 175px"
                      >
                        Андрей Грошев
                      </div>
                      <div class="text-xs text-gray-400">Сальск, Россия</div>
                    </div>

                    <div
                      class="
                        absolute
                        right-0
                        top-0
                        p-3
                        opacity-0
                        group-hover:opacity-100
                      "
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-5 text-custom-blue hover:text-custom-dark-blue"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
                        />
                        <path
                          d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
                        />
                      </svg>
                    </div>
                  </a>
                  <a
                    href="#"
                    class="
                      cursor-pointer
                      flex
                      items-center
                      px-2
                      hover:bg-gray-100
                      group
                      py-2
                      relative
                    "
                  >
                    <div class="flex-shrink-0">
                      <img
                        src="https://sun2-4.userapi.com/s/v1/ig2/-gu-b4mO-NWVJSWx1EdiCNFZhKool9OL06BI53D5IvRcUChadAfX7GKDf2v4RvaxPYO8TmWLDYZYFqE9b3eAEiNU.jpg?size=100x0&quality=96&crop=22,2,1035,1035&ava=1"
                        class="rounded-full w-8 mr-2 select-none"
                        alt="Саша Аська"
                      />
                    </div>
                    <div>
                      <div
                        class="
                          text-xs
                          font-medium
                          text-default-blue
                          truncate
                          pr-8
                        "
                        style="max-width: 175px"
                      >
                        Саша Аська
                      </div>
                      <div class="text-xs text-gray-400 opacity-0">Empty</div>
                    </div>

                    <div
                      class="
                        absolute
                        right-0
                        top-0
                        p-3
                        opacity-0
                        group-hover:opacity-100
                      "
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-5 text-custom-blue hover:text-custom-dark-blue"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
                        />
                        <path
                          d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
                        />
                      </svg>
                    </div>
                  </a>
                  <a
                    href="#"
                    class="
                      cursor-pointer
                      flex
                      items-center
                      px-2
                      hover:bg-gray-100
                      group
                      py-2
                      relative
                    "
                  >
                    <div class="flex-shrink-0">
                      <img
                        src="https://sun2-10.userapi.com/s/v1/if1/fQ41Wqtz2lM3NBeS4U_6_ZSEvknE43aDiMh6VWX-k2xReruNkDFpgwQ5b534X0lJxCyELIOZ.jpg?size=100x0&quality=96&crop=611,339,844,844&ava=1"
                        class="rounded-full w-8 mr-2 select-none"
                        alt="Владимир Анонимиш"
                      />
                    </div>
                    <div>
                      <div
                        class="
                          text-xs
                          font-medium
                          text-default-blue
                          truncate
                          pr-8
                        "
                        style="max-width: 175px"
                      >
                        Владимир Анонимиш
                      </div>
                      <div
                        class="text-xs text-gray-400 truncate pr-8"
                        style="max-width: 175px"
                      >
                        ЮРИУ (ф) РАНХиГС (СКАГС) при Президенте РФ
                      </div>
                    </div>

                    <div
                      class="
                        absolute
                        right-0
                        top-0
                        p-3
                        opacity-0
                        group-hover:opacity-100
                      "
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-5 text-custom-blue hover:text-custom-dark-blue"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
                        />
                        <path
                          d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
                        />
                      </svg>
                    </div>
                  </a>
                  <a
                    href="#"
                    class="
                      cursor-pointer
                      flex
                      items-center
                      px-2
                      hover:bg-gray-100
                      group
                      py-2
                      relative
                    "
                  >
                    <div class="flex-shrink-0">
                      <img
                        src="https://sun2-10.userapi.com/s/v1/if1/v8ocAz1p31475kvMJUdaZWZ5nsXWsfQz4coGtRg441jtYLYPCp5bXYTb-u6BGMNdua_dXl1B.jpg?size=100x0&quality=96&crop=0,0,960,960&ava=1"
                        class="rounded-full w-8 mr-2 select-none"
                        alt="Елена Акрилова"
                      />
                    </div>
                    <div>
                      <div
                        class="
                          text-xs
                          font-medium
                          text-default-blue
                          truncate
                          pr-8
                        "
                        style="max-width: 175px"
                      >
                        Елена Акрилова
                      </div>
                      <div class="text-xs text-gray-400 opacity-0">Empty</div>
                    </div>

                    <div
                      class="
                        absolute
                        right-0
                        top-0
                        p-3
                        opacity-0
                        group-hover:opacity-100
                      "
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-5 text-custom-blue hover:text-custom-dark-blue"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
                        />
                        <path
                          d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
                        />
                      </svg>
                    </div>
                  </a>
                  <a
                    href="#"
                    class="
                      cursor-pointer
                      flex
                      items-center
                      px-2
                      hover:bg-gray-100
                      group
                      py-2
                      relative
                    "
                  >
                    <div class="flex-shrink-0">
                      <img
                        src="https://sun2-12.userapi.com/s/v1/if1/2nIuGhH88UG4ZIhRCSlvOf3LRIznGGV8PMTr_lZZLFpre9bY4NCYdcdrtvdyTkJIsTEcKGCF.jpg?size=100x0&quality=96&crop=1,52,399,399&ava=1"
                        class="rounded-full w-8 mr-2 select-none"
                        alt="Екатерина Абрамович"
                      />
                    </div>
                    <div>
                      <div
                        class="
                          text-xs
                          font-medium
                          text-default-blue
                          truncate
                          pr-8
                        "
                        style="max-width: 175px"
                      >
                        Екатерина Абрамович
                      </div>
                      <div class="text-xs text-gray-400 opacity-0">Empty</div>
                    </div>

                    <div
                      class="
                        absolute
                        right-0
                        top-0
                        p-3
                        opacity-0
                        group-hover:opacity-100
                      "
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-5 text-custom-blue hover:text-custom-dark-blue"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
                        />
                        <path
                          d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
                        />
                      </svg>
                    </div>
                  </a>
                  <a
                    href="#"
                    class="
                      cursor-pointer
                      flex
                      items-center
                      px-2
                      hover:bg-gray-100
                      group
                      py-2
                      relative
                    "
                  >
                    <div class="flex-shrink-0">
                      <img
                        src="https://sun2-10.userapi.com/s/v1/if1/1mvOHybG9OP-RAspTzuDRzV8KJ-6joDZiTqKJ6hnsIaD8C5xhVVwZWdUFVGLEUNFVFoJskeS.jpg?size=100x0&quality=96&crop=43,5,1031,1031&ava=1"
                        class="rounded-full w-8 mr-2 select-none"
                        alt="Богдан Одинстрах"
                      />
                    </div>
                    <div>
                      <div
                        class="
                          text-xs
                          font-medium
                          text-default-blue
                          truncate
                          pr-8
                        "
                        style="max-width: 175px"
                      >
                        Богдан Одинстрах
                      </div>
                      <div class="text-xs text-gray-400">Лицей №9</div>
                    </div>

                    <div
                      class="
                        absolute
                        right-0
                        top-0
                        p-3
                        opacity-0
                        group-hover:opacity-100
                      "
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-5 text-custom-blue hover:text-custom-dark-blue"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
                        />
                        <path
                          d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
                        />
                      </svg>
                    </div>
                  </a>
                </div>
              </div>
            </div>

            <!-- notification -->
            <div
              class="
                px-4
                flex
                items-center
                h-12
                hover:bg-gray-100
                cursor-pointer
                flex-shrink-0
                group
              "
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-full text-gray-400 group-hover:text-gray-500"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
                />
              </svg>
            </div>
            <!-- player field -->
            <div>
              <!-- player short -->
              <!-- <div
              class="
                px-4
                flex
                items-center
                h-12
                hover:bg-gray-100
                cursor-pointer
                flex-shrink-0
                group
              "
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-full text-gray-400 group-hover:text-gray-500"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 19V6l12-3v13M9 19c0 1.105-1.343 2-3 2s-3-.895-3-2 1.343-2 3-2 3 .895 3 2zm12-3c0 1.105-1.343 2-3 2s-3-.895-3-2 1.343-2 3-2 3 .895 3 2zM9 10l12-3"
                />
              </svg>
            </div> -->
              <!-- player long -->
              <div
                class="
                  flex
                  items-center
                  hover:bg-gray-100
                  h-12
                  cursor-pointer
                  px-2
                "
              >
                <div class="mr-2">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="w-6 text-gray-400 hover:text-gray-500"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M15.707 15.707a1 1 0 01-1.414 0l-5-5a1 1 0 010-1.414l5-5a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 010 1.414zm-6 0a1 1 0 01-1.414 0l-5-5a1 1 0 010-1.414l5-5a1 1 0 011.414 1.414L5.414 10l4.293 4.293a1 1 0 010 1.414z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </div>
                <div class="mr-2">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="w-6 text-gray-400 hover:text-gray-500"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M14.752 11.168l-3.197-2.132A1 1 0 0010 9.87v4.263a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z"
                    />
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                    />
                  </svg>
                </div>
                <div class="mr-4">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="w-6 text-gray-400 hover:text-gray-500"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10.293 15.707a1 1 0 010-1.414L14.586 10l-4.293-4.293a1 1 0 111.414-1.414l5 5a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0z"
                      clip-rule="evenodd"
                    />
                    <path
                      fill-rule="evenodd"
                      d="M4.293 15.707a1 1 0 010-1.414L8.586 10 4.293 5.707a1 1 0 011.414-1.414l5 5a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </div>
                <div
                  class="truncate text-gray-400 select-none"
                  style="max-width: 14rem"
                >
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic
                  error natus sit necessitatibus minus voluptatem ullam! Odit,
                  dolores dignissimos doloremque ullam illo pariatur aut! Quos
                  nisi libero perferendis quo asperiores?
                </div>
              </div>
            </div>
          </div>

          <!-- right side -->
          <div class="relative">
            <div
              class="
                flex
                items-center
                cursor-pointer
                justify-center
                hover:bg-gray-100
                h-12
                px-2
                overflow-hidden
              "
              style="max-width: 12rem"
            >
              <!-- user -->
              <div class="mr-2 font-medium truncate select-none">Александр</div>
              <div class="flex-shrink-0">
                <img
                  src="https://sun2-10.userapi.com/s/v1/ig2/OVbuEzOUyjU-7i4fUPbmNfqHAHb_0TX3rHA5fFAPst1sUfZvfkOdEEuRC9XRuvIx0Q_MRO7O6FMohdY4deEEA9ox.jpg?size=50x0&quality=96&crop=64,227,1337,1337&ava=1"
                  class="rounded-full w-8 mr-2 select-none"
                  alt="Александр"
                />
              </div>
              <div>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="w-4 text-gray-400"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                    clip-rule="evenodd"
                  />
                </svg>
              </div>
            </div>
            <!-- dropdown -->
            <div class="absolute right-0 top-full border">
              <div class="bg-white border-b w-52 py-1">
                <a
                  href="#"
                  class="flex items-center px-4 py-1 hover:bg-gray-100"
                >
                  <div class="flex-shrink-0">
                    <img
                      src="https://sun2-10.userapi.com/s/v1/ig2/OVbuEzOUyjU-7i4fUPbmNfqHAHb_0TX3rHA5fFAPst1sUfZvfkOdEEuRC9XRuvIx0Q_MRO7O6FMohdY4deEEA9ox.jpg?size=50x0&quality=96&crop=64,227,1337,1337&ava=1"
                      class="rounded-full w-8 mr-2 select-none"
                      alt="Александр"
                    />
                  </div>
                  <div>
                    <div
                      class="text-xs truncate flex-shrink-0 text-default-blue"
                    >
                      Александр Грибашов
                    </div>
                    <div class="flex-shrink-0 text-xs text-gray-400">
                      Перейти в VK Connect
                    </div>
                  </div>
                </a>
                <div class="bg-gray-200 h-px mx-4 my-1"></div>
                <a
                  href="#"
                  class="text-xs flex items-center px-4 py-1 hover:bg-gray-100"
                  >Настройки</a
                >
                <a
                  href="#"
                  class="text-xs flex items-center px-4 py-1 hover:bg-gray-100"
                  >Помощь</a
                >
                <div class="bg-gray-200 h-px mx-4 my-1"></div>
                <a
                  href="#"
                  class="text-xs flex items-center px-4 py-1 hover:bg-gray-100"
                  >Выйти</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
  </body>
</template>

<script>
export default {
  name: "App"
};
</script>

<style src="./app.css"></style>
