<template>
  <div class="font-sans text-gray-800 leading-normal flex flex-col min-h-screen">
    <header class="border-t-14 border-blue">

      <nav class="container mx-auto flex flex-col sm:flex-row justify-between items-center py-8">

        <div class="mb-4 sm:mb-0">
          <a href="/">Mirko Skopljak</a>
        </div>
        
        <ul class="uppercase tracking-wide font-bold flex items-center">
          <li class="mr-8"><a href="#" class="text-gray-800 hover:text-gray-600">Project</a></li>
          <li class=""><a href="#" class="text-gray-800 hover:text-gray-600">Contact</a></li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>


export default {
  name: 'Header',
  props: {
    msg: String
  },
  components: {

  }
}
</script>
