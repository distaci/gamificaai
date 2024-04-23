<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gamifica Ai</title>
    <link rel="shortcut icon" href="img/favicon.png" type="image/x-icon">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Anta&display=swap" rel="stylesheet">


    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="banner">
        <header>
            <div class="container-grid">
                <img src="img/logo.png" alt="Logo da empresa Gamifica AI">
                <nav class="menu">
                    <a href="#sobre">Sobre</a>
                    <a href="#cases">Cases de Sucesso</a>
                    <a href="#portfolio">Portfolio</a>
                    <a href="#contato">Contate-nos</a>
                </nav>
            </div>
        </header>
        <!-- 
            PascalCase  -> ConteudoBanner   -> Java, C#
            camelCase   -> conteudoBanner   -> Javascript
            snake_case  -> conteudo_banner  -> Python (HTML e CSS)
            ?           -> conteudo-banner  -> HTML e CSS
         -->

        <div class="container-grid conteudo-banner">
            <p>GamificaAi: <span>Inovação através da Diversão!</span></p>
        </div>
    </div>
    <section id="sobre">
        <h2>Sobre nossa empresa</h2>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
            Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like
            Aldus PageMaker including versions of Lorem Ipsum.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia necessitatibus iure maiores, porro sapiente
            corporis nobis illo ratione enim! At repudiandae cupiditate odio dicta harum, doloribus eius aliquam sed ab?
        </p>
        <p>Silvio Santos Ipsum Eu só acreditoammmm.... Vendoammmm. Eu não queria perguntar isso publicamente, ma vou
            perguntar. Carla, você tem o ensino fundamentauam? O Raul Gil é gayam! ... Maa O Ah Ae! Ih Ih! O Raul Gil é
            gayamm! Você veio da caravana de ondeammm? O prêmio é em barras de ouro, que vale mais que dinheiroam. É com
            você Lombardiam. É dinheiro ou não éam?</p>
    </section>

    <section class="container-grid" id="cases">
        <h2>Cases de Sucesso</h2>
        <div class="container-cards">

            <div class="card">
                <img src="https://unsplash.it/600/400" alt="">
                <p>Reduzimos o desperdício de comida de uma escola em 80%.</p>
                <button>Ver mais</button>
            </div>
            <div class="card">
                <img src="https://unsplash.it/600/400" alt="">
                <p>Reduzimos o desperdício de comida de uma escola em 80%.</p>
                <button>Ver mais</button>
            </div>
            <div class="card">
                <img src="https://unsplash.it/600/400" alt="">
                <p>Reduzimos o desperdício de comida de uma escola em 80%.</p>
                <button>Ver mais</button>
            </div>
            <div class="card">
                <img src="https://unsplash.it/600/400" alt="">
                <p>Reduzimos o desperdício de comida de uma escola em 80%.</p>
                <button>Ver mais</button>
            </div>

        </div>
    </section>

    <section id="portfolio">
        <div class="filtro"></div>
        <div class="container-grid">
            <a href="#">Conheça nosso Portfolio Gamificado</a>
        
        </div>
    </section>

    <section id="contato">
        <h2>Contate-nos</h2>

        <form>
            <div class="campo">
                <label for="">Qual o seu nome?</label>
                <input id="nome" placeholder="Digite o seu nome..." type="text">
            </div>
            <div class="campo">
                <label for="">Em qual email podemos te responder?</label>
                <input id="email" placeholder="Digite o seu email..." type="email">
            </div>
            <div class="campo-descricao">
                <label for="">Descreva um pouco da sua empresa, e também o problema que está procurando
                    selecionar.</label>
                <textarea id="campo-texto" placeholder="Descreva a sua empresa e o problema que a sua empresa enfrenta..." cols="30" rows="10"></textarea>
            </div>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <div class="container-grid">
            <img src="img/logo.png" alt="Logo da empresa GamificaAi">
            <div class="redes-sociais">
                <p>Estamos também nas redes-sociais</p>
                <div class="icones-redes">
                    
                </div>
            </div>
        </div>
        <a href="#">
            <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M24.9999 38.6364C32.531 38.6364 38.6363 32.5311 38.6363 25C38.6363 17.4689 32.531 11.3636 24.9999 11.3636C17.4687 11.3636 11.3635 17.4689 11.3635 25C11.3635 32.5311 17.4687 38.6364 24.9999 38.6364ZM24.9999 34.0909C30.0206 34.0909 34.0908 30.0207 34.0908 25C34.0908 19.9792 30.0206 15.9091 24.9999 15.9091C19.9791 15.9091 15.909 19.9792 15.909 25C15.909 30.0207 19.9791 34.0909 24.9999 34.0909Z" fill="white"/>
                <path d="M38.6363 9.09082C37.381 9.09082 36.3635 10.1084 36.3635 11.3635C36.3635 12.6187 37.381 13.6363 38.6363 13.6363C39.8915 13.6363 40.909 12.6187 40.909 11.3635C40.909 10.1084 39.8915 9.09082 38.6363 9.09082Z" fill="white"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M1.48627 7.44559C0 10.3626 0 14.1811 0 21.8182V28.1818C0 35.8189 0 39.6375 1.48627 42.5543C2.79364 45.1202 4.87973 47.2064 7.44559 48.5136C10.3626 50 14.1811 50 21.8182 50H28.1818C35.8189 50 39.6375 50 42.5543 48.5136C45.1202 47.2064 47.2064 45.1202 48.5136 42.5543C50 39.6375 50 35.8189 50 28.1818V21.8182C50 14.1811 50 10.3626 48.5136 7.44559C47.2064 4.87973 45.1202 2.79364 42.5543 1.48627C39.6375 0 35.8189 0 28.1818 0H21.8182C14.1811 0 10.3626 0 7.44559 1.48627C4.87973 2.79364 2.79364 4.87973 1.48627 7.44559ZM28.1818 4.54545H21.8182C17.9246 4.54545 15.2778 4.549 13.232 4.71614C11.2392 4.87895 10.2201 5.17407 9.50918 5.5363C7.79861 6.40789 6.40789 7.79861 5.5363 9.50918C5.17407 10.2201 4.87895 11.2392 4.71614 13.232C4.549 15.2778 4.54545 17.9246 4.54545 21.8182V28.1818C4.54545 32.0755 4.549 34.722 4.71614 36.768C4.87895 38.7609 5.17407 39.78 5.5363 40.4909C6.40789 42.2014 7.79861 43.592 9.50918 44.4636C10.2201 44.8259 11.2392 45.1211 13.232 45.2839C15.2778 45.4509 17.9246 45.4545 21.8182 45.4545H28.1818C32.0755 45.4545 34.722 45.4509 36.768 45.2839C38.7609 45.1211 39.78 44.8259 40.4909 44.4636C42.2014 43.592 43.592 42.2014 44.4636 40.4909C44.8259 39.78 45.1211 38.7609 45.2839 36.768C45.4509 34.722 45.4545 32.0755 45.4545 28.1818V21.8182C45.4545 17.9246 45.4509 15.2778 45.2839 13.232C45.1211 11.2392 44.8259 10.2201 44.4636 9.50918C43.592 7.79861 42.2014 6.40789 40.4909 5.5363C39.78 5.17407 38.7609 4.87895 36.768 4.71614C34.722 4.549 32.0755 4.54545 28.1818 4.54545Z" fill="white"/>
                </svg>
                

        </a>
        <a href="#">
            <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M50 50H40V32.5024C40 27.7024 37.8825 25.0244 34.085 25.0244C29.9525 25.0244 27.5 27.8149 27.5 32.5024V50H17.5V17.5H27.5V21.1548C27.5 21.1548 30.6375 15.6494 37.7075 15.6494C44.78 15.6494 50 19.9653 50 28.8953V50ZM6.105 12.3022C2.7325 12.3022 0 9.5474 0 6.1499C0 2.7549 2.7325 0 6.105 0C9.475 0 12.2075 2.7549 12.2075 6.1499C12.21 9.5474 9.475 12.3022 6.105 12.3022ZM0 50H12.5V17.5H0V50Z" fill="white"/>
                </svg>
            </svg>

        </a>
        <a href="#">
            <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M42.4998 7.25013C40.2089 4.94208 37.482 3.11256 34.478 1.8679C31.4736 0.623253 28.2518 -0.0116202 24.9999 0.000161007C20.6527 0.00441099 16.3827 1.15078 12.6178 3.32446C8.85291 5.49814 5.72523 8.62285 3.54792 12.3856C1.37062 16.1484 0.220187 20.4173 0.211749 24.7645C0.203343 29.112 1.33728 33.3851 3.49999 37.1563L0 50L13.125 46.5625C16.7492 48.5788 20.8215 49.6534 24.9687 49.6875C31.5614 49.6878 37.8874 47.0838 42.5692 42.4425C47.2514 37.8016 49.9108 31.4988 49.9686 24.9063C49.9467 21.6167 49.2754 18.3637 47.9939 15.3339C46.7123 12.3041 44.8451 9.557 42.4998 7.25013ZM24.9999 45.4063C21.3052 45.4088 17.6781 44.4156 14.4999 42.5313L13.7499 42.0625L5.96873 44.125L8.03122 36.5313L7.53122 35.7501C4.87264 31.4585 3.88042 26.3407 4.74255 21.3664C5.60467 16.3922 8.26125 11.9069 12.209 8.76022C16.1568 5.61354 21.1215 4.02408 26.1627 4.29293C31.2039 4.56174 35.9717 6.6702 39.5624 10.2189C43.4873 14.057 45.7342 19.2923 45.8123 24.7813C45.763 30.2685 43.5483 35.5141 39.6505 39.3769C35.753 43.2394 30.4874 45.4066 24.9999 45.4063ZM36.2811 29.9688C35.6561 29.6563 32.6249 28.1563 32.0624 27.9688C31.4999 27.7813 31.0624 27.6563 30.6561 28.2813C30.0449 29.1191 29.3874 29.9223 28.6874 30.6876C28.3436 31.1251 27.9686 31.1563 27.3436 30.6876C23.7802 29.2795 20.8115 26.6857 18.9374 23.3439C18.2812 22.2501 19.5624 22.3126 20.7499 19.9689C20.8377 19.7998 20.8834 19.6123 20.8834 19.422C20.8834 19.2317 20.8377 19.0442 20.7499 18.8751C20.7499 18.5626 19.3437 15.5001 18.8437 14.2814C18.3437 13.0626 17.8437 13.2501 17.4374 13.2189H16.2187C15.9029 13.2237 15.5918 13.2959 15.3062 13.4306C15.0206 13.5654 14.767 13.7595 14.5624 14.0001C13.8613 14.6819 13.3144 15.5061 12.9586 16.4171C12.6028 17.3281 12.4464 18.3048 12.5 19.2814C12.6959 21.6192 13.5763 23.8473 15.0312 25.6876C17.6943 29.6745 21.344 32.9041 25.6249 35.0626C27.8702 36.3732 30.4796 36.9213 33.0624 36.6251C33.9224 36.4544 34.7371 36.1047 35.453 35.5985C36.1692 35.0926 36.7708 34.4413 37.2186 33.6876C37.6336 32.7676 37.7642 31.7448 37.5936 30.7501C37.3124 30.4376 36.9061 30.2813 36.2811 29.9688Z" fill="white"/>
                </svg>
                

        </a>


    </footer>

</body>

</html>
