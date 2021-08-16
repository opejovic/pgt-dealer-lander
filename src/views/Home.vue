<template>
  <div class="min-h-screen justify-center relative mx-auto">
    <!-- Header -->
    <header>
      <div
        class="
          flex
          justify-between
          align-middle
          items-center
          lg:px-36
          px-6
          py-8
          max-w-screen-2xl
          mx-auto
        "
      >
        <div>
          <svg
            class="text-pgtBlue md:w-48 w-24"
            fill="currentColor"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 57.5 40"
          >
            <path
              d="M46.5 31.5h-.3V31h.4c.2 0 .4.1.4.3 0 .2-.3.2-.5.2m.7-.3c0-.3-.2-.4-.5-.4h-.6v1.6h.2v-.7h.3l.5.7h.2l-.5-.7c.2-.1.4-.2.4-.5"
            ></path>
            <path
              d="M46.5 32.8c-.7 0-1.2-.5-1.2-1.2s.5-1.2 1.2-1.2 1.2.5 1.2 1.2-.5 1.2-1.2 1.2m0-2.6c-.8 0-1.4.6-1.4 1.4s.6 1.4 1.4 1.4 1.4-.6 1.4-1.4-.6-1.4-1.4-1.4"
            ></path>
            <path
              d="M56.8 8.6c-1.4-.1-6.1-.4-8.7-.4h-.3v20.7h-3.2v-5.7h-3.7v-7.4l.3.3.1.1h1.1v-.3c.2-1.1.7-2.2 1.4-3.3l.2-.4-.4-.2c-.9-.4-1.9-.7-2.8-.9v-3h-.3c-3 0-7.7.3-9 .4v-2h25.3v2.1zm-13 20.2h-3v-4.9h3v4.9zm0 4c-4 .7-8.6 1.5-13.1 1.5-9.1 0-19.8-2.9-19.8-11.1 0-1.5.3-3 1-4.3 3.4-.2 6.5-.7 8.7-1.9-1.3 1.9-2 4.1-2 6.3 0 6.1 4.7 9.7 12.5 9.7 2.1 0 4-.3 5.7-1l.2-.1v-6.4h-4.8v-1.6h8v5.6h3.7l-.1 3.3zM7.9 18.2h-.3v10.1H.7V6h12.1c6.6 0 10.1 1.6 10.4 4.9-2.9.6-5.5 1.6-7.5 2.9.2-.6.4-1.2.4-1.9 0-2.8-2.1-4.8-5-4.8H7.6v10H8c1.1 0 2.3-.1 3.4-.2.5-.1.9-.2 1.3-.4-.4.5-.8 1.1-1.2 1.7H7.9m15.3-6.6c-.2 4-3.4 6-10.9 6.5 2-3.1 5.7-5.4 10.9-6.5m-12 4.5c-.9.1-1.9.2-2.9.2V7.8h2.8c2.5 0 4.3 1.7 4.3 4.1 0 2.2-1.5 3.7-4.2 4.2m25.1 10v5.2c-1.5.6-3.3.8-5.2.8-7.5 0-11.8-3.3-11.8-9 0-7.2 6.1-10.4 12.2-10.4 3.4 0 6.5.9 8.6 2.5v7.9h-8.7v3h4.9zM40.9 12c.7.2 1.5.4 2.2.7-.6.9-1 1.9-1.2 2.9h-.3c-.2-.2-.5-.4-.7-.6v-3zm-.7-.2v2.6c-2.3-1.5-5.3-2.3-8.6-2.3-3.5 0-6.3.9-8.3 2.3.4-.8.7-1.8.7-2.9 2.3-.4 4.8-.7 7.5-.7 3.1 0 6 .3 8.7 1m-9.4-6v3.6h.4c.1 0 5.5-.4 9-.5v2.2c-2.7-.7-5.6-1-8.7-1-2.7 0-5.2.2-7.5.7-.3-2.6-2.5-5.5-11.1-5.5H0V29h8.3V18.9c1 0 1.9 0 2.8-.1-.6 1.3-.9 2.7-.9 4.2 0 7.2 8 11.8 20.5 11.8 4.7 0 9.5-.8 13.5-1.5l.3-.1v-3.8h3.9V8.8c3.1 0 8.6.5 8.7.5h.4V5.8H30.8z"
            ></path>
          </svg>
        </div>
        <div class="flex justify-end items-center space-x-4">
          <button
            class="
              w-20
              h-20
              lg:w-64
              rounded-xl
              bg-pgtGreen
              text-white
              px-6
              text-2xl
              font-bold
              flex
              items-center
              justify-center
            "
          >
            <svg
              class="h-8 w-8"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M6.62 10.79C8.06 13.62 10.38 15.93 13.21 17.38L15.41 15.18C15.68 14.91 16.08 14.82 16.43 14.94C17.55 15.31 18.76 15.51 20 15.51C20.55 15.51 21 15.96 21 16.51V20C21 20.55 20.55 21 20 21C10.61 21 3 13.39 3 4C3 3.45 3.45 3 4 3H7.5C8.05 3 8.5 3.45 8.5 4C8.5 5.25 8.7 6.45 9.07 7.57C9.18 7.92 9.1 8.31 8.82 8.59L6.62 10.79Z"
              />
            </svg>

            <span class="ml-3 hidden lg:block">321-123-456</span>
          </button>
          <button
            class="
              w-20
              h-20
              lg:w-64
              rounded-xl
              bg-pgtGray
              text-white
              px-6
              text-2xl
              font-bold
              flex
              items-center
              justify-center
            "
          >
            <svg
              class="h-8 w-8"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M12 2C8.13 2 5 5.13 5 9C5 14.25 12 22 12 22C12 22 19 14.25 19 9C19 5.13 15.87 2 12 2ZM12 11.5C10.62 11.5 9.5 10.38 9.5 9C9.5 7.62 10.62 6.5 12 6.5C13.38 6.5 14.5 7.62 14.5 9C14.5 10.38 13.38 11.5 12 11.5Z"
              />
            </svg>

            <span class="ml-3 hidden lg:block">Directions</span>
          </button>
        </div>
      </div>

      <!-- banner image  -->
      <div :style="bannerStyle"></div>
    </header>

    <!-- sub banner image pgt test dealer -->
    <main class="w-full px-4 md:px-10 lg:px-36 mx-auto max-w-screen-2xl">
      <div class="bg-pgtGray bg-opacity-90 -mt-16 text-white">
        <div class="lg:flex align-middle px-10 py-4 pt-10 mx-auto text-justify">
          <div class="w-full flex justify-center lg:block lg:w-auto">
            <svg
              class="text-white"
              width="184"
              height="95"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 57.5 40"
            >
              <path
                d="M46.5 31.5h-.3V31h.4c.2 0 .4.1.4.3 0 .2-.3.2-.5.2m.7-.3c0-.3-.2-.4-.5-.4h-.6v1.6h.2v-.7h.3l.5.7h.2l-.5-.7c.2-.1.4-.2.4-.5"
              ></path>
              <path
                d="M46.5 32.8c-.7 0-1.2-.5-1.2-1.2s.5-1.2 1.2-1.2 1.2.5 1.2 1.2-.5 1.2-1.2 1.2m0-2.6c-.8 0-1.4.6-1.4 1.4s.6 1.4 1.4 1.4 1.4-.6 1.4-1.4-.6-1.4-1.4-1.4"
              ></path>
              <path
                d="M56.8 8.6c-1.4-.1-6.1-.4-8.7-.4h-.3v20.7h-3.2v-5.7h-3.7v-7.4l.3.3.1.1h1.1v-.3c.2-1.1.7-2.2 1.4-3.3l.2-.4-.4-.2c-.9-.4-1.9-.7-2.8-.9v-3h-.3c-3 0-7.7.3-9 .4v-2h25.3v2.1zm-13 20.2h-3v-4.9h3v4.9zm0 4c-4 .7-8.6 1.5-13.1 1.5-9.1 0-19.8-2.9-19.8-11.1 0-1.5.3-3 1-4.3 3.4-.2 6.5-.7 8.7-1.9-1.3 1.9-2 4.1-2 6.3 0 6.1 4.7 9.7 12.5 9.7 2.1 0 4-.3 5.7-1l.2-.1v-6.4h-4.8v-1.6h8v5.6h3.7l-.1 3.3zM7.9 18.2h-.3v10.1H.7V6h12.1c6.6 0 10.1 1.6 10.4 4.9-2.9.6-5.5 1.6-7.5 2.9.2-.6.4-1.2.4-1.9 0-2.8-2.1-4.8-5-4.8H7.6v10H8c1.1 0 2.3-.1 3.4-.2.5-.1.9-.2 1.3-.4-.4.5-.8 1.1-1.2 1.7H7.9m15.3-6.6c-.2 4-3.4 6-10.9 6.5 2-3.1 5.7-5.4 10.9-6.5m-12 4.5c-.9.1-1.9.2-2.9.2V7.8h2.8c2.5 0 4.3 1.7 4.3 4.1 0 2.2-1.5 3.7-4.2 4.2m25.1 10v5.2c-1.5.6-3.3.8-5.2.8-7.5 0-11.8-3.3-11.8-9 0-7.2 6.1-10.4 12.2-10.4 3.4 0 6.5.9 8.6 2.5v7.9h-8.7v3h4.9zM40.9 12c.7.2 1.5.4 2.2.7-.6.9-1 1.9-1.2 2.9h-.3c-.2-.2-.5-.4-.7-.6v-3zm-.7-.2v2.6c-2.3-1.5-5.3-2.3-8.6-2.3-3.5 0-6.3.9-8.3 2.3.4-.8.7-1.8.7-2.9 2.3-.4 4.8-.7 7.5-.7 3.1 0 6 .3 8.7 1m-9.4-6v3.6h.4c.1 0 5.5-.4 9-.5v2.2c-2.7-.7-5.6-1-8.7-1-2.7 0-5.2.2-7.5.7-.3-2.6-2.5-5.5-11.1-5.5H0V29h8.3V18.9c1 0 1.9 0 2.8-.1-.6 1.3-.9 2.7-.9 4.2 0 7.2 8 11.8 20.5 11.8 4.7 0 9.5-.8 13.5-1.5l.3-.1v-3.8h3.9V8.8c3.1 0 8.6.5 8.7.5h.4V5.8H30.8z"
              ></path>
            </svg>
          </div>
          <div>
            <h1 class="text-2xl font-bold text-center lg:text-left">
              PGT Test Dealer
            </h1>
            <p class="mt-2">
              At PGT® Windows + Doors, protecting families is our purpose — and
              our promise. We build windows and doors for every day and once in
              a lifetime, providing reliable products and peace of mind to our
              customers.
            </p>
          </div>
        </div>
        <!-- Buttons -->
        <div
          class="
            flex flex-col
            xl:flex-row
            justify-center
            items-center
            xl:space-x-4
            pt-4
            pb-10
            px-4
            xl:px-0
          "
        >
          <button
            class="
              rounded-xl
              bg-pgtGreen
              text-white
              px-6
              py-4
              text-xl
              md:text-2xl
              font-bold
              h-20
              w-full
              md:w-80
              mb-2
              xl:mb-0
            "
          >
            Send Message
          </button>
          <button
            class="
              rounded-xl
              bg-white
              text-pgtGreen
              px-6
              py-4
              text-xl
              md:text-2xl
              font-bold
              h-20
              w-full
              md:w-80
            "
          >
            Get Quote
          </button>
        </div>
      </div>

      <section class="pt-20">
        <div
          class="
            w-4/6
            lg:w-7/12
            bg-gray-200
            pt-10
            pb-24
            px-10
            text-3xl
            font-bold
            text-pgtGreen
          "
        >
          PGT Products
        </div>

        <splide class="-mt-28" :options="slidesOptions">
          <splide-slide
            class="rounded-none"
            v-for="product in products"
            :key="product.id"
          >
            <img class="w-full relative" :src="product.src" />
            <div
              class="
                absolute
                bg-pgtGreen
                w-full
                bottom-0
                bg-opacity-50
                text-white
                flex
                justify-start
                px-2
                py-2
                items-center
              "
            >
              Description
            </div>
          </splide-slide>
        </splide>
      </section>

      <!-- What our trusted clients say / Testimonials -->
      <section class="pt-16 mx-auto">
        <h1 class="text-4xl font-bold text-center pb-16 text-pgtGray">
          What Our Trusted Clients Say
        </h1>

        <splide class="-mt-20" :options="testimonialsSlideOptions">
          <splide-slide
            class="bg-gray-200 w-full rounded-none"
            v-for="(testimonial, index) in testimonials"
            :key="`${index}_${testimonial.customer}_md_up`"
          >
            <div class="h-20 bg-white"></div>
            <div
              class="-top-16 left-10 text-pgtGreen"
              style="position: absolute; font-size: 16rem"
            >
              “
            </div>
            <div class="px-10 mx-auto pt-16 pb-10">
              <p class="mb-4 text-pgtGray max-h-24 overflow-y-auto">
                {{ testimonial.text }}
              </p>
              <p class="text-pgtGray font-bold italic">
                {{ testimonial.client }}
              </p>
            </div>
          </splide-slide>
        </splide>
      </section>

      <!-- Portfolio  -->
      <section class="pt-20">
        <div
          class="
            ml-auto
            w-4/6
            lg:w-7/12
            bg-gray-200
            pt-10
            pb-24
            px-10
            text-3xl
            font-bold
            text-pgtGreen
          "
        >
          Portfolio
        </div>
        <splide class="-mt-28" :options="slidesOptions">
          <splide-slide
            class="rounded-none"
            v-for="item in portfolio"
            :key="item.id"
          >
            <img class="w-full" :src="item.src" />
          </splide-slide>
        </splide>
      </section>

      <section class="pt-16">
        <h1 class="text-4xl font-bold text-center pb-16 text-pgtGray">
          Check Out These Other Brands
        </h1>

        <splide :options="otherBrandSlideOptions">
          <splide-slide
            class="rounded-none flex justify-center mx-auto"
            v-for="item in otherBrands"
            :key="item.id"
          >
            <figure class="flex flex-col items-start">
              <div class="h-16 mx-auto">
                <img class="w-32" :src="item.src" />
              </div>
              <p
                class="
                  text-center text-sm
                  font-semibold
                  text-gray-500
                  content-start
                "
              >
                {{ item.description }}
              </p>
            </figure>
          </splide-slide>
        </splide>
      </section>
    </main>

    <footer class="w-full bg-gray-200 text-black relative">
      <section data-name="chat" class="relative w-full h-full">
        <button
          @click="toggleChat"
          id="chat-button"
          type="button"
          class="
            h-20
            w-20
            bg-pgtGreen
            absolute
            right-10
            -top-10
            flex
            justify-center
            items-center
            rounded-full
          "
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-12 w-12 text-white z-0 pointer-events-none"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z"
              clip-rule="evenodd"
            />
          </svg>
        </button>

        <!-- chat -->
        <div
          v-show="chatOpen"
          class="
            shadow-2xl
            bg-white
            absolute
            bottom-20
            md:right-10
            right-0
            chat-popup
            z-50
          "
        >
          <div class="h-full w-full bg-white flex flex-col justify-between">
            <!-- chat header -->
            <div class="w-full bg-pgtGreen py-20 md:py-14 relative px-10">
              <div class="absolute top-12">
                <div class="flex justify-start space-x-4">
                  <div class="h-14 w-14 md:h-32 md:w-32 rounded-full px-4 md:px-0 avatar-bg" :style="`background: url(${require('@/assets/images/avatarPlaceholder.png')});`"></div>
                  <div class="text-white -mt-1">
                    <h1 class="text-sm md:text-xl font-semibold" style="overflow: hidden;
                        white-space: nowrap;
                        text-overflow: ellipsis;
                        max-width: 150px;">Pgt test dealer
                    </h1>
                    <div class="flex justify-start items-center space-x-2 mt-1">
                      <span class="h-2 w-2 bg-green-300 rounded-full"></span>
                      <span class="text-sm font-light">Online</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- chat body -->
            <div class="ml-10 pr-16 overflow-y-auto mt-20 pb-10">
              <div class="w-full flex flex-1 justify-start items-start">
                <div class="px-4 h-10 w-10 rounded-full mr-3 avatar-bg" :style="`background: url(${require('@/assets/images/avatarPlaceholder.png')});`"></div>
                <div class="w-full">
                  <p class="mt-1">Pgt Test Dealer</p>
                  <div class="py-3 px-3 text-sm rounded-lg bg-gray-200 mt-2">
                    <p>Hi, how can I help you today?</p>
                  </div>
                </div>
              </div>

              <div class="w-full flex justify-start items-start mt-4">
                <div class="w-full">
                  <p class="text-right">User</p>
                  <div
                    class="
                      py-3
                      px-3
                      text-sm
                      rounded-lg
                      bg-gray-400
                      text-white
                      mt-2
                    "
                  >
                    <p>I need assistance please.</p>
                  </div>
                </div>
              </div>
            </div>

            <!-- chat message box -->
            <div
              class="
                w-full
                h-28
                bg-gray-200
                flex
                justify-between
                items-start
                pl-10
                pr-16
              "
              style="min-height: 7rem"
            >
              <textarea
                class="bg-gray-200 w-3/5 text-sm outline-none mt-4"
                rows="3"
                placeholder="Send message"
              ></textarea>
              <button class="mr-4">
                <svg
                  class="text-pgtGreen h-8 mt-4"
                  viewBox="0 0 513 513"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M16.1769 464.429L496.177 256.429L16.1769 48.4288V208.429L336.177 256.429L16.1769 304.429V464.429Z"
                    fill="currentColor"
                  />
                </svg>
              </button>
            </div>
          </div>
        </div>
      </section>

      <div
        class="
          max-w-screen-2xl
          mx-auto
          lg:px-36
          px-6
          flex flex-col
          lg:flex-row
          items-center
          justify-between
          py-16
        "
      >
        <div class="mb-8 lg:mb-0">
          <!-- Logo -->
          <svg
            class="text-pgtBlue w-48"
            fill="currentColor"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 57.5 40"
          >
            <path
              d="M46.5 31.5h-.3V31h.4c.2 0 .4.1.4.3 0 .2-.3.2-.5.2m.7-.3c0-.3-.2-.4-.5-.4h-.6v1.6h.2v-.7h.3l.5.7h.2l-.5-.7c.2-.1.4-.2.4-.5"
            ></path>
            <path
              d="M46.5 32.8c-.7 0-1.2-.5-1.2-1.2s.5-1.2 1.2-1.2 1.2.5 1.2 1.2-.5 1.2-1.2 1.2m0-2.6c-.8 0-1.4.6-1.4 1.4s.6 1.4 1.4 1.4 1.4-.6 1.4-1.4-.6-1.4-1.4-1.4"
            ></path>
            <path
              d="M56.8 8.6c-1.4-.1-6.1-.4-8.7-.4h-.3v20.7h-3.2v-5.7h-3.7v-7.4l.3.3.1.1h1.1v-.3c.2-1.1.7-2.2 1.4-3.3l.2-.4-.4-.2c-.9-.4-1.9-.7-2.8-.9v-3h-.3c-3 0-7.7.3-9 .4v-2h25.3v2.1zm-13 20.2h-3v-4.9h3v4.9zm0 4c-4 .7-8.6 1.5-13.1 1.5-9.1 0-19.8-2.9-19.8-11.1 0-1.5.3-3 1-4.3 3.4-.2 6.5-.7 8.7-1.9-1.3 1.9-2 4.1-2 6.3 0 6.1 4.7 9.7 12.5 9.7 2.1 0 4-.3 5.7-1l.2-.1v-6.4h-4.8v-1.6h8v5.6h3.7l-.1 3.3zM7.9 18.2h-.3v10.1H.7V6h12.1c6.6 0 10.1 1.6 10.4 4.9-2.9.6-5.5 1.6-7.5 2.9.2-.6.4-1.2.4-1.9 0-2.8-2.1-4.8-5-4.8H7.6v10H8c1.1 0 2.3-.1 3.4-.2.5-.1.9-.2 1.3-.4-.4.5-.8 1.1-1.2 1.7H7.9m15.3-6.6c-.2 4-3.4 6-10.9 6.5 2-3.1 5.7-5.4 10.9-6.5m-12 4.5c-.9.1-1.9.2-2.9.2V7.8h2.8c2.5 0 4.3 1.7 4.3 4.1 0 2.2-1.5 3.7-4.2 4.2m25.1 10v5.2c-1.5.6-3.3.8-5.2.8-7.5 0-11.8-3.3-11.8-9 0-7.2 6.1-10.4 12.2-10.4 3.4 0 6.5.9 8.6 2.5v7.9h-8.7v3h4.9zM40.9 12c.7.2 1.5.4 2.2.7-.6.9-1 1.9-1.2 2.9h-.3c-.2-.2-.5-.4-.7-.6v-3zm-.7-.2v2.6c-2.3-1.5-5.3-2.3-8.6-2.3-3.5 0-6.3.9-8.3 2.3.4-.8.7-1.8.7-2.9 2.3-.4 4.8-.7 7.5-.7 3.1 0 6 .3 8.7 1m-9.4-6v3.6h.4c.1 0 5.5-.4 9-.5v2.2c-2.7-.7-5.6-1-8.7-1-2.7 0-5.2.2-7.5.7-.3-2.6-2.5-5.5-11.1-5.5H0V29h8.3V18.9c1 0 1.9 0 2.8-.1-.6 1.3-.9 2.7-.9 4.2 0 7.2 8 11.8 20.5 11.8 4.7 0 9.5-.8 13.5-1.5l.3-.1v-3.8h3.9V8.8c3.1 0 8.6.5 8.7.5h.4V5.8H30.8z"
            ></path>
          </svg>
        </div>

        <div class="flex space-x-2 items-center">
          <!-- Facebook -->
          <div>
            <a href="#">
              <svg
                class="bg-pgtGreen text-white h-12 w-12 p-3 rounded-full"
                width="26"
                height="26"
                viewBox="0 0 26 26"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <g clip-path="url(#clip0)">
                  <path
                    d="M18.4595 14.3342L19.1539 9.80975H14.8126V6.87372C14.8126 5.63593 15.419 4.42938 17.3633 4.42938H19.337V0.577332C19.337 0.577332 17.546 0.271667 15.8336 0.271667C12.2584 0.271667 9.92145 2.43866 9.92145 6.36151V9.80975H5.94733V14.3342H9.92145V25.2717H14.8126V14.3342H18.4595Z"
                  />
                </g>
                <defs>
                  <clipPath id="clip0">
                    <rect
                      width="25"
                      height="25"
                      fill="white"
                      transform="translate(0.142151 0.271667)"
                    />
                  </clipPath>
                </defs>
              </svg>
            </a>
          </div>

          <!-- Twitter -->
          <div>
            <a href="#">
              <svg
                class="bg-pgtGreen text-white h-12 w-12 p-3 rounded-full"
                width="26"
                height="26"
                viewBox="0 0 26 26"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <g clip-path="url(#clip0)">
                  <path
                    d="M22.5723 7.6797C22.5882 7.90177 22.5882 8.12389 22.5882 8.34596C22.5882 15.1194 17.4328 22.924 8.01017 22.924C5.10724 22.924 2.41056 22.0832 0.142151 20.6239C0.554602 20.6714 0.951135 20.6873 1.37946 20.6873C3.77472 20.6873 5.9797 19.8783 7.74049 18.4983C5.48795 18.4506 3.60026 16.9754 2.94987 14.9449C3.26715 14.9925 3.58439 15.0242 3.91754 15.0242C4.37755 15.0242 4.83761 14.9608 5.26588 14.8498C2.91818 14.3738 1.15734 12.3117 1.15734 9.8212V9.75778C1.83942 10.1385 2.63263 10.3764 3.4733 10.4081C2.09323 9.48805 1.18907 7.91764 1.18907 6.14098C1.18907 5.18922 1.44283 4.31676 1.88702 3.55533C4.40924 6.66447 8.2005 8.69489 12.4517 8.917C12.3724 8.53629 12.3248 8.13976 12.3248 7.74318C12.3248 4.91954 14.6091 2.61945 17.4485 2.61945C18.9238 2.61945 20.2563 3.2381 21.1922 4.23746C22.3502 4.01539 23.4606 3.58707 24.4441 3.00016C24.0633 4.1899 23.2544 5.18927 22.1916 5.82374C23.2227 5.71276 24.222 5.42716 25.1421 5.03063C24.4442 6.04581 23.5717 6.94996 22.5723 7.6797V7.6797Z"
                  />
                </g>
                <defs>
                  <clipPath id="clip0">
                    <rect
                      width="25"
                      height="25"
                      fill="white"
                      transform="translate(0.142151 0.271667)"
                    />
                  </clipPath>
                </defs>
              </svg>
            </a>
          </div>

          <!-- Instagram -->
          <div>
            <a href="#">
              <svg
                class="bg-pgtGreen text-white h-12 w-12 p-3 rounded-full"
                width="26"
                height="26"
                viewBox="0 0 26 26"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M12.647 7.15643C9.54157 7.15643 7.03668 9.66132 7.03668 12.7668C7.03668 15.8723 9.54157 18.3771 12.647 18.3771C15.7525 18.3771 18.2574 15.8723 18.2574 12.7668C18.2574 9.66132 15.7525 7.15643 12.647 7.15643ZM12.647 16.4142C10.6402 16.4142 8.99957 14.7785 8.99957 12.7668C8.99957 10.7551 10.6353 9.11932 12.647 9.11932C14.6588 9.11932 16.2945 10.7551 16.2945 12.7668C16.2945 14.7785 14.6539 16.4142 12.647 16.4142V16.4142ZM19.7955 6.92694C19.7955 7.65448 19.2095 8.23554 18.4869 8.23554C17.7593 8.23554 17.1783 7.6496 17.1783 6.92694C17.1783 6.20428 17.7642 5.61835 18.4869 5.61835C19.2095 5.61835 19.7955 6.20428 19.7955 6.92694ZM23.5113 8.25507C23.4283 6.50214 23.0279 4.9494 21.7437 3.6701C20.4644 2.39081 18.9117 1.99042 17.1588 1.90253C15.3521 1.79999 9.93707 1.79999 8.13043 1.90253C6.38239 1.98553 4.82965 2.38593 3.54547 3.66522C2.26129 4.94452 1.86578 6.49725 1.77789 8.25018C1.67535 10.0568 1.67535 15.4719 1.77789 17.2785C1.8609 19.0314 2.26129 20.5842 3.54547 21.8635C4.82965 23.1428 6.3775 23.5432 8.13043 23.631C9.93707 23.7336 15.3521 23.7336 17.1588 23.631C18.9117 23.548 20.4644 23.1476 21.7437 21.8635C23.023 20.5842 23.4234 19.0314 23.5113 17.2785C23.6138 15.4719 23.6138 10.0617 23.5113 8.25507V8.25507ZM21.1773 19.217C20.7964 20.174 20.0591 20.9113 19.0972 21.2971C17.6568 21.8683 14.2388 21.7365 12.647 21.7365C11.0552 21.7365 7.63239 21.8635 6.19684 21.2971C5.23981 20.9162 4.5025 20.1789 4.11676 19.217C3.54547 17.7765 3.67731 14.3586 3.67731 12.7668C3.67731 11.175 3.55035 7.75214 4.11676 6.31659C4.49762 5.35956 5.23492 4.62225 6.19684 4.23651C7.63727 3.66522 11.0552 3.79706 12.647 3.79706C14.2388 3.79706 17.6617 3.6701 19.0972 4.23651C20.0543 4.61737 20.7916 5.35468 21.1773 6.31659C21.7486 7.75702 21.6168 11.175 21.6168 12.7668C21.6168 14.3586 21.7486 17.7814 21.1773 19.217Z"
                />
              </svg>
            </a>
          </div>

          <!-- Youtube -->
          <div>
            <a href="#">
              <svg
                class="bg-pgtGreen text-white h-12 w-12 p-3 rounded-full"
                width="26"
                height="26"
                viewBox="0 0 26 26"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <g clip-path="url(#clip0)">
                  <path
                    d="M23.9987 7.04612C23.7261 6.01965 22.9229 5.21123 21.903 4.93688C20.0545 4.43835 12.6421 4.43835 12.6421 4.43835C12.6421 4.43835 5.22982 4.43835 3.38126 4.93688C2.36142 5.21127 1.55821 6.01965 1.2856 7.04612C0.790283 8.90667 0.790283 12.7885 0.790283 12.7885C0.790283 12.7885 0.790283 16.6704 1.2856 18.5309C1.55821 19.5574 2.36142 20.3321 3.38126 20.6065C5.22982 21.105 12.6421 21.105 12.6421 21.105C12.6421 21.105 20.0545 21.105 21.903 20.6065C22.9229 20.3321 23.7261 19.5574 23.9987 18.5309C24.494 16.6704 24.494 12.7885 24.494 12.7885C24.494 12.7885 24.494 8.90667 23.9987 7.04612V7.04612ZM10.2179 16.313V9.26409L16.4132 12.7886L10.2179 16.313V16.313Z"
                  />
                </g>
                <defs>
                  <clipPath id="clip0">
                    <rect
                      width="25"
                      height="25"
                      fill="white"
                      transform="translate(0.142151 0.271667)"
                    />
                  </clipPath>
                </defs>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import { Splide, SplideSlide } from "@splidejs/vue-splide";

