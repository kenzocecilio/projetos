# projetos
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!--GOOGLE FONTS-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
    <!--GOOGLE FONTS-->

    <!--BOOSTRAP ICONS-->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
    <!-- FIM BOOSTRAP ICONS-->
    <link rel="stylesheet" href="styles.css">

    <script src="menu.js" defer></script>

    <title>Portfolio Kenzo Miyashita </title>

</head>

<body>
    <header>
        <div class="interface">
            <div class="logo">
                <a href="#">
                    <img src="images/logo.png" alt="Logo do Portfólio KMC">
                </a>
            </div> <!--logo-->

            <nav class="menu-desktop">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Social Midias</a></li>
                </ul>
            </nav>

            <div class="kmc-contato">
                <a href="#">
                    <button>Contact me</button>
                </a>
            </div> <!--kmc-contato-->

            <div class="kmc-abrir-menu" id="kmc-menu">
                <i class="bi bi-list"></i>
            </div>

            <div class="menu-mobile" id="menu-mobile">

                <div class="kmc-fechar">
                    <i class="bi bi-x-lg"></i>

                </div> <!--kmc-fechar-->

                <nav>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">About</a></li>
                        <li><a href="#">Social Midias</a></li>
                        <li><a href="#">Contato</a></li>
                    </ul>
                </nav>
            </div> <!--menu-mobile-->

            <div class="overlay-menu" id="overlay-menu">

            </div> <!--overlay-->
        </div> <!--interface-->
    </header>

    <main>
        <section class="topo-do-site">
            <div class="interface">
            <div class="flex">
                <div class="txt-topo-site">
                    <h1>SOFTWARE DEVELOPER<span>.</span></h1>
                    <p>Nice to meet you! My name is Kenzo Miyashita Cecilio, i'm twenty years old, graduating in
                        Computer Science. I'm in the fifth semester, expected to finish at the end of 2025/beginning of
                        2026, I've been in the technology area for a few years and I intend to continue expanding my
                        knowledge in this field. My experiences during my academic and professional life were Low code,
                        Programming Logic, TOTVS System (Fluig), Object Orientation, Structed Programming, Office
                        Package, HTML & CSS, Python and SQL. I was also able to gain knowledge of Agile, Scrum, ITIL
                        methodologies.</p>

                    <div class="kmc-contato">
                        <a href="#">
                            <button>HIRE ME</button>
                        </a>
                    </div> <!--kmc-contato-->
                </div> <!--txt-topo-site-->
                <div class="img-topo-site">
                    <img src="images/ternopreto.png" alt="Foto-pessoal">
                </div><!--img-topo-site-->
            </div> <!--Interface-->
            </div> <!--flex-->
        </section> <!--Section-->

        <section class="redessociais">
            <div class="interface">
                <h2 class="titulo">MY <span>SOCIAL MIDIAS.</span></h2>
                <div class="flex">
                    <div class="redessociais-box">
                        <a href="https://instagram.com/kenzo.miyashita" target = "_blank"><button><i class="bi bi-instagram"></i></button></a>
                        <h3>Instagram</h3>
                        <p>Check out the news on my Instagram!</p>
                    </div> <!--redessociais-box-->

                    <div class="redessociais-box">
                        <a href="https://linkedin.com/in/kenzomiyashita" target = "_blank"><button><i class="bi bi-linkedin"></i></button></a>
                        <h3>Linkedin</h3>
                        <p>Check out my Linkedin to learn more about my professional career, come and connect with my
                            profile, I’ll be waiting for you there!</p>
                    </div> <!--redessociais-box-->

                    <div class="redessociais-box">
                        <i class="bi bi-github"></i>
                        <h3>GitHub</h3>
                        <p>Visit my GitHub to see my projects!</p>
                    </div> <!--redessociais-box-->
                </div> <!--Flex-->
            </div> <!--Interface-->
        </section> <!--Redes sociais-->

        <section class="sobre">
            <div class="interface">
                <div class="flex">
                    <div class="img-sobre">
                        <img src="images/camisabranca.png" alt="Retrato Sobre">
                    </div> <!--img-sobre-->

                    <div class="txt-sobre">
                        <h2>THERE ARE, <span>MY EXPERIENCES.</span></h2>
                        <p>As a proactive Estagiário de Desenvolvimento e Aplicação de Sistemas at CPTM, my recent work
                            involves enhancing team performance through the development of applications. Currently
                            pursuing a degree in Computer Science at UNIP, I am committed to refining my expertise in
                            software testing and customer satisfaction.</p>
                        <p> My tenure at CDHU honed my abilities in software maintenance and addressing customer queries
                            via TOTVS systems and supporting low-code areas. Our team's efforts facilitated improvements
                            in efficient application creation and document management, reflecting my dedication to
                            operational excellence and customer service.</p>
                        <div class="kmc-social">
                            <a href="https://instagram.com/kenzo.miyashita" target = "_blank"><button><i class="bi bi-instagram"></i></button></a>
                            <a href="https://linkedin.com/in/kenzomiyashita" target = "_blank"><button><i class="bi bi-linkedin"></i></button></a>
                            <a href="https://wa.me/5511971045044" target = "_blank"><button><i class="bi bi-whatsapp"></i></button></a>
                        </div> <!--kmc-social-->
                    </div> <!--txt-sobre-->
                </div> <!--flex-->
            </div> <!--interface-->
        </section> <!--sobre-->

        <section class="formulario">
            <div class="interface">
                <div class="interface">
                    <h2 class="titulo">SEND ME <span>A MESSAGE.</span></h2>

                    <form action="">
                        <input type="text" name="" id="" placeholder="Seu nome completo:" required>
                        <input type="text" name="" id="" placeholder="Seu email" required>
                        <input type="text" name="" id="" placeholder="Seu celular:">
                        <textarea name="" id="" placeholder="Sua mensagem:"></textarea>
                        <div class="kmc-enviar"><input type="submit" value="Enviar">
                        </div> <!--botao-enviar-->
                    </form>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <div class="interface">
            <div class="line-footer">
                <div class="flex">
                    <div class="logo-footer">
                        <img src="images/logo.png" alt="Logo Rodapé">
                    </div> <!--logo-footer-->
                    <div class="kmc-social">
                        <a href="https://instagram.com/kenzo.miyashita" target = "_blank"><button><i class="bi bi-instagram"></i></button></a>
                        <a href="https://linkedin.com/in/kenzomiyashita" target = "_blank"><button><i class="bi bi-linkedin"></i></button></a>
                        <a href="https://wa.me/5511971045044" target = "_blank"><button><i class="bi bi-whatsapp"></i></button></a>
                    </div> <!--kmc-social-->
                </div> <!--flex-->
            </div> <!--line-footer 1-->
            <div class="line-footer borda">
                <p><i class="bi bi-envelope-at"></i> <a href="mailto:kenmcec@gmail.com">kenmcec@gmail.com</a></p>
            </div> <!--line-footer 2-->
        </div> <!--interface-->
    </footer>
</body>

</html>
