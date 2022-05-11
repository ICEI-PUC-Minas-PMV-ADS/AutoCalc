# Instruções de utilização

## Instalação do Site

O site em HTML/CSS/JS é um projeto estático, logo pode ser utilizado tanto em servidores...

## Histórico de versões

### [0.1.0] - 11/05/2022

Linha 19 = Pagina inicial
Linha 55 = Gerenciar Conta
Linha 94 = Gerenciar Veículo
Linha 130 = Gerenciar Perfil
Linha 159 = Gerenciar Abastecimento
Linha 228 =  CSS


################################################################### Pagina Inicial ###################################################################


<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="AutoCalc .CSS" media="screen">
</head>
<body>
    <div>
        <h1 id="titulo"> AUTOCALC</h1>
    </div>
    <p id="subtitulo" > Controle de abastecimento</p>
    <img src = "Imagens/Logo Auto Calc.jpg"
        width = "300"
        height = "300" >
    <p>
    <a href="https://universoagvbrasil.online/"><img src = "imagens/Empresa 1.png" 
        width = "150"
        height = "50"
        alt = " Empresa parceira 1 ">
    <a href="https://assine.bulbeenergia.com.br/#/share/U4n2k2"><img src = "imagens/Empresa 2.png"
        width = "150"
        height= "50"
        alt =  "Empresa parceira 2" >
    </p>
    <div class="campo">
    <p>
    <a href="AutoCalc  registrar usuario.html"><button class="botao">Crie uma conta</button>
    <a href="AutoCalc login e senha.html"><button class="botao">Entre</button>
    </p>
    </div>
</body>
</html>
      
      
################################################################### Gerenciar Conta ###################################################################
      
      
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="AutoCalc .CSS" media="screen">
</head>
<body>
    <div>
        <h1 id="titulo">Cadastrar Usuário </h1>
    </div>
    <p id="subtitulo">Insira seus dados pessoais para prosseguir</p>
    <form>
        <Fieldset class="grupo">
                <div class="campo">
                     <label for="Nome"> Nome </label>
                     <input type="text" name="nome" id="nome" required>
                </div>

                <div class="campo">
                     <label for="sobrenome"> sobrenome </label>
                     <input type="text" name="sobrenome" id="sobrenome" required>
                </div>
        </Fieldset>
                <div class="campo">
                    <label for="E-mail"> E-mail</label>
                    <input type="e-mail" name="e-mail" id="e-mail" required>
                </div>
                <div  class="campo">
                    <label> Senha</label>
                    <input type="password" name="Senha" id="Senha" required>
                </div>
    </form>
    <a href="AutoCalc  registrar veiculo.html"><button class="botao">concluído</button>
    <a href="AutoCalc inicial .html"><button class="botao" >Cancelar</button>
</body>
</html>      
  
################################################################### Gerenciar Veiculos ###################################################################
  
  <!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="AutoCalc .CSS" media="screen">
</head>
<body>
    <div>
        <h1 id="titulo">Cadastrar Veículo</h1>
    </div>
    <p id="subtitulo">Insira os dados do seu carro para prosseguir</p>
    <form>
        <Fieldset class="grupo">
                <div class="campo">
                     <label> Modelo </label>
                     <input type="text" name="nome" id="nome" required>
                </div>

                <div class="campo">
                     <label> Placa do carro </label>
                     <input type="text" name="placa" id="placa" required>
                </div>

                <div class="campo">
                    <label> Ano </label>
                    <input type="number" name="ano" id="ano" required>
               </div>
        </Fieldset>
    </form>
    <a href="AutoCalc Perfil.html"><button class="botao">Concluído</button>
    <a href="AutoCalc  registrar usuario.html"><button class="botao">Cancelar</button>
</body>
</html>
  
  
      ################################################################### Gerenciar Perfil ###################################################################
      
      
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="AutoCalc .CSS" media="screen">
</head>
<body>
    <div>
        <h1 id="titulo">Perfil</h1>
    </div>
    <Img src = "Imagens/Perfil1.png">
