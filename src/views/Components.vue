<template>
  <div>
      <section id="start" class="section bg-gradient-default">
          <div class="container">
                  <div class="row pt-5">
                      <div class="col-lg-8">
                          <h1 class="display-2 text-gold">Liberdade Financeira
                              <span class="text-white">começa com boas decisões</span>
                          </h1>
                          <h4 class="lead text-gold">Nós te ajudamos a toma-las</h4>

                          <p class="lead text-white">Com a nossa assessoria, você tem ao seu lado especialistas que entendem o mercado e sabem como transformar seu dinheiro em um verdadeiro aliado.</p>
                          <div class="btn-wrapper">
                              <base-button tag="a"
                                        @click="redirectToWhatsApp"
                                      
                                      class="mb-3 mb-sm-0 text-white"
                                      type="info"
                                      icon="fa fa-whatsapp">
                                  Fale com um consultor
                              </base-button>
                          </div>
                      </div>
                  </div>
          </div>
      </section>

      <section id="servicos" class="section section-shaped my-0 overflow-hidden scroll-margin-top">
          <div class="shape shape-style-3 bg-gradient-default shape-skew">
              <span></span>
              <span></span>
              <span></span>
              <span></span>
              <span></span>
              <span></span>
              <span></span>
              <span></span>
          </div>
          <div class="container pb-200">
              <div class="row text-center justify-content-center">
                  <div class="col-lg-10">
                      <h2 class="display-3 text-white">Serviços</h2>
                      <p class="lead text-white">Transforme seu futuro financeiro com soluções personalizadas para investir com segurança, planejamento e eficiência.</p>
                  </div>
              </div>

              <div class="row row-grid mt-5">
                  <div class="col-lg-4">
                      <icon name="ni ni-single-copy-04" size="lg" gradient="white" shadow round color="primary"></icon>
                      <h5 class="text-white mt-3">Planejamento Financeiro</h5>
                      <p class="text-white mt-3">Alcance suas metas com segurança através de um planejamento personalizado.</p>
                  </div>
                  <div class="col-lg-4">
                      <icon name="ni ni-chart-bar-32" size="lg" gradient="white" shadow round color="primary"></icon>
                      <h5 class="text-white mt-3">Gerenciamento de investimentos</h5>
                      <p class="text-white mt-3">Construa seu patrimônio com um planejamento eficiente e sob medida.</p>
                  </div>
                  <div class="col-lg-4">
                      <icon name="ni ni-building" size="lg" gradient="white" shadow round color="primary"></icon>
                      <h5 class="text-white mt-3">Contratação de Seguros</h5>
                      <p class="text-white mt-3">Proteja o que é mais importante com coberturas sob medida para você.</p>
                  </div>
                  
              </div>

              <div class="row row-grid mt-5">
                  <div class="col-lg-4">
                      <icon name="ni ni-money-coins" size="lg" gradient="white" shadow round color="primary"></icon>
                      <h5 class="text-white mt-3">Quitação de dívidas da forma mais barata</h5>
                      <p class="text-white mt-3">Nós ajudamos você a sair das dívidas e se planejar financeiramente.</p>
                  </div>
                  <div class="col-lg-4">
                      <icon name="ni ni-world-2" size="lg" gradient="white" shadow round color="primary"></icon>
                      <h5 class="text-white mt-3">Investimentos no Exterior</h5>
                      <p class="text-white mt-3">Diversifique globalmente sua carteira para oportunidades internacionais.</p>
                  </div>
              </div>
          </div>
      </section>

      <section class="section">
          <div class="container">
              <div class="row row-grid align-items-center">
                  <div class="col-md-6">
                      <h3>Investir bem é uma questão de estratégia</h3>
                      <p>E nós estamos aqui para te ajudar a construir um futuro próspero com decisões financeiras inteligentes.</p>

                      <div class="btn-wrapper mt-5">
                          <base-button tag="a"
                          @click="redirectToWhatsApp"
                                  class="mb-3 mb-sm-0 text-white"
                                  type="info"
                                  icon="fa fa-whatsapp">
                              Fale com um consultor
                          </base-button>
                      </div>
                  </div>
                  
                  <div class="col-md-6">
                      <div >
                          <ul class="list-unstyled mt-3">
                              <li class="py-1">
                                  <div class="d-flex align-items-center">
                                      <div>
                                          <badge type="success" circle class="mr-3" icon="ni ni-settings"></badge>
                                      </div>
                                      <div>
                                          <h4 class="mb-0">Entenda</h4>
                                          <p>Alcance suas metas com segurança através de um planejamento personalizado.</p>
                                      </div>
                                  </div>
                              </li>
                              <li class="py-1">
                                  <div class="d-flex align-items-center">
                                      <div>
                                          <badge type="success" circle class="mr-3" icon="ni ni-settings"></badge>
                                      </div>
                                      <div>
                                          <h4 class="mb-0">Planeje</h4>
                                          <p>Alcance suas metas com segurança através de um planejamento personalizado.</p>
                                      </div>
                                  </div>
                              </li>
                              <li class="py-1">
                                  <div class="d-flex align-items-center">
                                      <div>
                                          <badge type="success" circle class="mr-3" icon="ni ni-settings"></badge>
                                      </div>
                                      <div>
                                          <h4 class="mb-0">Conquiste</h4>
                                          <p>Alcance suas metas com segurança através de um planejamento personalizado.</p>
                                      </div>
                                  </div>
                              </li>
                          </ul>
                      </div>
                  </div>
              </div>
          </div>
      </section>

      <!-- <section class="section">
          <div class="container">
              <div class="row text-center justify-content-center pb-4">
                  <div class="col-lg-10">
                      <h2 class="display-3">Testmonials</h2>
                      <p class="lead">What our clients talk about us.</p>
                  </div>
              </div>
              
              <div class="row justify-content-center">
                  <div class="col-lg-12">
                      <div class="row row-grid">
                          <div class="col-lg-6 d-flex">
                              <card class="border-0" hover shadow body-classes="py-5">
                                  <h6 class="text-primary text-uppercase">Jhon Doe</h6>
                                  <p class="description mt-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce magna  metus, iaculis nec tincidunt et, varius ut metus. Phasellus faucibus  cursus felis ut vehicula.</p>
                                  
                                  <div class="mr-0">
                                      <icon name="fa fa-star" color="info" class="pl-0"></icon>
                                      <icon name="fa fa-star" color="info"></icon>
                                      <icon name="fa fa-star" color="info"></icon>
                                      <icon name="fa fa-star" color="info"></icon>
                                      <icon name="fa fa-star" color="info"></icon>
                                  </div>
                                  <div class="pt-3">
                                      <base-button tag="a" href="#" type="primary">
                                      Learn more
                                  </base-button>
                                  </div>
                              </card>
                          </div>
                          <div class="col-lg-6">
                              <card class="border-0" hover shadow body-classes="py-5">
                                  <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                                  </icon>
                                  <h6 class="text-success text-uppercase">Build Something</h6>
                                  <p class="description mt-3">Argon is a great free UI package based on Bootstrap
                                      4 that includes the most important components and features.</p>
                                  <div>
                                      <badge type="success" rounded>business</badge>
                                      <badge type="success" rounded>vision</badge>
                                      <badge type="success" rounded>success</badge>
                                  </div>
                                  <base-button tag="a" href="#" type="success" class="mt-4">
                                      Learn more
                                  </base-button>
                              </card>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
      </section> -->

      <section id="sobre" class="section scroll-margin-top">
          <div class="container">
              <div class="row text-center justify-content-center mb-5">
                  <div class="col-lg-10">
                      <h2 class="display-3">Quem somos</h2>
                  </div>
              </div>

              <div class="row row-grid align-items-center">
                  <div class="col-md-6">
                      <div class="card bg-default shadow border-0">
                        <!-- <img src="img/theme/promo-1.png"> -->
                        <!-- <img src="/img/theme/quemsomos.jpg"> -->
                          <img v-lazy="'/img/theme/quemsomos.jpg'" class="card-img-top" alt="Descrição da imagem">
                      </div>
                  </div>
                  <div class="col-md-6">
                      <div class="pl-md-5">
                          <p class="lead">Transforme suas finanças e conquiste o futuro que você merece com a [Nome da Empresa]. Juntos, vamos além!</p>

                          <p>Na [Nome da Empresa], acreditamos que a liberdade financeira é alcançável para todos – basta um planejamento estratégico e as orientações corretas. Com anos de experiência no mercado, oferecemos soluções personalizadas para cada fase da sua vida financeira, sempre priorizando a transparência e o compromisso com os seus objetivos.</p>

                          <p>Nossa missão é simplificar o mundo dos investimentos, capacitando você a tomar decisões informadas e seguras. Seja para construir patrimônio, planejar a aposentadoria ou conquistar um sonho específico, estamos ao seu lado em cada passo.</p>
                      </div>
                  </div>
              </div>
          </div>
      </section>


      <section class="section section-lg">
          <div class="container">
              <card gradient="info"
                  no-body
                  shadow-size="lg"
                  class="border-0">
                  <div class="p-5">
                      <div class="row align-items-center">
                          <div class="col-lg-8">
                              <h3 class="text-white">Investir ficou mais simples.</h3>
                              <p class="lead text-white mt-3">Pense grande, invista com inteligência e alcance seus objetivos sem complicação. Com a nossa assessoria, você tem um plano personalizado para fazer seu dinheiro crescer com segurança.</p>
                          </div>
                          <div class="col-lg-4 ml-lg-auto">
                              <base-button tag="a" @click="redirectToWhatsApp" class="text-white" type="default" block size="lg">
                                  Fale com um consultor
                              </base-button>
                          </div>
                      </div>
                  </div>
              </card>
          </div>
      </section>

      <section id="contato" class="section scroll-margin-top">
          <div class="container">
              <div class="row text-center justify-content-center">
                  <div class="col-lg-10">
                      <h2 class="display-3">Contato</h2>
                      <h4 class="mb-1">Ficou interessado?</h4>
                      <p class="mt-0">Mande-nos uma mensagem.</p>
                  </div>
              </div>

              <div class="row justify-content-center">
                  <div class="col-lg-10">
                    <form @submit.prevent="sendEmail">
                        <card gradient="default" body-classes="p-lg-5">
                            <base-input class="mt-5"
                                v-model="form.name"
                                        alternative
                                        placeholder="Nome"
                                        addon-left-icon="ni ni-circle-08">
                            </base-input>
                            <base-input 
                                v-model="form.email"
                                    alternative
                                        placeholder="Email"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea 
                                    class="form-control form-control-alternative" 
                                    v-model="form.message"
                                    name="name" rows="4" cols="80" placeholder="Mensagem..."></textarea>
                            </base-input>
                            <base-button type="info" nativeType="submit" hover="true" round block size="lg">
                                Enviar
                            </base-button>
                            <p v-if="statusMessage">{{ statusMessage }}</p>
                        </card>
                    </form>
                  </div>
              </div>
          </div>
      </section>

  </div>
</template>

<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
    name: "home",
    components: {
    BCarousel,
    BCarouselSlide
    },
    data() {
        return {
        form: { name: "", email: "", message: "" },
        statusMessage: "",
        };
    },

    methods: {
        redirectToWhatsApp() {
            const phoneNumber = "5561998122458";
            const message = "Olá, gostaria de mais informações!";
            const encodedMessage = encodeURIComponent(message);
            const whatsappURL = `https://wa.me/${phoneNumber}?text=${encodedMessage}`;

            window.open(whatsappURL, "_blank", "noopener,noreferrer");
        },

        async sendEmail() {
            try {
                const response = await fetch("https://thaisgodev.com/sendEmail.php", {
                    method: "POST",
                    headers: { "Content-Type": "application/x-www-form-urlencoded"},
                    body: new URLSearchParams(this.form).toString(),
                });

                const data = await response.json();
                this.statusMessage = data.message;
            } catch (error) {
                console.error("Erro ao enviar email:", error);
                this.statusMessage = "Erro ao enviar o email.";
            }
        },
    }
};
</script>
