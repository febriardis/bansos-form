<template>
  <div class="index flex justify-center">
    <div class="card border md:w-9/12 w-full mt-20 rounded">
      <div class="card-head p-4 bg-blue-200 text-center">
        <h4 class="text-xl">lorem ipsum dolor sit amet</h4>
        <!-- Formulir Bantuan Sosial Kota Bandung -->
      </div>
      <div class="card-content p-4">
        <div class="w-9/12 md:w-12/12 m-auto">
          <Stepper />
        </div>
        <p>lorem ipsum dolor sit amet</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  components: {
    Stepper: () => import('@/components/molecules/Stepper')
  }
}
</script>
