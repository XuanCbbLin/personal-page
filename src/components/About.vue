<template>
  <section class="py-10">
    <div class="container w-[1200px] mx-auto flex justify-center">
      <div class="w-[384px] text-center">
        <div>
          <h2 class="text-[64px] mb-10">About</h2>
          <img src="../assets/images/photo.png" alt="about-me" />
          <div class="pt-5 pb-6 border-b-[1px] border-black">
            <p class="text-2xl mb-1">Joanne Chen</p>
            <p class="text-2xl mb-2">1997/10/10</p>
            <p class="text-2xl">National Hex School Normal University Department of Visual Design</p>
          </div>
        </div>
        <ul class="resume pt-7">
          <li class="text-2xl"><span>Founder of ‘’XXXD Official’’</span></li>
          <li class="text-2xl"><span>Graphic Designer</span></li>
          <li class="text-2xl"><span>Graphic Intern of Hex School</span></li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped>
.resume {
  li {
    &:before {
      content: "";
      width: 8px;
      height: 8px;
      display: inline-block;
      border-radius: 50%;
      background-color: #891818;
      margin-right: 10px;
      vertical-align: middle;
    }
    ~ li {
      margin-top: 28px;
    }

    span {
      display: inline-block;
      vertical-align: middle;
    }
  }
}
</style>
