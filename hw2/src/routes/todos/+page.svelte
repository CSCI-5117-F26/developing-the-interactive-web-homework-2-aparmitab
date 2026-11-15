
<!-- TODO: make todo item a component, also check complete should be a component-->

<div class="columns m-5 is-multiline">
    <div class="column"><h1 class="title">To Do</h1></div>
    <div class="column is-narrow"><a href="/done" class="button">See completed items</a></div>
    <div class="column is-full">
        <ul class="m-2">
            <!-- {#each items as item}
                <li>
                    <input type="checkbox">
                    <a href="/todos/{id}">Todo item</a>
                </li>
            {/each} -->

            <li class="is-size-5">
                <input type="checkbox">
                <a href="/todos/1">Todo item</a>
            </li>
        </ul>

        <form method="post">
            <div class="field is-grouped">
                <input class="input" name="content" type="text" placeholder="Enter a todo here" required>
                <button class="button" type="submit">Create</button>
            </div>
        </form>
    </div>
</div>
