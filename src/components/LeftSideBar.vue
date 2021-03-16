<template>
  <div class="w-40 mr-2 flex-shrink-0">
    <ul class="-ml-1">
      <!-- My page -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z"
              />
            </svg>
          </div>
          Моя страница
        </a>
      </li>

      <!-- News -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9a2 2 0 00-2-2h-2m-4-3H9M7 16h6M7 8h6v4H7V8z"
              />
            </svg>
          </div>
          Новости
        </a>
      </li>

      <!-- Messages -->
      <li>
        <a
          href="#"
          class="flex justify-between items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="flex items-center">
            <div class="mr-2">
              <svg
                class="w-5 text-blue-500"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"
                />
              </svg>
            </div>

            <div>Мессенджер</div>
          </div>
          <div>
            <div
              class="bg-gray-400 rounded-full w-5 h-5 flex justify-center items-center text-white text-xs"
            >
              2
            </div>
          </div>
        </a>
      </li>

      <!-- Friends -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z"
              />
            </svg>
          </div>
          Друзья
        </a>
      </li>

      <!-- Community -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"
              />
            </svg>
          </div>
          Сообщества
        </a>
      </li>

      <!-- Music -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
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
          </div>
          Музыка
        </a>
      </li>

      <!-- Video -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
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
          Видео
        </a>
      </li>

      <!-- Clips -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M7 4v16M17 4v16M3 8h4m10 0h4M3 12h18M3 16h4m10 0h4M4 20h16a1 1 0 001-1V5a1 1 0 00-1-1H4a1 1 0 00-1 1v14a1 1 0 001 1z"
              />
            </svg>
          </div>
          Клипы
        </a>
      </li>

      <!-- Games -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M11 4a2 2 0 114 0v1a1 1 0 001 1h3a1 1 0 011 1v3a1 1 0 01-1 1h-1a2 2 0 100 4h1a1 1 0 011 1v3a1 1 0 01-1 1h-3a1 1 0 01-1-1v-1a2 2 0 10-4 0v1a1 1 0 01-1 1H7a1 1 0 01-1-1v-3a1 1 0 00-1-1H4a2 2 0 110-4h1a1 1 0 001-1V7a1 1 0 011-1h3a1 1 0 001-1V4z"
              />
            </svg>
          </div>
          Игры
        </a>
      </li>

      <!-- Line-->
      <div class="bg-gray-200 h-px mx-1 my-2"></div>
      <!-- Line-->

      <!-- Applications -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"
              />
            </svg>
          </div>
          Приложения
        </a>
      </li>

      <!-- Job -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
              />
            </svg>
          </div>
          Работа
        </a>
      </li>

      <!-- Line-->
      <div class="bg-gray-200 h-px mx-1 my-2"></div>
      <!-- Line-->

      <!-- Market -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"
              />
            </svg>
          </div>
          Маркет
        </a>
      </li>

      <!-- Favorites -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z"
              />
            </svg>
          </div>
          Закладки
        </a>
      </li>

      <!-- Files -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z"
              />
            </svg>
          </div>
          Файлы
        </a>
      </li>

      <!-- Advertising -->
      <li>
        <a
          href="#"
          class="flex items-center px-2 py-1.5 rounded hover:bg-gray-200"
        >
          <div class="mr-2">
            <svg
              class="w-5 text-blue-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M11 5.882V19.24a1.76 1.76 0 01-3.417.592l-2.147-6.15M18 13a3 3 0 100-6M5.436 13.683A4.001 4.001 0 017 6h1.832c4.1 0 7.625-1.234 9.168-3v14c-1.543-1.766-5.067-3-9.168-3H7a3.988 3.988 0 01-1.564-.317z"
              />
            </svg>
          </div>
          Реклама
        </a>
      </li>

      <!-- Line-->
      <div class="bg-gray-200 h-px mx-1 my-2"></div>
      <!-- Line-->

      <ul class="flex flex-wrap">
        <li class="mb-1">
          <a href="#" class="text-gray-400 px-2 text-sm hover:underline"
            >Блог</a
          >
        </li>

        <li class="mb-1">
          <a href="#" class="text-gray-400 px-2 text-sm hover:underline"
            >Разработчикам</a
          >
        </li>

        <li>
          <a href="#" class="text-gray-400 px-2 text-sm hover:underline"
            >Реклама</a
          >
        </li>

        <li @mouseover="window = !window" @mouseout="window = !window">
          <div class="relative">
            <a
              href="#"
              class="flex items-center text-gray-400 px-2 text-sm hover:underline group"
              >Еще
              <svg
                class="text-gray-400 w-3 group-hover:text-gray-500 mt-0.5"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>

            <!-- Dropdown -->
            <div class="absolute top-full left-0 mt-1" v-show="window">
              <div
                class="bg-white border border-gray-300 w-52 py-1 rounded shadow-sm whitespace-nowrap"
              >
                <a
                  href="#"
                  class="flex items-center px-4 py-2 text-blue-900 hover:bg-gray-100"
                >
                  О ВКонтакте
                </a>

                <a
                  href="#"
                  class="flex items-center px-4 py-2 text-blue-900 hover:bg-gray-100"
                >
                  Вакансии
                </a>

                <a
                  href="#"
                  class="flex items-center px-4 py-2 text-blue-900 hover:bg-gray-100"
                >
                  Правовая информация
                </a>

                <a
                  href="#"
                  class="flex items-center px-4 py-2 text-blue-900 hover:bg-gray-100"
                >
                  Защита данных
                </a>

                <a
                  href="#"
                  class="flex items-center px-4 py-2 text-blue-900 hover:bg-gray-100"
                >
                  Центр безопасности
                </a>

                <a
                  href="#"
                  class="flex items-center px-4 py-2 text-blue-900 hover:bg-gray-100"
                >
                  Язык: русский
                </a>
              </div>

              <!-- Arrow -->
              <div
                class="absolute left-0 top-0 ml-8 w-4 h-4 -mt-3 overflow-hidden"
              >
                <div
                  class="absolute right-0 left-0 -bottom-2 h-full mb-px bg-white border border-gray-300 transform rotate-45 origin-center"
                ></div>
              </div>
              <!-- Arrow -->
            </div>
            <!-- Dropdown -->
          </div>
        </li>
      </ul>
    </ul>
  </div>
</template>

<script>
export default {
  data(){
    return{
      window: false
    }
  }
}
</script>