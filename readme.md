# Digital Agency - Bootstrap    
This is a complete bootstrap front-end project for a Digital Agency website.

## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Links](#links)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview
### Screenshots

Desktop Screenshot

![Desktop](/res/desktop-home.png)
Moile Screenshot

![Mobile](/res/mob-home.png)

### Links

- Live Site URL: [https://sunilsharmapoudel.github.io/SEOAgency-Bootstrap/](https://sunilsharmapoudel.github.io/SEOAgency-Bootstrap/)

### Built with

- Semantic HTML5 markup
- Bootstrap 5

### What I learned

This was my first Bootstrap porject and from this project I learned to use bootstrap CSS for fast development and good result.

```html
<!--Main Section-->
 <nav class="navbar sticky-top bg-light">
      <div class="container-fluid">
        <div class="ps-5">
          <a class="navbar-brand" href="/">
            <img src="/res/logo.png" alt="logo" height="50px" width="100px">
            </a>
        </div>

        <div class="justify-content-center fw-bold d-none d-md-block">
          <ul class="nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >Services</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >About us</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Blogs</a>
            </li>
          </ul>
        </div>

        <div class="pe-5 justify-content-end d-none d-md-block">
          <button type="button" class="btn btn-success">
            <strong>Buy iokit</strong>
          </button>
        </div>

        <!--Off Canvas Nav-->
        <div class="d-sm-none">
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="offcanvas"
            data-bs-target="#offcanvasDarkNavbar"
            aria-controls="offcanvasDarkNavbar"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="offcanvas offcanvas-end text-bg-dark bg-light"
            tabindex="-1"
            id="offcanvasDarkNavbar"
            aria-labelledby="offcanvasDarkNavbarLabel"
          >
            <div class="offcanvas-header">
              <div class="ps-5">
                <a class="navbar-brand" href="/">
                  <img
                    src="/res/logo-dark.svg"
                    alt="Logo"
                    width="100"
                    height="94"
                    class="d-inline-block align-text-top"
                /></a>
              </div>

              <button
                type="button"
                class="btn-close btn-close-dark"
                data-bs-dismiss="offcanvas"
                aria-label="Close"
              ></button>
            </div>

            <div class="offcanvas-body d-flex justify-content-center fs-5">
              <ul class="navbar-nav">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#"
                    >Services</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">About us</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#">Contact us</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#">Blogs</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </nav>
    <!--Navbar-->

    <!--Main Section-->
    <div class="container">
      <div class="row mt-5">
        <div class="col-md-6">
          <div
            class="row"
            style="font-size: 60px; font-family: 'Righteous', cursive"
          >
            <p>Setup your Digital Agency with ioKit</p>
          </div>
          <div class="row align-items-center">
            <div class="col-md-4 fw-bold">
              <button type="button" class="btn btn-primary btn-lg my-3">
                Purchase
              </button>
            </div>
            <div class="col-md-6 fw-bold fs-4">
              <button type="button" class="btn btn-outline-dark btn-lg">
                View Style Guide
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-6 fw-semibold fs-5">
          <div
            class="row mt-5"
            style="
              background-image: url(res/banner.webp);
              background-size: 100% 100%;
              background-repeat: no-repeat;
            "
          >
            <div class="row mx-3 my-3">
              <div class="col-6">+50 Pre-Builg Pages</div>
              <div class="col-6">22+ Bootstrap Element</div>
            </div>
            <div class="row my-3 mx-2">
              <div class="col-6">Style guide & Docs included</div>
              <div class="col-6">Regularly updated</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid">
      <div class="container">
        <div class="row" style="margin-top: 100PX;">
          <div class="row mt-5" style="margin-bottom: 100px;">
            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Home 1</div>
                <div class="row">
                  <img class="img-thumbnail" src="res/home_1.png" alt="about" />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Home 2</div>
                <div class="row">
                  <img class="img-thumbnail" src="res/home_2.png" alt="about" />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Home 3</div>
                <div class="row">
                  <img class="img-thumbnail" src="res/Home_3.png" alt="carrer" />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Home 4</div>
                <div class="row">
                  <img
                    class="img-thumbnail"
                    src="res/Home_4.png"
                    alt="Careeropening"
                  />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Home 5</div>
                <div class="row">
                  <img class="img-thumbnail" src="res/Home_5.png" alt="coming" />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Home 6</div>
                <div class="row">
                  <img
                    class="img-thumbnail"
                    src="res/Home_6.png"
                    alt="contact"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid" style="background-color: #f3f8ff">
      <div class="container">
        <div class="row">
          <div class="row" style="margin-top: 100px">
            <h2 class="fw-bold" style="font-family: 'Righteous', cursive">
              Inner Pages
            </h2>
          </div>

          <div class="row mt-5" style="margin-bottom: 100px">
            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">About</div>
                <div class="row">
                  <img class="img-thumbnail" src="res/about.png" alt="about" />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">About</div>
                <div class="row">
                  <img class="img-thumbnail" src="res/about.png" alt="about" />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Carrer</div>
                <div class="row">
                  <img class="img-thumbnail" src="res/career.png" alt="carrer" />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Career Opening</div>
                <div class="row">
                  <img
                    class="img-thumbnail"
                    src="res/career_item.png"
                    alt="Careeropening"
                  />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Coming Soon</div>
                <div class="row">
                  <img class="img-thumbnail" src="res/coming.png" alt="coming" />
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="row">
                <div class="row fw-bold fs-4 mb-3 ms-1">Contact</div>
                <div class="row">
                  <img
                    class="img-thumbnail"
                    src="res/contact.png"
                    alt="contact"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row justify-content-center my-5">
        <h2 class="fs-2 fw-bold" style="font-family: 'Righteous', cursive" ;>
          Account Pages
        </h2>
        <div class="row mt-5" style="margin-bottom: 100px">
          <div class="col-md-4">
            <div class="row">
              <div class="row fw-bold fs-4 mb-3 ms-1">About</div>
              <div class="row">
                <img class="img-thumbnail" src="res/about.png" alt="about" />
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="row">
              <div class="row fw-bold fs-4 mb-3 ms-1">About</div>
              <div class="row">
                <img class="img-thumbnail" src="res/about.png" alt="about" />
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="row">
              <div class="row fw-bold fs-4 mb-3 ms-1">Carrer</div>
              <div class="row">
                <img class="img-thumbnail" src="res/career.png" alt="carrer" />
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="row">
              <div class="row fw-bold fs-4 mb-3 ms-1">Career Opening</div>
              <div class="row">
                <img
                  class="img-thumbnail"
                  src="res/career_item.png"
                  alt="Careeropening"
                />
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="row">
              <div class="row fw-bold fs-4 mb-3 ms-1">Coming Soon</div>
              <div class="row">
                <img class="img-thumbnail" src="res/coming.png" alt="coming" />
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="row">
              <div class="row fw-bold fs-4 mb-3 ms-1">Contact</div>
              <div class="row">
                <img class="img-thumbnail" src="res/contact.png" alt="contact" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid" style="background-color: #f3f8ff">
      <div class="container">
        <div class="row">
          <div class="row" style="margin-top: 100px; margin-bottom: 50px">
            <h2 class="fw-bold" style="font-family: 'Righteous', cursive">
              Blog Pages
            </h2>
          </div>
          <div class="row" style="margin-bottom: 100px">
            <div id="carouselExampleIndicators" class="carousel slide">
              <div class="carousel-indicators bg-black">
                <button
                  type="button"
                  data-bs-target="#carouselExampleIndicators"
                  data-bs-slide-to="0"
                  class="active"
                  aria-current="true"
                  aria-label="Slide 1"
                ></button>
                <button
                  type="button"
                  data-bs-target="#carouselExampleIndicators"
                  data-bs-slide-to="1"
                  aria-label="Slide 2"
                ></button>
                <button
                  type="button"
                  data-bs-target="#carouselExampleIndicators"
                  data-bs-slide-to="2"
                  aria-label="Slide 3"
                ></button>
              </div>
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img
                    src="res/blog_sidebar.png"
                    class="d-block w-100"
                    alt="..."
                  />
                </div>
                <div class="carousel-item">
                  <img src="res/blog_grid.png" class="d-block w-100" alt="..." />
                </div>
                <div class="carousel-item">
                  <img
                    src="res/article_sidebar.png"
                    class="d-block w-100"
                    alt="..."
                  />
                </div>
              </div>
              <button
                class="carousel-control-prev bg-black"
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide="prev"
              >
                <span
                  class="carousel-control-prev-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button
                class="carousel-control-next bg-black"
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide="next"
              >
                <span
                  class="carousel-control-next-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row" style="margin-top: 100px; margin-bottom: 100px">
        <div class="row my-3">
          <div class="col d-flex justify-content-center">
            <p
              class="fw-bolder fs-1 text-primary"
              style="font-family: 'Righteous', cursive"
            >
              Ready To Get Started?
            </p>
          </div>
        </div>
        <div class="row">
          <div class="col d-flex justify-content-center">
            <button class="btn btn-primary btn-lg">Download Toolkit</button>
          </div>
        </div>
      </div>
    </div>

    <!--Main Section-->

    <!--Footer-->
    <div class="container-fluid" style="background-color: #14234b">
      <div class="container">
        <div class="row">
          <div class="d-flex justify-content-between align-items-center">
            <div>
              <a class="navbar-brand" href="/">
                <img
                  src="res/logo-light.svg"
                  alt="Logo"
                  width="100"
                  height="94"
                  class="d-inline-block align-text-top"
              /></a>
            </div>

            <div class="fw-bold">
              <ul class="nav">
                <li class="nav-item">
                  <a
                    class="nav-link active text-light"
                    aria-current="page"
                    href="#"
                    >Services</a
                  >
                </li>
                <li class="nav-item">
                  <a
                    class="nav-link active text-light"
                    aria-current="page"
                    href="#"
                    >About us</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link text-light" href="#">Contact us</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link text-light" href="#">Blogs</a>
                </li>
              </ul>
            </div>

            <div>
              <a class="navbar-brand" href="/">
                <img
                  src="res/creabik.svg"
                  alt="Logo"
                  width="100"
                  height="94"
                  class="d-inline-block align-text-top"
              /></a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!--Footer-->

```

## Author

- Website - [Sunil Sharma](https://github.com/sunilsharmapoudel)
- Facebook - [@mesunilsharmapoudel](https://www.facebook.com/mesunilsharmapoudel)
- Twitter - [@techsunilsharma](https://www.twitter.com/techsunilsharma)