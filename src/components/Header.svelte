<style lang="postcss">
    @reference "../styles/global.css";

    .header {
        @apply px-24 pt-6 flex flex-row bg-[transparent] w-full absolute justify-between items-center;
    }
    .header img {
        @apply h-14;
    }
    .header .download_btn {
        @apply bg-[url(/images/btn_bg.png)] bg-cover bg-no-repeat bg-left w-fit flex flex-row justify-center items-center px-8 py-3 text-white text-base tracking-wider rounded-md cursor-pointer;
    }

    /* // X-Small devices (portrait phones, less than 576px) */
    @media (max-width: 575.98px) { 
        .header {
            @apply px-4;
        }
        .header img {
            @apply h-10;
        }
        .header .download_btn {
            @apply bg-[url(/images/btn_bg.png)] bg-cover bg-no-repeat bg-left w-fit flex flex-row justify-center items-center px-6 py-3 text-white text-sm tracking-wider rounded-md cursor-pointer;
        }
     }

    /* // Small devices (landscape phones, less than 768px) */
    /* @media (max-width: 767.98px) { ... } */

    /* // Medium devices (tablets, less than 992px) */
    /* @media (max-width: 991.98px) { ... } */

    /* // Large devices (desktops, less than 1200px) */
    /* @media (max-width: 1199.98px) { ... } */

    /* // X-Large devices (large desktops, less than 1400px) */
    /* @media (max-width: 1399.98px) { ... } */

    /* // XX-Large devices (larger desktops)
    // No media query since the xxl breakpoint has no upper bound on its width */
</style>

<section class="header">
    <img src="/images/jb_logo.png" alt="Just Buy logo" />
    <a href="https://tinyurl.com/Datankoaa" target="_blank" class="download_btn poppins-regular">
        <span>Download app</span>
    </a>
</section>