<script setup>
    import Logo from "@/components/layout/topBarParts/logoSection/V1.vue";
</script>
<template>
    <header class=" col-start-1 col-span-full bg-[FFFFFF] grid grid-cols-12 h-full">
        <div class="col-start-1 col-span-12 flex-col ">
            <div class="flex gap-4 justify-end text-xs pt-[14px] mx-7">
                <div>Siparişlerim</div>
                <div>Süper Fiyat, Süper Teklif</div>
                <div>Yurt Dışından</div>
                <div>Kampanyalar</div>
                <div>Girişimci Kadınlar</div>
                <div>Çözüm Merkezi</div>
                <div>Hepsiburada Premium</div>
                <div>Hepsiburada'da Satıcı Ol</div>
            </div>
            <div class=" grid grid-cols-12 pb-4 mx-7 h-full">
                <div class="col-start-1 col-span-2 justify-end">
                    <div class="flex flex-col items-center justify-end w-full">
                        <Logo/>
                        <b class="flex items-center justify-end text-sm font-semibold w-9/12">
                            <a href="https://hepsiburada.com/premium?utm_source=web_header" class="px-1 underline-offset-4 font-bold text-[#FF6000] hover:underline">Premium'u </a> keşfet
                        </b>
                    </div>
                </div>
                <div class="col-start-3 col-span-5 flex justify-center items-center pt-4">
                    <div class="w-full h-full border-solid border-2 border-[#919191] flex justify-center items-center">
                        <input type="text" class=" w-10/12 h-full focus:outline-none" placeholder="Ürün, kategori veya marka ara">
                    </div>
                </div>
                <div class="col-start-8 col-span-5 flex justify-center items-center">
                    <div class="">login</div>
                </div>
            </div>
        </div>
    </header>
</template>