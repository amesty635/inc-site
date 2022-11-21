<template>
  <v-app>
    <v-app-bar
        color="secondary"
        fixed>
      <v-container class="d-flex align-center py-0">
        <v-app-bar-title class="pl-0">
          <div class="d-flex align-center">
            <v-avatar
                rounded="0"
                class="mr-3"
                image="https://cdn.vuetifyjs.com/docs/images/logos/v.png"
            />

            INCODICE
          </div>
        </v-app-bar-title>
        <div class="d-flex align-end">
          <v-btn variant="plain">
            Our Team
          </v-btn>
        </div>
      </v-container>
    </v-app-bar>

    <v-main>
      <section id="hero">
        <v-sheet
            class="d-flex align-center pb-16 fill-height"
            color="primary"

        >
          <v-container class="text-center">
            <v-responsive class="mx-auto" width="500">
              <v-img
                  src="https://cdn.vuetifyjs.com/docs/images/logos/v.png"
                  height="400"
              />

              <h3 class="text-h3">
                INCODICE
              </h3>

              <p class="mt-4 text-medium-emphasis">
                - Experts in the field of clinical laboratory diagnostics.
                We create unique products and solutions in the field of laboratory diagnostics and medicine.
              </p>
            </v-responsive>
          </v-container>
        </v-sheet>
      </section>

      <v-sheet class="py-16 bg-blue-grey-lighten-5">
        <section id="filter">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="auto">
                <v-responsive>
                  <h2 class="text-h5">
                    Management for the launch and transformation of laboratories
                  </h2>


                  <ul class="mt-8">
                    <li>Design of buildings and production sites</li>
                    <li>Development and planning of IT ecosystem</li>
                    <li>Project management for the implementation of information systems</li>
                    <li>Selection of the optimal equipment configuration</li>
                  </ul>

                </v-responsive>
              </v-col>
              <v-img
                  max-width="400"
                  src="./img/img_1_lab3d.png"
              />
            </v-row>
          </v-container>
        </section>

        <v-container>
          <v-divider class="my-12" color="primary"/>
        </v-container>

        <section id="controls">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="auto">
                <v-responsive>
                  <h2 class="text-h5">
                    Tools for modeling laboratory business processes
                  </h2>

                  <ul class="mt-8">
                    <li>Determining the optimal laboratory configuration</li>
                    <li>Preliminary risk assessment</li>
                    <li>Comparative analysis of suppliers' offers.</li>
                    <li><i>Can be used both for individual functional areas and for the entire laboratory</i></li>
                  </ul>

                </v-responsive>
              </v-col>

              <v-img
                  max-width="400"
                  src="./img/img_2_sim.png"
              />
            </v-row>
          </v-container>
        </section>

        <v-container>
          <v-divider class="my-12" color="primary"/>
        </v-container>

        <section id="controls">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="auto">
                <v-responsive>
                  <h2 class="text-h5">
                    Production Cost Modeling Tool
                  </h2>

                  <ul class="mt-8">
                    <li>A tool for dynamic control of the cost of performing research</li>
                    <li>Comparison of expected and actual costs</li>
                    <li>Monitoring the efficiency of the laboratory</li>
                    <li>Financial modeling of various scenarios for the launch and development of production</li>
                  </ul>

                </v-responsive>
              </v-col>

              <v-img
                  max-width="400"
                  src="./img/img_3_costs.png"
              />
            </v-row>
          </v-container>
        </section>


        <v-container>
          <v-divider class="my-12" color="primary"/>
        </v-container>

        <section id="grid">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="auto">
                <v-responsive>
                  <h2 class="text-h5">
                    Catalogues management system
                  </h2>
                  <ul class="mt-8">
                    <li>System of internal and external catalogues</li>
                    <li>Creation and organization of centralized administration of
                      catalogues for any laboratory information system
                    </li>
                    <li>Provides the required data quality for further analytics, use in
                      decision support tools
                    </li>
                    <li>Significantly facilitates and accelerates integration processes
                      and interactions with other systems.
                    </li>
                  </ul>

                </v-responsive>
              </v-col>

              <v-img
                  max-width="400"
                  src=""
              />
            </v-row>
          </v-container>
        </section>

        <v-container>
          <v-divider class="my-12" color="primary"/>
        </v-container>

        <section id="grid">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="auto">
                <v-responsive>
                  <h2 class="text-h5">
                    Data collection and analysis infrastructure
                  </h2>
                  <ul class="mt-8">
                    <li>Development of interactive analytical dashboards</li>
                    <li>Infrastructure design - ETL, DWH, BI</li>
                    <li>Definition of key laboratory performance metrics, considering
                      the specifics of the laboratory's business model
                    </li>
                    <li>Monitoring of key performance indicators</li>
                  </ul>

                  <v-btn
                      class="mt-6 "
                      href=""
                      target="_blank"
                      rel="noopener noreferrer"

                  >
                    Want to know more?
                  </v-btn>

                </v-responsive>
              </v-col>

              <v-img
                  max-width="400"
                  src="./img/img_4_bi.png"
              />
            </v-row>
          </v-container>
        </section>

        <v-container>
          <v-divider class="my-12" color="primary"/>
        </v-container>

        <section id="grid">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="auto">
                <v-responsive>
                  <h2 class="text-h5">
                    Incodice Sample Tracker
                  </h2>
                  <ul class="mt-8">
                    <li>A system for tracking biomaterial from the moment of taking to the receipt of results.</li>
                    <li>Measurement and control of performance, work of employees, and biomaterial location</li>
                    <li>Does not require LIS, but integration is possible.</li>
                    <li>Works on both computers and mobile devices.</li>
                  </ul>

                  <v-btn
                      class="mt-6 "
                      href=""
                      target="_blank"
                      rel="noopener noreferrer"

                  >
                    Want to know more?
                  </v-btn>

                </v-responsive>
              </v-col>

              <v-img
                  max-width="400"
                  src="./img/img_5_ist.png"
              />
            </v-row>
          </v-container>
        </section>
      </v-sheet>

      <v-sheet
          class="py-16"
          color="primary"
      >
        <section >
          <v-container id="team">
            <h2 class="text-h4">
              Who we are?
            </h2>
          </v-container>
        </section>
        <section id="grid">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="10">
                <v-responsive>

                  <h2 class="text-h5">
                    Boris Gorodetskiy
                  </h2>
                  <p class="mt-5">
                    Doctor of Clinical laboratory diagnostics. 8 years of experience in management and organizational
                    activities in clinical diagnostic laboratories. Conducted consultations for groups of laboratories
                    in various countries (France, Saudi Arabia, India, etc.). Specialization in scientific and medical
                    activities in the field of laboratory diagnostics, management and automation of modern specialized
                    laboratories
                  </p>
                </v-responsive>
              </v-col>
              <v-col>
                <v-img
                    max-width="200"
                    src="./img/img_BG.png"
                />
              </v-col>
            </v-row>
          </v-container>


        </section>
        <v-container>
          <v-divider class="my-12"/>
        </v-container>
        <section id="grid">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="10">
                <v-responsive>

                  <h2 class="text-h5">
                    Roman Kuvshinov
                  </h2>
                  <p class="mt-5">
                    More than 10 years of experience in the laboratory industry in the field of automation of laboratory
                    processes, implementation and development of laboratory information systems, creation of BI
                    infrastructure, design and simulation of laboratory flows
                  </p>
                </v-responsive>
              </v-col>
              <v-col>
                <v-img
                    max-width="200"
                    src="./img/img_RK.png"
                />
              </v-col>
            </v-row>
          </v-container>
        </section>

        <v-container>
          <v-divider class="my-12"/>
        </v-container>

        <section id="grid">
          <v-container>
            <v-row justify="space-between">
              <v-col cols="10">
                <v-responsive>

                  <h2 class="text-h5">
                    Evgeniy Akimov
                  </h2>
                  <p class="mt-5">
                    More than 20 years of experience in IT, of which more than 5 years in the laboratory industry in
                    Russia and Europe. Worked in - Citilab, Exalab. As a consultant, he collaborated with companies such
                    as Abbott, Beckman Coulter, took part in World Bank projects in the field of healthcare.
                  </p>
                </v-responsive>
              </v-col>
              <v-col>
                <v-img
                    max-width="200"
                    src="./img/img_EA.png"
                />
              </v-col>
            </v-row>
          </v-container>
        </section>
        <v-btn
            class="mt-6"
            href=""
            target="_blank"
            rel="noopener noreferrer"
            color="secondary"
        >
          Contact us
        </v-btn>
      </v-sheet>
    </v-main>

    <v-footer color="secondary">
      <v-container class="text-overline d-flex align-center justify-space-between">
        <div>
          Copyright &copy; 2022 Incodice, LLC
        </div>

      </v-container>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'App',
}
</script>
