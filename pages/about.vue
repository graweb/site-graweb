<template>
  <div
    class="container pt-24 md:pt-48 px-6 mx-auto flex flex-wrap flex-col md:flex-row items-center"
  >
    <!--Left Col-->
    <div
      class="flex flex-col w-full xl:w-5/12 justify-center lg:items-start overflow-y-hidden"
    >
      <h1
        class="my-4 text-2xl md:text-4xl text-blue-800 font-bold leading-tight text-center md:text-left slide-in-bottom-h1"
      >
        About
      </h1>

      <figure class="bg-gray-100 rounded-xl p-8 dark:bg-slate-800">
        <img
          class="w-24 h-24 rounded-full mx-auto"
          src="~/assets/me.jpeg"
          alt=""
          width="384"
          height="512"
        />
        <div class="pt-6 text-center space-y-4">
          <blockquote>
            <p class="text-xs">
              I am a software developer dedicated to creating innovative solutions that make a difference. With a strong foundation in programming and a keen eye for detail, I strive to deliver high-quality applications.
            </p>
          </blockquote>
          <figcaption class="font-medium">
            <div class="text-sky-500 dark:text-sky-400">Gustavo Grativol</div>
            <div class="text-slate-700 dark:text-slate-500">
              Software Developer, Brazil | Rio de Janeiro
            </div>
          </figcaption>
        </div>
      </figure>
    </div>

    <!--Right Col-->
    <div class="w-full xl:w-7/12 py-6 overflow-y-hidden">
      <h1
        class="mx-4 my-4 text-2xl md:text-4xl text-blue-800 font-bold leading-tight text-center md:text-left slide-in-bottom-h1"
      >
        Skills that I worked
      </h1>

      <div class="grid lg:grid-cols-4 gap-4 justify-center">
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>PHP</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-10/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Laravel | CodeIgniter</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-11/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Vue | Nuxt</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-9/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>JavaScript | TypeScript</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-9/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Tailwind CSS</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-9/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Bootstrap | Bootstrap Vue</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-11/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Vuetify</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-10/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>HTML | CSS</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-11/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>MySQL</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-11/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>SQL Server</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-8/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>PostgreSql</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-9/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Firebase | SqLite</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-10/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Git | GitLab</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-9/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Scrum</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-11/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Flutter</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-8/12 h-1.5"></div>
            </div>
          </td>
        </div>
        <div>
          <td class="px-4 py-4 text-sm whitespace-nowrap">
            <label>Kanban</label>
            <div class="w-40 h-1.5 bg-blue-200 overflow-hidden rounded-full">
              <div class="bg-blue-500 w-10/12 h-1.5"></div>
            </div>
          </td>
        </div>
      </div>
    </div>
  </div>
</template>
