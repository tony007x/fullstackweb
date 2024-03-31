<script lang="ts">
    import Item from "./(components)/todo-item.svelte";
    const  title = "Todo | New";
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>

<form action="" method="">
    <input type="text" name="text" id="" placeholder="type to do" />
    <Item />
</form>

<Item />
<Item />
<Item />


