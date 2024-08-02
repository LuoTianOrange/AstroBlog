<template>
    <div class="mt-5">
        <a v-for="i in friendslink" :href="i.linkhref" target="_blank"
            class="min-h-[80px] flex items-center mt-3 shadow-md rounded-lg p-3 text-black bg-white hover:bg-gray-300 dark:text-white dark:bg-gray-600 dark:hover:bg-slate-400 transform">
            <div>
                <img :src="i.linklogo" alt="" class="w-12 h-12 rounded-full">
            </div>
            <div class="ml-4">
                {{ i.linkname }}
            </div>
        </a>
    </div>
</template>

<script setup>
import friendslink from "../../../assets/stores/friendslink.js"

</script>