export default {
  components: {
    Splide,
    SplideSlide,
  },

  name: "Home",

  data() {
    return {
      chatOpen: true,
      testimonials: [
        {
          client: "Lisa P.",
          text: "My home is almost completely silent after installing the impact windows and doors.",
        },
        {
          client: "Delilah B.",
          text: "It [impact products] lowered our insurance costs by more than $3,000 annually.",
        },
        {
          client: "Derreck O.",
          text: "My sliding glass door is like the door to a bank vault. I knew my family and all my belongings would be safe during the hurricane. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Velit debitis, a non esse laboriosam soluta quas eos, sapiente animi exercitationem quod optio nobis quaerat culpa dolor. Commodi, optio, consequatur similique, nostrum aliquam nam eum corrupti inventore nisi animi quis modi fuga reiciendis consequuntur? Qui iusto eius deleniti, recusandae consequatur suscipit velit architecto nam earum enim explicabo quia aut? Quibusdam suscipit temporibus similique veniam, nobis laboriosam tenetur alias magni modi, et sapiente, veritatis magnam laudantium minima. Quod, necessitatibus eveniet? Beatae veniam ducimus unde! Temporibus natus, incidunt esse ab distinctio corrupti aperiam, consequatur eligendi alias officiis culpa aliquid magnam? Ea, maxime quidem.",
        },
      ],

      products: [
        { id: "asda123", src: require("@/assets/images/image2.png") },
        { id: "asda124", src: require("@/assets/images/image3.png") },
        { id: "asda125", src: require("@/assets/images/winguard.png") },
        { id: "asda126", src: require("@/assets/images/image2.png") },
        { id: "asda127", src: require("@/assets/images/image3.png") },
        { id: "asda128", src: require("@/assets/images/winguard.png") },
      ],

      portfolio: [
        { id: "asda322", src: require("@/assets/images/image2.png") },
        { id: "asda534", src: require("@/assets/images/image3.png") },
        { id: "asda634", src: require("@/assets/images/winguard.png") },
        { id: "asda838", src: require("@/assets/images/image2.png") },
        { id: "asda001", src: require("@/assets/images/image3.png") },
        { id: "asda929", src: require("@/assets/images/winguard.png") },
      ],

      otherBrands: [
        {
          id: "a322",
          src: require("@/assets/images/cgilogo.png"),
          description:
            "This dealer also offers: CGI Impact Resistant Windows & Doors",
        },
        {
          id: "a326",
          src: require("@/assets/images/windoorlogo.png"),
          description: "This dealer also offers: Windoor",
        },
        {
          id: "a325",
          src: require("@/assets/images/ezblogo.png"),
          description: "This dealer also offers: Eze-Breeze Porch Enclosures",
        },
        {
          id: "a324",
          src: require("@/assets/images/ecologo.png"),
          description: "This dealer also offers: ECO",
        },
      ],

      slidesOptions: {
        type: "loop",
        perMove: 1,
        perPage: 3,
        breakpoints: {
          1024: {
            perPage: 1,
            height: 400,
            cover: true,
          },
          425: {
            perPage: 1,
            gap: 0,
            padding: 0,
            cover: true,
            heightRatio: 1,
            height: "100%",
          },
        },
        cover: true,
        height: 300,
        gap: "2rem",
        padding: "1rem",
        pagination: false,
      },

      testimonialsSlideOptions: {
        type: "slide",
        perMove: 1,
        perPage: 3,
        breakpoints: {
          1024: {
            perPage: 1,
            pagination: true,
          },
        },
        gap: "1rem",
        pagination: false,
        arrows: false,
        padding: {
          left: 0,
          right: 0,
        },
      },

      otherBrandSlideOptions: {
        type: "slide",
        perMove: 1,
        perPage: 4,
        breakpoints: {
          1024: {
            perPage: 1,
            pagination: true,
          },
        },
        gap: "1rem",
        pagination: false,
        arrows: false,
      },

      bannerStyle: {
        backgroundImage: `url(${require("@/assets/images/hero-img.png")})`,
        "background-repeat": "no-repeat",
        "background-position": "center",
        "background-size": "cover",
        "object-fit": "cover",
        "min-height": "581px",
      },
    };
  },

  methods: {
    toggleChat() {
      this.chatOpen = !this.chatOpen;
    },
  },
};
</script>

