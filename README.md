<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portofolio</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

</head>

<body>
    <!-- Header (Navigation Bar) -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container">
            <a class="navbar-brand" href="#">My portofolio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">About Me</a></li>
                    <li class="nav-item"><a class="nav-link" href="#educations">Educations</a></li>
                    <li class="nav-item"><a class="nav-link" href="#find-me">Find Me</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact-me">Contact Me</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Me Section -->
    <section id="about" class="py-5 bg-light">
        <div class="container text-center">
            <img src="WhatsApp Image 2024-08-15 at 15.06.06_db1f7caa.jpg" alt="Profile Photo" class="rounded-circle" width="150">
            <h1 class="mb-3">M Rasyah Alvian</h1>
            <h2 class="text-muted">Class: XI TEL 12</h2>
            <div class="ratio ratio-16x9 mt-4">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/uajOhQrhIsw?si=Saf9uFw4uAichaAS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
        </div>
    </section>

    <!-- Educations Section -->
    <section id="educations" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Educations</h2>
            <h3>Partisipasi Organisasi</h3>
            <table class="table table-bordered">
                <thead>
                    <tr>
                        <th>Year</th>
                        <th>Role/Position</th>
                        <th>Description</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>2024</td>
                        <td>Sekbid 6</td>
                        <td>Osis Telkom</td>
                    </tr>
                    <tr>
                        <td>2023</td>
                        <td>Koordinator</td>
                        <td>Osis Darunnajah</td>
                    </tr>
                </tbody>
            </table>
            <h3>Riwayat Belajar</h3>
            <table class="table table-bordered">
                <thead>
                    <tr>
                        <th>School Name</th>
                        <th>Year</th>
                        <th>Description</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Smk Telkom jkt</td>
                        <td>2023-2026</td>
                        <td>sekolah it telkom school jkt.</td>
                    </tr>
                    <tr>
                        <td>SMP Darunnajah</td>
                        <td>2021-2023</td>
                        <td>Sekolah islam/pondok pesantren darunnajah.</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>

    <!-- Find Me Section -->
    <section id="find-me" class="py-5 bg-light">
        <div class="container text-center">
            <h2>Find Me</h2>
            <p>Email: mrasyahalvian@dmail.com | Phone: 0852-8004-3018</p>
            <div class="social-icons" style="padding-left: 0%; font-size: 60px;">
                    <a href="https://instagram.com/rasyahalv" target="_blank"><i class='bx bxl-instagram-alt' alt="Instagram"></i></a>
                    <a href="https://tiktok.com/@diamond.confirm" target="_blank"><i class='bx bxl-tiktok' alt="TikTok"></i></a>
                    <a href="https://wa.me/6285280043018?" target="_blank"><i class='bx bxl-whatsapp'></i></a>
                </div>
        </div>
    </section>

    <!-- Contact Me Section -->
    <section id="contact-me" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Me</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Your Name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Your Email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Your Message"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-primary text-white text-center py-3">
        <p>Copyright &copy; 2024 Rasyah Alvian</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
