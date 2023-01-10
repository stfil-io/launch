<template>
  <header class="header-nav position-relative" style="border-bottom: 1px solid #6752F01A;">
    <div class="container" >
      <nav class="navbar navbar-expand-xl navbar-light px-0">
        <a class="navbar-brand p-0" href="#">
          <img class="img-fluid logo-ad" src="@/assets/images/logo/logo.png">
        </a>

        <button class="navbar-toggler bg-white rounded-0 p-0" type="button" data-toggle="collapse" data-target="#navlinks"
                aria-controls="navlinks" aria-expanded="false" aria-label="Toggle navigation">
          <svg class="nav-toggle-icon" viewBox="0 0 100 100" width="40" >
            <path class="line top"
                  d="m 70,33 h -40 c 0,0 -8.5,-0.149796 -8.5,8.5 0,8.649796 8.5,8.5 8.5,8.5 h 20 v -20" />
            <path class="line middle" d="m 70,50 h -40" />
            <path class="line bottom"
                  d="m 30,67 h 40 c 0,0 8.5,0.149796 8.5,-8.5 0,-8.649796 -8.5,-8.5 -8.5,-8.5 h -20 v 20" /></svg>
        </button>
        <!-- mobile-nav control button -->

        <div class="collapse navbar-collapse" id="navlinks">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item" v-for="(menu ,index) in menus" :key="index">
              <a class="nav-link" href="#">{{menu.label}}</a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "IHeader",
  data(){
    return  {
      menus: [
        {
          label: 'home'
        },
        {
          label: 'other'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>
