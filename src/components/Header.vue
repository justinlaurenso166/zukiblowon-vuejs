<script setup>
import { ref } from "@vue/reactivity";

const showMenu = ref(false);
</script>

<template>
  <div>
    <div
      style="background: #FFF6EA"
      class="
        absolute
        bg-black
        w-full
        top-0
        lg:px-8 lg:pt-8 lg:pb-8
        py-5
        px-5
        z-10
      "
    >
      <div
        class="
          flex
          h-full
          border-b border-white
          items-center
          justify-center
          max-w-11xl
          mx-auto
          border-opacity-0
          flex-row-reverse
        "
      >
        <div class="flex-grow">
          <div class="flex justify-end">
            <a class="w-min-content" href="/">
              <div
                class="
                  hover:bg-black
                  hover:text-white hover:bg-opacity-20
                  p-2
                  rounded-lg
                  text-black
                  opacity-80
                  hover:opacity-100 hover:text-black
                  text-3xl
                  px-4
                "
                style="font-family: 'Knewave', cursive"
              >
                Zukiblowon
              </div>
            </a>
          </div>
        </div>
        <div class="items-center hidden lg:flex">
          <ul class="flex space-x-3">
            <li>
              <router-link
                class="
                  bg-opacity-20
                  text-black
                  opacity-80
                  items-center
                  relative
                  h-7
                  tracking-wider
                  pt-0.5
                  first::pt-0
                  uppercase
                  text-sm
                  font-500
                  padding-huge
                  bg-black
                  hover:text-white
                  duration-200
                  items-center
                  px-4
                  hover:bg-opacity-70
                  rounded
                  flex
                  justify-center
                  flex-row
                "
                to="sneak_peeks"
                :class="$route.path === '/sneak_peeks' ? 'bg-opacity-70' : ''"
                >Sneak Peeks</router-link
              >
            </li>
            <li>
              <router-link
                class="
                  bg-opacity-20
                  text-black
                  opacity-80
                  items-center
                  relative
                  h-7
                  items-center
                  tracking-wider
                  pt-0.5
                  first::pt-0
                  duration-1000
                  uppercase
                  text-sm
                  font-500
                  padding-huge
                  bg-black
                  hover:text-white
                  duration-200
                  items-center
                  px-4
                  hover:bg-opacity-70
                  rounded
                  flex
                  justify-center
                  flex-row
                "
                to="/roadmap"
                :class="$route.path === '/roadmap' ? 'bg-opacity-70' : ''"
                >Roadmap</router-link
              >
            </li>
            <li>
              <router-link
                class="
                  bg-opacity-20
                  text-black
                  opacity-80
                  relative
                  h-7
                  items-center
                  tracking-wider
                  pt-0.5
                  first::pt-0
                  duration-1000
                  uppercase
                  text-sm
                  font-500
                  padding-huge
                  bg-black
                  hover:text-white
                  duration-200
                  px-4
                  hover:bg-opacity-70
                  rounded
                  flex
                  justify-center
                  flex-row
                "
                to="/team"
                :class="$route.path === '/team' ? 'bg-opacity-70' : ''"
                >Team</router-link
              >
            </li>
            <li>
              <router-link
                class="
                  bg-opacity-20
                  text-black
                  opacity-80
                  items-center
                  relative
                  h-7
                  tracking-wider
                  pt-0.5
                  first::pt-0
                  duration-1000
                  uppercase
                  text-sm
                  font-500
                  padding-huge
                  bg-black
                  hover:text-white
                  duration-200
                  px-4
                  hover:bg-opacity-70
                  rounded
                  flex
                  justify-center
                  flex-row
                "
                to="/support"
                :class="$route.path === '/support' ? 'bg-opacity-70' : ''"
                >Support</router-link
              >
            </li>
            <li>
              <router-link
                class="
                  bg-opacity-20
                  text-black
                  opacity-80
                  items-center
                  relative
                  h-7
                  items-center
                  tracking-wider
                  pt-0.5
                  first::pt-0
                  duration-1000
                  uppercase
                  text-sm
                  font-500
                  padding-huge
                  bg-black
                  hover:text-white
                  duration-200
                  items-center
                  px-4
                  hover:bg-opacity-70
                  rounded
                  flex
                  justify-center
                  flex-row
                "
                to="/merch"
                :class="$route.path === '/merch' ? 'bg-opacity-70' : ''"
                >Merch</router-link
              >
            </li>
            <li>
              <div
                class="
                  text-black
                  opacity-80
                  bg-opacity-20
                  items-center
                  relative
                  h-7
                  items-center
                  tracking-wider
                  pt-0.5
                  first::pt-0
                  duration-1000
                  uppercase
                  text-sm
                  font-500
                  padding-huge
                  bg-black
                  hover:text-white
                  duration-200
                  items-center
                  px-4
                  hover:bg-opacity-70
                  rounded
                  flex
                  justify-center
                  flex-row
                "
              >
                <div>
                  <div>
                    <div>
                      <button
                        id="headlessui-menu-button-1"
                        type="button"
                        aria-haspopup="true"
                        aria-expanded="false"
                      >
                        LANGUAGE
                      </button>
                    </div>
                  </div>
                </div>
              </div>
            </li>
            <li class="">
              <a
                href=""
                target="_blank"
                class="
                  w-full
                  items-center
                  block
                  relative
                  flex
                  text-black
                  bg-black
                  hover:text-white bg-opacity-20
                  hover:bg-opacity-70
                  px-2
                  py-1
                  rounded-lg
                "
                rel="noreferrer"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="ml-auto fill-current stroke-current h-5 w-5 text-black hover:text-white"
                  viewBox="0 0 40 40"
                >
                  <path
                    d="M38.526 8.625a15.199 15.199 0 01-4.373 1.198 7.625 7.625 0 003.348-4.211 15.25 15.25 0 01-4.835 1.847 7.6 7.6 0 00-5.557-2.404c-4.915 0-8.526 4.586-7.416 9.346-6.325-.317-11.934-3.347-15.69-7.953C2.01 9.869 2.97 14.345 6.358 16.612a7.58 7.58 0 01-3.446-.953c-.084 3.527 2.444 6.826 6.105 7.56a7.63 7.63 0 01-3.438.13 7.618 7.618 0 007.112 5.286A15.306 15.306 0 011.42 31.79a21.55 21.55 0 0011.67 3.42c14.134 0 22.12-11.937 21.637-22.643a15.499 15.499 0 003.799-3.941z"
                  ></path></svg
              ></a>
            </li>
            <li class="">
              <a
                href=""
                target="_blank"
                class="
                  w-full
                  items-center
                  block
                  relative
                  flex
                  text-black
                  bg-black
                  hover:text-white bg-opacity-20
                  hover:bg-opacity-70
                  px-2
                  py-1
                  rounded-lg
                "
                rel="noreferrer"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="ml-auto fill-current stroke-current h-5 w-5 text-black hover:text-white"
                  viewBox="0 0 40 40"
                >
                  <path
                    d="M27.524 1.79c3.334.17 5.899 1.11 7.694 2.992 1.796 1.88 2.822 4.36 2.993 7.694 0 1.314.078 3.651.085 7.089v2.108c-.002 2.768-.014 4.702-.085 5.85-.171 3.335-1.112 5.9-2.993 7.695-1.88 1.796-4.36 2.822-7.694 2.993-1.15.071-3.143.083-5.88.085h-3.317c-2.768-.002-4.702-.014-5.85-.085-3.335-.171-5.9-1.112-7.695-2.993-1.796-1.795-2.822-4.36-2.993-7.694-.065-1.04-.08-2.771-.084-5.118v-4.812c.004-2.347.02-4.078.084-5.118.171-3.334 1.112-5.899 2.993-7.694 1.795-1.796 4.36-2.822 7.694-2.993 1.04-.065 2.771-.08 5.118-.084h4.847c2.361.004 4.043.02 5.083.084Zm-7.61 8.805c-2.65 0-4.873.94-6.668 2.736C11.45 15.212 10.51 17.35 10.51 20c0 2.65.94 4.873 2.736 6.669 1.88 1.795 4.018 2.736 6.668 2.736 2.65 0 4.874-.94 6.67-2.736 1.795-1.881 2.735-4.019 2.735-6.669 0-2.65-.94-4.873-2.736-6.669-1.795-1.88-4.018-2.736-6.669-2.736Zm0 3.25c1.71 0 3.164.598 4.36 1.795A6.076 6.076 0 0 1 26.07 20c0 1.624-.598 3.078-1.795 4.275-1.197 1.197-2.65 1.795-4.36 1.795-1.71 0-3.164-.598-4.36-1.795-1.198-1.112-1.796-2.565-1.796-4.275 0-1.71.598-3.163 1.795-4.36 1.197-1.197 2.65-1.796 4.36-1.796Zm9.833-5.9c-.599 0-1.112.257-1.54.684-.427.427-.683.94-.683 1.539 0 .598.256 1.111.684 1.539.427.427.94.684 1.539.684.598 0 1.111-.257 1.538-.684.428-.428.684-.94.684-1.54 0-.598-.256-1.11-.684-1.538-.427-.427-.94-.684-1.538-.684Z"
                  ></path></svg
              ></a>
            </li>
            <li class="">
              <a
                href=""
                target="_blank"
                class="
                  w-full
                  items-center
                  block
                  relative
                  flex
                  text-black
                  bg-black
                  hover:text-white bg-opacity-20
                  hover:bg-opacity-70
                  px-2
                  py-1
                  rounded-lg
                "
                rel="noreferrer"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="ml-auto fill-current stroke-current h-5 w-5 text-black hover:text-white"
                  viewBox="0 0 40 40"
                >
                  <path
                    d="M33.567 7.554a32.283 32.283 0 00-7.969-2.472.12.12 0 00-.128.06c-.344.613-.725 1.411-.992 2.039a29.804 29.804 0 00-8.95 0 20.625 20.625 0 00-1.008-2.038.126.126 0 00-.128-.06 32.194 32.194 0 00-7.968 2.47.114.114 0 00-.053.046C1.296 15.18-.095 22.577.588 29.88c.003.036.023.07.05.092 3.349 2.459 6.593 3.952 9.776 4.941a.127.127 0 00.137-.045 23.203 23.203 0 002-3.253.124.124 0 00-.068-.172A21.379 21.379 0 019.43 29.99a.126.126 0 01-.012-.209c.205-.153.41-.313.607-.475a.121.121 0 01.126-.017c6.407 2.925 13.343 2.925 19.675 0a.12.12 0 01.128.015c.196.162.4.324.608.477a.126.126 0 01-.011.209c-.975.57-1.99 1.051-3.055 1.454a.125.125 0 00-.067.173 26.052 26.052 0 001.998 3.252c.031.043.087.062.138.046 3.199-.99 6.442-2.482 9.79-4.941a.126.126 0 00.052-.09c.816-8.445-1.368-15.78-5.789-22.283a.1.1 0 00-.05-.046zm-20.06 17.88c-1.928 0-3.517-1.771-3.517-3.946 0-2.175 1.558-3.946 3.518-3.946 1.975 0 3.549 1.787 3.518 3.946 0 2.175-1.558 3.946-3.518 3.946zm13.01 0c-1.93 0-3.52-1.771-3.52-3.946 0-2.175 1.56-3.946 3.52-3.946 1.974 0 3.548 1.787 3.517 3.946 0 2.175-1.543 3.946-3.518 3.946z"
                  ></path></svg
              ></a>
            </li>
            <li class="">
              <a
                href=""
                target="_blank"
                class="
                  w-full
                  items-center
                  block
                  relative
                  flex
                  text-black
                  bg-black
                  hover:text-white bg-opacity-20
                  hover:bg-opacity-70
                  px-2
                  py-1
                  rounded-lg
                "
                rel="noreferrer"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="ml-auto fill-current stroke-current h-5 w-5 text-black hover:text-white"
                  viewBox="0 0 40 40"
                >
                  <path
                    d="M20 1C9.508 1 1 9.508 1 20s8.508 19 19 19 19-8.508 19-19S30.496 1 20 1Zm-9.625 19.638.08-.129 4.943-7.733c.072-.11.243-.099.297.023.824 1.85 1.539 4.153 1.204 5.586-.14.589-.532 1.387-.973 2.124a3.808 3.808 0 0 1-.186.316.168.168 0 0 1-.14.072h-5.081a.168.168 0 0 1-.144-.259Zm22.028 2.66a.172.172 0 0 1-.102.16c-.384.163-1.695.768-2.239 1.524-1.39 1.934-2.45 4.7-4.826 4.7h-9.902c-3.512 0-6.354-2.853-6.354-6.376v-.114a.17.17 0 0 1 .171-.167h5.518c.11 0 .19.099.182.209-.042.357.027.726.198 1.06a1.94 1.94 0 0 0 1.74 1.08h2.732V23.24H16.82a.175.175 0 0 1-.14-.273 20.887 20.887 0 0 0 1.083-1.714c.247-.433.486-.897.68-1.36.038-.084.068-.171.103-.255.053-.148.106-.289.144-.426.038-.117.072-.239.103-.353.09-.395.129-.813.129-1.246 0-.171-.008-.35-.023-.517a6.939 6.939 0 0 0-.053-.559c-.015-.163-.046-.327-.076-.494a10.282 10.282 0 0 0-.156-.74l-.023-.096c-.045-.17-.087-.33-.14-.501a18.721 18.721 0 0 0-.521-1.54 8.252 8.252 0 0 0-.224-.562c-.114-.281-.232-.536-.338-.775a5.642 5.642 0 0 1-.149-.312c-.053-.114-.106-.228-.163-.338-.038-.083-.084-.163-.114-.24l-.334-.615c-.046-.083.03-.186.121-.16l2.09.567h.015l.274.08.304.083.11.03V9.688c0-.6.479-1.087 1.076-1.087.296 0 .566.122.756.32.194.197.315.467.315.767v1.843l.224.06c.016.008.035.016.05.027.053.038.133.099.232.175.08.06.163.137.262.217.201.163.444.372.707.611.068.061.136.122.201.187.338.315.718.684 1.083 1.094.103.118.201.232.304.357.099.126.209.247.3.369.126.163.255.334.373.513.053.083.117.17.167.254.152.225.281.456.406.688.054.107.107.224.152.338.141.312.251.627.32.947.022.068.038.14.045.209v.015c.023.091.03.19.038.292.03.323.015.65-.053.977a4.37 4.37 0 0 1-.114.407c-.05.133-.095.27-.156.402-.118.27-.254.544-.418.795-.053.095-.118.193-.178.288-.069.1-.141.194-.202.285a6.16 6.16 0 0 1-.273.35c-.084.114-.168.228-.263.33-.129.156-.254.3-.387.441-.076.092-.16.187-.247.27-.084.095-.171.179-.247.255-.133.133-.24.232-.33.319l-.217.194a.16.16 0 0 1-.114.045h-1.665v2.132h2.094c.467 0 .912-.163 1.273-.471.122-.106.657-.57 1.292-1.27a.15.15 0 0 1 .08-.049l5.78-1.672a.17.17 0 0 1 .216.164v1.223Z"
                  ></path></svg
              ></a>
            </li>
          </ul>
        </div>
        <div class="lg:hidden z-50">
          <div class="single-small flex items-center">
            <button
              @click="showMenu = true"
              class="hamburger single-small single-small--magnetic text-black"
              type="button"
            >
              <img src="../../src/assets/img/menu.png" class="w-7">
            </button>
          </div>
          <div
            v-if="showMenu"
            class="
              lg:hidden
              w-screen
              items-start
              h-screen
              flex flex-col
              fixed
              top-0
              px-6
              -ml-5
              pt-10
              bg-white
              hover:text-white bg-opacity-70
              backdrop-blur-lg
              cursor-pointer
              will-change-opacity
              overflow-scroll
              z-90
              font-bold
              tracking-wider
            "
            style="opacity: 1"
          >
            <div class="flex justify-between w-full">
              <div class="w-9" @click="showMenu = false">
                <img src="../../src/assets/svg/close.svg" class="w-full" />
              </div>
              <div>
                <a class="w-min-content" href="/">
                  <div
                    class="
                      hover:bg-black
                      hover:text-black hover:bg-opacity-20
                      bg-white
                      p-2
                      px-4
                      rounded-lg
                      text-black
                      opacity-80
                      text-3xl
                    "
                    style="font-family: 'Knewave', cursive"
                  >
                    Zukiblowon
                  </div>
                </a>
              </div>
            </div>
            <ul class="text-xl w-full uppercase font-900 pt-10">
              <li class="border-b border-black border-opacity-10">
                <a
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  href="/sneak_peeks"
                  >Sneak Peeks
                </a>
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  href="/roadmap"
                  >Roadmap
                </a>
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  href="/team"
                  >Team
                </a>
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  href="/support"
                  >Support
                </a>
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  href="/merch"
                  >Merch
                </a>
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  target="_blank"
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  rel="noreferrer"
                  ><div class="w-full">
                    <div>
                      <div class="w-full">
                        <button
                          class="
                            text-black
                            font-bold
                            text-left
                            item-center
                            w-full
                            outline-none
                          "
                          id="headlessui-menu-button-2"
                          type="button"
                          aria-haspopup="true"
                          aria-expanded="false"
                        >
                          LANGUAGE
                        </button>
                      </div>
                    </div>
                  </div></a
                >
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  href=""
                  target="_blank"
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  rel="noreferrer"
                  >twitter
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="ml-auto fill-current stroke-current h-4 w-4"
                    viewBox="0 0 40 40"
                  >
                    <path
                      d="M38.526 8.625a15.199 15.199 0 01-4.373 1.198 7.625 7.625 0 003.348-4.211 15.25 15.25 0 01-4.835 1.847 7.6 7.6 0 00-5.557-2.404c-4.915 0-8.526 4.586-7.416 9.346-6.325-.317-11.934-3.347-15.69-7.953C2.01 9.869 2.97 14.345 6.358 16.612a7.58 7.58 0 01-3.446-.953c-.084 3.527 2.444 6.826 6.105 7.56a7.63 7.63 0 01-3.438.13 7.618 7.618 0 007.112 5.286A15.306 15.306 0 011.42 31.79a21.55 21.55 0 0011.67 3.42c14.134 0 22.12-11.937 21.637-22.643a15.499 15.499 0 003.799-3.941z"
                    ></path></svg
                ></a>
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  href=""
                  target="_blank"
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  rel="noreferrer"
                  >instagram
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="ml-auto fill-current stroke-current h-4 w-4"
                    viewBox="0 0 40 40"
                  >
                    <path
                      d="M27.524 1.79c3.334.17 5.899 1.11 7.694 2.992 1.796 1.88 2.822 4.36 2.993 7.694 0 1.314.078 3.651.085 7.089v2.108c-.002 2.768-.014 4.702-.085 5.85-.171 3.335-1.112 5.9-2.993 7.695-1.88 1.796-4.36 2.822-7.694 2.993-1.15.071-3.143.083-5.88.085h-3.317c-2.768-.002-4.702-.014-5.85-.085-3.335-.171-5.9-1.112-7.695-2.993-1.796-1.795-2.822-4.36-2.993-7.694-.065-1.04-.08-2.771-.084-5.118v-4.812c.004-2.347.02-4.078.084-5.118.171-3.334 1.112-5.899 2.993-7.694 1.795-1.796 4.36-2.822 7.694-2.993 1.04-.065 2.771-.08 5.118-.084h4.847c2.361.004 4.043.02 5.083.084Zm-7.61 8.805c-2.65 0-4.873.94-6.668 2.736C11.45 15.212 10.51 17.35 10.51 20c0 2.65.94 4.873 2.736 6.669 1.88 1.795 4.018 2.736 6.668 2.736 2.65 0 4.874-.94 6.67-2.736 1.795-1.881 2.735-4.019 2.735-6.669 0-2.65-.94-4.873-2.736-6.669-1.795-1.88-4.018-2.736-6.669-2.736Zm0 3.25c1.71 0 3.164.598 4.36 1.795A6.076 6.076 0 0 1 26.07 20c0 1.624-.598 3.078-1.795 4.275-1.197 1.197-2.65 1.795-4.36 1.795-1.71 0-3.164-.598-4.36-1.795-1.198-1.112-1.796-2.565-1.796-4.275 0-1.71.598-3.163 1.795-4.36 1.197-1.197 2.65-1.796 4.36-1.796Zm9.833-5.9c-.599 0-1.112.257-1.54.684-.427.427-.683.94-.683 1.539 0 .598.256 1.111.684 1.539.427.427.94.684 1.539.684.598 0 1.111-.257 1.538-.684.428-.428.684-.94.684-1.54 0-.598-.256-1.11-.684-1.538-.427-.427-.94-.684-1.538-.684Z"
                    ></path></svg
                ></a>
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  href=""
                  target="_blank"
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  rel="noreferrer"
                  >discord
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="ml-auto fill-current stroke-current h-4 w-4"
                    viewBox="0 0 40 40"
                  >
                    <path
                      d="M33.567 7.554a32.283 32.283 0 00-7.969-2.472.12.12 0 00-.128.06c-.344.613-.725 1.411-.992 2.039a29.804 29.804 0 00-8.95 0 20.625 20.625 0 00-1.008-2.038.126.126 0 00-.128-.06 32.194 32.194 0 00-7.968 2.47.114.114 0 00-.053.046C1.296 15.18-.095 22.577.588 29.88c.003.036.023.07.05.092 3.349 2.459 6.593 3.952 9.776 4.941a.127.127 0 00.137-.045 23.203 23.203 0 002-3.253.124.124 0 00-.068-.172A21.379 21.379 0 019.43 29.99a.126.126 0 01-.012-.209c.205-.153.41-.313.607-.475a.121.121 0 01.126-.017c6.407 2.925 13.343 2.925 19.675 0a.12.12 0 01.128.015c.196.162.4.324.608.477a.126.126 0 01-.011.209c-.975.57-1.99 1.051-3.055 1.454a.125.125 0 00-.067.173 26.052 26.052 0 001.998 3.252c.031.043.087.062.138.046 3.199-.99 6.442-2.482 9.79-4.941a.126.126 0 00.052-.09c.816-8.445-1.368-15.78-5.789-22.283a.1.1 0 00-.05-.046zm-20.06 17.88c-1.928 0-3.517-1.771-3.517-3.946 0-2.175 1.558-3.946 3.518-3.946 1.975 0 3.549 1.787 3.518 3.946 0 2.175-1.558 3.946-3.518 3.946zm13.01 0c-1.93 0-3.52-1.771-3.52-3.946 0-2.175 1.56-3.946 3.52-3.946 1.974 0 3.548 1.787 3.517 3.946 0 2.175-1.543 3.946-3.518 3.946z"
                    ></path></svg
                ></a>
              </li>
              <li class="border-b border-black border-opacity-10">
                <a
                  href=""
                  target="_blank"
                  class="
                    py-3
                    w-full
                    items-center
                    block
                    relative
                    flex
                    text-black
                  "
                  rel="noreferrer"
                  >opensea
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="ml-auto fill-current stroke-current h-4 w-4"
                    viewBox="0 0 40 40"
                  >
                    <path
                      d="M20 1C9.508 1 1 9.508 1 20s8.508 19 19 19 19-8.508 19-19S30.496 1 20 1Zm-9.625 19.638.08-.129 4.943-7.733c.072-.11.243-.099.297.023.824 1.85 1.539 4.153 1.204 5.586-.14.589-.532 1.387-.973 2.124a3.808 3.808 0 0 1-.186.316.168.168 0 0 1-.14.072h-5.081a.168.168 0 0 1-.144-.259Zm22.028 2.66a.172.172 0 0 1-.102.16c-.384.163-1.695.768-2.239 1.524-1.39 1.934-2.45 4.7-4.826 4.7h-9.902c-3.512 0-6.354-2.853-6.354-6.376v-.114a.17.17 0 0 1 .171-.167h5.518c.11 0 .19.099.182.209-.042.357.027.726.198 1.06a1.94 1.94 0 0 0 1.74 1.08h2.732V23.24H16.82a.175.175 0 0 1-.14-.273 20.887 20.887 0 0 0 1.083-1.714c.247-.433.486-.897.68-1.36.038-.084.068-.171.103-.255.053-.148.106-.289.144-.426.038-.117.072-.239.103-.353.09-.395.129-.813.129-1.246 0-.171-.008-.35-.023-.517a6.939 6.939 0 0 0-.053-.559c-.015-.163-.046-.327-.076-.494a10.282 10.282 0 0 0-.156-.74l-.023-.096c-.045-.17-.087-.33-.14-.501a18.721 18.721 0 0 0-.521-1.54 8.252 8.252 0 0 0-.224-.562c-.114-.281-.232-.536-.338-.775a5.642 5.642 0 0 1-.149-.312c-.053-.114-.106-.228-.163-.338-.038-.083-.084-.163-.114-.24l-.334-.615c-.046-.083.03-.186.121-.16l2.09.567h.015l.274.08.304.083.11.03V9.688c0-.6.479-1.087 1.076-1.087.296 0 .566.122.756.32.194.197.315.467.315.767v1.843l.224.06c.016.008.035.016.05.027.053.038.133.099.232.175.08.06.163.137.262.217.201.163.444.372.707.611.068.061.136.122.201.187.338.315.718.684 1.083 1.094.103.118.201.232.304.357.099.126.209.247.3.369.126.163.255.334.373.513.053.083.117.17.167.254.152.225.281.456.406.688.054.107.107.224.152.338.141.312.251.627.32.947.022.068.038.14.045.209v.015c.023.091.03.19.038.292.03.323.015.65-.053.977a4.37 4.37 0 0 1-.114.407c-.05.133-.095.27-.156.402-.118.27-.254.544-.418.795-.053.095-.118.193-.178.288-.069.1-.141.194-.202.285a6.16 6.16 0 0 1-.273.35c-.084.114-.168.228-.263.33-.129.156-.254.3-.387.441-.076.092-.16.187-.247.27-.084.095-.171.179-.247.255-.133.133-.24.232-.33.319l-.217.194a.16.16 0 0 1-.114.045h-1.665v2.132h2.094c.467 0 .912-.163 1.273-.471.122-.106.657-.57 1.292-1.27a.15.15 0 0 1 .08-.049l5.78-1.672a.17.17 0 0 1 .216.164v1.223Z"
                    ></path></svg
                ></a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

