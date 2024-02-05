<template>
  <main class="flex-1">
    <section class="w-full py-12 bg-gray-100 dark:bg-gray-800" id="about" >
      <div class="container px-4 md:px-6 flex flex-col md:flex-row gap-6 mx-auto">
        <div>
          <h5 class="text-slate-50 font-bold sm:text-2xl">About Us</h5>
          <h2 class="text-3xl font-bold tracking-tighter text-white sm:text-5xl">Solutions for your investment</h2>
          <p class="max-w-[900px] md:text-xl/relaxed lg:text-base/relaxed xl:text-xl/relaxed dark:text-gray-200">
            We are a company dedicated to providing innovative solutions for your investment.
          </p>
          <button class="mt-4 bg-blue-500 text-white py-2 px-4 rounded">For More</button>
        </div>
        <img
          class="w-full md:w-1/2 h-64 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70"
          height="300"
          src="../assets/Screen2.jpg"
          style="aspect-ratio: 300 / 300; object-fit: cover;"
          width="300"
        />
      </div>
    </section>
    <section class="w-full py-12" id="services">
      <div class="container px-4 md:px-6 grid grid-cols-1 md:grid-cols-3 gap-6 mx-auto">
        <h5 class="text-slate-600 font-bold sm:text-2xl">Services</h5>
        <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl col-span-full">We offer the best of the best</h2>
        <div class="border rounded-lg p-4">
          <img
            class="w-24 h-24 object-cover rounded-full mx-auto transition duration-300 ease-in-out hover:opacity-70"
            height="100"
            src="../assets/Screen3.jpg"
            style="aspect-ratio: 100 / 100; object-fit: cover;"
            width="100"
          />
          <h3 class="text-xl font-bold mt-4">Security measures</h3>
          <p class="text-gray-500">We offer state-of-the-art security measures, with a facial retina authentication system, from your eye to your cell phone</p>
        </div>
        <div class="border rounded-lg p-4">
          <img
            class="w-24 h-24 object-cover rounded-full mx-auto transition duration-300 ease-in-out hover:opacity-70"
            height="100"
            src="../assets/Screen4.jpg"
            style="aspect-ratio: 100 / 100; object-fit: cover;"
            width="100"
          />
          <h3 class="text-xl font-bold mt-4">Quick Purchase</h3>
          <p class="text-gray-500">Anything you want to pay for is done in an instant, if you've made a purchase, it doesn't take long - our system differs from traditional banks</p>
        </div>
        <div class="border rounded-lg p-4">
          <img
            class="w-24 h-24 object-cover rounded-full mx-auto transition duration-300 ease-in-out hover:opacity-70"
            height="100"
            src="../assets/Screen5.jpg"
            style="aspect-ratio: 100 / 100; object-fit: cover;"
            width="100"
          />
          <h3 class="text-xl font-bold mt-4">Smart Stock Exchange</h3>
          <p class="text-gray-500">
We operate with several stock exchanges on the market, your money is quickly saved in the investment you want</p>
        </div>
      </div>
    </section>
    
    <section class="w-full py-12 bg-gray-100 dark:bg-gray-800" id="portfolio">
      <div class="container px-4 md:px-6 mx-auto">
        <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl text-white">Portfolio</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 mt-6">
          <div>
            <img
              class="w-full h-48 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70"
              height="200"
              src="../assets/Screen6.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <h3 class="text-xl font-bold mt-4 text-white">High loans, low interest rates</h3>
            <p class="dark:text-gray-200">We offer an interest arrears plan, you can't pay in the next few months, we'll help you without paying more interest</p>
          </div>
          <div>
            <img
              class="w-full h-48 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70"
              height="200"
              src="../assets/Screen7.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <h3 class="text-xl font-bold mt-4 text-white">Coverage services</h3>
            <p class="dark:text-gray-200">We have partnerships with several websites that will give you discounts and coupons if you buy from us</p>
          </div>
          <div>
            <img
              class="w-full h-48 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70"
              height="200"
              src="../assets/Screen8.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <h3 class="text-xl font-bold mt-4 text-white">Active technical support</h3>
            <p class="dark:text-gray-200">
                Our support is always available 24 hours a day, so you can complain as much as you like</p>
          </div>
        </div>
      </div>
    </section>
    <section class="w-full py-12" id="blog">
      <div class="container px-4 md:px-6 mx-auto">
        <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl">Blog</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-6">
          <div class="border rounded-lg p-4 mt-6 flex flex-col md:flex-row gap-6">
            <img
              class="w-full md:w-1/2 h-48 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70"
              height="200"
              src="../assets/Screen9.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <div>
              <h3 class="text-xl font-bold">How to save and invest your money</h3>
              <p class="text-gray-500">We teach you how to invest healthily and secure that money</p>
            </div>
          </div>
          <div class="border rounded-lg p-4 mt-6 flex flex-col md:flex-row gap-6">
            <img
              class="w-full md:w-1/2 h-48 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70"
              height="200"
              src="../assets/Screen10.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <div>
              <h3 class="text-xl font-bold">Beware of fraud</h3>
              <p class="text-gray-500">How to avoid fraud and being scammed</p>
            </div>
          </div>
          <div class="border rounded-lg p-4 mt-6 flex flex-col md:flex-row gap-6">
            <img
              class="w-full md:w-1/2 h-48 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70"
              height="200"
              src="../assets/Screen11.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <div>
              <h3 class="text-xl font-bold">How to keep an eye on your bills?</h3>
              <p class="text-gray-500">You need help with your accounts, you're getting lost, we'll help you with this blog</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="w-full py-12 bg-gray-100 dark:bg-gray-800" id="team">
      <div class="container px-4 md:px-6 mx-auto">
        <h2 class="text-3xl font-bold tracking-tighter sm:text-5xl text-white">Team</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 mt-6">
          <div>
            <img
              class="w-full h-100 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70 hover:scale-105"
              height="200"
              src="../assets/Persona1.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <h3 class="text-xl font-bold mt-4 text-white">Daniel Marks</h3>
            <p class="dark:text-gray-200">IT Manager</p>
          </div>
          <div>
            <img
              class="w-full h-100 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70 hover:scale-105"
              height="200"
              src="../assets/Persona2.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <h3 class="text-xl font-bold mt-4 text-white">James Brow</h3>
            <p class="dark:text-gray-200">Financial Manager</p>
          </div>
          <div>
            <img
              class="w-full h-100 object-cover rounded-lg transition duration-300 ease-in-out hover:opacity-70 hover:scale-105"
              height="200"
              src="../assets/Persona3.jpg"
              style="aspect-ratio: 300 / 200; object-fit: cover;"
              width="300"
            />
            <h3 class="text-xl font-bold mt-4 text-white">Sarah Mcdonald</h3>
            <p class="dark:text-gray-200">Vice President</p>
          </div>
        </div>
      </div>
    </section>
  </main>
  <!-- eslint-disable-next-line vue/max-attributes-per-line -->
</template>