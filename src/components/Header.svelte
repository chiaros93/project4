<script>
    import Logo from "./Logo.svelte";
    import Link from "./Link.svelte";
    import Button from "./Button.svelte";
</script>

<header>
    <Logo />
    <nav>
        <Link text="Inicio" />
        <Link text="Peliculas" />
        <Link text="Series" />
        <Link text="Colecciones" />
        <Link text="Festivales" />
    </nav>

    <Button />

   
</header>

<style>
    header {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        margin: 20px 40px;
        gap: 20px;
        font-family: Arial, Helvetica, sans-serif ;
        font-weight: 200;
    }
    
</style>