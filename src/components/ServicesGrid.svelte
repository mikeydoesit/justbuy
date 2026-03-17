<style lang="postcss">
    @reference "../styles/global.css";

    .services {
        @apply bg-services_bg h-auto w-full flex flex-col px-8 py-20;
    }
    .services .heading {
        @apply text-5xl leading-14 text-heading_secondary mb-10 text-center max-w-[500px] mx-auto tracking-wider;
    }
    .services .services_grid {
        @apply grid grid-cols-4 gap-6 w-full px-16;
    }
    .services .services_grid .item {
        @apply bg-white rounded-lg p-6 shadow-md hover:shadow-lg transition ease-in-out;
    }
    .services .services_grid .item .icon {
        @apply w-10 h-10 mb-4;
    }
    .services .services_grid .item .title {
        @apply font-semibold text-lg text-heading_secondary mb-2;
    }
    .services .services_grid .item .text {
        @apply text-heading_secondary text-sm;
    }


/* // X-Small devices (portrait phones, less than 576px) */
    @media (max-width: 575.98px) { 
        .services {
            @apply bg-services_bg h-auto w-full flex flex-col px-4 py-12;
        }
        .services .heading {
            @apply text-3xl leading-10 text-heading_secondary mb-8 text-center max-w-[500px] mx-auto tracking-wide;
        }
        .services .services_grid {
            @apply grid grid-cols-2 gap-6 w-full px-0;
        }
        .services .services_grid .item {
            @apply bg-white rounded-lg p-4 shadow-md hover:shadow-lg transition ease-in-out;
        }
        .services .services_grid .item .icon {
            @apply w-8 h-8 mb-4;
        }
        .services .services_grid .item .title {
            @apply font-semibold text-base text-heading_secondary mb-2;
        }
        .services .services_grid .item .text {
            @apply text-heading_secondary text-xs;
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

<section class="services">
    <h2 class="heading poppins-bold">
      What You Can Do With Just Buy
    </h2>
    <div class="services_grid">
        <div class="item">
            <img src="/images/invoice_1.png" alt="Pay Bills" class="icon"/>
            <h3 class="title">Pay Bills</h3>
            <p class="text">ECG, Ghana Water, and more in seconds</p>
        </div>
        <div class="item">
            <img src="/images/phone-call_1.png" alt="Buy Airtime" class="icon"/>
            <h3 class="title">Buy Airtime</h3>
            <p class="text">Top up your phone instantly</p>
        </div>
        <div class="item">
            <img src="/images/mobile-data_1.png" alt="Purchase Data" class="icon"/>
            <h3 class="title">Purchase Data</h3>
            <p class="text">Data bundles for all networks</p>
        </div>
        <div class="item">
            <img src="/images/cedi_1.png" alt="Manage Money" class="icon"/>
            <h3 class="title">Manage Money</h3>
            <p class="text">Track expenses, savings, and payments</p>
        </div>
    </div>

</section>