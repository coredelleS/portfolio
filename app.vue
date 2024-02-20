<template>
    <nav>
        <ul>
            <li>
                <NuxtLink to="/">Main</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/about">About</NuxtLink>
            </li>
        </ul>
    </nav>
    <div>
        <!-- nuxtPage is nuxt's way of showing current page which defaults to (index.vue) page in pages folder -->
        <NuxtPage />
    </div>
</template>