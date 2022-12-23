<template>
    <header :class=$style.header>
        <div :class=$style.logo>
            Logo
        </div>
        <ul :class=$style.navbar>
            <li>Home</li>
            <li>About</li>
            <li>Photos</li>
            <li>Contact</li>
        </ul>
    </header>
</template>


<style module>
.header{
    @apply bg-lime-400 flex justify-around items-center p-2 absolute w-full bg-opacity-50 text-2xl text-lime-50 backdrop-blur-2xl select-none drop-shadow-xl 
}
.logo{
    @apply text-4xl font-light uppercase tracking-widest;
    text-shadow: 2px 2px rgb(163 230 53), 4px 4px rgb(24 24 27);
}
.navbar{
    @apply flex list-none gap-10
}
.navbar li{
    @apply drop-shadow-sm p-2 hover:bg-zinc-900 hover:text-lime-500 cursor-pointer
}

</style>