<script>
    import {maListe} from "../stores/groceriesStore";
    import ItemBox from "./ItemBox.svelte";

</script>
{#each $maListe as item}
<ItemBox item={item}/>
{/each}