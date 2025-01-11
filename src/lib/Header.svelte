<script>
    import logo from '../assets/images/logo.webp';
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
        gap: 10px;
    }

    figure{
        margin: 0;
        padding: 10px;

        & img{
            border-radius: 20px;
            mix-blend-mode: difference;
            /* mix-blend-mode: screen; */
        }
    }

    a{
        text-decoration: none;
        color: inherit;
    }
</style>