<p>
    Login
    E-mail
    Nome do veículo
    Placa do veículo
</p>
<p>
    <a href="AutoCalc  registrar abastecimento.html"><button class="botao">Cadastrar Abastecimento</button> 
    <a href="AutoCalc  registrar veiculo.html"><button class="botao">Cadastrar outro Veículo</button>
    <a href=""><button class="botao">Relatórios</button>   
    <a href="AutoCalc inicial .html"><button class="botao">Sair</button>
</p>
</body>
</html>
      
      
      ################################################################### Gerenciar Abastecimento ###################################################################
  
      
  <!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="AutoCalc .CSS">
</head>
<body>
    <div>
        <h1 id="titulo">Cadastro Abastecimento</h1>
    </div>
    <p id="subtitulo">Insira os dados de seu Abastecimento</p>

    <form>
                <div class="campo">
                     <label> Data </label>
                     <input type="date" name="Data" id="Data" >
                </div>

                <div class="campo">
                     <label> Nome do Posto </label>
                     <input type="text" name="Nome do Posto" id="Nome do Posto" >
                </div>

                <div class="campo">
                    <label> Valor por Litro </label>
                    <input type="number" name="Valor por Litro" id="Valor por Litro" >
                </div>

                <div class="campo">
                    <label> Valor Total </label>
                    <input type="number" name="valor total" id="valor total" >
                </div>

                <div class="campo">
                <label> Total de Litros Abastecido </label>
                <input type="number" name="Total de Litros" id="Total de Litros" >
                </div>

                <div class="campo">
                    <label> Kilometragem total do veículo</label>
                    <input type="number" name="kilometragem total" id="kilometragem total" >
                </div>

                <div class="campo">
                    <label>Qual tipo de Combústivel?</label>
                    <label> Gasolina 
                        <input type="radio" name="Combustivel" value="Gasolina" >
                    </label>
                    <label> Alcool 
                        <input type="radio" name="Combustivel" Value="Alcool" >
                    </label>
                </div>

                    <div class="campo">
                        <label> Observações </label>
                        <input type="text" name="Observações" id="Observações">
                    </div>
                    
    </form>
    
        <a href="AutoCalc Perfil.html"><button class="botao">Concluído</button>
        <a href="AutoCalc Perfil.html"><button class="botao">Cancelar</button>

</body>
</html>
  
  
################################################################### CSS ###################################################################
  
  
  *{
    margin:0;
    padding:0;
}

#titulo {
    font-family: sans-serif;
    color: black;
    justify-content: center
}

#subtitulo {
    font-family: sans-serif;
    color: black;
    justify-content: center
}
fieldset {
border: 0;
}

body {
    background-color: white;
    font-family: sans-serif;
    font-size: small ;
    color: black;
    margin-top: 2%;
    margin-left: 36%;
    justify-content: center;
}

input, select, textarea, button {
    border-radius: 5px;
} 

.campo {
margin-bottom: 1em;
}

.campo label {
    margin-bottom: 0.2em;
    color: black;
    display: block;
}

fieldset .grupo .campo {
    float: left;
    margin-right: 1em;
}

.campo input[type= "text"], .campo input[type= "number"], .campo input[type= "radio"], .campo input[type= "e-mail"], .campo input[type= "password"] {
padding: 0.2 em;
border: 1px solid black;
display: block;
}

.campo select option {
    padding-right: 1em;
}

.campo input:focus, .campo select:focus, .campo textarea {
    background: white;
}

.botao {
    font-size: 1.2em;
    background: black;
    border:0;
    margin-bottom: 1em;
    color: white ;
    padding: 0.2em 0.6em;
}

.botao:hover {
    background-color: grey;
    box-shadow: inset 2px 2px 2px grey;
    text-shadow: none;
}
  
  
  
