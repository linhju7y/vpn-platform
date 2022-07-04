<template>
  <div>
    <div class="flex justify-center h-screen">
      <img class="hidden bg-cover lg:block lg:w-2/3" :src="VngImage" />
      <div
        class="
          bg-gradient-to-bl
          from-lime-300
          flex
          items-center
          w-full
          max-w-md
          px-6
          mx-auto
          lg:w-2/6
        "
      >
        <div
          class="bg-white shadow-2xl p-6 rounded-2xl border-2 border-gray-50"
        >
          <h2 class="text-xl font-bold text-gray-800 text-left mb-5 text-center">
            Game Technical
          </h2>
          <form action="" class="w-full">
            <div id="button" class="flex flex-col w-full my-5">
              <button
                type="button"
                class="
                  w-full
                  border border-indigo-500
                  bg-indigo-500
                  text-white
                  rounded-md
                  px-4
                  py-2
                  transition
                  duration-500
                  ease
                  select-none
                  hover:bg-indigo-600
                  focus:outline-none focus:shadow-outline
                "
              >
                <div class="flex flex-row items-center justify-center">
                  <div class="mr-2">
                    <svg
                      class="w-6 h-6"
                      fill="none"
                      stroke="currentColor"
                      viewBox="0 0 24 24"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M11 16l-4-4m0 0l4-4m-4 4h14m-5 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h7a3 3 0 013 3v1"
                      ></path>
                    </svg>
                  </div>
                  <div>Log In As VNG O365 (CAS)</div>
                </div>
              </button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import VngImage from "../assets/images/s11.jpeg";
export default {
  data() {
    return {
      VngImage,
    };
  },
};
</script>

<style>
</style>