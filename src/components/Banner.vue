<template>
  <div class="banner">
    <div class="container mx-auto w-[1200px] h-[960px] flex justify-center items-center">
      <div class="text-white w-[300px]">
        <div>Here’s</div>
        <div class="text-[80px]">JOANNE</div>
        <p class="text-2xl mb-6">Founder of “XXXD Official’’ & Graphic Designer</p>
        <ul class="flex">
          <li>
            <a href="#" class="inline-block"><img src="../assets/icons/iconfinder_6_social_2609577.png" alt="Be" /> </a>
          </li>
          <li>
            <a href="#" class="inline-block"> <img src="../assets/icons/iconfinder_1_social_2609541.png" alt="fb" /> </a>
          </li>
          <li>
            <a href="#" class="inline-block"><img src="../assets/icons/iconfinder_25_social_2609558.png" alt="ig" /> </a>
          </li>
          <li>
            <a href="#" class="inline-block"><img src="../assets/icons/iconfinder_6_social_2609577.png" alt="youtube" /> </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped lang="scss">
.banner {
  background: url("../assets/images/banner.png") no-repeat;

  li {
    ~ li {
      margin-left: 20px;
    }
  }
}
</style>
