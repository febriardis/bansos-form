<template>
  <div class="stepper">
    <div>
      <div class="stepper-item bg-blue-500 border-blue-500 text-white">
        <span>1</span>
      </div>
      <span class="text-item -ml-4 mt-2 text-gray-800">Buat Akun</span>
    </div>
    <div class="box-circle"></div>
    <div>
      <div class="stepper-item">
        <span>2</span>
      </div>
      <span class="text-item -ml-7 mt-2">Lengkapi Profil</span>
    </div>
    <div class="box-circle"></div>
    <div>
      <div class="stepper-item">
        <span>3</span>
      </div>
      <span class="text-item -ml-1 mt-2">Alamat</span>
    </div>
    <div class="box-circle"></div>
    <div>
      <div class="stepper-item">
        <span>4</span>
      </div>
      <span class="text-item -ml-1 mt-2">Selesai</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'StepperComponent'
}
</script>

<style lang="scss">
.stepper {
  @apply flex items-center justify-between mt-10 mb-16;
  .stepper-item {
    @apply w-8 h-8 md:w-11 md:h-11 z-10 font-bold rounded-full bg-white border-2 border-gray-500 flex items-center justify-center;
  }
  .text-item {
    @apply absolute text-gray-500 text-xs md:text-base;
  }
  .box-circle {
    @apply border-2 border-gray-500 bg-gray-500 w-full;
  }
}
</style>