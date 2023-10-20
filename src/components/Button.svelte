
<script>
    let imagePath = 'src/assets/Search.png';
  </script>


<div class="buttonContainer">

    <button class="suscribete">
    SUSCRÍBETE
    </button>

    <button class="sesion">
    INICIAR SESIÓN
    </button>


    <button class="search">
        <img src={imagePath} alt="Immagine del pulsante" />
    </button>

</div>

<style>

    .suscribete {
       background-color: #02ffa1;
       color: black;
       font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
       font-weight: 800;    
       border-radius: 5px; 
       border: 2px solid #02ffa1;
       margin-right: 10px;
       
    }

    .sesion {
        background-color: black;
        color:white;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-weight: 800;
        border-radius: 5px;
        border: 2px solid #ffff;     
        margin-right: 15px;
    }

    .search {
        background-color: transparent;
        border: none;
    }

    img {
        display: flex;
        flex-wrap: wrap;
        width: 25px;
        height: 25px;
        background-color: transparent;
    }  

    div{
        display: flex;
        margin-left: auto;
        }
   
</style>