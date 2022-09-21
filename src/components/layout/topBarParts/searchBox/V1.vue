<script setup>
    import SearchIcon from "@/components/icons/search.vue";
</script>
<template>
    <div class="col-start-3 col-span-5 flex justify-center items-center pt-4">
        <div class=" w-10/12 h-[48px] border-solid border-2 border-[#919191] rounded-md flex justify-center items-center">
            <div class=" px-4">
                <SearchIcon/>
            </div>
            <input type="text" class=" w-10/12 h-full focus:outline-none" placeholder="Ürün, kategori veya marka ara">
            <div class="bg-[#919191] w-2/12 h-[48px] rounded-md translate-x-1 flex justify-center items-center text-white font-bold">ARA</div>
        </div>
    </div>
</template>