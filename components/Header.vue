<template>
  <div>
    <div class="primary-bg">
      <div class="container mx-auto py-20">
        <div class="bg-white p-5 mb-20">
          <div class="flex items-center">
            <div class="min-w-max">
              <h2 class="text-3xl font-bold text-black">Lanxvax</h2>
            </div>

            <div class="w-full">
              <ul class="flex justify-center gap-3 text-xl">
                <li><nuxt-link to="/">Home</nuxt-link></li>
                <li><nuxt-link to="/">Registration</nuxt-link></li>
                <li><nuxt-link to="/">Verify</nuxt-link></li>
                <li><nuxt-link to="/">Vaccine Card</nuxt-link></li>
                <li><nuxt-link to="/">Help</nuxt-link></li>
                <li><nuxt-link to="/">FAQs</nuxt-link></li>
              </ul>
            </div>

            <div class="min-w-max">
              <nuxt-link class="primary-bg p-3 text-white rounded-xl" to="/">Register Now</nuxt-link>
            </div>
          </div>
        </div>

        <div class="flex items-center">
          <div class="w-full">
            <h1 class="text-9xl font-bold text-white uppercase">Vaccine</h1>
            <h2 class="text-7xl font-medium text-white mb-6">Registration</h2>
            <p class="text-xl text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab aliquam, consectetur culpa dignissimos doloremque enim facere, harum magnam minima placeat</p>
          </div>
          <div class="min-w-max">
            <img src="~/static/img/Vaccine-bro.png" alt="" width="616">
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>
