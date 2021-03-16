<template>
  <div class="w-56 mr-4 flex-shrink-0">
    <div class="bg-white rounded border p-3 mb-4">
      <div>
        <img class="rounded-sm" src="../img/avatar2.jpg" alt="Айбол Бисенкул" />
      </div>

      <div class="pt-3">
        <button
          type="button"
          class="bg-gray-200 rounded w-full px-3 py-2 text-xs text-gray-500 hover:text-opacity-75"
        >
          Редактировать
        </button>
      </div>

      <ul class="pt-3 -mx-3">
        <li>
          <a href="#" class="flex items-center px-3 py-1 text-gray-500 hover:bg-gray-100 group">
            <div class="mr-2">
              <svg
                class="w-3 text-gray-400 group-hover:text-gray-500"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"
                />
              </svg>
            </div>
            Статистика страницы
          </a>
        </li>
      </ul>
    </div>

    <div class="bg-white rounded border p-4 mb-4">Center</div>
  </div>
</template>

<style>
.text-xs {
  font-size: 0.8rem;
}
</style>