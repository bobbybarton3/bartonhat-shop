<script>
    import Book from "../components/Book.svelte";




</script>

<div class="background">
    <Book/>
</div>

<style lang="scss">
    .background{   
        position: absolute;
        overflow:hidden;
        background-image: url("bookshelf-backgroundBHC2.jpg");
        background-repeat: no-repeat;
        background-size:cover;
        height: 100vh;
        width: 100vw;
    }

    
</style>