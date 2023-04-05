<script lang='ts'>
    export let background: string = "";

</script>   

<figure style:background={background}>
    <div class="content">
        <div class="logo"></div>
        <div class="upper">
            <slot name="upper"/>
        </div>
        <div class="lower">
            <slot name="lower"/>
        </div>
    </div>
</figure>

<style>
    figure {
        position:relative;
        display: block;
        box-sizing: border-box;
        width: 100%;
        height: 100%;
        font-size: 1.5rem;
    }

    .content {
        padding: 3em;
    }

    .upper, .lower {
        display: flex;
    }
    .upper {
        
    }

    .lower {
        
    }
</style>