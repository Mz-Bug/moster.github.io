<template>
  <q-page class="q-pa-sm bg-dark area">
    <div class="row q-mr-xl q-ml-md">
      <ul class="circles">
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
      </ul>
      <div class="col-3 col-sm-12 col-md-3">
        <q-card
          dark
          class="my-card q-py-sm bg-transparent q-mt-lg"
          style="border-radius: 30px"
          bordered
          flat
        >
          <q-card-section>
            <div class="row">
              <div class="col-6 text-h3">MaAz</div>
              <div class="col-6 text-regular text-right">
                Framer Designer & Developer
              </div>
            </div>
          </q-card-section>
          <q-card-section>
            <q-img
              src="~assets/profile.png"
              alt="profile image"
              fit="contain"
              :ratio="4 / 3"
            />
          </q-card-section>
          <q-card-section class="text-center text-h6">
            hello@MaAz.Developer Base in Lahore, Punjab Pakistan
          </q-card-section>
          <q-card-section class="q-py-none text-center text-grey">
            © 2022 MaAz. All Rights Reserved
          </q-card-section>
          <q-card-section class="text-center">
            <div class="q-gutter-sm">
              <q-btn
                round
                size="17px"
                icon="eva-twitter"
                outline
                color="grey"
                class="button1"
                href="https://twitter.com/MaAz_oo"
                target="_blank"
              />
              <q-btn
                round
                size="17px"
                outline
                icon="eva-globe"
                color="grey"
                class="button1"
                href="https://stackoverflow.com/users/20837883/maaz"
                target="_blank"
              />
              <q-btn
                round
                size="17px"
                outline
                icon="eva-linkedin"
                color="grey"
                class="button1"
                href="https://www.linkedin.com/in/maaz-ali-07b0aa202/"
                target="_blank"
              />
              <q-btn
                round
                size="17px"
                outline
                icon="eva-github"
                color="grey"
                class="button1"
                href="https://github.com/Mz-Bug"
                target="_blank"
              />
            </div>
          </q-card-section>
          <q-card-section>
            <q-btn
              rounded
              align="center"
              class="full-width q-py-md text-black text-weight-regular mainbutton"
              color="positive"
              icon="eva-email-outline"
              label="Hire Me"
            />
          </q-card-section>
        </q-card>
      </div>

      <div class="col-8 container">
        <q-scroll-area style="height: 95vh">
          <div style="margin-top: 100px; margin-left: 20vh" ref="introduce">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="eva-home-outline" color="white" />
              <span class="q-pl-sm text-white">introduce</span>
            </q-btn>
            <div
              class="text-weight-thin q-mt-xl text-white"
              style="font-size: 60px"
            >
              Say Hi from <span class="text-positive">MaAz</span>, <br />
              Framer Designer and Developer
            </div>
            <div class="text-grey q-mt-lg text-h5">
              I design and code beautifully simple things and i love what i do.
              <br />
              Just simple like that!
            </div>
            <div class="q-mt-lg">
              <div class="row text-white">
                <div class="q-mr-xl">
                  <span class="text-h1 text-positive">1+</span>
                  <br />
                  <div class="q-pl-md">
                    YEARS OF <br />
                    EXPERIENCE
                  </div>
                </div>
                <div class="q-ml-xl">
                  <span class="text-h1 text-positive">15+</span>
                  <br />
                  <div class="q-pl-md">
                    PROJECTS COMPLETED ON <br />
                    3 COUNTRIES
                  </div>
                </div>
              </div>
              <br />
            </div>
          </div>
          <div style="margin-top: 150px; margin-left: 20vh" ref="ABOUT">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="eva-person-outline" color="white" />
              <span class="q-pl-sm text-white">ABOUT</span>
            </q-btn>

            <div
              class="text-weight-thin q-mt-xl text-white"
              style="font-size: 60px"
            >
              Every great design begin with an even
              <span class="text-positive">better story</span>
            </div>
            <div class="text-grey q-mt-lg text-h5 text-justify">
              Since beginning my journey as a freelance designer nearly 1 years
              ago, I've done remote work for agencies, consulted for startups,
              and collaborated with talented people to create digital products
              for both business and consumer use. I'm quietly confident,
              naturally curious, and perpetually working on improving my
              chopsone design problem at a time.
            </div>
          </div>
          <div style="margin-top: 150px; margin-left: 20vh" ref="RESUME">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="eva-file-text-outline" color="white" />
              <span class="q-pl-sm text-white">RESUME</span>
            </q-btn>
            <div class="q-px-lg q-pb-md text-white">
              <q-timeline dark color="secondary">
                <q-timeline-entry heading>
                  <div class="text-weight-thin q-mt-xl" style="font-size: 60px">
                    Education &
                    <span class="text-positive">Experience</span>
                  </div></q-timeline-entry
                >

                <q-timeline-entry
                  subtitle="2023 - Present "
                  color="positive"
                  class="q-pb-xl text-grey"
                >
                  <div class="text-h6 q-mt-lg text-white">
                    Framer Desinger & Developer"
                  </div>
                  <div>Powersoft Pvt Ltd</div>
                  <div class="text-h6 q-mt-lg text-white">
                    Framer Web & Mobile app Developer"
                  </div>
                  <div>Android and IOS App</div>
                </q-timeline-entry>
                <q-timeline-entry
                  subtitle="2021 - 2022"
                  color="positive"
                  class="q-pb-xl text-grey"
                >
                  <div class="text-h6 q-mt-lg text-white">
                    Webflow Developer
                  </div>
                  <div>Designflow Studio</div>
                  <div class="text-h6 q-mt-lg text-white">Web Development</div>
                  <div>Freelance</div>
                  <div class="text-h6 q-mt-lg text-white">Projects</div>
                  <div>Workout App (Final Year Project)</div>
                  <div>Multikart website</div>
                  <div>CRM-based project</div>
                  <div>POS Front-End</div>
                </q-timeline-entry>
                <q-timeline-entry
                  subtitle="2018 - 2022"
                  color="positive"
                  class="q-pb-xl text-grey"
                >
                  <div class="text-h6 q-mt-lg text-white">
                    Bachelor's in Computer Science
                  </div>
                  <div>Government College University, Lahore</div>
                  <div class="text-h6 q-mt-lg text-white">
                    Search Engine Optimization
                  </div>
                  <div>DigiSkills Training Program</div>
                </q-timeline-entry>
              </q-timeline>
            </div>
          </div>

          <div style="margin-top: 150px; margin-left: 20vh" ref="SERVICES">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="eva-hard-drive-outline" color="white" />
              <span class="q-pl-sm text-white">SERVICES</span>
            </q-btn>

            <div
              class="text-weight-thin q-mt-xl text-white"
              style="font-size: 60px"
            >
              My
              <span class="text-positive">Specializations</span>
            </div>
            <div class="q-mt-lg">
              <q-card
                dark
                class="my-card bg-transparent q-my-sm card"
                style="border-radius: 30px"
                bordered
                flat
                v-for="item in skills"
                :key="item"
              >
                <q-card-section class="text-white">
                  <q-item>
                    <q-item-section>
                      <q-item-label class="text-h5 q-py-md">{{
                        item.title
                      }}</q-item-label>
                      <q-item-label lines="2" class="text-grey">{{
                        item.description
                      }}</q-item-label>
                    </q-item-section>

                    <q-item-section side top>
                      <q-icon :name="item.icon" color="positive" size="lg" />
                    </q-item-section>
                  </q-item>
                </q-card-section>
                <q-card-section>
                  <q-item>
                    <q-item-section>
                      <q-item-label>{{ item.project }}</q-item-label>
                    </q-item-section>
                  </q-item>
                </q-card-section>
              </q-card>
            </div>
          </div>

          <div style="margin-top: 150px; margin-left: 20vh" ref="SKILLS">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="eva-layers-outline" color="white" />
              <span class="q-pl-sm text-white">MY SKILLS</span>
            </q-btn>

            <div
              class="text-weight-thin q-mt-xl text-white"
              style="font-size: 60px"
            >
              My
              <span class="text-positive">Advantages</span>
            </div>
            <div class="text-grey row q-gutter-lg q-mt-md">
              <div v-for="item in advantages" :key="item">
                <q-card
                  dark
                  class="my-card q-px-lg q-py-md bg-transparent card"
                  style="border-radius: 80px; width: 170px; height: 200px"
                  bordered
                  flat
                >
                  <div class="text-center">
                    <div class="q-gutter-sm q-py-md text-grey">
                      <q-icon size="80px">
                        <q-img :src="require(`assets/${item.src}`)" />
                      </q-icon>
                    </div>
                    <div class="text-h4 text-positive q-pl-sm">
                      {{ item.number }}
                    </div>
                  </div>
                </q-card>
                <p class="text-center q-pt-md text-subtitle1 text-white">
                  {{ item.name }}
                </p>
              </div>
            </div>
          </div>
          <div style="margin-top: 150px; margin-left: 20vh" ref="PORTFOLIO">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="eva-grid-outline" color="white" />
              <span class="q-pl-sm text-white">PORTFOLIO</span>
            </q-btn>

            <div
              class="text-weight-thin q-mt-xl text-white"
              style="font-size: 60px"
            >
              Featured
              <span class="text-positive">Projects</span>
            </div>
            <div class="text-grey q-mt-lg">
              <q-img src="~assets/portfolio2.jpg" style="border-radius: 30px">
                <div class="absolute-bottom bg-transparent">
                  <div class="q-gutter-md">
                    <q-btn
                      no-caps
                      rounded
                      class="text-black q-px-lg q-py-sm button2"
                      color="grey-3"
                      label="WordPress"
                      @click="onClick"
                    />
                    <q-btn
                      no-caps
                      rounded
                      class="text-black q-px-lg q-py-sm button2"
                      color="grey-3"
                      label="Framer"
                      @click="onClick"
                    />
                    <q-btn
                      no-caps
                      rounded
                      class="text-black q-px-lg q-py-sm button2"
                      color="grey-3"
                      label="Figma"
                      @click="onClick"
                    />
                  </div>
                </div>
              </q-img>
              <div class="q-py-lg text-h5">
                <a href="" class="text-white" style="text-decoration: none"
                  >Bureau - Architecture Studio Website</a
                >
              </div>
              <div class="row q-col-gutter-xl q-mt-md">
                <div class="col-6">
                  <q-img
                    src="~assets/portfolio3.jpg"
                    style="border-radius: 30px; height: 400px"
                  >
                    <div class="absolute-bottom bg-transparent">
                      <div class="q-gutter-md">
                        <q-btn
                          no-caps
                          rounded
                          class="text-black q-px-lg q-py-sm button2"
                          color="grey-3"
                          label="WordPress"
                          @click="onClick"
                        />
                        <q-btn
                          no-caps
                          rounded
                          class="text-black q-px-lg q-py-sm button2"
                          color="grey-3"
                          label="Framer"
                          @click="onClick"
                        />
                      </div>
                    </div>
                  </q-img>
                  <div class="q-py-lg text-h5">
                    <a href="" class="text-white" style="text-decoration: none"
                      >Moonex WordPress Theme</a
                    >
                  </div>
                </div>
                <div class="col-6">
                  <q-img
                    src="~assets/portfolio4.jpg"
                    style="border-radius: 30px; height: 400px"
                  >
                    <div class="absolute-bottom bg-transparent">
                      <div class="q-gutter-md">
                        <q-btn
                          no-caps
                          rounded
                          class="text-black q-px-lg q-py-sm button2"
                          color="grey-3"
                          label="WordPress"
                          @click="onClick"
                        />
                        <q-btn
                          no-caps
                          rounded
                          class="text-black q-px-lg q-py-sm button2"
                          color="grey-3"
                          label="Framer"
                          @click="onClick"
                        />
                      </div>
                    </div>
                  </q-img>
                  <div class="q-py-lg text-h5">
                    <a href="" class="text-white" style="text-decoration: none"
                      >Taskly Dashboard</a
                    >
                  </div>
                </div>
              </div>
              <q-img
                src="~assets/portfolio5.jpg"
                class="q-mt-xl"
                style="border-radius: 30px"
              >
                <div class="absolute-bottom bg-transparent">
                  <div class="q-gutter-md">
                    <q-btn
                      no-caps
                      rounded
                      class="text-black q-px-lg q-py-sm button2"
                      color="grey-3"
                      label="WordPress"
                      @click="onClick"
                    />
                    <q-btn
                      no-caps
                      rounded
                      class="text-black q-px-lg q-py-sm button2"
                      color="grey-3"
                      label="Vue Js"
                      @click="onClick"
                    />
                  </div>
                </div>
              </q-img>
              <div class="q-py-lg text-h5">
                <a href="" class="text-white" style="text-decoration: none"
                  >Hinterland - Real Estate Site Redesign</a
                >
              </div>
              <q-img
                src="~assets/portfolio6.jpg"
                class="q-mt-xl"
                style="border-radius: 30px"
              >
                <div class="absolute-bottom bg-transparent">
                  <div class="q-gutter-md">
                    <q-btn
                      no-caps
                      rounded
                      class="text-black q-px-lg q-py-sm button2"
                      color="grey-3"
                      label="WordPress"
                      @click="onClick"
                    />
                    <q-btn
                      no-caps
                      rounded
                      class="text-black q-px-lg q-py-sm button2"
                      color="grey-3"
                      label="Vue Js"
                      @click="onClick"
                    />
                  </div>
                </div>
              </q-img>
              <div class="q-py-lg text-h5">
                <a href="" class="text-white" style="text-decoration: none"
                  >Lewis Portfolio Framer Template</a
                >
              </div>
            </div>
          </div>
          <div style="margin-top: 150px; margin-left: 20vh" ref="TESTIMONIAL">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="eva-award-outline" color="white" />
              <span class="q-pl-sm text-white">TESTIMONIAL</span>
            </q-btn>

            <div
              class="text-weight-thin q-mt-xl text-white"
              style="font-size: 60px"
            >
              Trusted by
              <span class="text-positive">Hundered Clients</span>
            </div>
            <div class="text-grey q-mt-lg">
              <q-card style="border-radius: 30px" bordered flat dark>
                <q-carousel
                  transition-prev="slide-right"
                  transition-next="slide-left"
                  autoplay
                  swipeable
                  animated
                  v-model="slide"
                  ref="carousel"
                  infinite
                  class="bg-transparent"
                  height="auto"
                >
                  <q-carousel-slide :name="1">
                    <q-card-section>
                      <q-item>
                        <q-item-section top avatar>
                          <q-avatar>
                            <img
                              src="~assets/testimonial-1.jpg"
                              alt="testmonial"
                            />
                          </q-avatar>
                        </q-item-section>
                        <q-item-section>
                          <q-item-label class="text-h6"
                            >Paublo Dybala</q-item-label
                          >
                          <q-item-label lines="2" class="text-white"
                            >CEO of
                            <span class="text-positive"
                              >IBM Global</span
                            ></q-item-label
                          >
                        </q-item-section>
                      </q-item>
                    </q-card-section>
                    <q-card-section>
                      <q-item>
                        <q-item-section>
                          <q-item-lebel class="text-h5">
                            Maaz - A Developer with the creativity, professional
                            and master of code. Much more than what i'm expect.
                            High quality product & flexiable price.
                            Recommended!.”
                          </q-item-lebel>
                          <q-item-lebel class="q-py-md">
                            <q-btn
                              dense
                              flat
                              label="PROJECTS"
                              @click="onClick"
                            />
                          </q-item-lebel>
                        </q-item-section>
                      </q-item>
                    </q-card-section>
                  </q-carousel-slide>
                  <q-carousel-slide :name="2">
                    <q-card-section>
                      <q-item>
                        <q-item-section top avatar>
                          <q-avatar>
                            <img
                              src="~assets/testimonial-3.jpg"
                              alt="testmonial"
                            />
                          </q-avatar>
                        </q-item-section>
                        <q-item-section>
                          <q-item-label class="text-h6"
                            >Phil Foden</q-item-label
                          >
                          <q-item-label lines="2" class="text-white"
                            >Director of
                            <span class="text-positive"
                              >Envato LLC</span
                            ></q-item-label
                          >
                        </q-item-section>
                      </q-item>
                    </q-card-section>
                    <q-card-section>
                      <q-item>
                        <q-item-section>
                          <q-item-lebel class="text-h5">
                            "Maaz was a real pleasure to work with and we look
                            forward to working with him again. He's definitely
                            the kind of designer that you can trust with any
                            project from A-Z.”
                          </q-item-lebel>
                          <q-item-lebel class="q-py-md">
                            <q-btn
                              dense
                              flat
                              label="PROJECTS"
                              @click="onClick"
                            />
                          </q-item-lebel>
                        </q-item-section>
                      </q-item>
                    </q-card-section>
                  </q-carousel-slide>
                  <q-carousel-slide :name="3">
                    <q-card-section>
                      <q-item>
                        <q-item-section top avatar>
                          <q-avatar>
                            <img
                              src="~assets/testimonial-2.jpg"
                              alt="testmonial"
                            />
                          </q-avatar>
                        </q-item-section>
                        <q-item-section>
                          <q-item-label class="text-h6"
                            >Christina Morillo</q-item-label
                          >
                          <q-item-label lines="2" class="text-white"
                            >Product Management of
                            <span class="text-positive"
                              >Invision App Inc</span
                            ></q-item-label
                          >
                        </q-item-section>
                      </q-item>
                    </q-card-section>
                    <q-card-section>
                      <q-item>
                        <q-item-section>
                          <q-item-lebel class="text-h5">
                            “Extremely profressional and fast service!. Drake is
                            a master of code and he also very creative. We done
                            3 projects with him and certain will continue.”
                          </q-item-lebel>
                          <q-item-lebel class="q-py-md">
                            <q-btn
                              dense
                              flat
                              label="PROJECTS"
                              @click="onClick"
                            />
                          </q-item-lebel>
                        </q-item-section>
                      </q-item>
                    </q-card-section>
                  </q-carousel-slide>
                </q-carousel>
              </q-card>
              <div class="q-my-sm q-pl-sm q-gutter-md">
                <q-btn
                  round
                  outline
                  class="text-grey"
                  style="border-radius: 30px"
                  @click="$refs.carousel.previous()"
                >
                  <q-icon name="eva-arrow-ios-back-outline" color="white" />
                </q-btn>
                <q-btn
                  round
                  outline
                  class="text-grey"
                  style="border-radius: 30px"
                  @click="$refs.carousel.next()"
                >
                  <q-icon name="eva-arrow-ios-forward-outline" color="white" />
                </q-btn>
              </div>
              <div style="margin-top: 100px">
                WORK WITH 10+ BRANDS WORLDWIDE
                <div class="row q-gutter-xl">
                  <q-icon
                    size="150px"
                    v-for="item in logo"
                    :key="item"
                    class="logo"
                  >
                    <q-img :src="require(`assets/${item.src}`)" />
                  </q-icon>
                </div>
              </div>
            </div>
          </div>
          <div style="margin-top: 150px; margin-left: 20vh">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="attach_money" color="white" />
              <span class="q-pl-sm text-white">PRICING</span>
            </q-btn>

            <div
              class="text-weight-thin q-mt-xl text-white"
              style="font-size: 60px"
            >
              My
              <span class="text-positive">Pricing</span>
            </div>
            <div class="row q-col-gutter-md">
              <div class="col-6">
                <q-card
                  dark
                  class="my-card full-height q-py-sm bg-transparent q-mt-lg card"
                  style="border-radius: 30px"
                  bordered
                  flat
                >
                  <q-card-section>
                    <div class="row q-px-md">
                      <div class="col-6 text-h5">BASIC</div>
                      <div class="col-6 text-regular text-right">
                        Have design ready to build? or small budgetr
                      </div>
                    </div>
                  </q-card-section>
                  <q-card-section>
                    <div class="q-px-md">
                      <span class="text-positive text-h3"> $49</span>
                      <span class="text-h5 text-grey q-pl-sm">/ hours </span>
                    </div>
                  </q-card-section>
                  <q-separator dark inset />
                  <q-card-section class="q-my-md">
                    <div class="q-py-sm">Need your wireframe</div>
                    <div class="q-py-sm">Design with Figma, Framer</div>
                    <div class="q-py-sm">
                      Implement Front-End with Quasar, Vue js, HTML,CSS,
                      javascript
                    </div>
                    <div class="q-py-sm">Node js/ Firebase</div>
                    <div class="q-py-sm">Remote/Online</div>
                    <div class="q-py-sm">
                      Work in business days, no weekend.
                    </div>
                    <div class="q-py-sm">Support 1 months</div>
                  </q-card-section>
                  <q-card-section>
                    <q-btn
                      rounded
                      align="center"
                      class="full-width q-py-md text-black text-weight-regular mainbutton"
                      color="positive"
                      icon="eva-email-outline"
                      label="Pick this plan"
                    />
                  </q-card-section>
                </q-card>
              </div>
              <div class="col-6">
                <q-card
                  dark
                  class="my-card full-height q-py-sm bg-transparent q-mt-lg card"
                  style="border-radius: 30px"
                  bordered
                  flat
                >
                  <q-card-section>
                    <div class="row q-px-md">
                      <div class="col-6 text-h5">PREMIUM</div>
                      <div class="col-6 text-regular text-right">
                        Not have any design? Leave its for me
                      </div>
                    </div>
                  </q-card-section>
                  <q-card-section>
                    <div class="q-px-md">
                      <span class="text-positive text-h3"> $99</span>
                      <span class="text-h5 text-grey q-pl-sm">/ hours</span>
                    </div>
                  </q-card-section>
                  <q-separator dark inset />
                  <q-card-section>
                    <div class="q-py-sm">Don't need wireframe or anything</div>
                    <div class="q-py-sm">
                      Design with Figma, Framer from scratch
                    </div>
                    <div class="q-py-sm">
                      Implement Front-End with Quasar, Vue js, HTML,CSS,
                      javascript,
                    </div>
                    <div class="q-py-sm">Node js/ Firebase</div>
                    <div class="q-py-sm">Remote/Online</div>
                    <div class="q-py-sm">Work with both weekend</div>
                    <div class="q-py-sm">Support 3 months</div>
                    <div class="q-py-sm">Your project alway be priority</div>
                  </q-card-section>
                  <q-card-section>
                    <q-btn
                      rounded
                      align="center"
                      class="full-width q-py-md text-black text-weight-regular mainbutton"
                      color="positive"
                      icon="eva-email-outline"
                      label="Pick this plan"
                    />
                  </q-card-section>
                </q-card>
              </div>
            </div>
            <div class="q-my-xl q-pt-xl text-grey-11">
              Don't find any package match with your plan! <br />
              Want to setup a new tailor-made package for only you?.
              <a href="" class="text-positive">Contact Us</a>
            </div>
          </div>
          <div style="margin-top: 150px; margin-left: 20vh" ref="CONTACT">
            <q-btn
              rounded
              outline
              dense
              size="sm"
              class="text-grey q-px-lg q-py-sm"
            >
              <q-icon name="eva-message-circle-outline" color="white" />
              <span class="q-pl-sm text-white">CONTACT</span>
            </q-btn>

            <div
              class="text-weight-thin q-mt-xl text-white"
              style="font-size: 60px"
            >
              Let's
              <span class="text-positive"> Work Together!</span>
            </div>
            <div class="text-grey q-mt-lg">
              <div class="row q-col-gutter-md">
                <div class="col-6">
                  <q-card
                    dark
                    class="my-card full-height q-py-sm bg-transparent"
                    flat
                  >
                    <q-card-section>
                      <div>FULL NAME *</div>
                      <div>
                        <q-input
                          class="text-white"
                          outlined
                          v-model="text"
                          placeholder="Your Full Name"
                          color="white"
                        />
                      </div>
                    </q-card-section>

                    <q-card-section>
                      <div>PHONE <span class="text-grey">(optional)</span></div>
                      <div>
                        <q-input
                          class="text-white"
                          outlined
                          v-model="text"
                          placeholder="Your Number Phone"
                          color="white"
                        />
                      </div>
                    </q-card-section>

                    <q-card-section>
                      <div>
                        YOUR BUDGET<span class="text-grey">(optional)</span>
                      </div>
                      <div>
                        <q-input
                          class="text-white"
                          outlined
                          v-model.number="model"
                          type="number"
                          placeholder="Your Budget"
                          color="white"
                        />
                      </div>
                    </q-card-section>

                    <q-card-section>
                      <div>MESSAGE</div>
                      <div>
                        <q-input
                          class="text-white"
                          outlined
                          v-model="text"
                          placeholder="Write your message here"
                          color="white"
                        />
                      </div>
                    </q-card-section>
                  </q-card>
                </div>
                <div class="col-6">
                  <q-card
                    dark
                    class="my-card full-height q-py-sm bg-transparent"
                    flat
                  >
                    <q-card-section>
                      <div>EMAIL *</div>
                      <div>
                        <q-input
                          class="text-white"
                          outlined
                          v-model="email"
                          placeholder="Your Full Name"
                          color="white"
                        />
                      </div>
                    </q-card-section>

                    <q-card-section>
                      <div>SUBJECT *</div>
                      <div>
                        <q-select
                          outlined
                          v-model="model1"
                          :options="options"
                          :placeholder="model1"
                        />
                      </div>
                    </q-card-section>
                  </q-card>
                </div>
              </div>
              <div class="q-my-lg">
                <q-separator dark inset />
              </div>
              <div>
                <q-btn
                  rounded
                  align="center"
                  class="q-py-md q-px-lg text-black text-weight-regular mainbutton"
                  color="positive"
                  icon="eva-email-outline"
                  label="SEND MESSAGE"
                />
              </div>
            </div>
          </div>
        </q-scroll-area>
      </div>

      <div class="col text-center" style="margin-top: 100px">
        <q-btn round outline class="text-grey" style="border-radius: 30px">
          <q-icon name="eva-menu-outline" color="white" />
        </q-btn>
        <div class="flex flex-center">
          <q-card
            dark
            class="my-card q-py-sm bg-transparent q-mt-xl"
            style="border-radius: 30px; width: 60px"
            bordered
            flat
          >
            <div class="q-gutter-sm q-py-md text-grey">
              <q-btn
                icon="eva-home-outline"
                class="button1"
                @click="scrollToContent($refs.introduce)"
              >
                <q-tooltip
                  anchor="center left"
                  self="center right"
                  :offset="[10, 10]"
                  transition-show="rotate"
                  transition-hide="scale"
                >
                  <span>Home</span>
                </q-tooltip>
              </q-btn>
              <q-btn
                icon="eva-person-outline"
                class="button1"
                @click="scrollToContent($refs.ABOUT)"
              >
                <q-tooltip
                  anchor="center left"
                  self="center right"
                  :offset="[10, 10]"
                  transition-show="rotate"
                  transition-hide="scale"
                >
                  <span>About</span>
                </q-tooltip></q-btn
              >
              <q-btn
                icon="eva-file-text-outline"
                class="button1"
                @click="scrollToContent($refs.RESUME)"
              >
                <q-tooltip
                  anchor="center left"
                  self="center right"
                  :offset="[10, 10]"
                  transition-show="rotate"
                  transition-hide="scale"
                >
                  <span>Resume</span>
                </q-tooltip>
              </q-btn>
              <q-btn
                icon="eva-hard-drive-outline"
                class="button1"
                @click="scrollToContent($refs.SERVICES)"
              >
                <q-tooltip
                  anchor="center left"
                  self="center right"
                  :offset="[10, 10]"
                  transition-show="rotate"
                  transition-hide="scale"
                >
                  <span>Services</span>
                </q-tooltip>
              </q-btn>
              <q-btn
                icon="eva-layers-outline"
                class="button1"
                @click="scrollToContent($refs.SKILLS)"
              >
                <q-tooltip
                  anchor="center left"
                  self="center right"
                  :offset="[10, 10]"
                  transition-show="rotate"
                  transition-hide="scale"
                >
                  <span>Skills</span>
                </q-tooltip>
              </q-btn>
              <q-btn
                icon="eva-grid-outline"
                class="button1"
                @click="scrollToContent($refs.PORTFOLIO)"
              >
                <q-tooltip
                  anchor="center left"
                  self="center right"
                  :offset="[10, 10]"
                  transition-show="rotate"
                  transition-hide="scale"
                >
                  <span>Portfolio</span>
                </q-tooltip>
              </q-btn>
              <q-btn
                icon="eva-award-outline"
                class="button1"
                @click="scrollToContent($refs.TESTIMONIAL)"
              >
                <q-tooltip
                  anchor="center left"
                  self="center right"
                  :offset="[10, 10]"
                  transition-show="rotate"
                  transition-hide="scale"
                >
                  <span>Testimonial</span>
                </q-tooltip>
              </q-btn>
              <q-btn
                icon="eva-message-circle-outline"
                class="button1"
                @click="scrollToContent($refs.CONTACT)"
              >
                <q-tooltip
                  anchor="center left"
                  self="center right"
                  :offset="[10, 10]"
                  transition-show="rotate"
                  transition-hide="scale"
                >
                  <span>Contact</span>
                </q-tooltip>
              </q-btn>
            </div>
          </q-card>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
