# Aula-bootstrap
Utilizando bootstrap
Iniciando os trabalhos

!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Minha página</title>
        <meta charset="utf-8">
        <link rel="stylesheet" type="text/css" href="bootstrap/css/bootstrap.min.css">
        <link rel="stylesheet" type="text/css" href="css/style.css">
    </head>
    <body>
      
         <nav class="navbar navbar-expand-lg navbar-light margin">
            <a class="navbar-brand" href="#">
            <img src="logo.png" width="200" height="80">
        </a>
        <div class="collapse navbar-collapse">
        <ul class="navbar-nav">
            <li class="nav-item">
                <a class="nav-link" href="#quemsomos" Quem somos></a>

            </li>
            <li class="nav-item">
                <a class="nav-link" href="#parceiros" Parceiros></a>
            </li>
        
        <li class="nav-item">
            <a class="nav-link" href="#serviços" Serviços></a>
        </li>
            
        </ul>
       <div>
        </nav>

        <section id="quem somos">
            <div class="container-fluid quem.somos text-center margin">
                <h3 class="margin">Quem somos</h3>
               <img src="time.jpeg" class="rounded-circle" width="400" height="400">
               <h3>Somos um time comprometido com os resultados</h3>

            </div>
        </section>

        <selection id="Parceiros">
            <div class="container-fluid text-center margin parceiros">
                <h3 class="margin">Parceiros</h3>
                <div class="container">
                    <div class="row">
                        <div class="col-lg-4">
                            <img src="digital-innovation-one.jpg" width="200" height="200">
                        </div>
                        <div class="col-lg-4">
                            <img src="digital-innovation-one.jpg" width="200" height="200">
                        </div>
                    <div class="col-lg-4">
                        <img src="digital-innovation-one.jpg" width="200" height="200">
                    </div>
                    </div>
                </div>
            </div>
        </selection>
        <section id="servicos">
            <div class="container-fluid text-center margin servicos">
                <h3 class="margin">Serviços</h3>
                <div class="container">
                    <div class="row">
                        <div class="col-lg-6">
                            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                          <img src="app.jpeg" width="400" height="400">
                        </div>
                        <div class="col-lg-6">
                            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                          <img src="computador.jpeg" width="400"height="400" >
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <footer class=" container-fluid text-center bg-footer margin">
            <p>Desenvolvido por Samantha Gomes</p>
        </footer>
    </body>
</html>
