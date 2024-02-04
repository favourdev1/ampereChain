<template>
  <div class="relative overflow-hidden">
    <!-- Hero section  -->
    <div
      class="flex flex-col items-center justify-center min-h-96 pt-64 bg-red-30 text-white text-lg inset-0"
    >
      <div class="w-full md:w-1/2 mx-auto text-center z-10">
        <h1
          class="text-5xl md:text-8xl animatedText font-black"
          data-aos="zoom-in-up"
        >
          Build on the Interchain.
        </h1>
        <p>
          Build a blockchain using the best-in-class open source libraries and
          services.
        </p>
      </div>

      <div
        class="absolute flex items-center justify-center mt-auto -z-10 w-full h-full"
      >
        <!-- <img src="../assets/images/bg.png"   class=" backdrop- w-full h-full" style=" filter: blur(10px); " alt=""> -->
        <div class="canvas graphics z-0 flex-column">
          <img
            
            src="@/assets/images/blurImg.png"
            class="bg"
          />
          <div class="-translate-y-[30rem]">

          
          <svg
            data-v-4f848afc=""
            width="1136"
            height="1136"
            viewBox="0 0 1136 1136"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="svg"
          >
            <circle
              data-v-4f848afc=""
              cx="568.167"
              cy="568"
              r="567"
              stroke="white"
              stroke-opacity="0.1"
            ></circle>
            <circle
              data-v-4f848afc=""
              cx="568.167"
              cy="568"
              r="374"
              stroke="white"
              stroke-opacity="0.1"
            ></circle>
            <path
              data-v-4f848afc=""
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M528.519 457.248L495.124 476.528V515.089L528.519 534.369L561.913 515.089V476.528L528.519 457.248ZM565.477 474.471L528.519 453.133L491.56 474.471V517.147L528.519 538.485L565.477 517.147V474.471ZM528.769 598.002L495.374 617.282V655.843L528.769 675.123L562.163 655.843V617.282L528.769 598.002ZM565.727 615.225L528.769 593.887L491.81 615.225V657.901L528.769 679.238L565.727 657.901V615.225ZM454.644 546.907L488.038 527.627L521.433 546.907V585.468L488.038 604.748L454.644 585.468V546.907ZM488.038 523.512L524.997 544.85V587.526L488.038 608.863L451.08 587.526V544.85L488.038 523.512ZM569.499 527.627L536.105 546.907V585.468L569.499 604.748L602.894 585.468V546.907L569.499 527.627ZM606.458 544.85L569.499 523.512L532.541 544.85V587.526L569.499 608.863L606.458 587.526V544.85ZM617.816 546.907L651.21 527.627L684.605 546.907V585.468L651.21 604.748L617.816 585.468V546.907ZM651.21 523.512L688.168 544.85V587.526L651.21 608.863L614.252 587.526V544.85L651.21 523.512ZM610.829 457.248L600.902 462.979L577.434 476.528V515.089L610.829 534.369L644.223 515.089V476.528L610.829 457.248ZM647.787 474.471L610.829 453.133L599.12 459.893L573.87 474.471V517.147L610.829 538.485L647.787 517.147V474.471ZM576.835 617.263L610.23 597.982L643.624 617.263V655.823L610.23 675.104L576.835 655.823V617.263ZM610.23 593.867L647.188 615.205V657.881L610.23 679.219L573.271 657.881V615.205L610.23 593.867Z"
              fill="url(#paint0_radial_13509_92956)"
            ></path>
            <defs data-v-4f848afc="">
              <radialGradient
                data-v-4f848afc=""
                id="paint0_radial_13509_92956"
                cx="0"
                cy="0"
                r="1"
                gradientUnits="userSpaceOnUse"
                gradientTransform="translate(619.524 475.895) rotate(117.246) scale(228.719 189.463)"
              >
                <stop
                  data-v-4f848afc=""
                  offset="0.141956"
                  stop-color="white"
                  stop-opacity="0.86"
                ></stop>
                <stop
                  data-v-4f848afc=""
                  offset="1"
                  stop-color="white"
                  stop-opacity="0.17"
                ></stop>
              </radialGradient>
            </defs>
          </svg>
        </div>
      </div>
        <HeroSvg class="h-full w-full hidden"></HeroSvg>
      </div>
    </div>

    <!-- comunity owned section  -->
    <div
      class="flex flex-col items-center justify-center min-h-96 md:pt-64 bg-red-30 text-white text-lg mt-40 py-20 px-6"
    >
      <div class="w-full md:w-1/2 flex items-center">
        <p class="text-slate-400 text-sm font-base">
          COMMUNITY-OWNED AND OPERATED
        </p>
      </div>

      <div class="w-full md:w-1/2 block md:flex items-center relative stats">
        <div class="flex-1 xl:pr-20">
          <h3
            class="font-bold bg-gradient-to-r from-gray-200 via-gray-600 to-white bg-clip-text text-transparent text-4xl md:text-6xl my-8"
          >
            Enter a new universe of connected services.
          </h3>
          <p class="text-slate-50 text-xl font-light">
            Cosmos apps and services connect using IBC, the Inter-Blockchain
            Communication protocol. This innovation enables you to freely
            exchange assets and data across sovereign.
          </p>
          <div class="block md:flex items-center mt-5">
            <div class="w-full md:w-max  h-max">
              <button
                href="#"
                class="text-decoration-none py-4 md:py-6 w-full md:w-max px-16 bg-slate-100 font-semibold text-black rounded-xl"
                >Learn <span class="icon__right">→</span></button
              >
            </div>
            <div class="w-full md:w-max h-max">
              <button
                href="#"
                class="text-decoration-none mt-5 md:mt-auto py-4 md:py-6 w-full md:w-max md:ml-6 font-semibold text-slate-100 rounded-lg"
                >Explore tokens <span class="icon__right">→</span></button
              >
            </div>
          </div>
        </div>

        <div class="flex-col h-100 relative mt-5 md:mt-auto">
          <div class="h-full text-start md:text-end">
            <h3 class="font-bold text-white-400 text-5xl md:text-7xl">
              249<small>+</small>
            </h3>

            <p class="text-slate-100 text-sm mt-2 font-thin">
              Apps & services, and growing.
            </p>
          </div>

          <div class="h-full text-start md:text-end mt-10">
            <h3 class="font-bold text-white-400 text-5xl md:text-7xl">
              $65B<small>+</small>
            </h3>

            <p class="text-slate-100 text-sm mt-2 font-thin">
              <!-- Apps & services, and growing. -->
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- Security that sales  -->
    <div
      class="flex flex-col items-center justify-center min-h-96 bg-red-30 text-white text-lg mt-20 md:mt-40 py-20 relative px-6"
      data-aos="fade-up"
      data-aos-duration="800"
    >
      <div class="w-full md:w-2/3 block md:flex items-center relative ">
        <div class="flex-1 basis-1/2 my-6 md:my-auto">
          <h3
            class="font-bold inline bg-gradient-to-r from-purple-200 via-purple-400 to-indigo-200 bg-clip-text text-transparent text-4xl md:text-6xl my-8"
          >
            Security that scales to thousands of contracts
          </h3>
          <p class="text-slate-400  text-lg md:text-xl font-thin">
            Deploy a smart contract platform or launch an EVM-compatible chain.
          </p>
        </div>
        <Backdrop1></Backdrop1>
        <div class="flex-col h-100 relative basis-1/3">
          <div
            class="h-full backdrop-blur bg-neutral-900/50 relative ring-1 ring-white/10 rounded-2xl p-10"
          >
            <div
              class="absolute -top-px left-20 right-11 h-px bg-gradient-to-r from-blue-300/0 via-blue-300/70 to-blue-300/0"
            ></div>
            <div
              class="absolute -bottom-px left-11 right-20 h-px bg-gradient-to-r from-blue-400/0 via-blue-400 to-blue-400/0"
            ></div>
            <div>
              <NeutronSvg />
              <h3 class="font-bold text-white-400 text-4xl my-8">Neutron</h3>
              <p class="text-slate-100 text-sm mt-2 font-thin mb-5">
                The most secure smart-contract platform on the Interchain.
              </p>
              <a
                href="#"
                class="text-decoration-none font-semibold text-slate-100 rounded-lg"
                >Learn More <span class="icon__right">↗</span></a
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Feature of ampere chain  -->

    <div
      class="text-center relative w-full flex flex-column justify-center align-center md:p-10 md:w-5/6 justify-center mx-auto"
    >
      <Backdrop2></Backdrop2>
      <GraphicsUi class="absolute top-0 left-0"></GraphicsUi>
      <div class="relative">
        <h3
          class="font-bold text-5xl bg-gradient-to-r from-gray-50 via-gray-300 to-white bg-clip-text text-transparent"
        >
          Features 
        </h3>
        <p class="text-slate-300 text-lg mt-2 font-thin mb-5">
          The most secure smart-contract platform on the Interchain.
        </p>

        <div class="block md:flex flex-1 items-center">
          <div class="flex-1 flex-col h-100 relative mx-5 py-4 h-full">
            <div
              data-aos="fade-up"
              data-aos-duration="400"
              class="h-full backdrop-blur bg-neutral-900/50 relative ring-1 ring-white/10 rounded-2xl px-7 py-8 md:p-10"
            >
              <div
                class="absolute -top-px left-20 right-11 h-px bg-gradient-to-r from-purple-300/0 via-purple-300/70 to-purple-300/0"
              ></div>
              <div
                class="absolute -bottom-px left-11 right-20 h-px bg-gradient-to-r from-purple-400/0 via-purple-400 to-purple-400/0"
              ></div>
              <div class="text-center">
                <div
                  style="
                    opacity: 1;
                    transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1)
                      rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
                    transform-style: preserve-3d;
                  "
                  class="backdrop-blur-lg h-24 p-5 rounded-full w-24 mx-auto"
                >
                  <img
                    src="https://assets-global.website-files.com/6596e1df914ba595fb917495/6596e1df914ba595fb91755a_Content%20Icon.webp"
                    loading="lazy"
                    alt=""
                    class=""
                  />
                </div>

                <h3
                  class="font-bold bg-gradient-to-r from-gray-200 via-gray-600 to-white bg-clip-text text-transparent text-4xl my-4"
                >
                  TPS
                </h3>
                <p class="text-slate-100 text-sm mt-2 font-thin mb-5">
                  With less than 1s block confirmation and 300 MB block size
                  AmpereChain process 2 millions transactions per seconds.
                </p>
              </div>
            </div>
          </div>

          <div
            class="flex-1 flex-col h-100 relative mx-5 py-4 h-full"
            data-aos="fade-up"
            data-aos-duration="600"
          >
            <div
              class="h-full backdrop-blur bg-neutral-900/50 relative ring-1 ring-white/10 rounded-2xl px-7 py-8 md:p-10"
            >
              <div
                class="absolute -top-px left-20 right-11 h-px bg-gradient-to-r from-purple-300/0 via-purple-300/70 to-purple-300/0"
              ></div>
              <div
                class="absolute -bottom-px left-11 right-20 h-px bg-gradient-to-r from-purple-400/0 via-purple-400 to-purple-400/0"
              ></div>
              <div class="text-center">
                <div
                  style="
                    opacity: 1;
                    transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1)
                      rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
                    transform-style: preserve-3d;
                  "
                  class="backdrop-blur-lg h-24 p-5 rounded-full w-24 mx-auto"
                >
                  <img
                    src="https://assets-global.website-files.com/6596e1df914ba595fb917495/6596e1df914ba595fb91755a_Content%20Icon.webp"
                    loading="lazy"
                    alt=""
                    class=""
                  />
                </div>

                <h3
                  class="font-bold bg-gradient-to-r from-gray-200 via-gray-600 to-white bg-clip-text text-transparent text-4xl my-4"
                >
                  Privacy protection
                </h3>
                <p class="text-slate-100 text-sm mt-2 font-thin mb-5">
                  AmpereChain is only public blockchain which support
                  transaction and data privacy using Tessera node.
                </p>
              </div>
            </div>
          </div>

          <div
            class="flex-1 flex-col h-100 relative mx-5 py-4 h-full"
            data-aos="fade-up"
            data-aos-duration="900"
          >
            <div
              class="h-full backdrop-blur bg-neutral-900/50 relative ring-1 ring-white/10 rounded-2xl px-7 py-8 md:p-10"
            >
              <div
                class="absolute -top-px left-20 right-11 h-px bg-gradient-to-r from-purple-300/0 via-purple-300/70 to-purple-300/0"
              ></div>
              <div
                class="absolute -bottom-px left-11 right-20 h-px bg-gradient-to-r from-purple-400/0 via-purple-400 to-purple-400/0"
              ></div>
              <div class="text-center">
                <div
                  style="
                    opacity: 1;
                    transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1)
                      rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
                    transform-style: preserve-3d;
                  "
                  class="backdrop-blur-lg h-24 p-5 rounded-full w-24 mx-auto"
                >
                  <img
                    src="https://assets-global.website-files.com/6596e1df914ba595fb917495/6596e1df914ba595fb91755a_Content%20Icon.webp"
                    loading="lazy"
                    alt=""
                    class=""
                  />
                </div>

                <h3
                  class="font-bold bg-gradient-to-r from-gray-200 via-gray-600 to-white bg-clip-text text-transparent text-4xl my-4"
                >
                  Truely decentralized
                </h3>
                <p class="text-slate-100 text-sm mt-2 font-thin mb-5">
                  We have developed own decentralized layer QBFT and now capable
                  to support users validator
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div>
      <Timeline />
    </div>

    <div class="bg-zinc-900">
      <div
        class="w-full flex flex-column justify-center align-center md:p-10 md:w-5/6 justify-center mx-auto"
      >
        <SupportVue />
      </div>
    </div>
  </div>
