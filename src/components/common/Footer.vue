<template>
  <div class="py-10 md:py-20 w-full px-6  lg:w-1/2 lg:max-w-1/2 mx-auto">
    <!-- <CosmosSdk></CosmosSdk> -->
    <div class="block md:flex mx-auto items-center justify-center text-white">
      <div class="flex-1">
        <h3
          class="font-bold bg-gradient-to-r from-gray-200 via-gray-600 to-white bg-clip-text text-transparent w-full text-4xl my-4 pr-10"
        >
          Subscribe To Our NewsLetter
        </h3>
        <p class="text-slate-700 text-sm">
          Unsubscribe at any time.
          <span><a href="#" class="text-slate-300"> Privacy policy↗</a></span>
        </p>
      </div>
      <div class="flex-1">
        <form action="#" class="w-full">
          <input
            type="email"
            class="bg-zinc-900 rounded-lg py-5 px-4 mt-5 w-full placeholder:text-slate-300 placeholder:text-light"
            placeholder="Your email"
          />
        </form>
      </div>
    </div>

    <div class="my-10">
      <div class="border-zinc-900 border-t"></div>
    </div>

    <!-- Footer Links  -->
    <div class="flex items-center">
      <div class="flex-1 hidden md:block">
        <!-- <img src="@/assets/images/amperechain.png" class="p" alt=""> -->
      </div>

      <div class="flex-1">
        <ul>
          <li class="my-3 hover:text-white text-white font-medium text-lg">
            Company
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">Feature</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">Tokenomics</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">Ecosystem</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">Timeline</a>
          </li>
        </ul>
      </div>
      <div class="flex-1">
        <ul>
          <li class="my-3 hover:text-white text-white font-medium text-lg">
            Exchange
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">PanCakeSwap</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">CoinMarketCap</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">CoinGecko</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">Crypto.com</a>
          </li>
        </ul>
      </div>
      <div class="flex-1">
        <ul>
          <li class="my-3 hover:text-white text-white font-medium text-lg">
            Resources
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">KYC</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">Audit</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">SAFU</a>
          </li>
          <li class="my-3 hover:text-white text-slate-300 font-light text-md">
            <a href="#">Tokens Lock</a>
          </li>
        </ul>
      </div>
    </div>

    <!-- Divider -->
    <div class="my-10">
      <div class="border-zinc-900 border-t"></div>
    </div>

    <div class="flex items-center">
      <div class="flex-1 flex items-center justify-left divide-x">
        <div class="pr-6">
        <img src="@/assets/images/amperechain.png" class="w-auto h-8" alt="">
      </div>

      <div class="text-white px-6">
        <a href="#">Privacy</a>
      </div>

      <div class="text-white px-6">
        <a href="#">Trademark</a>
      </div>
    </div>
    <div class="flex-1">


        <UrlLinks></UrlLinks>
    </div>
    </div>
  </div>
</template>

<script>
import UrlLinks from '@/components/common/UrlLinks.vue';

// import CosmosSdk from "@/components/svg/CosmosSdk.vue";
export default {
  name: "FooterUi",
  components: {
    UrlLinks
},
};
</script>
