<script>
	import ImageFullBleed from "$lib/images/imageFullBleed.svelte";

</script>

<div class="imagesContainer">
    <div class="image">
        <ImageFullBleed background={"url('https://dgpgx7de9sbjj.cloudfront.net/eyJidWNrZXQiOiJjb21yYWRzLWV2aWRlbi1wcmQiLCJrZXkiOiJtZWRpYVwvcHJpdmF0ZVwvZjRmXC80MDdcLzQwNy1zb3VyY2UucG5nIiwiZWRpdHMiOnsicmVzaXplIjp7IndpZHRoIjo2MjAsImZpdCI6ImNvdmVyIn19fQ==?signature=06b96eae9f6b3ba86f71a887bd7165ce564191e01ee6134c8d279ef35bc47dba&version=1')"}>
        text
        </ImageFullBleed>
    </div>

</div>

<style>
    .imagesContainer {
        display: flex;
        height: 100vh;
    }

    .image {
        max-width: 300px;
        max-height: 600px;
    }
</style>