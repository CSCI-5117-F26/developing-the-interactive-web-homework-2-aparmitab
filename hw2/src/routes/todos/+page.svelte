<!-- TODO: set up font awesome -->
<!-- TODO: make todo item a component, also check complete should be a component-->


<h1>To Do</h1>

<a href="/done">See completed items</a>

<ul>
    <!-- {#each items as item}
        <li>
            <button>
                <span class="icon">
                    <i class="fa-regular fa-square"></i> 
                </span>
            </button>
            <a href="/todos/{id}">Todo item</a>
        </li>
    {/each} -->

    <li>
        <button>
            <span class="icon">
                <i class="fa-regular fa-square" ></i> 
            </span>
        </button>
        <a href="/todos/1">Todo item</a>
    </li>
</ul>

<form>
    <input type="text" placeholder="Enter a todo here" required>
    <button type="submit">Create</button>
</form>
