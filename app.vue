<template>
  <div>
    <!---NavBar--->
    <header class="
      sticky 
      top-0 
      z-50 
      flex 
      justify-between 
      items-center 
      space-x-1 
      bg-slate-900
      p-4 
      shadow-md
      ">
      <a class="text-3xl font-mono text-slate-400" href=""> degenIO </a>
    </header>
    <!--homeHERO-->
    <div class="
      relative 
      h-screen 
      w-100 
      bg-no-repeat 
      bg-cover 
      bg-bottom 
      bg-[url('/public/img/gondolainspace.png')]
      ">
      <div class="
        z-10
        absolute
        w-full
        h-full
        flex
        justify-center
        items-center
      ">
        <div class="text-center w-1/2 h-4">
          <h1 class="text-8xl font-serif mb-10 text-slate-300 opacity-75">Find your inspiration today</h1>
        </div>
        <div class="w-1/4">
        </div>
      </div>
      <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>
    </div>

  </div>
</template>
<style scoped>
</style>
