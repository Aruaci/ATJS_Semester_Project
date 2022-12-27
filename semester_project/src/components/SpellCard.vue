<script>
export default {
    data() {
        return {
            spellName: 'Spell Name',
            spellDescription: 'Spell description like what it does and stuff'
        };
    }
}
</script>

<template>
    <div class="spell-card">
        <h3>{{ spellName }}</h3>
        <p>{{ spellDescription }}</p>
    </div>
</template>

<style>
    .spell-card {
        border: 2px solid rgb(171, 193, 244);
        background-color: white;
        border-radius: 5px;
        display: flex;
        flex-direction: column;
        place-items: center;
        height: 200px;
        width: 150px;
        padding: 10px;
    }

    .spell-card p {
        font-family: Arial, Helvetica, sans-serif;
    }
</style>