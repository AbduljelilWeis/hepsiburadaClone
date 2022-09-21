<script setup>
    import LocationIcon from "@/components/icons/location.vue";
    import chevronIcon from "@/components/icons/chevron.vue";
    import UserIcon from "@/components/icons/user.vue";
    import CartIcon from "@/components/icons/cart.vue";
</script>
<template>
    <div class="col-start-8 col-span-5 flex justify-center items-center pt-4">
        <div class="w-4/12 px-4 py-1 flex items-center">
            <LocationIcon/>
            <div class="flex-col w-full">
                <div class=" text-sm font-bold">Konum</div>
                <div class="flex justify-between items-center w-full">
                    <div class=" text-xs text-[#FF6000] font-semibold">Konum Sec</div>
                    <chevronIcon class=" fill-[#FF6000] w-2"/>
                </div>
            </div>
        </div>
        <div class="w-8/12 h-full flex gap-3 ml-3">
            <div class=" w-1/2 h-full border-solid border-2 border-[#919191] rounded-md flex items-center justify-evenly">
                <UserIcon/>
                <div class="flex-col justify-center">
                    <div class="text-sm font-bold">Giriş Yap</div>
                    <div class=" text-xs text-[#919191] font-semibold">veya üye ol</div>
                </div>
                <chevronIcon class=" fill-[#919191] w-4"/>
            </div>
            <div class=" w-1/2 h-full border-solid border-2 border-[#919191] rounded-md bg-[#919191] flex items-center justify-evenly">
                <div class=" flex">
                    <CartIcon/>
                    <div class=" bg-white rounded-lg text-xs w-4 h-4 flex items-center justify-center -translate-x-1 -translate-y-1">0</div>
                </div>
                <div class=" text-white">Sepetim</div>
            </div>
        </div>
    </div>
</template>