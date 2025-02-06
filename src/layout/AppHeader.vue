<template>
    <header class="header-global fixed-top">
        <base-nav class="navbar-main bg-gradient-default" transparent type="default" effect="light" expand>
            <!-- <router-link slot="brand" class="navbar-brand mr-lg-5" to="#start" @click.prevent="clearPath('start')">
                <img src="img/brand/white.png" alt="logo">
            </router-link> -->
            
            <div>
                <a class="navbar-brand mr-lg-5" href="#contato" @click.prevent="clearPath('start')">
                    <img src="img/brand/white.png" alt="logo">
                    </a>
            </div>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://www.google.com">
                        <img src="img/brand/blue.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#servicos" @click.prevent="clearPath('servicos')">
                        Serviços
                    </a>
                </li>
                <li class="nav-item px-4">
                    <a class="nav-link nav-link-icon" href="#sobre" @click.prevent="clearPath('sobre')">
                        Quem somos
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#contato" @click.prevent="clearPath('contato')">
                        Contato
                    </a>
                </li>
            </ul>

            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" 
                        href="https://www.google.com" 
                        target="_blank" 
                        rel="noopener"
                        data-toggle="tooltip" 
                        title="Like us on Facebook">
                        <i class="fa fa-facebook-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Facebook</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" 
                        href="https://www.google.com" 
                        target="_blank" 
                        rel="noopener"
                        data-toggle="tooltip" 
                        title="Like us on Instagran">
                        <i class="fa fa-instagram"></i>
                        <span class="nav-link-inner--text d-lg-none">Instagran</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" 
                        href="https://www.google.com" 
                        target="_blank" 
                        rel="noopener"
                        data-toggle="tooltip" 
                        title="Like us on Twitter">
                        <i class="fa fa-twitter-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Twitter</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  },
  methods: {
    clearPath(key) {
      // 1. Rola até a seção com id "contato"
      const section = document.getElementById(key);
      section.scrollIntoView({ behavior: "smooth" });

      // 2. Limpa o hash da URL para não mostrar "#contato"
    //   this.$router.replace('/'); // Limpa a rota e remove o hash
      this.$router.replace({ path: '/' });
    }
  }
};
</script>
<style>
</style>

