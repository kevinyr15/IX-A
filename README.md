<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kelas | VIII-A</title>
    <!-- Linking SwiperJS CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css">
    <style>
        /* Importing Google Font - Montserrat */
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
       
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "montserrat", sans-serif;
        }

        body {
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            max-height: 100vh;
            background: url("image/2.webp") #030728 no-repeat center;
            background-size: 100%;
        }
        
        .slider-wrapper {
          overflow: hidden;
          max-width: 1200px;
          margin: 0 70px 55px;
        }

        .card-list .card-item {
            color: #fff;
            min-height: 100vh;
            max-height: 100vh;
            user-select: none;
            width: 400px;
            padding: 35px;
            display: flex;
            align-items: center;
            flex-direction: column;
            justify-content: center;
            border-radius: 8px;
            backdrop-filter: blur(30px);
            background: rgba(255, 255, 255, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.5);
        }

        .card-list .card-item .user-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 40px;
            border: 3px solid #fff;
            padding: 4px;
        }

        .card-list .card-item .user-profession {
            font-size: 1.15rem;
            color: #e3e3e3;
            font-weight: 500;
            margin: 14px 0 40px;
        }

        .card-list .card-item .message-button {
            font-size: 1.25rem;
            padding: 10px 35px;
            color: #030728;
            border-radius: 6px;
            font-weight: 500;
            cursor: pointer;
            background: #fff;
            border: 1px solid transparent;
            transition: 0.2s ease;
        }

        .card-list .card-item .message-button:hover {
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid #fff;
            color: #fff;
        }
        
        .slider-wrapper .swiper-pagination-bullet {
          background: #fff;
          height: 15px;
          width: 15px;
        }
        
        .slider-wrapper .swiper-slide-button {
          color: #fff;
          margin-top: -50px;
          transition: 0.2s ease;
        }
        
        .slider-wrapper .swiper-slide-butyon:hover {
          color: #4658ff;
        }
        
        @media (max-width: 768px) {
          .slider-wrapper {
            margin: 0 10px 40px;
          }
          
          .slider-wrapper .swiper-slide-button {
            display: none;
          }
        }
@media (min-width: 481px) {
  /* Kosongkan atau comment rule grid 2/3 kolom */
}
    </style>
</head>
<body>
    <div class="container swiper">
        <div class="slider-wrapper">
            <div class="card-list swiper-wrapper">
                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Sulis Stianingsih</h2>
                    <p class="user-profession">Wali Kelas</p>
                    <button class="message-button">Biodata</button>
                </div>
                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Andi Rahmat Triantino</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Akhmad Hepiansyah</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Deva Erlingga</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Desti Nur Faedah</h2>
                    <p class="user-profession">Bendahara Kelas</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Dira Aurel Kharisma Putri</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Farel Raditya</h2>
                    <p class="user-profession">Olahraga</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Feby Ramadhani</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide ">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Fraisa Zaira Putri</h2>
                    <p class="user-profession">Sekertaris Kelas</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Jeni Aldriani</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Justin Antonio</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Kevin Yulio Rafadil</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide ">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Marvin Ardiansyah Saputra</h2>
                    <p class="user-profession">Keamanan</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Ridho Maulana</h2>
                    <p class="user-profession">Wakil Ketua Kelas</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Rizki Candra Cristian</h2>
                    <p class="user-profession">Absensi</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide ">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Sandy Ritama Atmajaya</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Sefta Aggie Fitrah Rianto</h2>
                    <p class="user-profession">Ketua Kelas</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Riko Siregar</h2>
                    <p class="user-profession">Kebersihan</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Wedad</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Zaskia Prisilia</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>

                <div class="card-item swiper-slide">
                    <img src="2.jpg" alt="Username Image" class="user-image">
                    <h2 class="user-name">Zhora Septada</h2>
                    <p class="user-profession">Member</p>
                    <button class="message-button">Biodata</button>
                </div>
            </div>
            
            <div class="swiper-pagination"></div>
            <div class="swiper-slide-button swiper-button-prev"></div>
            <div class="swiper-slide-button swiper-button-next"></div>
        </div>
    </div>
    <!-- Linking SwiperJS script -->
    <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
    
    <script>
      const swiper = new Swiper('.slider-wrapper', {
  loop: true,
  grabCursor: true,
  spaceBetween: 30,
  
  // If we need pagination
  pagination: {
    el: '.swiper-pagination',
    clickable: true,
    dynamicBullets: true
  },
  
  // Navigation arrows
  navigation: {
    nextEl: '.swiper-button-next',
    prevEl: '.swiper-button-prev',
  },
  
  // Responsive breakpoints
  breakpints: {
    0: {
      slidesPerView: 1
    },
    620: {
      slidesPerView: 2
    },
    1024: {
      slidesPerView: 3
    },
  }
});
    </script>
    <!-- Linking custom script -->
    <sript src='script.js'></sript>
</body>
</html>
