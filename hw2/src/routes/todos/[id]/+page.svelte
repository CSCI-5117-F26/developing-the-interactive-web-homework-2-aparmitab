<script>
    import BackButton from "../../BackButton.svelte";
</script>

<h1>Edit To Do</h1>

<!-- Check complete component -->

<form method="post">
    <textarea name="content" value={"content"}></textarea>
    <button type="submit">Save</button>
</form>

<button>Mark as completed</button>

<BackButton/>
