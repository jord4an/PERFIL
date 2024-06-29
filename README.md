<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>

<body>
    <nav class="navbar bg-body-tertiary">
        <div class="navegacao">
            <div class="header">
                <a class="navbar-brand" href="#">
                    <img src="img/Logo.svg" alt="Logo" width="100" height="60" class="d-inline-block align-text-top">
                </a>
            </div>
            <div class="casa">
                <p>HOME</p>
                <p>Categorias</p>
                <p class="ok">MINHAS PARTIDAS</p> <!-- Adicione a classe d-flex aqui -->
            </div>
            <div class="user">
                <img src="/img/adicionar.svg" alt="">
                <p>Criar uma Partida</p>
                <img src="/img/Usuario.svg" alt="">
                <p>Meu Perfil</p>
            </div>
        </div>
    </nav>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-4 col-sm-12 d-flex justify-content-center">
                <img src="cr7.png" width="300" height="300" alt="imagem de perfil" class="perfil">
            </div>
            <div class="col-md-8 col-sm-12">
                <div class="row">
                    <div class="col-12">
                        <h1 class="Titulo">Meu perfil</h1>
                    </div>

                    <div class="col-12">
                        <div class="row">
                            <div class="col-11 linha"></div>
                        </div>
                    </div>

                    <div class="col-md-6 col-sm-12 mt-5">
                        <label for="text" class="laranja">NOME: <input type="text" class="inputText full-width" id="nomeUser"></label>
                    </div>
                    <div class="col-md-6 col-sm-12 mt-5">
                        <label for="text" class="laranja">TELEFONE: <input type="text" class="inputText" id="telefoneUser"></label>
                    </div>
                    <div class="col-md-8 col-sm-12 mt-5">
                        <label for="text" class="laranja">E-MAIL: <input type="text" class="inputText" id="emailUser"></label>
                    </div>
                    <div class="col-md-4 col-sm-12 mt-5">
                        <label for="text" class="laranja">DATA: <input type="date" class="inputText" id="dataUser"></label>
                    </div>
                </div>
            </div>
        </div>




        <div class="row mt-5">
            <div class="col-md-4 col-sm-12">
                <div class="row texto">
                    <div class="col-12 card custom-rounded" id="cardzada">
                        <h1 class="tituloDescricao">Descrição: </h1>
                        <textarea type="text" id="descricaoOutput" rows="4"></textarea>
                    </div>
                    <div class="col-12 mt-2 d-flex justify-content-center">
                        <button onclick="alteraPerfil()" class="buttonPerfil">Editar perfil</button>
                    </div>
                </div>
            </div>
            <div class="col-md-8 col-sm-12">
                <h1 class="Titulo">Últimas partidas</h1>
                <div class="row">
                    <div id="cards" class="d-flex">

                    </div>
                </div>
            </div>
        </div>

    </div>



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
    <script src="script.js"></script>
</body>

</html>
