




<template>

<section><div class="flex flex-col items-center justify-center mt-32" x-cloak x-data="appData()" x-init="appInit()">
    <div class="flex flex-col">
        <!-- Page Scroll Progress -->
        <div class="fixed inset-x-0 top-0 z-50 h-0.5 mt-0.5
            bg-blue-500" :style="`width: ${percent}%`"></div>

        <!-- Navbar -->
        <nav class="flex justify-around py-4 bg-white/80
            backdrop-blur-md shadow-md w-full
            fixed top-0 left-0 right-0 z-10">

            <!-- Logo Container -->
            <div class="flex">
                <!-- Logo -->
                <a class="cursor-pointer">
                    <h3 class="text-2xl font-medium text-blue-500">
                        <img class="h-10 object-cover"
                            src="../New folder/Group 3.svg" alt="Store Logo">
                    </h3>
                </a>
            </div>
            <ul class="flex items-center hidden space-x-8 lg:flex">
      <li><a href="/" aria-label="Sign in" title="Sign in" class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400">Sign in</a></li>
      <li>
        <a
          href="/"
          class="inline-flex items-center justify-center h-12 px-6 font-medium tracking-wide  transition duration-200 rounded shadow-md bg-green-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
          aria-label="Sign up"
          title="Sign up"
        >
          Sign up
        </a>
      </li>
    </ul>
</nav>
            
    </div>
    </div>
</section>


<div class="bg-green-400 relative flex flex-col-reverse py-16 lg:py-0 lg:flex-col -my-12">
        <div class="w-full max-w-xl px-4 mx-auto md:px-0 lg:px-8 lg:py-20 lg:max-w-screen-xl">
          <div class="mb-0 lg:max-w-lg lg:pr-8 xl:pr-6">
            <h2 class="mb-5 font-sans text-3xl font-bold tracking-tight text-white sm:text-4xl sm:leading-none md:text-left">
                AnyTime, anywhere <br>
                Learn on your schedule<br> from any device
            </h2>
            <p class="italic mb-5 text-base text-gray-700 md:text-lg md:text-left">
                We Believe everyone has the capcity to be creative Course Pro is a place where people develop their <br> own potential
            </p>
            <div class="mb-10 text-left rounded md:mb-16 lg:mb-20">
              <a
                href="/"
                class="inline-flex items-center justify-left w-full h-12 px-6 font-medium tracking-wide text transition duration-200 rounded shadow-md md:w-auto "
              >
                Learn more
              </a>
            </div>
        
        </div>
        <div class="inset-y-0 top-0 right-0 w-full max-w-xl px-4 mx-auto mb-6 md:px-0 lg:pl-8 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-1/2 lg:max-w-full lg:absolute xl:px-0">
          <img
            class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none md:h-96 lg:h-full"
            src="../New folder/b1.png"
            alt=""
          />
        </div>
      </div>



</div>

<div class="bg-[url('../New folder/Group 3.svg')]">
    <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
        <div class="grid row-gap-8 sm:grid-cols-3">
          <div class="text-center">
            <p class="font-bold text-slate-400 text-3xl  ">Downloads</p>
            <h6 class="text-5xl font-bold text-deep-purple-accent-400 py-5 underline decoration-green-400 ">5140</h6>
            
          </div>
          <div class="text-center">
            <p class="font-bold text-slate-400 text-3xl">Subscribers</p>
            <h6 class="text-5xl font-bold text-deep-purple-accent-400 py-5 underline decoration-green-400 ">4123</h6>
            
          </div>
          <div class="text-center">
            <p class="font-bold text-slate-400 text-3xl ">Users</p>
            <h6 class="text-5xl font-bold text-deep-purple-accent-400 py-5 underline decoration-green-400 ">4.18 Lac</h6>
           
          </div>
        </div>
      </div>
    </div>




