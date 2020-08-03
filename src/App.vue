<template>
<section>
    <header class="border-t-14 border-teal-500">
      <nav class="container mx-auto flex flex-col sm:flex-row justify-between items-center py-8">

        <div class="mb-4 sm:mb-0">
          <h1 class="text-4xl font-bold w-full text-teal-500">Mirko Skopljak</h1>
        </div>
        
        <ul class="uppercase tracking-wide font-bold flex items-center">
          <li class="mr-8"><a href="#project" class="text-gray-800 hover:text-gray-600">Project</a></li>
          <li class=""><a href="#contact" class="text-gray-800 hover:text-gray-600">Contact</a></li>
        </ul>
      </nav>
    </header>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <h1>Web Developer</h1>
        <h2 class="text-teal-500">Welcome to my website</h2>
      </div>
      <div class="mt-8 sm:mt-0">
        <img src="./assets/image/developer.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div> 
    <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-xl">Hi, my name is Mirko. I'm from Serbia. I am a Technical School graduante in the field of Typography, and at the Vivify Academy in Novi Sad finished course for Basci Web Developer. I still consider mysqlf a beginner in programming. I am a persistent person who loves to study hard, learn new things and accept challenges.</p>


      <div class="flex justify-between items-center py-16">
        <div class="w-1/2">
          <p class="text-center">I want to learn</p>
          <img src="./assets/image/browser.svg" alt="browser">
        </div>
        <div class="w-1/2 flex justify-end">
          <img src="./assets/image/mobile.svg" alt="mobile">
        </div>
      </div>
    </div>
    <!-- end -->

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16">
        <h3 class="font-bold mb-6">Education:</h3>

        <ul class="ml-6">
          <li class="mb-6"> - Sep 2008 - June 2012 High school degree in Typography</li>
          <li class="mb-6"> - Oct 2019 - Jan 2020 Basic course Full Stack Web Programming - Vivify Academy</li>
          <li class="mb-6"> - Udemy Course (The Web Developer Bootcamp, Build Responsive Real World Websites with HTML5 and CSS3, Java Programming Masterclass for Software Developers, etc...)</li>
        </ul>
        <div class="text-center mx-auto sm:mx-auto pt-6" >
          <img src="./assets/image/certificate.jpg" alt="sertifikat">
        </div>
        <div class="text-center mx-auto sm:mx-auto pt-6" >
          <img src="./assets/image/certificate2.jpg" alt="sertifikat">
        </div>
      </div>
    <!-- end projects -->
    </div>

    <div class="overflow-x-hidden" id="project">
      <div class="projects container-inner mx-auto text-xl border-gray-500 border-b py-16 mb-16">
        <h3 class="font-bold mb-6">Projects:</h3>

        <p class="mb-6">I don't have a live project, everything I studied and worked on <a class="text-teal-500" href="https://github.com/mirko93" target="_blank">GitHub</a></p>
        <ul class="ml-6">
          <li class="checkmark mb-6">Netflix-clone (PHP / MySQL / jQuery) <a class="text-teal-500" href="https://github.com/mirko93/NetflixClone" target="_blank">NetFlix-clone</a></li>
          <li class="checkmark mb-6">Instagram-clone (Laravel / VueJs) <a class="text-teal-500" href="https://github.com/mirko93/instagram-clone" target="_blank">Instagram-clone</a></li>
          <li class="checkmark mb-6">Contact Application (Laravel-API-VueJS) <a class="text-teal-500" href="https://github.com/mirko93/Laravel-API-VueJS" target="_blank">Instagram-clone</a></li>
          <li class="checkmark mb-6">Final work at the academy I attended (PHP / MySQL) <a class="text-teal-500" href="https://github.com/mirko93/php-mini-projects/tree/master/blog" target="_blank">Blog</a></li>
          <li class="checkmark mb-6">Google Clone (PHP / MySQL / JS) <a class="text-teal-500" href="https://github.com/mirko93/php-mini-projects/tree/master/google-clone" target="_blank">Doodle :)</a></li>
          <li class="checkmark mb-6">Suggest Search <a class="text-teal-500" href="https://github.com/mirko93/php-mini-projects/tree/master/suggest-search" target="_blank">Search</a></li>
        </ul>
      </div>
    <!-- end projects -->
    </div>    
      <!-- end get-to-know-me -->

      <div class="contact-me container-inner mx-auto text-xl pb-4 mb-4">
        <h3 class="font-bold mb-6" id="contact">Contact me:</h3>

        <div class="text-xl mb-16 ml-6">
          If you're looking to get in contact with me for business inquiries or if you have a question, feel free to <a class="text-blue" href="mailto:skopljak.mirko93@gmail.com">email me</a>.
        </div>
      </div>
      <!-- end contact section -->
      
      <footer class="bg-teal-500 text-white">
      <div class="container mx-auto flex flex-col sm:flex-row items-center justify-between py-8">
        <div class="mb-8 sm:mb-0">Designed - Mirko Skopljak</div>
        <ul class="flex items-center">
          <li class="mr-8">
            <a href="https://github.com/mirko93" target="_blank">GitHub</a>
          </li>
          <li class="mr-8">
            <a href="https://www.facebook.com/MirkoOoo93" target="_blank">Facebook</a>
          </li>
          <li class="">
            <a href="https://www.linkedin.com/in/mirko-skopljak-55b241184/" target="_blank">Linkedin</a>
          </li>
        </ul>
      </div>
    </footer>
  </section>
</template>

<script>
// import Header from './components/Header'

export default {
  name: 'App',
  components: {
    // Header
  }
}
</script>

<style src="./assets/css/app.css" />

