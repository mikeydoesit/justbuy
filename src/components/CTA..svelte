<style lang="postcss">
    @reference "../styles/global.css";

    .cta {
        @apply bg-[url(/images/CTA_bg.png)] bg-cover bg-no-repeat bg-center h-auto w-full flex flex-col px-24 py-20 justify-center items-center;
    }
    .cta .heading {
        @apply text-5xl leading-14 text-heading_secondary mb-6 text-center max-w-[600px] mx-auto tracking-wide;
    }
    .cta p {
        @apply text-base text-prime_grey pt-4 pb-10 max-w-[400px] text-center;
    }
    .cta .download_btn {
        @apply bg-[url(/images/btn_bg.png)] bg-cover bg-no-repeat bg-left w-fit flex flex-row justify-center items-center px-8 py-3 text-white text-base tracking-wider rounded-md cursor-pointer;
    }

    /* // X-Small devices (portrait phones, less than 576px) */
    @media (max-width: 575.98px) { 
        .cta {
            @apply bg-[url(/images/CTA_bg.png)] bg-cover bg-no-repeat bg-center h-auto w-full flex flex-col px-4 py-12 justify-center items-center;
        }
        .cta .heading {
            @apply text-3xl leading-10 text-heading_secondary mb-6 text-center max-w-[600px] mx-auto tracking-wide;
        }
        .cta p {
            @apply text-base text-prime_grey pt-0 pb-8 max-w-[400px] text-center;
        }
        .cta .download_btn {
            @apply bg-[url(/images/btn_bg.png)] bg-cover bg-no-repeat bg-left w-fit flex flex-row justify-center items-center px-8 py-3 text-white text-base tracking-wider rounded-md cursor-pointer;
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

<section class="cta">
    <h2 class="heading poppins-bold">Take Control of Your Digital Payments</h2>
    <p class="poppins-medium">Download the Just Buy app, fund your wallet and start paying for airtime, data and bills the smarter way.</p>
    <a href="https://tinyurl.com/Datankoaa" target="_blank" class="download_btn poppins-regular">
        <span>Download app</span>
    </a>
</section>