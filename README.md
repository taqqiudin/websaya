
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Materi belajar fungsi linier untuk kelas 8. Pelajari konsep dasar fungsi linier dengan contoh dan latihan.">
    <meta name="keywords" content="fungsi linier, matematika, kelas 8, belajar, contoh soal, latihan">
    <title>Fungsi Linier Kelas 8</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(90deg, #4a90e2, #003366);
            color: white;
            padding: 1rem 0;
        }

        nav {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 1rem;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 1rem;
        }

        .nav-links li a {
            color: white;
            text-decoration: none;
            font-size: 1rem;
            transition: color 0.3s;
        }

        .nav-links li a:hover {
            color: #ffdd57;
        }

        .burger {
            display: none;
            flex-direction: column;
            gap: 0.3rem;
            cursor: pointer;
        }

        .burger div {
            width: 25px;
            height: 3px;
            background: white;
            transition: all 0.3s;
        }

        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .home h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .home p {
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

        .content {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        img {
            max-width: 100%;
            border-radius: 10px;
        }

        footer {
            background: #4a90e2;
            color: white;
            text-align: center;
            padding: 0.5rem 0;
        }

        /* Mobile First */
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
                align-items: flex-start;
            }

            .nav-links {
                display: none;
                flex-direction: column;
                width: 100%;
                background-color: #4a90e2;
                position: absolute;
                top: 60px;
                left: 0;
                padding: 1rem 0;
            }

            .nav-links.active {
                display: flex;
            }

            .burger {
                display: flex;
            }

            .burger.toggle div:nth-child(1) {
                transform: rotate(-45deg) translate(-5px, 6px);
            }

            .burger.toggle div:nth-child(2) {
                opacity: 0;
            }

            .burger.toggle div:nth-child(3) {
                transform: rotate(45deg) translate(-5px, -6px);
            }

            .home h1 {
                font-size: 2rem;
            }

            .home p {
                font-size: 1rem;
            }

            .container {
                padding: 1rem;
            }
        }

        @media (max-width: 480px) {
            .home h1 {
                font-size: 1.8rem;
            }

            .home p {
                font-size: 0.9rem;
            }

            .nav-links {
                flex-direction: column;
                align-items: flex-start;
            }

            .container {
                padding: 0.5rem;
            }

            .logo {
                font-size: 1.2rem;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>

<body>
    <header>
        <nav>
            <div class="logo">Fungsi Linier Kelas 8</div>
            <ul class="nav-links">
                <li><a href="beranda 2.html"><i class="fas fa-home"></i> Beranda</a></li>
                <li><a href="materi.html"><i class="fas fa-book"></i> Materi</a></li>
                <li><a href="contoh soal.html"><i class="fas fa-pencil-alt"></i> Contoh Soal</a></li>
                <li><a href="latihan soal.html"><i class="fas fa-edit"></i> Latihan Soal</a></li>
                <li><a href="geogebra.html"><i class="fas fa-cogs"></i> Geogebra</a></li>
                <li><a href="kuis.html"><i class="fas fa-question-circle"></i> Kuis</a></li>
                <li><a href="kontak.html"><i class="fas fa-envelope"></i> Kontak</a></li>
            </ul>
            <div class="burger">
                <div></div>
                <div></div>
                <div></div>
            </div>
        </nav>
    </header>

    <main>
        <section class="home">
            <div class="container content">
                <div class="bg-image">
                    <img src="fkip1.jpg" alt="Mathematics Image">
                </div>
                <header>
                    <h1>Pembelajaran Fungsi Linear Kelas 8 SMP</h1>
                </header>

                <section id="pengantar">
                    <h2>Pengantar Fungsi Linear</h2>
                    <div class="Pengertian">
                        <p>Fungsi linear adalah suatu jenis fungsi matematis yang menggambarkan hubungan antara dua variabel, yaitu variabel independen (sering disebut 𝑥) dan variabel dependen (sering disebut 𝑦).</p>
                    </div>
                </section>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Fungsi Linier Kelas 8. M.Taqqiudin.</p>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const burger = document.querySelector('.burger');
            const navLinks = document.querySelector('.nav-links');

            burger.addEventListener('click', () => {
                navLinks.classList.toggle('active');
                burger.classList.toggle('toggle');
            });

            navLinks.addEventListener('click', (event) => {
                if (event.target.tagName === 'A') {
                    navLinks.classList.remove('active');
                    burger.classList.remove('toggle');
                }
            });
        });
    </script>
</body>

</html>
