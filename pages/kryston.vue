<template>
  <div>
    <header class="mt-6 px-6">
      <nav class="flex justify-between">
        <a href="#" class="py-4">
          <svg
            class="text-primary"
            width="38"
            height="24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M16.235 23.591L10.466 12.96l5.36-5.976H9.803l-4.729 5.662h-.189V0H0v23.591h4.886v-4.435l2.207-2.453 3.657 6.888h5.485zM23.526 24c4.728 0 7.313-2.328 7.313-5.536 0-7.36-9.71-4.12-9.71-6.826 0-.88.947-1.478 2.428-1.478 1.608 0 2.46.692 2.617 1.698h4.224c-.22-3.46-2.995-5.284-6.84-5.284-4.446 0-6.842 2.454-6.842 5.284 0 7.14 9.395 3.87 9.395 6.858 0 .943-.915 1.54-2.554 1.54-1.607 0-2.585-.597-2.71-1.76H16.4C16.496 21.86 18.734 24 23.526 24zM34.777 24c1.608 0 2.68-1.07 2.68-2.61 0-1.48-1.072-2.611-2.68-2.611-1.482 0-2.68 1.132-2.68 2.61 0 1.541 1.198 2.611 2.68 2.611z"
              fill="currentcolor"
            />
          </svg>
        </a>
        <ul class="my-auto">
          <li>
            <svg
              class="h-6 w-6 text-primary"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M21 18H3v-2h18v2zm0-5H3v-2h18v2zm0-5H3V6h18v2z"
                fill="currentColor"
              />
            </svg>
          </li>
        </ul>
      </nav>
    </header>

    <main class="px-6">
      <section class="mt-10">
        <div class="w-[25rem] h-[30rem] shadow-xl">
          <img
            src="~/assets/kryston/images/profil.webp"
            alt="Profil Image"
            class="w-full h-full object-cover rounded-lg"
          />
        </div>
      </section>
    </main>

    <footer class=""></footer>
  </div>
</template>

<script>
export default {
  layout: "kryston",
  head: {
    title: "Kryston Schwarze",
    meta: [{ hid: "description", name: "description", content: "konten" }],
    link: [{ rel: "icon", type: "image/x-icon", href: "/favicon.ico" }]
  }
};
</script>