import { ref } from "vue";
const skills = [
  {
    title: "Website Design",
    description:
      "I created digital products with unique ideas use Figma & Framer",
    project: "24 PROJECTS",
    icon: "code",
  },
  {
    title: "Development",
    description: "I build website go live with Framer, Webflow or WordPress",
    project: "8 PROJECTS",
    icon: "developer_mode",
  },
  {
    title: "SEO/Marketing",
    description: "Increase the traffic for your website with SEO optimized",
    project: "24 PROJECTS",
    icon: "account_tree",
  },
];
const logo = [
  {
    src: "logo.png",
  },
  {
    src: "logo2.png",
  },
  {
    src: "logo3.png",
  },
  {
    src: "logo4.png",
  },
  {
    src: "logo5.png",
  },
  {
    src: "logo6.png",
  },
  {
    src: "logo7.png",
  },
  {
    src: "logo8.png",
  },
];
const advantages = [
  {
    src: "figma.svg",
    number: "85%",
    name: "Figma",
  },
  {
    src: "wordpress.svg",
    number: "80%",
    name: "WordPress",
  },
  {
    src: "vue.svg",
    number: "85%",
    name: "Vue js",
  },
  {
    src: "node.svg",
    number: "80%",
    name: "Node js",
  },
  {
    src: "firebase.svg",
    number: "90%",
    name: "Firebase",
  },
  {
    src: "seo.svg",
    number: "95%",
    name: "SEO",
  },
  {
    src: "html.svg",
    number: "100%",
    name: "Html",
  },
  {
    src: "css.svg",
    number: "100%",
    name: "CSS",
  },
  {
    src: "boot.svg",
    number: "100%",
    name: "Bootstrap",
  },
  {
    src: "javascript.svg",
    number: "90%",
    name: "javascript",
  },
  {
    src: "quasar.svg",
    number: "90%",
    name: "Quasae framework",
  },
];
export default {
  setup() {
    const model = ref(10);
    const model1 = ref("Google");
    const slide = ref(1);

    function scrollToContent(contentRef) {
      contentRef.scrollIntoView({ behavior: "smooth" });
    }
    return {
      skills,
      advantages,
      logo,
      slide,
      model,
      model1,
      options: ["Google", "Facebook", "Twitter", "Apple", "Oracle"],
      scrollToContent,
    };
  },
};
</script>
<style>
@import url("https://fonts.googleapis.com/css?family=Exo:400,700");

