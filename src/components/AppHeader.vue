<template>
  <header>
    <nav class="navbar navbar-expand-sm navbar-light bg-light">
        <font-awesome-icon :icon="['fab', 'amazon']" />
            <font-awesome-icon icon="address-card" />
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
          <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#">Ricardo Uribe <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">History</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Projects</a>
            </li>
          </ul>
          <div class="social-part">
            <font-awesome-icon :icon="['fab', 'github']" />
            <font-awesome-icon :icon="['fab', 'twitter']" />
            <font-awesome-icon :icon="['fab', 'stack-overflow']" />
          </div>
        </div>
      </nav>
  </header>
</template>

<script>
import fontawesome from "@fortawesome/fontawesome";
import brands from "@fortawesome/fontawesome-free-brands";
import faSpinner from "@fortawesome/fontawesome-free-solid/faSpinner"; 
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'

fontawesome.library.add(brands, faSpinner);

export default {
    name: 'AppHeader',
    components: {
      FontAwesomeIcon
    }
}
</script>

<style>
  .navbar {
    background-color: #000;
    padding-left: 15px;
    padding-top: 8px;
    padding-right: 15px;
    padding-bottom: 4px;
    margin-top: 0px;
    align-items: right;
  }
  .title {
      color: #C6EFFF;
      font-weight: 600;
      font-size: larger;
      margin: 0px;
      padding-bottom: 0px;
      margin-bottom: 0px;
  }

  .social-part .fa{
    padding-right:20px;
  }
  ul li a{
      margin-right: 20px;
  }

</style>