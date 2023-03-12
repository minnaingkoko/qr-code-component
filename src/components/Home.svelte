<main class="home">
    <div class="container">
        <img class="qr" src="/images/image-qr-code.png" alt="qr_image">
        <h1 class="heading">Improve your front-end skills by building projects</h1>
        <div class="text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next levels</div>
    </div>
</main>

<style>

.home {
    @apply w-screen h-screen flex justify-center items-center bg-[#d6e2f0];
}
.container {
    @apply flex flex-col h-[500px] bg-[#ffffff] items-center pl-[16px] pr-[16px] pt-[16px] rounded-[15px];
}
.qr {
    @apply rounded-[15px];
}
.heading {
    @apply text-[#1f3251] text-[20px] font-bold mt-[16px] text-center;
}
.text {
    @apply text-[15px] text-[#7b879d] mt-[20px] mb-[16px] text-center;
}

@media only screen and (min-width: 376px) {
    .container {
        width: 324px;
    }
    .qr {
        width: 294px;
        height: 294px;
    }
}

@media only screen and (max-width: 375px) {
    .container {
        width: 250px;
    }
    .qr {
        width: 218px;
        height: 218px;
    }
}

</style>