<section>
  

  <div class="relative mx-auto max-w-7xl align-centre">
    <div class="container px-5  mx-auto">
    <p class="italic text-green-400 text-xl text-center	 md:text-centre">
      Courses</p>
    <h1 class="text-3xl text-bold font-medium title-font text-gray-900 text-center	">Our most popular courses</h1>
  </div>


    <div class="grid max-w-lg gap-12 mx-auto mt-12 lg:grid-cols-3 lg:max-w-none">
      
      <div class="flex flex-col mb-12 overflow-hidden cursor-pointer">
        <a href="/blog-post">
          <div class="flex-shrink-0">
            <img class="object-cover w-full h-100% rounded-lg" src="../New folder/1.1.png" alt="">
          </div>
        </a>
        <div class="flex flex-col justify-between flex-1">
          <a href="/blog-post"></a>
          <div class="flex-1">
            
            <a href="#" class="block mt-2 space-y-6">
              <h3 class="text-2xl font-semibold leading-none tracking-tighter text-neutral-600">Ultimate Business Intelligence Analyst A to Z Course 2021</h3>
              <p class="text-lg font-normal text-gray-500">46,995 Student</p>
            </a>
          </div>
        </div>
      </div>

      <div class="flex flex-col mb-12 overflow-hidden cursor-pointer">
        <a href="/blog-post">
          <div class="flex-shrink-0">
            <img class="object-cover w-full h-100% rounded-lg" src="../New folder/2.2.png" alt="">
          </div>
        </a>
        <div class="flex flex-col justify-between flex-1">
          <a href="/blog-post"></a>
          <div class="flex-1">
           
            <a href="#" class="block mt-2 space-y-6">
              <h3 class="text-2xl font-semibold leading-none tracking-tighter text-neutral-600">Adobe Photoshop Training: From Beginner to Pro</h3>
              <p class="text-lg font-normal text-gray-500">6,995 Student</p>
            </a>
          </div>
        </div>
      </div>

      <div class="flex flex-col mb-12 overflow-hidden cursor-pointer">
        <a href="/blog-post">
          <div class="flex-shrink-0">
            <img class="object-cover w-full h-100% rounded-lg" src="../New folder/3.3.png" alt="">
          </div>
        </a>
        <div class="flex flex-col justify-between flex-1">
          <a href="/blog-post"></a>
          <div class="flex-1">
           
            <a href="#" class="block mt-2 space-y-6">
              <h3 class="text-2xl font-semibold leading-none tracking-tighter text-neutral-600">Social Media Marketing - A to Z Content Marketing class 2021</h3>
              <p class="text-lg font-normal text-gray-500">46,995 Student</p>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>



<section class="text-gray-600 body-font mb-4 ">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-col text-center w-full mb-20 mx-20 ">
      <p class="italic text-green-400 text-xl  md:text-left">
        Top Earners
            </p>
     <h1 class="text-2xl text-bold font-medium title-font text-gray-900 mb-12 text-left Noto Sans ">Transforming your ideas <br>Into reality</h1>
    </div>
    <div class="flex flex-wrap -m-20 mx-20">
      <div class="p-4 lg:w-1/4 md:w-1/2">
        <div class="h-full flex flex-col items-center text-center">
          <img alt="team" class="flex-shrink-0 rounded-lg w-full h-56 object-cover object-center mb-4" src="../New folder/1.png">
          <div class="w-full">
            <h2 class="title-font font-medium text-lg text-gray-900">Alper Kamu</h2>
            <h3 class="text-gray-500 mb-3">UI Developer</h3>
            
            
          </div>
        </div>
      </div>
      <div class="p-4 lg:w-1/4 md:w-1/2">
        <div class="h-full flex flex-col items-center text-center">
          <img alt="team" class="flex-shrink-0 rounded-lg w-full h-56 object-cover object-center mb-4" src="../New folder/2.png">
          <div class="w-full">
            <h2 class="title-font font-medium text-lg text-gray-900">Holden Caulfield</h2>
            <h3 class="text-gray-500 mb-3">UI Developer</h3>
            
            
          </div>
        </div>
      </div>
      <div class="p-4 lg:w-1/4 md:w-1/2">
        <div class="h-full flex flex-col items-center text-center">
          <img alt="team" class="flex-shrink-0 rounded-lg w-full h-56 object-cover object-center mb-4" src="../New folder/3.png">
          <div class="w-full">
            <h2 class="title-font font-medium text-lg text-gray-900">Atticus Finch</h2>
            <h3 class="text-gray-500 mb-3">UI Developer</h3>
            
          </div>
        </div>
      </div>
      <div class="p-4 lg:w-1/4 md:w-1/2">
        <div class="h-full flex flex-col items-center text-center">
          <img alt="team" class="flex-shrink-0 rounded-lg w-full h-56 object-cover object-center mb-4" src="../New folder/4.png">
          <div class="w-full">
            <h2 class="title-font font-medium text-lg text-gray-900">Henry Letham</h2>
            <h3 class="text-gray-500 mb-3">UI Developer</h3>
            
            
          </div>
        </div>
      </div>
    </div>
  </div>
</section>



<div class="px-20">
        <p class="italic text-green-400 text-xl  md:text-left">
          Refer        </p>
<h1 class="text-2xl text-bold font-medium title-font text-gray-900 mb-12 text-left">How it's Work</h1>
<img class="h-2/3 max-w-full" src="../New folder/img.png" alt="image description">

    </div>






