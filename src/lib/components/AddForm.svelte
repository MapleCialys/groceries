<script>
    import {maListe} from "../stores/groceriesStore";

    function ajouter()
    {
        let newItem = document.getElementById('itemAjoute').value;
        $maListe = [...$maListe, newItem];
        document.getElementById('itemAjoute').value = "";
    }
</script>

<div class="box">
    <h2 class="subtitle">Ajouter a votre liste</h2>
    <div class="field">
        <div class="control">
            <textarea class="textarea" name="itemAjoute" id="itemAjoute"></textarea>
        </div>
        <div class="control">
            <button class="button is-primary" on:click={ajouter}>
                Ajouter
            </button>
        </div>
    </div>
</div>