</template>

<script>
import HeroSvg from "@/components/svg/chainSvg.vue";
import NeutronSvg from "@/components/svg/NeutronSvg.vue";
import Backdrop1 from "@/components/svg/Backdrop1.vue";
import Backdrop2 from "@/components/svg/Backdrop2.vue";
import Timeline from "@/components/landing/timeline.vue";
import SupportVue from "@/components/landing/Support.vue";
import GraphicsUi from "@/components/common/GraphicsUi"
export default {
  name: "HomePage",
  components: {
    HeroSvg,
    NeutronSvg,
    Backdrop1,
    Backdrop2,
    Timeline,
    SupportVue,
    GraphicsUi
  },
};
</script>

<style scoped>
.bg {
  position: relative;
  width: 100%;
  filter: blur(10px);
}

@keyframes gradientAnimation {
  0% {
    background-position: 0% 0%;
  }
  100% {
    background-position: 100% 0%;
  }
}

.animatedText {
  background: linear-gradient(-25deg, hsla(0, 0%, 100%, 0) 56%, #bbbaff 98%),
    linear-gradient(-125deg, #b6baf6 23%, #fff 60%);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
  padding-bottom: 10px;
  font-size: calc(1.57625rem + 5.37833vw) !important;
  /* font-family: unset !important;; */
}

.stats:after,
.stats:before {
  display: block;
  width: 1rem;
  height: 1rem;
  border-right: 0.0625rem solid white;
}

.stats:after {
  border-bottom: 0.0625rem solid white;
  bottom: 0;
}

.stats:before {
  border-top: 0.0625rem solid white;
  top: 0;
}

.stats:after,
.stats:before {
  content: "";
  position: absolute;
  right: 0;
}

html {
  font: 400 100%/1.5 "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
}
</style>
