<template>
  <div class="navbar navbar-expand-sm navbar-light navbar-creative">
    <div class="navbar-logo">
      <a class="navbar-brand d-flex align-items-center mr-1" href="#">
        <img src="../assets/logo-creative-coders.svg" alt="logo creative coders"/>
      </a>
    </div>
    <div style="margin-right:10px">
      <button v-on:click='toggleShow'
              class="navbar-toggler mr-1"
              type="button">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div v-if='showMenu' v-on:click='toggleShow' class='menu'>
        <img src="../assets/close.svg" alt="close-logo">
				<ul class="navbar-nav mr-auto">
          <li class="nav-item m-1">
            <a class="nav-link" href="#nos-solutions">Nos solutions</a>
          </li>
          <li class="nav-item m-1">
            <a class="nav-link" href="#nos-engagements">Nos engagements</a>
          </li>
          <li class="nav-item m-1">
            <a class="nav-link" href="#a-propos">À propos</a>
          </li>
          <li class="nav-item m-1">
            <a class="nav-link" href="#nos-technologies">Nos technologies</a>
          </li>
          <li class="nav-item m-1">
            <a class="nav-link" href="#nous-contacter">Nous contacter</a>
          </li>
      </ul>
			</div>
    </div>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
          <li class="nav-item m-1">
            <a class="nav-link" href="#nos-solutions">Nos solutions</a>
          </li>
          <li class="nav-item m-1">
            <a class="nav-link" href="#nos-engagements">Nos engagements</a>
          </li>
          <li class="nav-item m-1">
            <a class="nav-link" href="#a-propos">À propos</a>
          </li>
          <li class="nav-item m-1">
            <a class="nav-link" href="#nos-technologies">Nos technologies</a>
          </li>
          <li class="nav-item m-1">
            <a class="nav-link" href="#nous-contacter">Nous contacter</a>
          </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data: function() {
    return {
      showMenu: false
    }
  },
  methods: {
    toggleShow: function() {
      this.showMenu = !this.showMenu
    }
  }
}
</script>

<style scoped>
img {
  width: 30px;
}

.app{
  position: relative;
}
.navbar{
  position: fixed;
  z-index: 20;
  width: 100%;
}
.navbar-creative {
  justify-content: space-between;
  background: white;
}
.navbar-creative .navbar-collapse {
  flex-grow: 0;
  margin-right: 10px;
}
.navbar-creative .navbar-brand img {
  width: 100px;
}
.navbar-logo {
  padding-left: 20px;
  margin-left: 10px;
}
.menu {
  margin: 20px;
  padding: 20px;
  position:absolute;
  top: 50%;
  right: 10%;
  background-color: #b4b2b2e1;
  border-radius: 10px;
  z-index: 20;
}

</style>
