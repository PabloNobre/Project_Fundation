<template>
    <div id="footer">
        <div id="content_footer">

            <img src="../assets/logo_branca.jpg" alt="#" id="logo">

            <div class="abas">
                <div class="abasEspecificas">
                    <h2>REDES SOCIAIS</h2>
                </div>

                <div class="abasEspecificas">
                    <h2>GAMES</h2>
                    <a href="#">Battle Royale</a>
                    <a href="#">FPS</a>
                    <a href="#">PVP</a>
                    <a href="#">FPA</a>
                    <a href="#">RTS</a>
                    <a href="#">MOBA</a>
                    <a href="#">RPG</a>
                    <a href="#">MMORPG</a>
                </div>

                <div class="abasEspecificas">
                    <h2>NOTÍCIAS</h2>
                    <a href="#">Battle Royale</a>
                    <a href="#">FPS</a>
                    <a href="#">PVP</a>
                    <a href="#">FPA</a>
                    <a href="#">RTS</a>
                    <a href="#">MOBA</a>
                    <a href="#">RPG</a>
                    <a href="#">MMORPG</a>
                </div>

                <div class="abasEspecificas">
                    <h2>CROONOGRAMA</h2>
                    <a href="#">Battle Royale</a>
                    <a href="#">FPS</a>
                    <a href="#">PVP</a>
                    <a href="#">FPA</a>
                    <a href="#">RTS</a>
                    <a href="#">MOBA</a>
                    <a href="#">RPG</a>
                    <a href="#">MMORPG</a>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
    export default{
        name: 'FooterPage'
    }
</script>

<style>
    #footer{
        background-image: url(../assets/footer.png);
        height: 540px;
    }

    #content_footer{
        justify-content: center;
        align-items: center; 
        padding: 50px;
        margin: 0 134px;
        display: flex;
    }

    .abas{
        display: flex;
    }

    .abasEspecificas{
        display: flex;
        flex-direction: column;
    }
</style>