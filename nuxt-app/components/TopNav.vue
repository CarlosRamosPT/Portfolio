<template>
        <nav class="navbar">
      <ul class="navlinks">
        <li >
           <nuxtLink class="nuxtlink flex flex-row gap-4" active-class="text-yellow-300" to="/" ><img src="/assets/images/home-1-svgrepo-com.svg" alt="Home logo">Home</nuxtLink>
        </li>
        <span class="crossbar"></span>
        <li>
          <nuxtLink class="nuxtlink flex flex-row gap-4" to="/cv"><img src="/assets/images/curriculum-resume-svgrepo-com.svg">CV</nuxtLink>
        </li>
        <span class="crossbar"></span>
        <li>
            <nuxtLink class="nuxtlink flex flex-row gap-4" to = "/project"><img src="/assets/images/toolboxx.svg" alt="toolbox logo">Projects</nuxtLink>
        </li>
        <span class="crossbar"></span>
        <li >
            <nuxtLink class="contactMe flex flex-row gap-4" to = "/contact"><img src="/assets/images/contact-us-svgrepo-com.svg" alt="contact me logo">Contact Me</nuxtLink>
        </li>
      </ul>
    </nav>
</template>