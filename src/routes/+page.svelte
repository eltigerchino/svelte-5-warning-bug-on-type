<script lang="ts">
  import { page } from "$app/stores";

  const { form }: {
    form: {
      example: string;
    }
  } = $derived($page.form);
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
