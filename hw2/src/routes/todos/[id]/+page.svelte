<script>
    import BackButton from "../../BackButton.svelte";
</script>

<section class="section">
<h1 class="title ">Edit To Do</h1>
</section>

<!-- Check complete component -->

<section class="section">
    <form method="post">
        <div class="field">
            <textarea class="textarea" name="content" value={"content"}></textarea>
        </div>
        <div class="field">
            <button class="button" type="submit">Save</button>
            <button class="button">Mark as completed</button>
        </div>
    </form>
</section>

<section class="section">
<BackButton/>
</section>
