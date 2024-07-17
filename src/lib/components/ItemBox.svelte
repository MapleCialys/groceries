<script>
    export let item;

    function toggleItem()
    {
        let checkbox = this.checked;
        this.parentNode.style.textDecoration = checkbox ? "line-through" : "none";
        console.log(this.parentNode);
    }
</script>
<div class="box">
    <label class="checkbox">
        <input type="checkbox" id="check" on:click={toggleItem}>
        {item}
    </label>
</div>