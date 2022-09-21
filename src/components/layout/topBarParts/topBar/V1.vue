<script setup>
    import Logo from "@/components/layout/topBarParts/logoSection/V1.vue";
    import topLinks from "@/components/layout/topBarParts/topLinks/V2.vue";
    import SearchBox from "@/components/layout/topBarParts/searchBox/V1.vue";
    import ButtonsRightBar from "@/components/layout/topBarParts/buttonsRightBar/V1.vue";
    import ColoredBar from "@/components/layout/topBarParts/coloredBar/V1.vue";
</script>
<template >
    <header  class=" col-span-12 bg-white flex h-full ">
        <div class="flex-col w-full">
            <topLinks/>
            <div class=" grid grid-cols-12 pb-4 max-w[1200px]" style="margin:0 calc(49vw - 600px);">
                <Logo />
                <SearchBox/>
                <ButtonsRightBar/>
            </div>
            <ColoredBar/>            
        </div>
    </header>
</template>