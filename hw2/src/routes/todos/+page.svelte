
<!-- TODO: make todo item a component, also check complete should be a component-->


<h1>To Do</h1>

<a href="/done">See completed items</a>

<ul>
    <!-- {#each items as item}
        <li>
            <input type="checkbox">
            <a href="/todos/{id}">Todo item</a>
        </li>
    {/each} -->

    <li>
        <input type="checkbox">
        <a href="/todos/1">Todo item</a>
    </li>
</ul>

<form method="post">
    <input name="content" type="text" placeholder="Enter a todo here" required>
    <button type="submit">Create</button>
</form>
