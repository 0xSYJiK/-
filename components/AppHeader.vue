<template>
  <span>
    <div class="navbar bg-base-200 rounded-lg shadow-lg sticky top-2 transition-all ">
      <div class="flex-1">
        <NuxtLink class="btn btn-ghost text-xl">websitename</NuxtLink>
      </div>
      <div class="flex-none">
        <ul class="menu menu-horizontal px-1">
          <li><NuxtLink>Link</NuxtLink></li>
          <li>
            <details>
              <summary>
                Parent
              </summary>
              <ul class="p-2 bg-base-100 rounded-t-none">
                <li><NuxtLink>Link 1</NuxtLink></li>
                <li><NuxtLink>Link 2</NuxtLink></li>
              </ul>
            </details>
          </li>
        </ul>
      </div>
    </div>
    <slot />
  </span>
</template>