<template>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-xl navbar-light bg-navbar position-fixed w-100 py-5">
        <h2>
            <a class="navbar-brand d-flex text-white mr-0" href="#">
                <div class="logo bg-cover mr-1 mr-md-3"></div>
                <div class="d-flex flex-column justify-content-between">
                    <span class="h2">Nefer Digital</span>
                    <span class="h3">完美數位</span>
                </div>
            </a>
        </h2>
        <button class="navbar-toggler px-2" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="material-icons text-white">
            menu
            </span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
            <ul class="navbar-nav">
            <li class="nav-item active text-center mx-3">
                <a class="nav-link text-white h5" href="#">Home</a>
            </li>
            <li class="nav-item text-center mx-3">
                <a class="nav-link text-white h5" href="#">Service</a>
            </li>
            <li class="nav-item text-center mx-3">
                <a class="nav-link text-white h5" href="#">Works</a>
            </li>
            <li class="nav-item text-center mx-3">
                <a class="nav-link text-white h5" href="#">Profession</a>
            </li>
            <li class="nav-item text-center mx-3">
                <a class="nav-link text-white h5" href="#">Contacts</a>
            </li>
            </ul>
        </div>
    </nav>
    <!-- Gotop -->
    <button class="d-inline-block gotop bg-cover"></button>
</template>

<style lang="scss" scoped>
@import '../../assets/all.scss';
// Navbar
.navbar {
  z-index: 9999;

  .nav-link {
    border-bottom: 2px solid transparent;
    line-height: 32px;
    transition: all .33s;

    &:hover {
      border-bottom-color: white;
    }
  }
}

@include mobile {
    .h2 {
        font-size: 24px !important;
    }

    .h3 {
        font-size: 20px !important;
    }
}

.logo {
  width: 119px;
  height: 113px;
  background-image: url('../../assets/images/u4.png');

  @include mobile {
      width: 96px;
      height: 92px;
  }
}

.gotop {
    position: fixed;
    z-index: 9999;
    width: 60px;
    height: 60px;
    bottom: 20px;
    right: 20px;
    border: none;
    border-radius: 50%;
    background-color: #fff;
    background-image: url('../../assets/images/u71.png');
    transform: rotate(-90deg);
}

</style>
