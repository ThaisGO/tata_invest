<template>
    <footer class="footer">
        <div class="container">
            <div class="row py-3">
                <div class="col-md-4">
                        <h3>How to Find Us</h3>

                        <h5 class="mb-2">Headquarters</h5>
                        <p class="m-0">9863 - 9867 MILL ROAD, CAMBRIDGE, MG09 99HT.</p>
                        <p class="m-0">Telephon: +1 800 603 6035</p>
                        <p class="mt-0 mb-2">E-mail: mail@demolink.org</p>
                        
                        <h5 class="mb-2">Headquarters</h5>
                        <p class="m-0">9863 - 9867 MILL ROAD, CAMBRIDGE, MG09 99HT.</p>
                        <p class="m-0">Telephon: +1 800 603 6035</p>
                        <p class="m-0">E-mail: mail@demolink.org</p>
                </div>

                <div class="col-md-4">
                        <h3>Navigation</h3>
                        <ul class="list-unstyled mt-3">
                                <li class="py-1">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-0">Carefully crafted components</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-html5"></badge>
                                        <h6 class="mb-0">Amazing page examples</h6>
                                    </div>
                                </li>
                        </ul>
                </div>
                <div class="col-md-4">
                        <h3>Contact Us</h3>
                        <div class="btn-wrapper">
                                    <base-button 
                                        tag="a"
                                        href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                                        class="mb-3 mb-sm-0"
                                        type="success"
                                        icon="fa fa-code">
                                        Components
                                    </base-button>
                                </div>

                </div>
            </div>

            <hr>

            <div class="row align-items-center justify-content-md-between">
                <div class="col-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a href="https://www.creative-tim.com" target="_blank" rel="noopener">Creative Tim</a> & <a href="https://www.binarcode.com" target="_blank" rel="noopener">Binar Code</a>
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