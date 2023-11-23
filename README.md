<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bobur</title>

  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="./assets/images2/infinite-co-2-PhotoRoom.png-PhotoRoom.png" type="image/x-icon">
  

  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">

  <!--
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>

<body>

  <!--
    - #MAIN
  -->

  <main>

    <!--
      - #SIDEBAR
    -->

    <aside class="sidebar" data-sidebar>

      <div class="sidebar-info">

        <figure class="avatar-box">
          <img src="./assets/images2/infinite-co-2-PhotoRoom.png-PhotoRoom.png" alt="Infinite Co" width="80">
        </figure>

        <div class="info-content">
          <h1 class="name" title="Cheksizlik sari!">Infinite Co</h1>
<!-- FullStack Web | Python developer -->
          <p class="title">Yuqori daraja va sifat</p>
        </div>

        <button class="info_more-btn" data-sidebar-btn>
          <!-- <span>Show Contacts</span> -->

          <ion-icon name="chevron-down"></ion-icon>
        </button>

      </div>

      <div class="sidebar-info_more">

        <div class="separator"></div>

        <ul class="contacts-list">

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="mail-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Email manzil</p>

              <a href="boburanvarjon@gmail.com" class="contact-link">MYMAIL@gmail.com</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="phone-portrait-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Telefon</p>

              <a href="tel:+998905717301" class="contact-link">+998 (99) 904 55 76</a>
            </div>

          </li>

        <!--   <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="calendar-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Birthday</p>

              <time datetime="1982-06-23">June 23, 1982</time>
            </div>

          </li> -->

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Manzil</p>

              <address>Paxtaobod, Andijon, O`zbekiston</address>
            </div>

          </li>

        </ul>

        <div class="separator"></div>

        <ul class="social-list">

          <li class="social-item">
            <a href="#" class="social-link">
              <ion-icon name="logo-facebook"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://t.me/Infinite_IT_CENTER_channel" class="social-link">
              <ion-icon name="navigate-circle-outline"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://www.instagram.com/infinite_co_markazi/" class="social-link">
              <ion-icon name="logo-instagram" ></ion-icon>
            </a>
          </li>

        </ul>

      </div>

    </aside>





    <!--
      - #main-content
    -->

    <div class="main-content">

      <!--
        - #NAVBAR
      -->

      <nav class="navbar">

        <ul class="navbar-list">

          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Resume</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Portfolio</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Blog</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
          </li>

        </ul>

      </nav>





      <!--
        - #ABOUT
      -->

      <article class="about  active" data-page="about">

        <header>
          <h2 class="h2 article-title">Haqimizda</h2>
        </header>

        <section class="about-text">
          <p>
            Kanpaniya 2021-yildan beri o`z ish faoliyatini olib bormoqda!
            Mijozlarga tez va sifatli hizmat ko`rsatib kelmoqda!
          </p>

          <p>
            Kanpaniyaning vazifasi veb-saytlar (website) ishlab chiqarish va hozirda bizning kanpaniyada 'telegram bot', 'desktop' (konputerning ilovasi) va 'mobil' (telefonlarni ilovasi) ishlab chiqarish yo`lga qo`yilgan! 
          </p>
          <p>
            Bizning jamoada tajribali va malakali dasturchilar faoliyat olib boradi va dasturlar juda sifatli va zamonaviy

          </p>
        </section>


        <!--
          - service
        -->

        <section class="service">

          <h3 class="h3 service-title">Biz nima qila olamiz?</h3>

          <ul class="service-list">

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-design.svg
                " alt="design icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">veb dizayn(Web design)</h4>

                <p class="service-item-text">
                  Professional darajada tayyorlangan eng zamonaviy va sifatli dizayn.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-dev.svg" alt="Web development icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">veb dasturchi(Web development)</h4>

                <p class="service-item-text">
                  Professional darajada saytlarni yuqori sifatda ishlab chiqish.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title"> mobil ilovalar(Mobile apps)</h4>

                <p class="service-item-text">
                  iOS va Android uchun ilovalarni professional ishlab chiqish.                
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-photo.svg" alt="camera icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title"> marketing(Photography)</h4>

                <p class="service-item-text">
                  Bizda yuqori darajadagi marketing va sifatli reklama uchun materialllarni topishingiz mumkin.
                </p>
              </div>

            </li>

          </ul>

        </section>


        <!--
          - testimonials
        -->

        <section class="testimonials">

          <h3 class="h3 testimonials-title">Jamoa</h3>

          <ul class="testimonials-list has-scrollbar">

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Muhtoriddin Erkinboyev</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    INFINITE.CO kanpaniyasi asoschisi va malakali dasturchi.
                    O`z faoliyatini 2015-yildan boshlagan va hozirgi kungacha olib bormoqda.
                    INFINITE.CO kanpaniyasiga 2021-yil 19-iyulda asos solgan.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-1.png" alt="Jessica miller" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Fayzullo Asqarov</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    INFINITE.CO kanpaniyasining kanpaniya bo`lib yetishishiga o`z hissasini qo`shgan shaxs.
                    Hozirda kanpaniya bosh dasturchisi sifatida faoliyat olib bormoqda va o`z bilimlarini bolajak dasturchilarga ham bo`lishib kelmoqda.
                    
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-1.png" alt="Emily evans" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Ma'murbek Muhtorov</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    INFINITE.CO kanpaniyasining kanpaniya bo`lib yetishishiga o`z hissasini qo`shgan shaxs.
                    Hozirgi kunda kanpaniyada dasturchi bo`lib o`z faoliyati olib bormoqda va DIGITAL GENERATION UZBEKISTAN (mchj)da ham 
                    faoliyatini olib bormoqda.
                  </p>
                </div>

              </div>
            </li>

            <!-- <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-4.png" alt="Henry william" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Henry william</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Roman was hired to create a corporate identity. We were very pleased with the work done. He has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li> -->

          </ul>

        </section>


        <!--
          - testimonials modal
        -->

        <div class="modal-container" data-modal-container>

          <div class="overlay" data-overlay></div>

          <section class="testimonials-modal">

            <button class="modal-close-btn" data-modal-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>

            <div class="modal-img-wrapper">
              <figure class="modal-avatar-box">
                <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img>
              </figure>

              <img src="./assets/images/icon-quote.svg" alt="quote icon">
            </div>

            <div class="modal-content">

              <h4 class="h3 modal-title" data-modal-title>Muhtoriddin Erkinboyev</h4>

              <time datetime="2021-06-14">19 July, 2021</time>

              <div data-modal-text>
                <p>
                  INFINITE.CO kanpaniyasi asoschisi va hozirgi kunda malakali dasturchi.
                  O`z faoliyatini 2015-yildan boshlagan va hozirgi kungacha olib bormoqda.
                  INFINITE.CO kanpaniyasiga 2021-yil 19-iyulda asos solgan.
                </p>
              </div>

            </div>

          </section>

        </div>


        <!--
          - clients
        -->

        <section class="clients">

          <h3 class="h3 clients-title">Hamkorlar</h3>

          <ul class="clients-list has-scrollbar">

            <li class="clients-item">
              <a href="http://akfabuild.com/">
                <img src="./assets/images2/akfa_build_logo.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="https://it-park.uz/">
                <img src="./assets/images2/It_park.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="https://raqamliavlod.uz/">
                <img src="./assets/images2/photo_2023-09-28_12-26-56-removebg-preview.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="https://paxtaobodpress.uz/">
                <img src="./assets/images2/Press.jpg" alt="client logo" style="width: 120px; height: 90px;">
              </a>
            </li>

            <li class="clients-item">
              <a href="https://president.uz/">
                <img src="./assets/images2/Prezident.png" alt="client logo">
              </a>
            </li>

            <!-- <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-6-color.png" alt="client logo">
              </a>
            </li> -->

          </ul>

        </section>

      </article>





      <!--
        - #RESUME
      -->

      <article class="resume" data-page="resume">

        <header>
          <h2 class="h2 article-title">Resume</h2>
        </header>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">O'qitish</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Infinite education</h4>

              <span>2022-yildan hozirgacha</span>

              <p class="timeline-text">
                Bizda malakali va tajribaga ega dasturchilar dasr beradi!
              </p>

            </li>

          </ol>

        </section>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Infinite education</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Dasturlash asoslari (PYTHON)</h4>

              <span>5 oydan 9 oygacha</span>

              <p class="timeline-text">
                - Dasturlashni 0dan o`rganish va malakali ustoz-dasturchilar tomonidan qiziqarli darslar o`tilish imkoniyati bor.
              </p>
               <p class="timeline-text">
                - Dasturlash  sizlar uchun tajribali dasturchilar  hamda python developerlar tomonidan darslar o`tib boriladi.
              </p>
               <p class="timeline-text">
                - Bizda darslar Python dasturlash tilida olib boriladi.
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Veb dasturlash</h4>

              <span>3 oydan 5 oygacha</span>

              <p class="timeline-text">
                - Bizda darslar davomida Fronend va Backend toliq o`rganasiz.
              </p>
              <p class="timeline-text">
                - Veb-sayt dizayn bo`yicha HTML, CSS,  Bootstrap hamda JavaScript darslari ham olib boriladi.
                  
               </p>
 
               <p class="timeline-text">
                - Tajribali va o`z ishini ustalari tomonidan ishab chiqilgan veb satylar bilan tanishuv va amaliyotda sinab ko`rish imkoniyati.
                
              </p>
               <p class="timeline-text">
               -  Sizda dasturchilarimiz tomonidan yaratilinayotdan veb saytlarni ular bilan birgalikda ishlab chiqish imkoniyati mavjud.
              </p>
               
            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Bot (Telegram)</h4>

              <span>2 oydan 5 oygacha</span>

              <p class="timeline-text">
                - Telegram botlar yaratish va ular ustida ishlash.
              </p>
              <p class="timeline-text">
                - Darslar davomida siz eng kamida bitta Telegram bot ustida ishlab, o`zingiznig shaxsiy Telegram botingiz bo`lish imokoniyati mavjud.
              </p>
              <!-- <p class="timeline-text">
                - Worked with backend engineers to optimize existing API calls to create efficiencies by deprecating unneeded API calls.
              </p>
              <p class="timeline-text">
                - Used Object Oriented Programming concepts to develop UI components that could be reused across the Web Application.
              </p> -->

            </li>

          </ol>

        </section>

        <section class="skill">

          <h3 class="h3 skills-title">Dasturchilarimiz bilim darajasi</h3>

          <ul class="skills-list content-card">

            <!-- <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Web design</h5>
                <data value="80">95%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 95%;"></div>
              </div>

            </li> -->

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Bot (telegram)</h5>
                <data value="70">85%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 85%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Frontend(Html,Css,JavaScript)</h5>
                <data value="90">90%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Backend (Python)</h5>
                <data value="50">90%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Mobile app(Flutter)</h5>
                <data value="50">50%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 50%;"></div>
              </div>

            </li>

            <!-- <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Blockchain(Smart contract, Solidity,Rust, C, Solana, Golang, ERC20/721, TRC721, Dapp, Dex, Cex)</h5>
                <data value="50">90%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div>

            </li> -->


          </ul>

        </section>

      </article>





      <!--
        - #PORTFOLIO
      -->

      <article class="portfolio" data-page="portfolio">

        <header>
          <h2 class="h2 article-title">Portfolio</h2>
        </header>

        <section class="projects">

          <ul class="filter-list">

            <li class="filter-item">
              <button class="active" data-filter-btn>ALL</button>
            </li>

            <!-- <li class="filter-item">
              <button data-filter-btn>Web design</button>
            </li> -->

            <li class="filter-item">
              <button data-filter-btn>Telegram bot</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Veb saytlar</button>
            </li>

          </ul>

          <div class="filter-select-box">

            <button class="filter-select" data-select>

              <div class="select-value" data-selecct-value>Select category</div>

              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>

            </button>

            <ul class="select-list">

              <li class="select-item">
                <button data-select-item>Hammasi</button>
              </li>

             <!--  <li class="select-item">
                <button data-select-item>Web design</button>
              </li> -->

              <!-- <li class="select-item">
                <button data-select-item>Android/IOS App</button>
              </li> -->

              <li class="select-item">
                <button data-select-item>Web development</button>
              </li>

            </ul>

          </div>

          <ul class="project-list">

            <li class="project-item  active" data-filter-item data-category="veb saytlar">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images2/Pima.PNG" alt="pima" loading="lazy">
                </figure>

                <h3 class="project-title">Piima</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="veb saytlar">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images2/photoooo55.jpg" alt="galareya" loading="lazy">
                </figure>

                <h3 class="project-title">Galareya</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="veb saytlar">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images2/Akfa.PNG" alt="Akfa" loading="lazy">
                </figure>

                <h3 class="project-title">Akfa build</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="veb saytlar">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images2/Press.jpg" alt="Press" loading="lazy">
                </figure>

                <h3 class="project-title">Paxtaobodpress</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="veb saytlar">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images2/Edurent.jpg" alt="orizon" loading="lazy">
                </figure>

                <h3 class="project-title">Edurent</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="telegram bot">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images2/Natijalar.jpg" alt="orizon" loading="lazy">
                </figure>

                <h3 class="project-title">Natija.bot</h3>

                <p class="project-category">Telegram bot</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="telegram bot">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images2/Infinite_bot_logo.jpg" alt="orizon" loading="lazy">
                </figure>

                <h3 class="project-title">Infinite Co</h3>

                <p class="project-category">Telegram bot</p>

              </a>
            </li>

            <!-- <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-82.jpg" alt="orizon" loading="lazy">
                </figure>

                <h3 class="project-title">Social/Dating site</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-3.jpg" alt="fundo" loading="lazy">
                </figure>

                <h3 class="project-title">Fundo</h3>

                <p class="project-category">Web design</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-4.png" alt="brawlhalla" loading="lazy">
                </figure>

                <h3 class="project-title">Brawlhalla</h3>

                <p class="project-category">Applications</p>

              </a>
            </li>

             <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-83.jpg" alt="brawlhalla" loading="lazy">
                </figure>

                <h3 class="project-title">Trading</h3>

                <p class="project-category">Applications</p>

              </a>
            </li>

             <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-5.jpg" alt="Dating" loading="lazy">
                </figure>

                <h3 class="project-title">MakeLove</h3>

                <p class="project-category">Applications</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-5.png" alt="dsm." loading="lazy">
                </figure>

                <h3 class="project-title">DSM.</h3>

                <p class="project-category">Web design</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-6.png" alt="metaspark" loading="lazy">
                </figure>

                <h3 class="project-title">MetaSpark</h3>

                <p class="project-category">Web design</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-7.png" alt="summary" loading="lazy">
                </figure>

                <h3 class="project-title">Summary</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-8.jpg" alt="task manager" loading="lazy">
                </figure>

                <h3 class="project-title">Task Manager</h3>

                <p class="project-category">Applications</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-9.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Arrival</h3>

                <p class="project-category">Web development</p>

              </a>
            </li> -->

          </ul>

        </section>

      </article>





      <!--
        - #BLOG
      -->

      <article class="blog" data-page="blog">

        <header>
          <h2 class="h2 article-title">Blog</h2>
        </header>

        <section class="blog-posts">

          <ul class="blog-posts-list">

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-1.jpg" alt="Design conferences in 2022" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">Design conferences in 2022</h3>

                  <p class="blog-text">
                    Veritatis et quasi architecto beatae vitae dicta sunt, explicabo.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-2.jpg" alt="Best fonts every designer" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">Best fonts every designer</h3>

                  <p class="blog-text">
                    Sed ut perspiciatis, nam libero tempore, cum soluta nobis est eligendi.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-3.jpg" alt="Design digest #80" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">Design digest #80</h3>

                  <p class="blog-text">
                    Excepteur sint occaecat cupidatat no proident, quis nostrum exercitationem ullam corporis suscipit.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-4.jpg" alt="UI interactions of the week" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">UI interactions of the week</h3>

                  <p class="blog-text">
                    Enim ad minim veniam, consectetur adipiscing elit, quis nostrud exercitation ullamco laboris nisi.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-5.jpg" alt="The forgotten art of spacing" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">The forgotten art of spacing</h3>

                  <p class="blog-text">
                    Maxime placeat, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-6.jpg" alt="Design digest #79" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">Design digest #79</h3>

                  <p class="blog-text">
                    Optio cumque nihil impedit uo minus quod maxime placeat, velit esse cillum.
                  </p>

                </div>

              </a>
            </li>

          </ul>

        </section>

      </article>





      <!--
        - #CONTACT
      -->

      <article class="contact" data-page="contact">

        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>

        <section class="mapbox" data-mapbox>
          <figure>
            <iframe
              src="https://www.google.com/maps/place/Kyiv+city,+Kyiv,+Ukraine,+02000/@50.4020355,30.5326905,10z/data=!3m1!4b1!4m6!3m5!1s0x40d4cf4ee15a4505:0x5f251d1397901804!8m2!3d50.4501!4d30.5234!16s%2Fg%2F1tjwg7y4"
              width="400" height="300" loading="lazy">
            </iframe>
          </figure>
        </section>

        <section class="contact-form">

          <h3 class="h3 form-title">Contact Form</h3>

          <form action="#" class="form" data-form>

            <div class="input-wrapper">
              <input type="text" name="fullname" class="form-input" placeholder="Full name" required data-form-input>

              <input type="email" name="email" class="form-input" placeholder="Email address" required data-form-input>
            </div>

            <textarea name="message" class="form-input" placeholder="Your Message" required data-form-input></textarea>

            <button class="form-btn" type="submit" disabled data-form-btn>
              <ion-icon name="paper-plane"></ion-icon>
              <span>Send Message</span>
            </button>

          </form>

        </section>

      </article>

    </div>

  </main>






  <!--
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>

  <!--
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
