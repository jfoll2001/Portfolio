<script>
import Navbar from '@/components/Navbar.vue'
import Header from '@/components/Header.vue'
import Portfolio from '@/components/Portfolio.vue'
import About from '@/components/About.vue'
import Contact from '@/components/Contact.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    Navbar,
    Header,
    Portfolio,
    About,
    Contact,
    Footer
  }
}
</script>

<template>

  <body id="page-top">
    <!-- Navagation -->
    <Navbar />

    <!-- Masthead-->
    <Header />

    <!-- Portfolio Section-->
    <Portfolio />

    <!-- About Section-->
    <About />

    <!-- Contact Section-->
    <Contact />

    <!-- Footer-->
    <Footer />

    <!-- Portfolio Modals-->
    <!-- Portfolio Modal 1-->
    <div class="portfolio-modal modal fade" id="portfolioModal1" tabindex="-1" aria-labelledby="portfolioModal1"
      aria-hidden="true">
      <div class="modal-dialog modal-xl">
        <div class="modal-content">
          <div class="modal-header border-0"><button class="btn-close" type="button" data-bs-dismiss="modal"
              aria-label="Close"></button></div>
          <div class="modal-body text-center pb-5">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-lg-8">
                  <!-- Portfolio Modal - Title-->
                  <h2 class="portfolio-modal-title text-secondary text-uppercase mb-0">Appointments Manager</h2>
                  <!-- Icon Divider-->
                  <div class="divider-custom">
                    <div class="divider-custom-line"></div>
                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                    <div class="divider-custom-line"></div>
                  </div>
                  <!-- Portfolio Modal - Image-->
                  <img class="img-fluid rounded mb-5" src="" alt="AppointmentsManager" />
                  <!-- Portfolio Modal - Text-->
                  <p class="mb-4">Categories: VueJS, ExpressJS, MongoDBAtlas, Git, JavaScript, HTML, Bootstrap</p>
                  <p class="mb-4">This assignment was to create an app to manage appointments at a clinic, using VueJS
                    for the frontend
                    ExpressJS for the backend, MongoDBAtlas for the database, and then uploading it to Git Hub with
                    instructions on how to
                    start the project once it was cloned.
                  </p>
                  <p class="mb-4">Date Uploaded: 07/11/22</p>
                  <p class="mb-4">Link to: <a
                      href="https://github.com/jfoll2001/VueJS-ExpressJS-MongoDBAtlas-Git-Assignment.git">VueJS-ExpressJS-MongoDBAtlas-Git-Assignment</a>
                  </p>
                  <button class="btn btn-primary" data-bs-dismiss="modal">
                    <i class="fas fa-xmark fa-fw"></i>
                    Close Window
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Portfolio Modal 2-->
    <div class="portfolio-modal modal fade" id="portfolioModal2" tabindex="-1" aria-labelledby="portfolioModal2"
      aria-hidden="true">
      <div class="modal-dialog modal-xl">
        <div class="modal-content">
          <div class="modal-header border-0"><button class="btn-close" type="button" data-bs-dismiss="modal"
              aria-label="Close"></button></div>
          <div class="modal-body text-center pb-5">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-lg-8">
                  <!-- Portfolio Modal - Title-->
                  <h2 class="portfolio-modal-title text-secondary text-uppercase mb-0">Computer Store Manager</h2>
                  <!-- Icon Divider-->
                  <div class="divider-custom">
                    <div class="divider-custom-line"></div>
                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                    <div class="divider-custom-line"></div>
                  </div>
                  <!-- Portfolio Modal - Image-->
                  <img class="img-fluid rounded mb-5" src="" alt="ComputerStoreManager" />
                  <!-- Portfolio Modal - Text-->
                  <p class="mb-4">Categories: VueJS, ExpressJS, JavaScript, HTML, Bootstrap, MySQL</p>
                  <p class="mb-4">This assignment was create an app for a computer store management system, in which
                    VueJS was used to manage to the frontend, ExpressJS was used to manage the backend, and MySQL was
                    used to manage the database.</p>
                  <p class="mb-4">Date Uploaded: 07/05/22</p>
                  <p class="mb-4">Link to: <a
                      href="https://github.com/jfoll2001/Computer-Store-Management-System.git">Computer-Store-Management-System</a>
                  </p>
                  <button class="btn btn-primary" data-bs-dismiss="modal">
                    <i class="fas fa-xmark fa-fw"></i>
                    Close Window
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Portfolio Modal 3-->
    <div class="portfolio-modal modal fade" id="portfolioModal3" tabindex="-1" aria-labelledby="portfolioModal3"
      aria-hidden="true">
      <div class="modal-dialog modal-xl">
        <div class="modal-content">
          <div class="modal-header border-0"><button class="btn-close" type="button" data-bs-dismiss="modal"
              aria-label="Close"></button></div>
          <div class="modal-body text-center pb-5">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-lg-8">
                  <!-- Portfolio Modal - Title-->
                  <h2 class="portfolio-modal-title text-secondary text-uppercase mb-0">Managing Books</h2>
                  <!-- Icon Divider-->
                  <div class="divider-custom">
                    <div class="divider-custom-line"></div>
                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                    <div class="divider-custom-line"></div>
                  </div>
                  <!-- Portfolio Modal - Image-->
                  <img class="img-fluid rounded mb-5" src="" alt="ManaginbBooks" />
                  <!-- Portfolio Modal - Text-->
                  <p class="mb-4">Categories: ExpressJS, JavaScript, Bootstrap, JSON, CSS</p>
                  <p class="mb-4">This assignment was to create an app using ExpressJS for both the frontend and the
                    backend with a JSON file managing the data, EJS was used instead of HMTL.</p>
                  <p class="mb-4">Date Uploaded: 06/15/22</p>
                  <p class="mb-4">Link to: <a
                      href="https://github.com/jfoll2001/Managing-Books-Using-Express.git">Managing-Books-Using-Express</a>
                  </p>
                  <button class="btn btn-primary" data-bs-dismiss="modal">
                    <i class="fas fa-xmark fa-fw"></i>
                    Close Window
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Portfolio Modal 4-->
    <div class="portfolio-modal modal fade" id="portfolioModal4" tabindex="-1" aria-labelledby="portfolioModal4"
      aria-hidden="true">
      <div class="modal-dialog modal-xl">
        <div class="modal-content">
          <div class="modal-header border-0"><button class="btn-close" type="button" data-bs-dismiss="modal"
              aria-label="Close"></button></div>
          <div class="modal-body text-center pb-5">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-lg-8">
                  <!-- Portfolio Modal - Title-->
                  <h2 class="portfolio-modal-title text-secondary text-uppercase mb-0">Movie Rent System</h2>
                  <!-- Icon Divider-->
                  <div class="divider-custom">
                    <div class="divider-custom-line"></div>
                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                    <div class="divider-custom-line"></div>
                  </div>
                  <!-- Portfolio Modal - Image-->
                  <img class="img-fluid rounded mb-5" src="" alt="MovieRentSystem" />
                  <!-- Portfolio Modal - Text-->
                  <p class="mb-4">Categories: NodeJS, JavaScript, Bootstrap, JSON, CSS, MySQL</p>
                  <p class="mb-4">This assignment was created to manage moives, with HTML being used in the frontend and
                    NodeJS being used to run the server, with MySQL being used to manage the data.</p>
                  <p class="mb-4">Date Uploaded: 06/08/22</p>
                  <p class="mb-4">Link to: <a
                      href="https://github.com/jfoll2001/Movie-Rent-System.git">Movie-Rent-System</a></p>
                  <button class="btn btn-primary" data-bs-dismiss="modal">
                    <i class="fas fa-xmark fa-fw"></i>
                    Close Window
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>

</template>
