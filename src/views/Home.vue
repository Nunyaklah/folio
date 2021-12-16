<template>
  <div class="home font-body text-gray-800">
    <nav class="grid grid-cols-3 p-10">
      <div class="flex">
        <span
          ><svg
            class="w-5 h-5"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
            ></path></svg
        ></span>
        <span class="ml-3 font-bold">nunyaklah@gmail.com</span>
      </div>
      <div></div>
      <div class="px-4 cursor-pointer md:hidden" id="burger">
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
            d="M4 6h16M4 12h8m-8 6h16"
          ></path>
        </svg>
      </div>
      <div class="hidden md:block" id="menu">
        <ul class="grid md:grid-cols-4">
          <li>
            <a href="#works">Works</a>
          </li>
          <li>
            <a
              href="https://docs.google.com/document/d/1ZhEn85otVq396LA3DFnMZ47f_s81PCmhZ2lgzfSapS8/edit?usp=sharing"
              target="_blank"
              >Resume</a
            >
          </li>
          <li>
            <a href="#exp">Experience</a>
          </li>
          <li>
            <a href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="flex justify-center" data-aos="slide-down">
      <div class="bg-blue-100 rounded-full w-40">
        <img src="../assets/images/nunya.png" alt="Nunya" class="w-40" />
      </div>
    </div>
    <div class="flex justify-center pt-4">
      <p class="font-bold text-2xl">Hi, I'm Nunya Klah ✌</p>
    </div>
    <div
      class="
        flex
        justify-center
        pt-4
        text-center
        font-bold font-body
        text-6xl text-gray-800
      "
    >
      <p class="font-bold tracking-wide">
        Software Engineer <br />
        Building web <br />
        and mobile products
      </p>
    </div>
    <div class="flex justify-center pt-8 text-center">
      <p class="font-bold text-xl w-3/5">
        Software Engineer with a Computer Science background experienced in
        building Web & Mobile Applications. Proficient with Javascript (VueJs)
        and Scala. Expertise in leveraging Cloud Solutions (AWS).Interested in
        Golang, worked with Agile Project Management and Scrum, and interested
        in contributing and building Tech Communities.😉
      </p>
    </div>
    <div class="flex justify-center mt-10">
      <div
        class="
          bg-gray-800
          text-white
          btn
          hover:shadow-inner
          transform
          hover:scale-125
          transition
          ease-out
          duration-300
        "
      >
        Connect With Me
      </div>
    </div>
    <div class="grid md:grid-cols-3 mt-20 gap-10 p-10">
      <div class="col-span-1" data-aos="fade-right">
        <span>
          <img
            class="mb-10 h-96 object-cover"
            src="../assets/images/camera.jpg"
            alt="camera"
          />
        </span>
        <span>
          <img
            class="h-70 object-cover"
            src="../assets/images/coffee.jpg"
            alt="camera"
          />
        </span>
      </div>
      <div class="col-span-1" data-aos="fade-up">
        <span>
          <img
            class="mb-10 h-96 object-cover"
            src="../assets/images/paint.jpg"
            alt="camera"
          />
        </span>
        <span>
          <img
            class="h-80 object-cover"
            src="../assets/images/home.jpg"
            alt="camera"
          />
        </span>
      </div>
      <div class="col-span-1" data-aos="fade-left">
        <span>
          <img class="mb-10" src="../assets/images/laptop.jpg" alt="camera" />
        </span>
        <span>
          <img
            class="h-96 object-cover"
            src="../assets/images/monitor.jpg"
            alt="camera"
          />
        </span>
      </div>
    </div>
    <div class="mt-20 grid md:grid-cols-3 p-20 gap-20">
      <div class="" data-aos="fade-down">
        <h4 class="text-3xl pb-3 border-b border-gray-700 font-bold">
          Tech Stack
        </h4>
        <ul class="mt-7 text-xl">
          <li>JavaScript • Vue</li>
          <li>Flutter • Dart</li>
          <li>Tailwind CSS • BootStrap • Bulma</li>
          <li>Scala</li>
          <li>Interested in Golang(Building muscles for that)</li>
        </ul>
      </div>
      <div class="" data-aos="fade-up">
        <h4 class="text-3xl pb-3 border-b border-gray-700 font-bold">
          UI Design
        </h4>
        <ul class="mt-7 text-xl">
          <li>Figma</li>
          <li>Adobe XD</li>
          <li>Adobe Illustrator</li>
        </ul>
      </div>
      <div class="" data-aos="fade-down">
        <h4 class="text-3xl pb-3 border-b border-gray-700 font-bold">
          Infrastructure
        </h4>
        <ul class="mt-7 text-xl" data-aos=" fade-left">
          <li>AWS</li>
          <li>Google Cloud</li>
          <li>Heroku</li>
        </ul>
      </div>
    </div>
    <div class="px-16" id="exp">
      <h4 class="font-bold text-7xl border-b border-gray-900 pb-4">
        Who I've worked with
      </h4>
      <div class="grid md:grid-cols-2 gap-10 pt-10">
        <div class="" data-aos="fade-left">
          <h5 class="text-3xl font-bold">Turntabl</h5>
          <small class="">Software Agency</small>
          <p>
            Turntabl is a software agency based in London and Accra, Ghana.
            Turntabl is a technical partner that combines decades of Fortune 500
            technology and training experience with a track record in Ghana
            providing software solutions to large organisations and clients.
            Employees are taken through an intensive training program which
            lasts for three months, building a solid understanding of Operating
            Systems, C++, Java, Scala, Maching Learning etc.
          </p>
          <!-- <div class="flex items-center pt-2 cursor-pointer">
            <a
              class="text-xl pr-2 border-b border-gray-700"
              href="http://ideypay.com.gh"
              target="_blank"
            >
              Send me there</a
            >
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
                d="M17 8l4 4m0 0l-4 4m4-4H3"
              ></path>
            </svg>
          </div> -->
        </div>
        <div data-aos="fade-left">
          <h5 class="text-3xl font-bold">Wonchunii</h5>
          <small class="">Software Development</small>
          <p>
            Wonchunii is a software development company that provides a variety
            of software solutions to it's clients. Software solutions include
            from Web Applications Development, Mobile Applications development,
            Desktop Applications Development, User Inface Design , User
            Experience Design, Social Media Marketting, Graphic Design and
            Branding etc. Machu Digital is a place where our moto is "We work"
            and so as the moto goes this company provides to its client the best
            they can ask for when it comes to software
          </p>
          <!-- <div class="flex items-center pt-2 cursor-pointer">
            <a
              href="https://www.machudigital.com/"
              target="_blank"
              class="text-xl pr-2 border-b border-gray-700"
              >Send me there</a
            >
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
                d="M17 8l4 4m0 0l-4 4m4-4H3"
              ></path>
            </svg>
          </div> -->
        </div>
        <div data-aos="fade-left">
          <h5 class="text-3xl font-bold">IdeyPay Ghana</h5>
          <small class="">Fintech</small>
          <p>
            IdeyPay Ghana is a financial technology company that contributes to
            the digitization of payments. The company is geared toward providing
            smart, seamless and secure transactions. The compnay has a range of
            products that facilitate digital payments, micro lending, e-commerce
            and government bills and payments and so on. The company comprises
            of a rare mix of talented individuals who work as a team and are
            motivated to improve and create more channels for electronic payment
            modes throughout West Africa
          </p>
          <!-- <div class="flex items-center pt-2 cursor-pointer">
            <a
              href="https://theaddress.herokuapp.com/"
              target="_blank"
              class="text-xl pr-2 border-b border-gray-700"
              >Send me there</a
            >
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
                d="M17 8l4 4m0 0l-4 4m4-4H3"
              ></path>
            </svg>
          </div> -->
        </div>
      </div>
    </div>
    <div class="px-16 pt-14" id="works">
      <h4 class="font-bold text-7xl border-b border-gray-900 pb-4">
        Projects I've worked on
      </h4>
      <div class="grid md:grid-cols-2 gap-10 pt-10">
        <div class="" data-aos="fade-left">
          <h5 class="text-3xl font-bold">Febert HR/Pay</h5>
          <small class="">VueJs • MongoDB • Nodejs • AWS</small>
          <p>
            Febert HR/Pay is a Payroll and HR system that allows companies
            create Payrolls and manage employees with ease.
          </p>
          <!-- <div class="flex items-center pt-2 cursor-pointer">
            <a
              href="https://startupcrowd-home.herokuapp.com/"
              target="_blank"
              class="text-xl pr-2 border-b border-gray-700"
              >Take a look</a
            >
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
                d="M17 8l4 4m0 0l-4 4m4-4H3"
              ></path>
            </svg>
          </div> -->
        </div>
        <div data-aos="fade-left">
          <h5 class="text-3xl font-bold">IdeyPay Till Engine</h5>
          <small class="">VueJs • MongoDB • NodeJs</small>
          <p>
            The Till Engine (Odem) is a financial product that allows merchants
            to receive payments. It processes payments and shows a transaction
            history , allowing a merchat to trace and account for products,
            goods or services which have been paid for through the till. This
            product allows for invoicing, card payments etc. The product allows
            for third parties to integrate via API keys. The product ensures
            security, has a beautiful user interface and experience
          </p>
          <!-- <div class="flex items-center pt-2 cursor-pointer">
            <a
              href="#"
              target="_blank"
              class="text-xl pr-2 border-b border-gray-700"
              >Take a look</a
            >
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
                d="M17 8l4 4m0 0l-4 4m4-4H3"
              ></path>
            </svg>
          </div> -->
        </div>
        <div data-aos="fade-left">
          <h5 class="text-3xl font-bold">Quevy Mobile Application</h5>
          <small class="">Dart • Flutter • Firebase</small>
          <p>
            Quevy is an Android app built using Dart and Flutter. The app allows
            users to collect feedback, questions or complains form a targetted
            audience. All users need to do is generate a unique four digit code
            which can be used both to send in feedback, questions and complians
            and also view those entries sent in. Quevy was built with
            conferences in mind where audience can send their questions or
            suggestions to a speaker before or after a talk. Also it can be used
            to gather feedback about a product from the public. This is a
            personal project i built and it is currently on the Google PlayStore
          </p>
          <div class="flex items-center pt-2 cursor-pointer">
            <a
              href="https://play.google.com/store/apps/details?id=nunyaklah.quevy_final"
              target="_blank"
              class="text-xl pr-2 border-b border-gray-700"
              >Take a look</a
            >
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
                d="M17 8l4 4m0 0l-4 4m4-4H3"
              ></path>
            </svg>
          </div>
        </div>
        <div data-aos="fade-left">
          <h5 class="text-3xl font-bold">Quevy Web Application</h5>
          <small class="">VueJs</small>
          <p>
            Quevy as similar to the Android has a web version. The application
            allows users to collect feedback, questions or complains form a
            targetted audience. All users need to do is generate a unique four
            digit code which can be used both to send in feedback, questions and
            complians and also view those entries sent in. Quevy was built with
            conferences in mind where audience can send their questions or
            suggestions to a speaker before or after a talk. Also it can be used
            to gather feedback about a product from the public.
          </p>
          <div class="flex items-center pt-2 cursor-pointer">
            <a
              href="https://quevyapp.com/"
              target="_blank"
              class="text-xl pr-2 border-b border-gray-700"
              >Take a look</a
            >
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
                d="M17 8l4 4m0 0l-4 4m4-4H3"
              ></path>
            </svg>
          </div>
        </div>
      </div>
    </div>
    <h4 class="font-bold text-4xl flex justify-center mt-20">
      Want to see me ?
    </h4>
    <div class="grid md:grid-cols-2 pt-7 pb-20" id="contact">
      <div class="place-self-center" data-aos="fade-right">
        <img
          class="
            w-72
            h-72
            object-cover
            rounded
            shadow-lg
            transform
            hover:scale-125
            transition
            ease-out
            duration-300
          "
          src="../assets/images/yao.jpg"
          alt=""
        />
      </div>
      <div
        class="mt-7 text-center sm:text-left place-self-center"
        data-aos="fade-left"
      >
        <h5 class="font-bold text-xl">A little more👌</h5>
        <p class="pt-5 w-64">
          I am a highly motivated individual who is ever ready to learn and
          improve upon my skills. You can count on me to help you architect a
          software solution right from idea development , to delivering a well
          built solution to customers. Interested ? Just send me a mail and lets
          do some magic 😉
        </p>
        <p class="text-xs font-semibold text-gray-400 mt-5">Nunya Yao Klah</p>
        <p class="text-xs font-semibold text-gray-400">nunyaklah@gmail.com</p>
        <p class="text-xs font-semibold text-gray-400">Twitter : @klah_yao</p>
        <p class="text-xs font-semibold text-gray-400">GitHub : Nunyaklah</p>
      </div>
      <div></div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      ideypay: "www.ideypay.com.gh",
    };
  },
  mounted() {
    const burger = document.querySelector("#burger");
    const menu = document.querySelector("#menu");

    burger.addEventListener("click", () => {
      if (menu.classList.contains("hidden")) {
        menu.classList.remove("hidden");
      } else {
        menu.classList.add("hidden");
      }
    });
  },
};
</script>
