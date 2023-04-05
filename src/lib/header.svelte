<script lang='ts'>
    export let urlImg: string = "https://brand.eviden.com/skin/layout/images/logo.svg";
    export let fixedHeight: string = "";

    let addedStyles: string;
    if (fixedHeight && fixedHeight != "") addedStyles = `height: ${fixedHeight};`
</script>

<header style="{addedStyles}">
    <div class="container">
        <div class="logo">
            <a href="/">
                <img src={urlImg} alt="Eviden">
            </a>
        </div>
        <div class="headerRight">
            <slot/>
        </div>
    </div>
</header>

<style>
    header {
        padding: 5px 0;
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        width: 100%;
        height: 100%;
        top: 0;
        background: #fff;
        display: flex;
        flex-direction: row;
        z-index: 900;
    }

    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 1317px;
        width: 100%;
        margin:auto;
        padding: 0 20px;
    }

    .logo {
        width: 172px;
    }

    img {
        width: 100%;
        max-width: 165px;
    }
</style>