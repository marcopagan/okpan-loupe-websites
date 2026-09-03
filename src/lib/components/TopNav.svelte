<script lang="ts">
    import { IconBook2 } from '@tabler/icons-svelte';
</script>

<header>
    <div class="container mx-auto flex flex-wrap content-end justify-between px-16 py-8">
        <div class="flex gap-8">
            <img src="/brand/logo-okpan.svg" width="36" height="36" alt="Ọkpan logo"/>
            <h1 class="h2">Ọkpan</h1>
        </div>
	
	    <button type="button" class="btn hover:preset-tonal gap-8">
            User Guide <IconBook2 class="size-18" stroke='2'/>
        </button>
    </div>
</header>


<style>
    header{
        position: sticky;
        top:0;
        background: linear-gradient(var(--color-root-bg-light), #ffffff00);
    }
</style>