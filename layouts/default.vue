<template>
    <div id="MainLayout" class="w-full">
        <div id="TopMenu" class="w-full fixed z-50">
            <div class="navbar bg-base-100">
                <div class="navbar-start">
                    <div class="dropdown">
                    <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
                    </div>
                    <ul tabindex="0" class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52">
                        <li><NuxtLink to="/">HOME</NuxtLink></li>
                        <li><NuxtLink to="/profilo">PROFILO</NuxtLink></li>
                        <li><NuxtLink to="/trova-centro">TROVA CENTRO</NuxtLink></li>
                        <li>
                        <a>SERVIZI</a>
                        <ul class="p-2">
                            <li><a>ASSISTENZA ALLA PERSONA</a></li>
                            <li><a>BADANTI E ASSISTENTI FAMILIARI</a></li>
                            <li><a>BTELEMEDICINA E APP ANYCARE</a></li>
                            <li><a>PRATICHE AMMINISTRATIVE</a></li>
                            <li><a>ALTRI SERVIZI</a></li>
                        </ul>
                        </li>
                        <li><a>NEWS</a></li>
                        <li><a>CONTATTI</a></li>
                        <li><a>FRANCHISING</a></li>
                    </ul>
                    </div>
                    <a class="btn btn-ghost text-xl">Logo</a>
                </div>
                <div class="navbar-center hidden lg:flex">
                    <ul class="menu menu-horizontal px-1">
                    <li><NuxtLink to="/">HOME</NuxtLink></li>
                    <li><NuxtLink to="/profilo">PROFILO</NuxtLink></li>
                    <li><NuxtLink to="/trova-centro">TROVA CENTRO</NuxtLink></li>
                    <li class="relative group">
                        <div class="dropdown dropdown-bottom dropdown-hover">
                            <NuxtLink to="/servizi" tabindex="0">SERVIZI</NuxtLink>
                            <ul tabindex="0" class="dropdown-content z-[1] menu p-2 shadow bg-base-100 rounded-box w-52">
                                <li><NuxtLink>ASSISTENZA ALLA PERSONA</NuxtLink></li>
                                <li><NuxtLink>BADANTI E ASSISTENTI FAMILIARI</NuxtLink></li>
                                <li><NuxtLink>BTELEMEDICINA E APP ANYCARE</NuxtLink></li>
                                <li><NuxtLink>PRATICHE AMMINISTRATIVE</NuxtLink></li>
                                <li><NuxtLink>ALTRI SERVIZI</NuxtLink></li>
                            </ul>
                        </div>
                    </li>
                    <li><a>NEWS</a></li>
                    <li><a>CONTATTI</a></li>
                    <li><a>FRANCHISING</a></li>
                    </ul>
                </div>
                <div class="navbar-end">
                <a class="btn">Button</a>
            </div>
        </div>
        </div>
        <div id="BodyPage">
            <slot />

            <GeneralFooter/>
        </div>
    </div>
</template>

<script setup>
</script>
