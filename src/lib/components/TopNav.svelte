<script lang="ts">
    import { IconBook2 } from '@tabler/icons-svelte';
</script>

<header class="sticky top-0">
    <div class="container mx-auto flex flex-wrap content-end justify-between px-16 py-8">
        <div class="flex gap-8">
            <img src="/brand/logo-okpan.svg" width="36" height="36" alt="Ọkpan logo"/>
            <h1 class="h2">Ọkpan</h1>
        </div>
	
	    <a href="https://wikipedia.org" type="button" class="btn hover:preset-tonal gap-8">
            User Guide <IconBook2 class="size-18" stroke='2'/>
        </a>
    </div>
</header>


<style>
    header{
        background: linear-gradient(var(--color-white), #ffffff00);
    }
</style>