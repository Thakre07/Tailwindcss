# Tailwindcss<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    
    <title>Document</title>
</head>
<body class="text-gray-600 font-body">
    
    <div class="grid md:grid-cols-3">
        <div class="md:col-span-1 md:flex md:justify-end"> 
          <nav class="text-right">
            <div class="flex justify-between items-center">
              <h1 class="font-bold uppercase p-4 border-b border-gray-100">
                <a href="/" class="text-green-500 sm:text-red-500 ">Food Ninja</a>
              </h1>
              <div class="px-4 cursor-pointer md:hidden " id="burger">
                <svg class="w-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M0 96C0 78.3 14.3 64 32 64H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z"/></svg>

              </div>
            </div>
            <ul class="text-sm mt-6 hidden md:block" id="menu">
              <li class="text-gray-700 font-bold py-1">
                <a href="#" class="px-4 flex justify-end ml-4 border-r-4 border-red-400">
                  <span >Home</span>
                  <svg class="w-4 ml-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512"><path d="M575.8 255.5c0 18-15 32.1-32 32.1h-32l.7 160.2c0 2.7-.2 5.4-.5 8.1V472c0 22.1-17.9 40-40 40H456c-1.1 0-2.2 0-3.3-.1c-1.4 .1-2.8 .1-4.2 .1H416 392c-22.1 0-40-17.9-40-40V448 384c0-17.7-14.3-32-32-32H256c-17.7 0-32 14.3-32 32v64 24c0 22.1-17.9 40-40 40H160 128.1c-1.5 0-3-.1-4.5-.2c-1.2 .1-2.4 .2-3.6 .2H104c-22.1 0-40-17.9-40-40V360c0-.9 0-1.9 .1-2.8V287.6H32c-18 0-32-14-32-32.1c0-9 3-17 10-24L266.4 8c7-7 15-8 22-8s15 2 21 7L564.8 231.5c8 7 12 15 11 24z"/></svg>
                </a>
              </li>
              <li class="text-grey-700 font-bold py-1">
                <a href="# "class="px-4 flex justify-end ml-4 border-r-4">
                  <span>About</span>
                  <svg class="w-3 ml-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M80 160c0-35.3 28.7-64 64-64h32c35.3 0 64 28.7 64 64v3.6c0 21.8-11.1 42.1-29.4 53.8l-42.2 27.1c-25.2 16.2-40.4 44.1-40.4 74V320c0 17.7 14.3 32 32 32s32-14.3 32-32v-1.4c0-8.2 4.2-15.8 11-20.2l42.2-27.1c36.6-23.6 58.8-64.1 58.8-107.7V160c0-70.7-57.3-128-128-128H144C73.3 32 16 89.3 16 160c0 17.7 14.3 32 32 32s32-14.3 32-32zm80 320a40 40 0 1 0 0-80 40 40 0 1 0 0 80z"/></svg>
                </a>
              </li>
              <li class="text-grey-700 font-bold py-1">
                <a href="#" class="px-4 flex justify-end ml-4 border-r-4">
                  <span >Contact</span>
                  <svg class="w-3 ml-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M164.9 24.6c-7.7-18.6-28-28.5-47.4-23.2l-88 24C12.1 30.2 0 46 0 64C0 311.4 200.6 512 448 512c18 0 33.8-12.1 38.6-29.5l24-88c5.3-19.4-4.6-39.7-23.2-47.4l-96-40c-16.3-6.8-35.2-2.1-46.3 11.6L304.7 368C234.3 334.7 177.3 277.7 144 207.3L193.3 167c13.7-11.2 18.4-30 11.6-46.3l-40-96z"/></svg>
                </a>
              </li>
            </ul>
          </nav>
        </div>
      
        <main class="px-16 py-6 bg-gray-100 md:col-span-2">
          <div class="flex justify-center md:justify-end">
            <a href="#" class="text-red-400 rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider border-red-400 md:border-2 hover:bg-red-400 hover:text-white transition ease-out duration-500">LogIn</a>   
            <a href="#" class="text-red-400 ml-2 rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider border-red-400 md:border-2 hover:bg-red-400 hover:text-white transition ease-out duration-500">Signup</a>
          </div>
    
          <header>
            <h2 class="text-gray-700 text-6xl font-semibold">Recipes</h2>
            <h3 class="text-2xl font-semibold">For Ninjas</h3>
          </header>
    
          <div>
            <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">Latest Recipes</h4>
      
            <div class="mt-8 grid lg:grid-cols-3 gap-10">
              <!-- cards go here -->
              <div class="bg-white rounded overflow-hidden shadow-md relative hover:shadow-2xl"> 
                <img src="stew.jpg" alt="stew" class="w-full h-32 sm:h-48 object-corner ">
                <div class="m-4">
                  <span class="font-bold">5 Bean Chili Stew</span>
                  <span class="block text-gray-500 text-sm">Recipe by Mario</span>
                </div>
                <div class="bg-pink-200 text-black-100 text-xs uppercase font-bold rounded-full p-2 absolute top-0 ml-0 mt-1">
                  <span >10 mins</span>
                </div>
              </div>
              <div class="bg-white rounded overflow-hidden shadow-md relative hover:shadow-2xl"> 
                <img src="noodles.jpg" alt="Veg Noodles" class="w-full h-32 sm:h-48 object-corner ">
                <div class="m-4">
                  <span class="font-bold">Veg Noodles</span>
                  <span class="block text-gray-500 text-sm">Recipe by Mario</span>
                </div>
                <div class="bg-pink-200 text-black-100 text-xs uppercase font-bold rounded-full p-2 absolute top-0 ml-0 mt-1">
                  <span >15 mins</span>

                </div>
                </div>
                <div class="bg-white rounded overflow-hidden shadow-md relative hover:shadow-2xl"> 
                  <img src="curry (1).jpg" alt=" Tofu curry" class="w-full h-32 sm:h-48 object-corner ">
                  <div class="m-4">
                    <span class="font-bold">Tofu curry</span>
                    <span class="block text-gray-500 text-sm">Recipe by Mario</span>
                  </div>
                  <div class="bg-pink-200 text-black-100 text-xs uppercase font-bold rounded-full p-2 absolute top-0 ml-0 mt-1">
                    <span >25 mins</span>

                    </div>
                    </div>
            </div>
    
            <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">Most Popular</h4>
    
            <div class="mt-8">
              <!-- cards go here -->
            </div>
          </div>
    
          <div class="flex justify-center">
            <div class="bg-pink-100 text-black-200 rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider hover:shadow-inner transform hover:scale-125 hover:bg-opacity-50 transition ease-out duration-150">Load more</div>
          </div>    
        </main>
      </div>
    
    <script src="index.js"></script>
</body>
</html>