<style>
.clearfix:after {
  content: "\0020";
  display: block;
  height: 0;
  clear: both;
  visibility: hidden;
}
.pgt-dealer-banner {
  background: url("../assets/images/hero-img.png") no-repeat center;
  background-size: cover;
  height: 100%;
}

@keyframes splide-loading {
  0% {
    transform: rotate(0);
  }
  to {
    transform: rotate(1turn);
  }
}
.splide--draggable > .splide__track > .splide__list > .splide__slide {
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.splide--fade > .splide__track > .splide__list {
  display: block;
}
.splide--fade > .splide__track > .splide__list > .splide__slide {
  left: 0;
  opacity: 0;
  position: absolute;
  top: 0;
  z-index: 0;
}
.splide--fade > .splide__track > .splide__list > .splide__slide.is-active {
  opacity: 1;
  position: relative;
  z-index: 1;
}
.splide--rtl {
  direction: rtl;
}
.splide--ttb > .splide__track > .splide__list {
  display: block;
}
.splide--ttb > .splide__pagination {
  width: auto;
}
.splide__container {
  box-sizing: border-box;
  position: relative;
}
.splide__list {
  margin: 0 !important;
  padding: 0 !important;
  width: max-content;
  will-change: transform;
}
.splide.is-active .splide__list {
  display: -ms-flexbox;
  display: flex;
}
.splide__pagination {
  -ms-flex-align: center;
  align-items: center;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -ms-flex-pack: center;
  justify-content: center;
  margin: 0;
  width: 95%;
}
.splide__pagination li {
  display: inline-block;
  line-height: 1;
  list-style-type: none;
  margin: 0;
}
.splide {
  visibility: hidden;
}
.splide,
.splide__slide {
  outline: none;
  position: relative;
}
.splide__slide {
  box-sizing: border-box;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  list-style-type: none !important;
  margin: 0;
}
.splide__slide img {
  vertical-align: bottom;
}
.splide__slider {
  position: relative;
}
.splide__spinner {
  animation: splide-loading 1s linear infinite;
  border: 2px solid #999;
  border-radius: 50%;
  bottom: 0;
  display: inline-block;
  height: 20px;
  left: 0;
  margin: auto;
  position: absolute;
  right: 0;
  top: 0;
  width: 20px;
}
.splide__track {
  overflow-x: clip;
  overflow: hidden;
  position: relative;
  z-index: 0;
}
.splide__arrow {
  background: transparent;
  border: none;
  padding: 0;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  z-index: 1;
}
.splide__arrow svg {
  fill: #d9d9d6;
  height: 2.5em;
  transition: fill 0.2s linear;
  width: 2.5em;
}
.splide__arrow:hover {
  cursor: pointer;
}
.splide__arrow:hover svg {
  fill: #d9d9d6;
}
.splide__arrow:focus {
  outline: none;
}
.splide__arrow--prev {
  left: 1em;
}
.splide__arrow--prev svg {
  transform: scaleX(-1);
}
.splide__arrow--next {
  right: 1em;
}
.splide__slider > .splide__arrows .splide__arrow--prev {
  left: -2.5em;
}
.splide__slider > .splide__arrows .splide__arrow--next {
  right: -2.5em;
}
.splide__pagination {
  bottom: 1em;
  left: 50%;
  padding: 0;
  position: absolute;
  transform: translateX(-50%);
  z-index: 1;
}
.splide__pagination__page {
  background: rgb(235, 235, 235);
  border: none;
  border-radius: 2.5px;
  display: inline-block;
  height: 5px;
  margin: 3px;
  padding: 0;
  transition: all 0.2s linear;
  width: 12px;
  height: 12px;
  border-radius: 50%;
}
.splide__pagination__page.is-active {
  background: #31373b;
}
.splide__pagination__page:hover {
  background: #31373b;
  cursor: pointer;
}
.splide__pagination__page:focus {
  outline: none;
}
.splide__progress__bar {
  background: #d9d9d6;
  height: 3px;
  width: 0;
}
.splide {
  padding: 3em;
}
.splide__slide {
  border-radius: 4px;
}
.splide__spinner {
  border: 2px solid #d9d9d6;
  border-left-color: transparent;
}
.splide--nav > .splide__track > .splide__list > .splide__slide {
  border: 3px solid #fff;
  border-radius: 4px;
  cursor: pointer;
  opacity: 0.7;
}
.splide--nav > .splide__track > .splide__list > .splide__slide.is-active {
  border-color: #31373b;
  opacity: 1;
}
.splide--nav > .splide__track > .splide__list > .splide__slide:focus {
  outline: none;
}
.splide--rtl > .splide__arrows .splide__arrow--prev,
.splide--rtl > .splide__track > .splide__arrows .splide__arrow--prev {
  left: auto;
  right: 1em;
}
.splide--rtl > .splide__arrows .splide__arrow--prev svg,
.splide--rtl > .splide__track > .splide__arrows .splide__arrow--prev svg {
  transform: scaleX(1);
}
.splide--rtl > .splide__arrows .splide__arrow--next,
.splide--rtl > .splide__track > .splide__arrows .splide__arrow--next {
  left: 1em;
  right: auto;
}
.splide--rtl > .splide__arrows .splide__arrow--next svg,
.splide--rtl > .splide__track > .splide__arrows .splide__arrow--next svg {
  transform: scaleX(-1);
}
.splide--ttb > .splide__arrows .splide__arrow,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow {
  left: 50%;
  transform: translate(-50%);
}
.splide--ttb > .splide__arrows .splide__arrow--prev,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow--prev {
  top: 1em;
}
.splide--ttb > .splide__arrows .splide__arrow--prev svg,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow--prev svg {
  transform: rotate(-90deg);
}
.splide--ttb > .splide__arrows .splide__arrow--next,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow--next {
  bottom: 1em;
  top: auto;
}
.splide--ttb > .splide__arrows .splide__arrow--next svg,
.splide--ttb > .splide__track > .splide__arrows .splide__arrow--next svg {
  transform: rotate(90deg);
}
.splide--ttb > .splide__pagination {
  bottom: 50%;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-direction: column;
  flex-direction: column;
  left: auto;
  right: 1em;
  transform: translateY(50%);
}
.splide--ttb > .splide__pagination .splide__pagination__page {
  height: 20px;
  width: 5px;
}

.chat-popup {
  width: 680px;
}

@media only screen and (max-width: 767px) {
  .chat-popup {
    width: 100%;
    right: 0;
  }
}

.avatar-bg {
  background-size: cover !important;
  background-repeat: no-repeat !important;
  background-position: top center !important;
}
</style>
