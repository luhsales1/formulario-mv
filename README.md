# formulario-mv

 <!DOCTYPE HTML>
    <html>
      <head>
        <title>Café da manhã MV</title>
      </head>
      <body>
        <img src="img/imagemmv.png" width=100px>
      
      <h1>Café da Manhã MV</h1>   
  <section>

        
        <p>Nós ficamos muito felizes em poder nos reunir e trocar ideias e risadas. Abaixo tem um formulário a qual você precisa preencher com seus dados e informar o que gostaria de trazer para nosso momento de descontração:</p>
  
        <form>
      <center>
     <label for="nome"> Nome:</label>
      <input id="nome" type="text">

      <label for="opçãocafedamanha"> Opção café da           Manhã:</label>
      <input id="nome" type="text">
          
      <label for="cpf"> CPF:</label>
      <input id="CPF" type="number">
          
      <label for="telefone">Telefone:</label>
      <input id="telefone" type="number">
      <button id="botaoEnviar">Enviar</button>
        </center>
        </form>

      </body>
    </html>
  
  
  
  
  function validaFormulario(){

  if(document.getElementById("nome").value != "" &&
      document.getElementById("opcaocafedamanha").value != "" &&
      document.getElementById("CPF").value != "" &&
      document.getElementById("telefone").value != "" ){

    alert("Prontinho!")
   }else{
     alert("Por favor, preencha os campos nome e email.")
   }
 }
 
