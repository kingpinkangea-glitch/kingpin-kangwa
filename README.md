<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KMU | ICT Department</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        body{font-family:'Inter',sans-serif; line-height:1.6;}
        h1,h2,h3{font-family:'Playfair Display',sans-serif;}
        #hero{
            height:100vh; background:linear-gradient(rgba(0,0,0,0.7),rgba(13,110,253,0.6)),
            url('https://scontent.flun4-1.fna.fbcdn.net/v/t39.30808-6/465699981_8746982225324851_1427390016293842959_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeEAB3T0O302LdEAfSrPqGs7jN4na_Z9Bm2M3idr9n0GbU6bYxoaiuaEk54pvGiXrHUcMSaN0JFbN9fYD5vp2Zy8&_nc_ohc=r9w4eqcBOAgQ7kNvwGcMeyd&_nc_oc=AdqOg-1MCP4Rscos85TneF_Hec15DmVxeza8AN6MeC5mNSmiyX-Km4OOCxPI3kBujsw&_nc_zt=23&_nc_ht=scontent.flun4-1.fna&_nc_gid=P9SluTyQozzJ06yDFa1FnQ&_nc_ss=7b2a8&oh=00_Af4EF5dEK4NJGgh0F1a0gzmyDlLbyTR4jGhNdI3Hc4oQKw&oe=6A092F4C') center/cover;
            color:white; display:flex; align-items:center;
        }
        .course-card{
            transition:all 0.4s; border:none; border-radius:15px;
        }
        .course-card:hover{transform:translateY(-12px); box-shadow:0 20px 30px rgba(13,110,253,0.25);}
        .section-title:after{
            content:''; display:block; width:70px; height:4px; background:#0d6efd;
            margin:10px auto; border-radius:2px;
        }
    </style>
</head>
<body>

    <!-- Hero -->
    <section id="hero" class="text-center">
        <div class="container">
            <img src="image\logo.png.jpg" alt="Logo" class="mb-4" style="height:100px;">
            <h1 font=px-5>KAPASA MAKASA UNIVERSITY</h1>
            <h2>INFORMATION COMMUNICATION TECHNOLOGY</h2>
            <p class="lead mb-5">Learn to Innovate • Secure the Future</p>
            <a href="courses" class="btn btn-light btn-lg px-5">Explore Courses</a>
        </div>
    </section>

    <!-- Courses -->
    <section id="courses" class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title text-center text-primary mb-5">Our Courses</h2>
            <div class="row g-4">
                <div class="col-md-6 col-lg-4">
                    <div class="card course-card h-100 shadow">
                        <div class="card-body p-4">
                            <h5>System Security</h5>
                            <p>Malware analysis, OS hardening, vulnerability assessment & intrusion detection.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card course-card h-100 shadow">
                        <div class="card-body p-4">
                            <h5>Network Design & Administration</h5>
                            <p>Network topology, routing, switching, server admin & cloud networking.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card course-card h-100 shadow">
                        <div class="card-body p-4">
                            <h5>Network Security</h5>
                            <p>Firewalls, VPNs, IPS, DDoS protection and enterprise security.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card course-card h-100 shadow">
                        <div class="card-body p-4">
                            <h5>Wireless Security</h5>
                            <p>WPA3, IoT security, rogue AP detection & wireless attack prevention.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card course-card h-100 shadow">
                        <div class="card-body p-4">
                            <h5>Information Security</h5>
                            <p>CIA Triad, cryptography, risk management & security policies.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5 text-primary">Contact Us</h2>
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <form class="text-center">
                        <input type="text" class="form-control mb-3" placeholder="Your Name" required>
                        <input type="email" class="form-control mb-3" placeholder="Your Email" required>
                        <textarea class="form-control mb-4" rows="5" placeholder="Your Message"></textarea>
                        <button type="submit" class="btn btn-primary btn-lg px-5">Send Message</button>
                    </form>
                </div>
            </div>
            <div class="text-center mt-5">
                <p><i class="fas fa-envelope me-2"></i> ict@kmu.ac.zm</p>
                <p><i class="fas fa-phone me-2"></i> +255 662 556 699</p>
            </div>
        </div>
    </section>

    <!-- Work References -->
    <section class="py-5 bg-light">
        <div class="container">
            <h4 class="text-center mb-4 text-primary">References</h4>
            <div class="row justify-content-center">
                <!div class="col-lg-8">
                    <ul class="list-group">
                        <li class="list-group-item">Background Image: <a href="https://unsplash.com" target="_blank">Unsplash</a></li>
                        <li class="list-group-item">Bootstrap Framework: <a href="https://getbootstrap.com" target="_blank">Bootstrap 5.3.3</a></li>
                        <li class="list-group-item">Icons: <a href="https://fontawesome.com" target="_blank">Font Awesome 6</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-dark text-light text-center py-4">
        <p class="mb-0">&copy; 2026 Kapasa Makasa University - ICT Department</p>
    </footer>

     <!--references -->

</body>
</html>
