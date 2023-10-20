<div>
    <p class="Titulo">Descubre el cine que lo cambia todo</p>
</div>
<div>
    <p class="Subtitulo">
        Con nuestra suscripción, accede a obras maestras, clásicos, cine
        <br>
        independiente, series exclusivas, documentales y mucho más.
    </p>
</div>

<div class="Subscripcion">
        <p class="Introduce">Para iniciar tu suscripción, introduce tu email aquí</p>
    <input class="mail" type="email" name="email"
         placeholder="Tu email"
        pattern=".+@gmail.com">
<input class="button" type="submit" value="COMEZAR">
<p class="Descricion">Más de 10.000 películas y series. Cancela cuando quieras.</p>
</div>


<style>
.Titulo {
    color: white;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
        sans-serif;
    font-size: 60px;
    font-weight: 800;
    margin-top: 10%;
    margin-left: 15px;
    margin-right: 15px;
    justify-content: center;
    text-align: center;
    display: flex;

}

.Subtitulo {
    color: white;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
        sans-serif;
    justify-content: center; 
    font-size: 24px ;
    font-weight: bolder;
    text-align: center;
    margin-top: -2.5%;
    margin-bottom: 3rem;
    margin-left: auto;
    margin-right: auto;
    padding-left: 1rem;
    padding-right: 1rem;
    text-rendering: optimizeLegibility;
    line-height: 40px;
}
.Subscripcion {
    color: white;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
        sans-serif;
    justify-content: center; 
    margin: auto;
     justify-content: center;
    text-align: center;

}

.Introduce{
    color: white;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
        sans-serif;
}

.mail{
    
background-color: #000;
color: #fff;
font-family: Verdana, sans-serif;
font-size: 14px;
border: 2px solid;
border-color: gray;
width: 25rem;
padding: 0.75rem;
border-radius: 5px;
}

.button{
    background-color: #02ffa1;
       color: black;
       font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
       font-weight: 600;    
       border-radius: 5px; 
       border: 2px solid #02ffa1;
       padding: 0.85rem;
       justify-content: center;
}
.Descricion{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: gray;

}

input:focus {
    border:2px solid #02ffa1;
    outline: none;
}
</style>