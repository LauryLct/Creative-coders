<template>
  <div class="navbar navbar-expand-sm navbar-light navbar-creative">
    <div class="navbar-logo">
      <a class="navbar-brand d-flex align-items-center mr-1" href="#">
        <img src="../assets/logo1.svg" />
      </a>
    </div>
    <button class="navbar-toggler"
            type="button"
            data-toggle="collapse"
            data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="#1">Nos solutions</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#2">Nos technologies</a>
        </li>
         <li class="nav-item">
          <a class="nav-link" href="#3">Nos tarifs</a>
        </li>
         <li class="nav-item">
          <a class="nav-link" href="#4">Nous Contacter</a>
        </li>
        <li class="nav-item dropdown">
          <div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>

<style scoped>
.navbar-creative {
  justify-content: space-between;
  background: white;
}

.navbar-creative .navbar-collapse {
  flex-grow: 0;
}

.navbar-creative .navbar-brand img {
  width: 40px;
}
.navbar-logo {
  padding-left: 10px;
}
</style>
