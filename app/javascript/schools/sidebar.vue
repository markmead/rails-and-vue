<template>
  <div class="hidden md:flex md:flex-shrink-0">
    <div class="flex flex-col w-64 bg-white border-r border-gray-200">
      <div class="flex flex-col flex-1 h-0 px-4 pt-5 pb-4 overflow-y-auto">
        <div class="flex flex-col justify-between flex-1 mt-5">
          <slot />
        </div>
      </div>
    </div>
  </div>
</template>
