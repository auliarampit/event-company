<template>
  <div class="w-full h-full">
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
      rel="stylesheet"
    />

    <script src="https://unpkg.com/vue@next"></script>
    <!-- welcome component -->
    <div class="relative welcome">
      <div class="mx-auto py-8 px-4 sm:py-14 sm:px-4 lg:max-w-7xl lg:px-8">
        <img
          src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/caribarang-logo.png"
          alt="caribarang"
          class="mx-auto"
        />

        <div class="sm:w-10/12 mx-auto text-center text-white py-2 sm:py-6">
          <h1 class="text-xl sm:text-6xl font-bold capitalize leading-tight">
            Jadi pedagang online internasional dengan amazon FBA, Belajar
            langsung dari ahlinya
          </h1>
          <p class="mt-3 sm:text-xl italic text-base">
            <strong
              >(It's your turn to become a worldwide online seller!<br />Start
              selling from all around the world with Amazon FBA. Learn more from
              the expert!)</strong
            >
          </p>
        </div>

        <div
          class="w-full sm:w-10/12 mx-auto text-center text-white py-3 sm:py-6"
        >
          <p class="mt-6 sm:text-2xl text-base">
            <strong>5000+ orang</strong> sudah mengikuti seminar ini yang
            diadakan di berbagai negara asia seperti Singapura, Filipina,
            Malaysia, Taiwan, dan Hongkong
          </p>
          <p class="mt-6 sm:text-xl italic text-base">
            (Be part of 5.000+ people who successfully join our seminar from
            Southeast Asia, such as Singapore,<br />Malaysia, Taiwan, Hongkong,
            and Phillipines.)
          </p>
        </div>

        <div
          class="
            grid grid-cols-1
            lg:grid-cols-2 lg:grid-flow-col lg:auto-cols-fr
            bg-white
            rounded-lg
            mt-8
          "
        >
          <Schedule v-for="data of scheduleData" :key="data.id" :data="data" />
        </div>

        <div
          class="
            max-w-2xl
            mx-auto
            py-5
            px-4
            sm:py-5 sm:px-4
            lg:max-w-7xl lg:px-5
          "
        >
          <div class="w-full sm:w-6/12 mx-auto text-center text-gray-500">
            <a href="https://goo.gl/maps/wHDz3K6BsGopKqNGA" target="_blank"
              ><h1
                class="
                  text-md
                  sm:text-md
                  font-medium
                  leading-tight
                  capitalize
                  text-white
                "
              >
                <b>Lokasi Seminar</b>: Aston Kemayoran City Hotel (Ruangan
                Mentawai dan Raja Ampat Lt.25) <br />
                Jl. HBR Motik No.4, RW.10, Gn. Sahari Sel., Kec. Kemayoran,
                Jakarta Pusat.
              </h1></a
            >
          </div>
        </div>

        <div class="absolute -bottom-5 sm:-bottom-8 btn-center">
          <button
            class="
              flex
              bg-red-500
              text-white
              active:bg-red-600
              font-bold
              capitalize
              text-sm
              sm:text-lg
              px-6
              sm:px-12
              py-2
              sm:py-4
              rounded-xl
              shadow-md
              hover:shadow-lg
              outline-none
              focus:outline-none
              mr-1
              mb-1
              ease-linear
              transition-all
              duration-150
              border border-white
            "
          >
            Register Now
          </button>
        </div>
      </div>
    </div>

    <!-- amazon -->
    <div
      class="max-w-2xl mx-auto py-8 px-4 sm:py-14 sm:px-4 lg:max-w-7xl lg:px-8"
    >
      <h1 class="text-3xl sm:text-5xl font-bold text-gray-700 text-center">
        Apa itu Amazon FBA?
      </h1>
      <div class="w-full sm:w-8/12 mx-auto py-3">
        <p
          class="
            text-gray-400
            font-bold
            italic
            text-base
            sm:text-lg
            text-center
          "
        >
          (What is Amazon FBA?)
        </p>
      </div>
      <div class="w-full sm:w-8/12 mx-auto py-3">
        <p class="text-gray-500 text-base sm:text-lg text-center">
          Amazon FBA adalah singkatan dari Fullfilment By Amazon, yang bisa
          membantu kamu berjualan di berbagai negara melalui marketplace Amazon
        </p>
        <p class="text-gray-400 italic text-base sm:text-lg text-center">
          (Amazon FBA stands for Fulfillment by Amazon, which can help you sell
          your product<br />
          by the most popular international marketplace, Amazon)
        </p>
        <p
          class="text-base sm:text-lg text-gray-800 font-bold text-center pt-6"
        >
          Bagaimana cara kerja Amazon FBA?
        </p>
        <p
          class="
            text-gray-400
            font-bold
            italic
            text-base
            sm:text-lg
            text-center
          "
        >
          (How do Amazon FBA works?)
        </p>
      </div>
      <ul class="w-full mt-8">
        <li class="grid grid-cols-3 sm:grid-cols-2 gap-4 py-3 mb-8">
          <div class="col-span-1">
            <img
              src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/Ilustrasi-step-1.png"
              alt=""
            />
          </div>
          <div class="col-span-2 sm:col-span-1">
            <div class="flex flex-col justify-center h-full">
              <div class="w-full sm:w-10/12 mx-auto">
                <span
                  class="
                    bg-red-500
                    text-white
                    px-3
                    py-2
                    rounded-lg
                    text-base
                    mt-5
                    italic
                  "
                >
                  Step 1
                </span>
              </div>
              <div class="w-full sm:w-10/12 mx-auto my-3">
                <h1 class="text-gray-700 text-base sm:text-3xl font-bold">
                  Kirimkan barang jualan kamu ke gudang FBA
                </h1>
                <p class="text-gray-400 italic text-base sm:text-lg mt-2">
                  (Send your goods to the FBA warehouse)
                </p>
              </div>
              <div class="mt-3 w-full sm:w-10/12 mx-auto">
                <a
                  href=""
                  class="
                    w-full
                    text-red-500
                    border border-red-500
                    hover:bg-red-500 hover:text-white
                    text-sm
                    active:bg-red-600
                    font-semibold
                    capitalize
                    px-4
                    sm:px-8
                    py-1.5
                    sm:py-3
                    rounded-lg
                    outline-none
                    focus:outline-none
                    mr-1
                    mb-1
                    ease-linear
                    transition-all
                    duration-150
                    italic
                  "
                  >Register Now</a
                >
              </div>
            </div>
          </div>
        </li>
        <li class="grid grid-cols-3 sm:grid-cols-2 gap-4 py-3 mb-8">
          <div class="col-span-2 sm:col-span-1">
            <div class="flex flex-col justify-center h-full">
              <div class="w-full sm:w-10/12 mx-auto">
                <span
                  class="
                    bg-red-500
                    text-white
                    px-3
                    py-2
                    rounded-lg
                    text-base
                    mt-5
                    italic
                  "
                >
                  Step 2
                </span>
              </div>
              <div class="w-full sm:w-10/12 mx-auto my-3">
                <h1 class="text-gray-700 text-base sm:text-3xl font-bold">
                  Jual produk kamu di marketplace Amazon
                </h1>
                <p class="text-gray-400 italic text-base sm:text-lg mt-2">
                  (Sell your product in Amazon marketplace)
                </p>
              </div>
              <div class="mt-3 w-full sm:w-10/12 mx-auto">
                <a
                  href=""
                  class="
                    w-full
                    text-red-500
                    border border-red-500
                    hover:bg-red-500 hover:text-white
                    text-sm
                    active:bg-red-600
                    font-semibold
                    capitalize
                    px-4
                    sm:px-8
                    py-1.5
                    sm:py-3
                    rounded-lg
                    outline-none
                    focus:outline-none
                    mr-1
                    mb-1
                    ease-linear
                    transition-all
                    duration-150
                    italic
                  "
                  >Register Now</a
                >
              </div>
            </div>
          </div>
          <div class="col-span-1">
            <img
              src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/Ilustrasi%20step%202.png"
              alt=""
            />
          </div>
        </li>
        <li class="grid grid-cols-3 sm:grid-cols-2 gap-4 py-3 mb-8">
          <div class="col-span-1">
            <div class="w-9/12 mx-auto">
              <img
                src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/Ilustrasi%20step%203.png"
                alt=""
              />
            </div>
          </div>
          <div class="col-span-2 sm:col-span-1">
            <div class="flex flex-col justify-center h-full">
              <div class="w-full sm:w-10/12 mx-auto">
                <span
                  class="
                    bg-red-500
                    text-white
                    px-3
                    py-2
                    rounded-lg
                    text-base
                    mt-5
                    italic
                  "
                >
                  Step 3
                </span>
              </div>
              <div class="w-full sm:w-10/12 mx-auto my-3">
                <h1 class="text-gray-700 text-base sm:text-3xl font-bold">
                  Amazon FBA akan mengurus stok dan mengirimkan produk ke
                  customer kamu
                </h1>
                <p class="text-gray-400 italic text-base sm:text-lg mt-2">
                  (Amazon FBA will take care of your products and deliver to
                  your customers)
                </p>
              </div>
              <div class="mt-3 w-full sm:w-10/12 mx-auto">
                <a
                  href=""
                  class="
                    w-full
                    text-red-500
                    border border-red-500
                    hover:bg-red-500 hover:text-white
                    text-sm
                    active:bg-red-600
                    font-semibold
                    capitalize
                    px-4
                    sm:px-8
                    py-1.5
                    sm:py-3
                    rounded-lg
                    outline-none
                    focus:outline-none
                    mr-1
                    mb-1
                    ease-linear
                    transition-all
                    duration-150
                    italic
                  "
                  >Register Now</a
                >
              </div>
            </div>
          </div>
        </li>
        <li class="grid grid-cols-3 sm:grid-cols-2 gap-4 py-3 mb-8">
          <div class="col-span-2 sm:col-span-1">
            <div class="flex flex-col justify-center h-full">
              <div class="w-full sm:w-10/12 mx-auto">
                <span
                  class="
                    bg-red-500
                    text-white
                    px-3
                    py-2
                    rounded-lg
                    text-base
                    mt-5
                    italic
                  "
                >
                  Step 4
                </span>
              </div>
              <div class="w-full sm:w-10/12 mx-auto my-3">
                <h1 class="text-gray-700 text-base sm:text-3xl font-bold">
                  Kamu tinggal duduk dan terima profit penjualan
                </h1>
                <p class="text-gray-400 italic text-base sm:text-lg mt-2">
                  (You just chill and earn your profit)
                </p>
              </div>
              <div class="mt-3 w-full sm:w-10/12 mx-auto">
                <a
                  href=""
                  class="
                    w-full
                    text-red-500
                    border border-red-500
                    hover:bg-red-500 hover:text-white
                    text-sm
                    active:bg-red-600
                    font-semibold
                    capitalize
                    px-4
                    sm:px-8
                    py-1.5
                    sm:py-3
                    rounded-lg
                    outline-none
                    focus:outline-none
                    mr-1
                    mb-1
                    ease-linear
                    transition-all
                    duration-150
                    italic
                  "
                  >Register Now</a
                >
              </div>
            </div>
          </div>
          <div class="col-span-1">
            <img
              src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/Ilustrasi%20step%204.png"
              alt=""
            />
          </div>
        </li>
      </ul>
      <div class="mt-10 py-0 sm:py-5">
        <h1 class="text-3xl sm:text-5xl font-bold text-gray-700 text-center">
          Master Trainer Andy
        </h1>
        <div class="w-full sm:w-9/12 mx-auto py-3">
          <p class="text-gray-500 text-base sm:text-lg text-center">
            Beliau ini berhasil mencetak ratusan pedagang online internasional
            dengan omset puluhan bahkan ratusan juta setiap bulannya, dan kali
            ini Master Trainer Andy datang ke Indonesia untuk berbagi ilmu
            dengan metode yang telah terbukti efektif untuk menjual di Amazon.
          </p>
        </div>
        <div class="w-full sm:w-9/12 mx-auto py-3">
          <p class="text-gray-400 italic text-base sm:text-lg text-center">
            (Coach Andy has succeed in teaching hundreds of international online
            merchants with a turnover of tens or even hundreds of millions
            rupiah every month, and this time Master Trainer Andy will come to
            Indonesia to share his knowledge and proven methods in selling on
            Amazon.)
          </p>
        </div>
        <div>
          <img
            src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/Foto%20master%20trainer%20andy.png"
            alt=""
            class="w-full"
          />
        </div>
        <div class="pt-5 text-center">
          <button
            class="
              text-red-500
              border border-red-500
              hover:bg-red-500 hover:text-white
              text-sm
              active:bg-red-600
              font-bold
              capitalize
              italic
              px-20
              py-3
              rounded-lg
              outline-none
              focus:outline-none
              mr-1
              mb-1
              ease-linear
              transition-all
              duration-150
            "
          >
            Register Now
          </button>
        </div>
      </div>
    </div>

    <!-- learn -->
    <div style="background-color: rgba(2, 132, 199)" class="text-white">
      <div class="max-w-2xl mx-auto lg:max-w-7xl py-6 px-3">
        <div class="w-full sm:w-6/12 mx-auto text-center text-white sm:py-6">
          <h1 class="text-xl sm:text-5xl font-bold leading-tight">
            Apa yang akan kamu pelajari di seminar ini?
          </h1>
          <p
            class="
              text-white
              font-bold
              italic
              text-base
              mt-3
              sm:text-xl
              text-center
            "
          >
            (What will you learn from the seminar?)
          </p>
        </div>

        <div class="py-5 grid grid-cols-2 sm:grid-cols-4 gap-2">
          <Learn v-for="data of learnData" :key="data.id" :data="data" />
        </div>

        <div class="py-5 text-center">
          <button
            class="
              text-white
              border border-white
              hover:bg-gray-500 hover:text-white
              active:bg-gray-600
              font-bold
              capitalize
              italic
              text-base
              px-20
              py-3
              rounded-lg
              outline-none
              focus:outline-none
              mr-1
              mb-1
              ease-linear
              transition-all
              duration-150
            "
          >
            Register Now
          </button>
        </div>
      </div>
    </div>

    <!-- testi -->
    <div class="bg-white py-6">
      <div class="max-w-2xl mx-auto lg:max-w-7xl lg:px-8">
        <div
          class="w-10/12 sm:w-6/12 mx-auto text-center text-gray-700 sm:py-6"
        >
          <h1 class="text-2xl sm:text-5xl font-bold leading-tight">
            Mau Seperti Mereka? Daftar Sekarang
          </h1>
          <p
            class="
              text-gray-400
              font-bold
              italic
              text-base
              sm:text-lg
              text-center
              mt-2
            "
          >
            (Want to earn from your own international online store?<br />Register
            Now!)
          </p>
        </div>
      </div>

      <div class="hidden sm:block w-full relative mt-8 mb-10">
        <div class="bg-red-500 testy-bg"></div>
        <div class="max-w-2xl mx-auto lg:max-w-7xl lg:px-8 z-10 relative">
          <div class="grid grid-cols-4">
            <div v-for="data of testiData" :key="data.id" class="px-6">
              <div
                class="
                  bg-white
                  rounded-t-lg
                  shadow-lg
                  rounded-b-lg
                  overflow-hidden
                "
              >
                <img :src="data.image" />
                <div class="bg-white w-full text-center py-2 flex flex-col">
                  <span class="text-2xl text-gray-700">{{ data.price }}</span>
                  <span class="text-gray-400">per month</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- question -->
    <div class="bg-gray-200">
      <div
        class="
          max-w-2xl
          mx-auto
          py-8
          px-4
          sm:py-10 sm:px-4
          lg:max-w-7xl lg:px-8
        "
        style="background-color: rgba(229, 229, 229)"
      >
        <div class="w-full sm:w-6/12 mx-auto text-center text-gray-700">
          <h1 class="text-xl sm:text-4xl font-bold leading-tight capitalize">
            Frequently asked question
          </h1>
        </div>
        <div class="py-6 grid grid-cols-1 sm:grid-cols-2 gap-3 mt-5">
          <div v-for="data of questionData" :key="data.id">
            <h3 class="text-gray-600 text-base sm:text-xl font-bold">
              {{ data.question }}
            </h3>
            <p class="text-gray-400 italic text-base sm:text-lg font-bold">
              ({{ data.translateQuestion }})
            </p>
            <div class="flex py-3 text-gray-500 text-sm sm:text-base">
              <span class="pr-2"><i class="fas fa-play"></i></span>
              <p>
                {{ data.answer }}
              </p>
            </div>
            <div class="flex py-3 pl-5 text-gray-500 text-sm sm:text-base">
              <p class="italic">({{ data.translateAnswer }})</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- schedule -->
    <div class="schedule w-full">
      <div
        class="
          max-w-2xl
          mx-auto
          py-8
          px-4
          sm:py-14 sm:px-4
          lg:max-w-7xl lg:px-8
        "
      >
        <div
          class="
            w-full
            grid grid-cols-1
            sm:grid-cols-2
            gap-6
            sm:gap-6
            px-4
          "
        >
          <div
            class="
              bg-white
              shadow-lg
              sm:py-8 sm:px-8
              py-4
              px-4
              rounded
              text-center
            "
          >
            <span
              class="bg-red-500 text-white px-3 py-2 rounded-lg text-base mt-5"
            >
              Tuesday
            </span>
            <div class="py-5 flex flex-col">
              <span class="text-2xl sm:text-5xl font-bold text-gray-800"
                >28</span
              >
              <span class="text-gray-500 text-base sm:text-1xl font-medium"
                >June 2022</span
              >
            </div>
            <div class="py-3 flex flex-col">
              <span class="text-gray-500 text-base sm:text-1xl font-bold"
                >14.00 - 17.00 WIB</span
              >
            </div>
            <div class="mt-5">
              <button
                class="
                  block
                  text-center
                  bg-red-500
                  text-white
                  active:bg-red-600
                  font-bold
                  capitalize
                  text-base
                  sm:text-sm
                  px-2
                  sm:px-3
                  py-4
                  sm:py-2
                  rounded
                  shadow-md
                  hover:shadow-lg
                  outline-none
                  focus:outline-none
                  mr-1
                  mb-1
                  ease-linear
                  transition-all
                  duration-150
                  w-full
                "
              >
                Register Now
              </button>
            </div>
          </div>
          <div
            class="
              bg-white
              shadow-lg
              sm:py-8 sm:px-8
              py-4
              px-4
              rounded
              text-center
            "
          >
            <span
              class="bg-red-500 text-white px-3 py-2 rounded-lg text-base mt-5"
            >
              Wednesday
            </span>
            <div class="py-5 flex flex-col">
              <span class="text-2xl sm:text-5xl font-bold text-gray-800"
                >29</span
              >
              <span class="text-gray-500 text-base sm:text-1xl font-medium"
                >June 2022</span
              >
            </div>
            <div class="py-3 flex flex-col">
              <span class="text-gray-500 text-base sm:text-1xl font-bold"
                >14.00 - 17.00 WIB</span
              >
            </div>
            <div class="mt-5">
              <button
                class="
                  block
                  text-center
                  bg-red-500
                  text-white
                  active:bg-red-600
                  font-bold
                  capitalize
                  text-base
                  sm:text-sm
                  px-2
                  sm:px-3
                  py-4
                  sm:py-2
                  rounded
                  shadow-md
                  hover:shadow-lg
                  outline-none
                  focus:outline-none
                  mr-1
                  mb-1
                  ease-linear
                  transition-all
                  duration-150
                  w-full
                "
              >
                Register Now
              </button>
            </div>
          </div>
        </div>
        <div
          class="
            max-w-2xl
            mx-auto
            py-8
            px-4
            sm:py-10 sm:px-4
            lg:max-w-7xl lg:px-8
          "
        >
          <div class="w-full sm:w-6/12 mx-auto text-center text-gray-500">
            <div target="_blank">
              <h1
                class="text-md sm:text-md font-medium leading-tight capitalize"
              >
                <b>Lokasi Seminar</b>: Aston Kemayoran City Hotel (Ruangan
                Mentawai dan Raja Ampat Lt.25) <br />
                Jl. HBR Motik No.4, RW.10, Gn. Sahari Sel., Kec. Kemayoran,
                Jakarta Pusat.
              </h1>
            </div>
          </div>
        </div>
        <div class="mt-3 sm:mt-6 sosmed">
          <ul class="w-full flex justify-center">
            <li class="px-3">
              <button>
                <img
                  src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/icons8_instagram.png"
                  alt=""
                  class="w-8"
                />
              </button>
            </li>
            <li class="px-3">
              <button>
                <img
                  src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/icons8_facebook_1.png"
                  alt=""
                  class="w-8"
                />
              </button>
            </li>
            <li class="px-3">
              <button>
                <img
                  src="https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/icons8_website.png"
                  alt=""
                  class="w-8"
                />
              </button>
            </li>
          </ul>
          <p class="text-center text-gray-400 py-2 font-semibold">
            © 2021 caribarang.id, All rights reserved.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ScheduleDummy from "@/data/ScheduleDummy";
import LearnDummy from "@/data/LearnDummy";
import TestiDummy from "@/data/TestiDummy";
import QuestionDummy from "@/data/Question";

export default Vue.extend({
  name: "IndexPage",
  data() {
    return {
      scheduleData: ScheduleDummy,
      learnData: LearnDummy,
      testiData: TestiDummy,
      questionData: QuestionDummy,
    };
  },
});
</script>


<style scoped>
.welcome {
  background-size: cover;
  background-attachment: fixed;
  background-image: url("https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/Background%20seminar(1).jpg");
}
.schedule {
  background-image: url("https://caribarang.oss-ap-southeast-1.aliyuncs.com/general/lp/Background%20world.png");
  background-position: 50%;
  background-size: cover;
  background-attachment: fixed;
  background-repeat: no-repeat;
}
.btn-center {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
}
</style>