* {
  margin: 0px;
  padding: 0px;
}

body {
  font-family: "Exo", sans-serif;
}

.context {
  width: 100%;
  position: absolute;
  top: 50vh;
}

.context h1 {
  text-align: center;
  color: #fff;
  font-size: 50px;
}

.area {
  background: #000000;
  /* background: -webkit-linear-gradient(to left, #0f1af0, #060fb5); */
  width: 100%;
  height: 100vh;
}

.circles {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.circles li {
  position: absolute;
  display: block;
  list-style: none;
  width: 20px;
  height: 20px;
  background: rgba(255, 255, 255, 0.2);
  animation: animate 25s linear infinite;
  bottom: -150px;
}

.circles li:nth-child(1) {
  left: 25%;
  width: 80px;
  height: 80px;
  animation-delay: 0s;
}

.circles li:nth-child(2) {
  left: 10%;
  width: 20px;
  height: 20px;
  animation-delay: 2s;
  animation-duration: 12s;
}

.circles li:nth-child(3) {
  left: 70%;
  width: 20px;
  height: 20px;
  animation-delay: 4s;
}

.circles li:nth-child(4) {
  left: 40%;
  width: 60px;
  height: 60px;
  animation-delay: 0s;
  animation-duration: 18s;
}

.circles li:nth-child(5) {
  left: 65%;
  width: 20px;
  height: 20px;
  animation-delay: 0s;
}

.circles li:nth-child(6) {
  left: 75%;
  width: 110px;
  height: 110px;
  animation-delay: 3s;
}

.circles li:nth-child(7) {
  left: 35%;
  width: 150px;
  height: 150px;
  animation-delay: 7s;
}

.circles li:nth-child(8) {
  left: 50%;
  width: 25px;
  height: 25px;
  animation-delay: 15s;
  animation-duration: 45s;
}

.circles li:nth-child(9) {
  left: 20%;
  width: 15px;
  height: 15px;
  animation-delay: 2s;
  animation-duration: 35s;
}

.circles li:nth-child(10) {
  left: 85%;
  width: 150px;
  height: 150px;
  animation-delay: 0s;
  animation-duration: 11s;
}

@keyframes animate {
  0% {
    transform: translateY(0) rotate(0deg);
    opacity: 1;
    border-radius: 0;
  }

  100% {
    transform: translateY(-1000px) rotate(720deg);
    opacity: 0;
    border-radius: 50%;
  }
}
.q-field__native,
.q-field__prefix,
.q-field__suffix,
.q-field__input {
  color: white !important;
}
.button1:hover {
  color: #28e98c !important;
}
.mainbutton:hover {
  background-color: transparent !important;
  color: #28e98c !important;
  border: 2px solid #28e98c !important;
}
.card:hover {
  border: 1px solid #28e98c !important;
}
.button2:hover {
  background-color: #000000 !important;
  color: white !important;
}
.logo:hover {
  transform: scale(1.1);
}
</style>