<section class="text-gray-600 body-font px-20">
  
  <div class="container px-5 py-24 mx-auto">
    <p class="italic text-green-400 text-xl  md:text-left">
                Testimonials
            </p>
    <h1 class="text-2xl text-bold font-medium title-font text-gray-900 mb-12 text-left">Check out What Our <br> Students Think About Us</h1>
    <div class="flex flex-wrap -m-4">
      <div class="p-4 md:w-1/2 w-full">
        <div class="h-full bg-gray-100 p-8 rounded">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="block w-5 h-5 text-gray-400 mb-4" viewBox="0 0 975.036 975.036">
            <path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z"></path>
          </svg>
          <p class="leading-relaxed mb-6">It's a comprehensive online learning platform for everyone looking to learn and course pro. provinding this platform which is very beneficial for practicals. Students can revise everything at home like dissection and slides</p>
          <a class="inline-flex items-center">
            <img alt="testimonial" src="https://dummyimage.com/106x106" class="w-12 h-12 rounded-full flex-shrink-0 object-cover object-center">
            <span class="flex-grow flex flex-col pl-4">
              <span class="title-font font-medium text-gray-900">Anshul Jain</span>
              <span class="text-gray-500 text-sm">Yesterday</span>
            </span>
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/2 w-full">
        <div class="h-full bg-gray-100 p-8 rounded">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="block w-5 h-5 text-gray-400 mb-4" viewBox="0 0 975.036 975.036">
            <path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z"></path>
          </svg>
          <p class="leading-relaxed mb-6">It's A Comprehensive Online Learning Platform For Everyone Looking To Learn And Course Pro. Provinding This Platform Which Is Very Beneficial For Practicals. Students Can Revise Everything At Home Like Dissection And Slides</p>
          <a class="inline-flex items-center">
            <img alt="testimonial" src="https://dummyimage.com/107x107" class="w-12 h-12 rounded-full flex-shrink-0 object-cover object-center">
            <span class="flex-grow flex flex-col pl-4">
              <span class="title-font font-medium text-gray-900">Rajkumar Jain</span>
              <span class="text-gray-500 text-sm">Yesterday</span>
            </span>
          </a>
        </div>
      </div>
    </div>
  </div>
</section>


<section class="text-gray-600 body-font relative">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-col text-center w-full mb-12">
      <p class="italic text-green-400 text-xl  md:text-centre">
        Contact Us
            </p>
    <h1 class="text-2xl text-bold font-medium title-font text-gray-900 mb-12 text-centre">Reach Out with any question you have</h1>
    </div>
    <div class="lg:w-1/2 md:w-2/3 mx-auto">
      <div class="flex flex-wrap -m-2">
        <div class="p-2 w-1/2">
          <div class="relative">
            <label for="name" class="leading-7 text-sm text-gray-600">Name</label>
            <input type="text" id="name" name="name" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
          </div>
        </div>
        <div class="p-2 w-1/2">
          <div class="relative">
            <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
            <input type="email" id="email" name="email" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
          </div>
        </div>
        <div class="p-2 w-full">
          <div class="relative">
            <label for="message" class="leading-7 text-sm text-gray-600">Message</label>
            <textarea id="message" name="message" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"></textarea>
          </div>
        </div>
        <div class="p-2 w-full">
          <button class="flex mx-auto text-white bg-green-400 border-0 py-2 px-8 focus:outline-none hover:bg-green-700 rounded text-lg">Button</button>
        </div>
        <div class="p-2 w-full pt-8 mt-8 border-t border-gray-200 text-center">
          <a class="text-indigo-500">example@email.com</a>
          <p class="leading-normal my-5">49 Smith St.
            <br>Saint Cloud, MN 56301
          </p>
          <span class="inline-flex">
            <a class="text-gray-500">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
              </svg>
            </a>
            <a class="ml-4 text-gray-500">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"></path>
              </svg>
            </a>
            <a class="ml-4 text-gray-500">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
              </svg>
            </a>
            <a class="ml-4 text-gray-500">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M21 11.5a8.38 8.38 0 01-.9 3.8 8.5 8.5 0 01-7.6 4.7 8.38 8.38 0 01-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 01-.9-3.8 8.5 8.5 0 014.7-7.6 8.38 8.38 0 013.8-.9h.5a8.48 8.48 0 018 8v.5z"></path>
              </svg>
            </a>
          </span>
        </div>
      </div>
    </div>
  </div>
</section>
 

<footer class="p-4 mx-20 font-bold bg-white rounded-lg shadow md:flex md:items-center md:justify-between md:p-6 dark:bg-gray-800">
    <span class="text-sm text-gray-500 sm:text-center dark:text-gray-400"> <a href="#" class="hover:underline">2021-2022 © Course Pro Private Limited.</a>
    </span>
    <ul class="flex flex-wrap items-center mt-3 text-sm text-gray-500 dark:text-gray-400 sm:mt-0">
        <li>
            <a href="#" class="mr-4 hover:underline md:mr-6 ">Term & Condition</a>
        </li>
        <li>
            <a href="#" class="mr-4 hover:underline md:mr-6">Privacy Policy</a>
        </li>
    </ul>
</footer>




</template>
