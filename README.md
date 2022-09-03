<!DOCTYPE html>
<html lang="en">
</head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Cadastro</title>
<head>
<body>

    <div>
        <h1>Cadastro de DEVs</h1>
        <p>Complete as suas informações</p>
        <br>
    </div>

<form>
    <fieldset>
        <div>
            <label>Nome</label>
            <input type="text" name="nome" id="nome">
        </div>
    
<div>
<label class="Sobrenome">Sobrenome</label>
<input type="text" name="Sobrenome" id="Sobrenome">
</div>
</fieldset>

<div >
    <label>Email</label class="email">
    <input type="email" name="email" id="email">
</div class="campo">
<br>
<div>
    <label>De qual lado da aplicação você desenvolve</label>
    <label>
        <input type="radio" name="Devweb" value="FrontEnd"checked>Front-End
    </label>
    <label>
        <input type="radio" name="devweb" value="Back-End">Back-End
    </label>
    <label>
        <input type="radio" name="Devweb" value="Full-Stack">Full-Stack
    </label>
</div>
<br>
<div>
   <label>Senioridade:</label> 
   <select id="senioridade">
    <option selected disabled value="">Escolha</option>
   <option>Junior</option>
   <option>Pleno</option>
   <option>Sênior</option>
</div>

<fieldset>
    <div id="check">
    <br>
        <label>selecione as tecnologias que utiliza</label>
        <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
        <label for="tecnologia3">Javascript</label>
        <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
        <label for="tecnologia4">PHP</label>
        <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
        <label for="tecnologia5">C#</label>
        <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
        <label for="tecnologia6">Python</label>
        <input type="checkbox" id="tecnologia7" name="tecnologia7" value="Java">
        <label for="tecnologia7">Java</label>
        <input type="checkbox" id="tecnologia8" name="tecnologia8" value="C++">
        <label for="tecnologia8">C++</label>
    </div>
</fieldset>

<div>
    <br>
    <label>Conte um pouco da sua experiência</label>
    <textarea></textarea>
</div>

<button type="submit">Concluido!!!</button>

</form>

</body>
</html>


*{
    margin:0
    padding:0;
}

#titulo{
    font-family: sans-serif;
    color: #380b61;
    margin-left: 7%;
}

#subtitulo{
    font-family: sans-serif;
    color:#380b61;
    margin-left: 10%;
}

fieldset{
    border: 0%;
}

body{
    background-color: #380b61;
    font-family: sans-serif;
    font-size: 1em;
    color:#380b61;
    margin-left: 36%;
    margin-top: 2%;
    justify-content: center;
}

input, select, textarea, button{
    border-radius: 5px;
}

.campo{
    margin-bottom: 1em;
}

.campo label{
    margin-bottom: 0.2em;
    color:#742cb7;
    display: block;
}

fieldset.grupo.campo{
float:left;
margin-right: 1em;
}

.campo input[type="text"], .campo input[type="email"], .campo select, .campo textarea{
    padding:0.2em
    border:1px solid color: #724cb7;
    box-shadow:2px, 2px, 2px rgb(0,0,0,0.2em);
    display:block
}

.campo select option{
    padding-right:1em;
}

.campo input:focus, .campo select:focus, .campo textearea:focus{
background-color: rgb(116, 44, 183);
}

.botão{
font-size: 1.2em;
background: #742cb7;
border: 0;
margin-bottom: 1em;
color: #742cb7;
padding: 0.2em 0.6em;
box-shadow: 2px 2px 2px rgba(116, 44, 183);
text-shadow: 1px 1px 1px rgba(116, 44, 183);
position: absolute;
top:90%;
left: 90%;
margin-right: -50%;
transform: translate(-50%, -50%);
}

.botão:houver {
    background: #380b61;
    box-shadow: #742cb7 2px, 2px, 2px rgba(0,0,0,0,); 
    text-shadow: none;
}

#check{
    display: inline-block;
}

*{
    margin:0
    padding:0;
}

#titulo{
    font-family: sans-serif;
    color: #380b61;
    margin-left: 7%;
}

#subtitulo{
    font-family: sans-serif;
    color:#380b61;
    margin-left: 10%;
}

fieldset{
    border: 0%;
}

body{
    background-color: #380b61;
    font-family: sans-serif;
    font-size: 1em;
    color:#380b61;
    margin-left: 36%;
    margin-top: 2%;
    justify-content: center;
}

input, select, textarea, button{
    border-radius: 5px;
}

.campo{
    margin-bottom: 1em;
}

.campo label{
    margin-bottom: 0.2em;
    color:#742cb7;
    display: block;
}

fieldset.grupo.campo{
float:left;
margin-right: 1em;
}

.campo input[type="text"], .campo input[type="email"], .campo select, .campo textarea{
    padding:0.2em
    border:1px solid color: #724cb7;
    box-shadow:2px, 2px, 2px rgb(0,0,0,0.2em);
    display:block
}

.campo select option{
    padding-right:1em;
}

.campo input:focus, .campo select:focus, .campo textearea:focus{
background-color: rgb(116, 44, 183);
}

.botão{
font-size: 1.2em;
background: #742cb7;
border: 0;
margin-bottom: 1em;
color: #742cb7;
padding: 0.2em 0.6em;
box-shadow: 2px 2px 2px rgba(116, 44, 183);
text-shadow: 1px 1px 1px rgba(116, 44, 183);
position: absolute;
top:90%;
left: 90%;
margin-right: -50%;
transform: translate(-50%, -50%);
}

.botão:houver {
    background: #380b61;
    box-shadow: #742cb7 2px, 2px, 2px rgba(0,0,0,0,); 
    text-shadow: none;
}

#check{
    display: inline-block;
}

