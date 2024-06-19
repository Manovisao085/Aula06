<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro</title>
    <link rel="stylesheet" href="formulario.css">
</head>
<body>
    
    <!-- Título -->
    <div class="campo">
        <h1 id="titulo">Cadastro</h1>
    </div>
    <div class="campo">
       
    </div>
    <div class="campo">
       
    </div>

    <form>
        <Fieldset class="grupo">
            <Div class="campo">
                <label>
                    <strong>Nome</strong>
                </label>
                <input type="text" name="Nome" id="Nome" >
            </Div>
            <Div class="campo">
                <label>
                    <strong>Sobrenome</strong>
                </label>
                <input type="text" name="Sobrenome" id="Sobrenome" input>
            </Div>
        </Fieldset>
        
        <Fieldset class="grupo">
            <Div class="campo">
                <label>
                    <strong>Email</strong>
                </label>
                <input type="email" name="email" id="email" >
            </Div>
            <Div class="campo">
                <label>
                    <strong>Senha</strong>
                </label>
                <input type="password" name="senha" id="senha" input>
            </Div>
        </Fieldset>
        
        <div>
            <div class="campo">
                <label>
                    <strong>Data de nascimento</strong>
                </label>
                <input type="date" name = "nasc" id="nasc">
            </div> 
                <label>
                    <strong>Curso</strong>
                </label> 
                <label>
                    <input type="radio" name="curso" value="front-end"> Frontend   
                </label>    
                <label>
                    <input type="radio" name="curso" value="back-end"> Back-End
                </label>      
                <label>
                    <input type="radio" name="curso" value ="Full-Stack"> Full-Stack  
                </label>  
        </div>

        <div class="campo">
            <label>
                <strong>Turno</strong>
            </label>
            <select>
                <option selected disabled>Selecione</option>
                <option>Manhã</option>
                <option>Tarde</option>
                <option>Noite</option>
            </select>
        </div>

        <!--botão--> 

        <button class="botao" type="submit" >Cadastrar</button>
    </form>

</body>
</html>
