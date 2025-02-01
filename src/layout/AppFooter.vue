<template>
    <footer class="footer bg-gradient-default">
        <div class="container">
            <div class="row py-3">
                <div class="col-md-4">
                        <h3 class="text-white">Endereço</h3>

                        <h5 class="mb-2 text-white">Brasil</h5>
                        <p class="m-0 text-white">9863 - 9867 MILL ROAD, CAMBRIDGE, MG09 99HT.</p>
                        <p class="m-0 text-white">Telephon: +1 800 603 6035</p>
                        <p class="mt-0 mb-2 text-white">E-mail: mail@demolink.org</p>
                        
                        <h5 class="mb-2 text-white">EUA</h5>
                        <p class="m-0 text-white">9863 - 9867 MILL ROAD, CAMBRIDGE, MG09 99HT.</p>
                        <p class="m-0 text-white">Telephon: +1 800 603 6035</p>
                        <p class="m-0 text-white">E-mail: mail@demolink.org</p>
                </div>

                <div class="col-md-4">
                        <h3 class="text-white">Navegação</h3>
                        <ul class="list-unstyled mt-3">
                                <li class="py-1">
                                    <a class="" href="#contato">
                                        <h6 class="text-white">Serviços</h6>
                                    </a>
                                </li>
                                <li class="py-2">
                                    <a class="" href="#contato">
                                        <h6 class="text-white">Quem somos</h6>
                                    </a>
                                </li>
                                <li class="py-1">
                                    <a class="" href="#contato">
                                        <h6 class="text-white">Contato</h6>
                                    </a>
                                </li>
                        </ul>
                </div>
                <div class="col-md-4">
                        <h3 class="text-white">Contact Us</h3>
                        <div class="btn-wrapper">
                                    <base-button 
                                        tag="a"
                                        href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                                        class="mb-3 mb-sm-0"
                                        size="md"
                                        type="success"
                                        icon="fa fa-whatsapp">
                                        Atendimento
                                    </base-button>
                                </div>

                </div>
            </div>

            <hr class="bg-light">

            <div class="row align-items-center justify-content-md-between">
                <div class="col-6">
                    <div class="copyright text-light">
                        &copy; {{year}}
                        <a href="https://www.creative-tim.com" target="_blank" rel="noopener" class="text-gold">Creative Tim</a> & <a href="https://www.binarcode.com" target="_blank" rel="noopener" class="text-gold">Binar Code</a>
                    </div>
                </div>

                <div class="col-6 text-lg btn-wrapper">

                    <!-- <div class="col-lg-6 text-lg btn-wrapper"> -->
                        <ul class="nav nav-footer justify-content-end">

                        <a target="_blank" rel="noopener" href="https://twitter.com/creativetim" data-toggle="tooltip" data-original-title="Follow us" class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg">
                            <i class="fa fa-twitter"></i>
                        </a>
                            
                            <a target="_blank" rel="noopener" href="https://www.facebook.com/creativetim" data-toggle="tooltip" data-original-title="Like us" class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg"><i class="fa fa-facebook-square"></i></a>
                            
                            <a target="_blank" rel="noopener" href="https://dribbble.com/creativetim" data-toggle="tooltip" data-original-title="Follow us" class="btn btn-neutral btn-icon-only btn-dribbble btn-lg btn-round"><i class="fa fa-dribbble"></i></a>
                            
                            <a target="_blank" rel="noopener" href="https://github.com/creativetimofficial" data-toggle="tooltip" data-original-title="Star on Github" class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg"><i class="fa fa-github"></i></a>
                        </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>