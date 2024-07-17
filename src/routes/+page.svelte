<script>
    import AddForm from "../lib/components/AddForm.svelte";
    import ItemList from "../lib/components/ItemList.svelte";
</script>
<h1 class="title has-text-centered">Liste de course</h1>
<div class="columns is-centered">
    <div class="column is-one-third">
        <AddForm/>
    </div>
    <div class="column is-one-third">
        <ItemList/>
    </div>
</div>