# mkt-digital-site
#Formulário responsivo

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
<style>
body 
  
  { 
    background-color: #1e1e1e;
    font-family: Arial, sans-serif;
    padding: 3%; 
    color: white;
    margin: 10px;
    margin-top: auto;
    min-width: 320px; 
    max-width: 1280px; 
    margin: auto; 
    

   
}

form {
  width: 410px;
  margin: 0 auto;
}

input[type="text"], input[type="email"], input[type="tel"] {
  width: 100%;
  padding: 12px 20px;
  margin: 12px 0;
  box-sizing: border-box;
  border-radius: 90px;
  text-align: left;
  
}

input[type="submit"] {
  background-color: yellow;
  color: #1e1e1e;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  border-radius: 90px;
 
  
}

input[type="submit"]:hover {
  opacity: 0.9;
}
</style>
</head>
<body>

  <center>
    <div><img src="groovin duo.png" alt="logo_imagem" width="410px" ></center>

    </div>
   
   
  
  
<h1>Fale com a gente</h1>
  
  <style>
    h1 { text-align: center; font-size: 24px;
         padding: 30px;
    
    }
    
    
  </style>

<form action="mailto:clarinsantista@gmail.com" method="post">
  <label for="fname">Nome:</label><br>
  <input type="text" id="name" name="name" placeholder="seu nome"><br>
  
  <label for="phone">Whatsapp:</label><br>
  <input type="tel" id="phone" name="phone" placeholder="whatsapp com DDD"><br>
  
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email"placeholder="seu email"><br>
  
  <input type="submit" value="Enviar">
  


 
</form>

</body>
</html>
