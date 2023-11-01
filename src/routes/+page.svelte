<script>
  import TodoItem from "$lib/todo-item.svelte";

  const title = "Todo"
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>
<form action="" method="">
    <input type="text" name="text" aria-label="add a item" placeholder="+ Type here to add item">
</form>


<TodoItem></TodoItem>
<TodoItem></TodoItem>
<TodoItem></TodoItem>


