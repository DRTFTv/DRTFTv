<h1>Opa bão?</h1>

<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Tic Tac Toe</title>

        <script src="script.js"></script>
        <link rel="stylesheet" type="text/css" href="css/bootstrap.min.css" media="screen" />
        <link rel="stylesheet" type="text/css" href="css/CSSVELHA.css" media="screen" />
    </head>
    <body>
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 text-dark bg-light text-center">
                    <h1>TIC TAC TOE</h1> <br>
                    <button type="button" class="btn btn-outline-dark btn-sm" onclick="start()">START</button>
                    <button type="button" class="btn btn-outline-dark btn-sm" id="type" onclick="tipo()">ESCRITO</button> <br>
                    <div id="vez"></div>
                </div>
            </div>
            <div class="row game">
                <div class="col-12 text-center">
                    <button type="button" class="btn btn-outline-light butto" id="area_1" onclick="jogada(this.id)" disabled></button>
                    <button type="button" class="btn btn-outline-light butto" id="area_2" onclick="jogada(this.id)" disabled></button>
                    <button type="button" class="btn btn-outline-light butto" id="area_3" onclick="jogada(this.id)" disabled></button>
                </div>
            </div>
            <div class="row">
                <div class="col-12 text-center">
                    <button type="button" class="btn btn-outline-light butto" id="area_4" onclick="jogada(this.id)" disabled></button>
                    <button type="button" class="btn btn-outline-light butto" id="area_5" onclick="jogada(this.id)" disabled></button>
                    <button type="button" class="btn btn-outline-light butto" id="area_6" onclick="jogada(this.id)" disabled></button>
                </div>
            </div>   
            <div class="row">
                <div class="col-12 text-center">
                    <button type="button" class="btn btn-outline-light butto" id="area_7" onclick="jogada(this.id)" disabled></button>
                    <button type="button" class="btn btn-outline-light butto" id="area_8" onclick="jogada(this.id)" disabled></button>
                    <button type="button" class="btn btn-outline-light butto" id="area_9" onclick="jogada(this.id)" disabled></button>
                </div>
            </div>   
        </div>
    </body>
</html>
