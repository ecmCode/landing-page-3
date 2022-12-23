<template>
  <div :class=$style.body>
    <div :class=$style.head>
      Hello World
    </div>
    <div :class=$style.text>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore animi atque recusandae excepturi iste possimus placeat autem et, maiores nobis ea ipsa veniam, explicabo repellendus fugiat nisi aliquam, praesentium repudiandae.
      <hr/>
    </div>
    <div :class=$style.enter>
      <input />
      <button>Submit</button>
    </div>
    
  </div>
</template>


<style module>
.body{
  @apply flex flex-col justify-center items-center w-full h-screen bg-gradient-to-br from-zinc-900 via-zinc-800 to-lime-800
}
.head{
  @apply text-7xl text-lime-500 font-bold tracking-wider
}
.text{
  @apply text-left text-lime-50 w-1/2 py-10
}
.enter{
  @apply flex gap-4
}
.enter button{
  @apply px-10
}
</style>