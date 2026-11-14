<script>
    import BackButton from "../../BackButton.svelte";
</script>

<h1>Edit To Do</h1>

<!-- Check complete component -->

<form>
    <textarea value={content}></textarea>
    <button type="submit">Save</button>
</form>

<BackButton/>
