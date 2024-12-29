<script>
    import logo from '../assets/images/logob.png';
    // import menu from '../assets/images/menu.png';

</script>

<header>
    <figure>
        <img src={logo} alt="logo" height="90">
    </figure>


    <!-- <figure>
        <img src={menu} alt="" width="40">
    </figure> -->
    <nav>
        <a href="#">Inicio</a>
        <a href="#buscador">Verificador</a>
    </nav>
</header>

<style>
    header{
        padding: 10px 0;
        border-bottom: 4px solid var(--terciary-red);
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 100px;
    }

    figure{
        margin: 0;
        padding: 0;
    }

    a{
        text-decoration: none;
        color: inherit;
    }
</style>