<script>
    import Book1 from "../components/Book1.svelte";
    import Book2 from "../components/Book2.svelte";
    import Book3 from "../components/Book3.svelte";
    import Book4 from "../components/Book4.svelte";
    import Book5 from "../components/Book5.svelte";
    import Trunk from "../components/Trunk.svelte";
</script>

<div class="shelf">
    <Book1 />
    <Book2/>
    <Book3/>
    <Book4/>
    <Book5/>
    <Trunk/>
</div>

<style lang="scss">
    .shelf{   
        position: absolute;
        background-image: url("bookshelf-backgroundBHC2.jpg");
        background-repeat: no-repeat;
        background-size:cover;
        height: 316*1.5px;
        width: 283*1.5px;
    }

    
</style>