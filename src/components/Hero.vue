<template>
   <section class="relative h-[500px] md:h-[700px]">
    <img
      class="absolute inset-0 object-cover w-full h-full"
      src="../assets/Screen1.png"
      alt="Hero section image"
      width="1000"
      height="700"
      style="aspect-ratio: 1000 / 700; object-fit: cover;"
    />
    <div class="relative h-full bg-black bg-opacity-50 flex items-center justify-start pl-4 md:pl-52 mx-auto">
      <div>
        <h1 class="text-4xl md:text-6xl text-white font-bold">Invest in Your Wallet</h1>
        <div class="max-w-2xl mx-auto text-white py-10">
        <div class="text-center">
            <h3 class="text-3xl mb-3"> Download our safe wallet </h3>
            <p>Be safe and secure with your money </p>
            <div class="flex justify-center my-10">
                <div class="flex items-center border w-auto rounded-lg px-4 py-2 mx-2 transition ease-in-out hover:opacity-70 hover:scale-105 hover:text-black hover:bg-white duration-300 cursor-pointer" onclick="window.location='https://play.google.com  '">
                    <img src="https://cdn-icons-png.flaticon.com/512/888/888857.png" class="w-7 md:w-8">
                    <div class="text-left ml-3">
                        <p class="text-xs md:text-xs">Download on </p>
                        <p class="text-sm md:text-base"> Google Play Store </p>
                    </div>
                </div>
                <div class="flex items-center border w-auto rounded-lg px-4 py-2 mx-2 transition ease-in-out hover:opacity-70 hover:scale-105 hover:text-black hover:bg-white duration-300 cursor-pointer" onclick="window.location='https://www.apple.com/'">
                    <img src="https://cdn-icons-png.flaticon.com/512/888/888841.png" class="w-7 md:w-8">
                    <div class="text-left ml-3">
                        <p class="text-xs md:text-xs">Download on </p>
                        <p class="text-sm md:text-base"> Apple Store </p>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>
</template>
