<!-- <script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script> -->

<template>
  <div class="w-10/12 m-auto">
    <nav class="flex justify-between items-center font-bold m-5 border-b-4 border-gray-500 h-[130px]">
      <div class="logo flex flex-row">
        <img src="@/assets/images/fourdots_logo.svg" alt="4 dots logo" class="w-[40px] h-[90px] p-1">
        <h1 class="after:content-['D'] after:text-orange-600 font-jolly font-black text-7xl">x</h1>
      </div>
      <div class="font-jolly font-black text-5xl">
        <a href="#" class="underline p-4 text-orange-500">HOME</a>
        <a href="#" class="underline p-4">CATEGORY</a>
        <a href="#" class="underline p-4">MEN'S</a>
        <a href="#" class="underline p-4">WOMEN'S</a>
        <a href="#" class="underline p-4">JEWELRY</a>
        <a href="#" class="underline p-4">PERFUM</a>
      </div>
      <div class="cart flex flex-row">
        <img src="@/assets/images/user.png" alt="user logo" class="w-[60px] h-[60px]">
        <img src="@/assets/images/cart.png" alt="cart logo" class="w-[60px] h-[60px]">
        <h2 class="font-jolly font-black text-5xl">Cart(0)</h2>
      </div>
    </nav>

    <section class="flex flex-col">
        <div class="flex justify-between h-[400px]">
          <div class="left_header w-[1000px] ml-28 m-16">
            <h2 class="font-itim text-purple-600 text-7xl font-bold">Trending items</h2><br>
            <h1 class="text-8xl font-itim font-bold leading-relaxed">WOMEN'S LATEST FASTION SALE</h1><br>
            <p class="text-gray-400 text-3xl font-medium w-[400px]">Ready to start your new outfit today</p>
          </div>
        <div class="right_header items-end">        
          <img src="@/assets/images/women-logo.png" alt="women" class="w-[450px] mr-32">
        </div>
      </div>
      <div class="mt-64 m-auto">
        <div class="w-[1400px] h-[60px] border-solid border-black border-2 rounded-full flex items-center justify-between font-itim text-3xl">
          <!-- <input type="text"/> -->
          <div class="flex">
            <img src="@/assets/images/search.png" alt="search icon" class="w-[35px] h-[35px] m-5">
            <p class="text-left text-gray-400 p-4">Search more product</p>
          </div>
          <button class=" bg-orange-600 w-[120px] h-[50px] rounded-full text-white m-2">Search</button>
        </div>
      </div>
    </section>
    <section class="m-16 ml-60">
      <div class="grid grid-cols-5">
        <div class="border-solid border-2 border-gray-500 rounded-lg font-jaldi">
          <h1 class="font-bold ml-7 mt-3 text-3xl">CATEGORY</h1>
          <div class="text-gray-500 flex items-center justify-between m-3 text-2xl">
            <div class="flex text-center items-center">
              <img src="@/assets/images/dressc1.png" alt="dress catogory" class="w-[80px] h-[80px]">
              <p class="p-5">Clothes</p>
            </div>
            <p class="pr-6">+</p>
          </div>
          <div class="text-gray-500 flex items-center justify-between m-3 text-2xl">
            <div class="flex text-center items-center">
              <img src="@/assets/images/footware.png" alt="dress catogory" class="w-[100px] h-[70px]">
              <p class="p-2">Footware</p>
            </div>
            <p class="pr-7">+</p>
          </div>
          <div class="text-gray-500 flex items-center justify-between m-3 text-2xl">
            <div class="flex text-center items-center">
              <img src="@/assets/images/jewelry.png" alt="dress catogory" class="w-[80px] h-[70px]">
              <p class="p-5">Jewelry</p>
            </div>
            <p class="pr-7">+</p>
          </div>
          <div class="flex-grow h-px bg-gray-400 m-5"></div> 
          <div class="flex flex-col mx-7 font-jaldi text-2xl">
            <div class="text-gray-500 flex justify-between">
              <p>Earrings</p>
              <p>23</p>
            </div>
            <div class="text-gray-500 flex justify-between">
              <p>Couple Rings</p>
              <p>76</p>
            </div>
            <div class="text-gray-500 flex justify-between">
              <p>Necklace</p>
              <p>51</p>
            </div>
          </div>
          <div class="text-2xl">
            <div class="text-gray-500 flex items-center justify-between m-3">
              <div class="flex text-center items-center">
                <img src="@/assets/images/perfume.png" alt="dress catogory" class="w-[80px] h-[60px]">
                <p class="p-4">Perfume</p>
              </div>
              <p class="pr-7">+</p>
            </div>
            <div class="text-gray-500 flex items-center justify-between m-3">
              <div class="flex text-center items-center">
                <img src="@/assets/images/beutiful.png" alt="dress catogory" class="w-[90px] h-[60px]">
                <p class="p-2">Cosmetics</p>
              </div>
              <p class="pr-7">+</p>
            </div>
            <div class="text-gray-500 flex items-center justify-between m-3">
              <div class="flex text-center items-center">
                <img src="@/assets/images/glasses.png" alt="dress catogory" class="w-[80px] h-[60px]">
                <p class="p-5">Glasses</p>
              </div>
              <p class="pr-7">+</p>
            </div>
            <div class="text-gray-500 flex items-center justify-between m-3">
              <div class="flex text-center items-center">
                <img src="@/assets/images/bag.png" alt="dress catogory" class="w-[70px] h-[50px]">
                <p class="pl-7">Bags</p>
              </div>
              <p class="pr-7">+</p>
            </div>
          </div>
        </div>
        <div class="col-span-3 ml-12">
          <div class="flex justify-between font-jaldi ml-7">
            <div>
              <h2 class="font-bold text-2xl">New Arrivals</h2>
              <div class="flex-grow h-px bg-gray-400 w-[350px]"></div> 
            </div>
            <div>
              <h2 class="font-bold text-2xl">Trending</h2>
              <div class="flex-grow h-px bg-gray-400 w-[350px]"></div> 
            </div>
            <div>
              <h2 class="font-bold text-2xl">Top Rated</h2>
              <div class="flex-grow h-px bg-gray-400 w-[350px]"></div> 
            </div>
          </div>

          <div class="grid grid-rows-3 overflow-x-scroll mt-14">
            <!--grid row 1-->
            <div class="flex">
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/black-tshirt.png" alt="black t-shirt" class="w-[100px] h-[100px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Black T-Shirt</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$7.99</p>
                    <p class="text-gray-500 text-lg line-through">$12.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/women-dress.png" alt="black t-shirt" class="w-[80px] h-[130px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Women's Dress</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$25.99</p>
                    <p class="text-gray-500 text-lg line-through">$37.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/white-skirt.png" alt="women short skirt" class="w-[90px] h-[100px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">White Short Skirt</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$12.99</p>
                    <p class="text-gray-500 text-lg line-through">$15.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/denim-jackit.png" alt="women short skirt" class="w-[90px] h-[100px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Men's Denim Jean Jacket</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$31.00</p>
                    <p class="text-gray-500 text-lg line-through">$45.00</p>
                  </div>
                </div>
              </div>
            </div>
            <!-- row2 -->
            <div class="flex">
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/men-jean.png" alt="men jeans" class="w-[80px] h-[120px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Men's Jeans</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$27.99</p>
                    <p class="text-gray-500 text-lg line-through">$30.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/men-shirt.png" alt="men shirt" class="w-[80px] h-[100px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Men's Jeans</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$20.</p>
                    <p class="text-gray-500 text-lg line-through">$27.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/men-suit.png" alt="men suit" class="w-[80px] h-[120px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Men's Jeans</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$250.99</p>
                    <p class="text-gray-500 text-lg line-through">$295.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/men-hoodi.png" alt="men suit" class="w-[90px] h-[110px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Men's Jeans</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$250.99</p>
                    <p class="text-gray-500 text-lg line-through">$295.00</p>
                  </div>
                </div>
              </div>
            </div>
            <!-- row3 -->
            <div class="flex">
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/sport-clown.png" alt="men suit" class="w-[110px] h-[90px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Sports Clown</h3>
                  <p class="text-gray-500">Sport</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$57.99</p>
                    <p class="text-gray-500 text-lg line-through">$60.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/men-belt.png" alt="men suit" class="w-[120px] h-[80px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Leader Belt, Brown</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$25.99</p>
                    <p class="text-gray-500 text-lg line-through">$37.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/silver.png" alt="men suit" class="w-[110px] h-[90px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Leader Belt, Brown</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$25.99</p>
                    <p class="text-gray-500 text-lg line-through">$37.00</p>
                  </div>
                </div>
              </div>
              <div class="flex w-[400px] h-[165px] border-solid border-2 rounded-lg items-center m-5">
                <div class="m-5">
                  <img src="@/assets/images/women-boots.png" alt="men suit" class="w-[110px] h-[90px]">
                </div>
                <div class="m-5">
                  <h3 class="font-bold">Women's Boots</h3>
                  <p class="text-gray-500">Clothes</p>
                  <div class="flex justify-between">
                    <p class="text-green-700 text-lg font-bold">$25.99</p>
                    <p class="text-gray-500 text-lg line-through">$30.00</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <footer class="flex justify-between items-center h-[150px] border-t-4 border-orange-500 font-itim text-2xl font-semibold">
      <div class="flex m-5">
        <img src="@/assets/images/facebook-icon.png" alt="facebook icon" class="w-[70px] h-[60px]">
        <img src="@/assets/images/instagram-icon.png" alt="instagram icon" class="w-[70px] h-[65px]">
        <img src="@/assets/images/line-icon.png" alt="line icon" class="w-[70px] h-[65px]">
      </div>
      <div class="text-purple-600">
        <a href="#" class="underline p-5">About us</a>
        <a href="#" class="underline p-5">Contact us</a>
        <a href="#" class="underline p-5">Sign in</a>
      </div>
      <div class="flex m-5">
        <img src="@/assets/images/visa.png" alt="facebook icon" class="w-[70px] h-[60px]">
        <img src="@/assets/images/mastercard.png" alt="instagram icon" class="w-[70px] h-[60px]">
        <img src="@/assets/images/americanexpress.png" alt="line icon" class="w-[70px] h-[60px]">
      </div>
    </footer>
</div> 
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Nunito:400,700&display=swap');

  .font-jolly{
    font-family: 'Jolly Lodger', cursive;
  }
  .font-itim{ 
    font-family: 'Itim', cursive;
  }
  .font-jaldi{
    font-family: 'Jaldi', sans-serif;
  }

</style>

