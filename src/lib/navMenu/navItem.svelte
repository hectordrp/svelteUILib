<script lang='ts'>
    export let href:string|null = null;
    export let title:string|null = null;
</script>

<a {href} {title} on:click> <slot/> </a>

<style>
    a {
        text-decoration: none;
        color: inherit;
        position: relative;
        display: inline-block;
        margin: 0 20px;
        color: #000000;
        position: relative;
        outline: none;
        cursor: pointer;
    }
    a::after {
        bottom: -5px;
        content: '';
        width: 0;
        height: 3px;
        background: #FF6D43;
        display: block;
        position: absolute;
        transition: all .3s;
    }
    a:hover::after {
        width: 100%;
    }
</style> 