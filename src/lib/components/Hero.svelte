<script lang="ts">
    import { IconChevronDown } from '@tabler/icons-svelte';
    import { Dialog  } from '@skeletonlabs/skeleton-svelte';
	import DownloadModal from './DownloadModal.svelte';
</script>

<section class="container mx-auto px-0 md:px-16">
    <div class="hero h-700 sm:rounded-lg flex flex-col flex-wrap gap-24 text-center justify-center items-center px-16 md:px-48">

        <h3 class="h1 leading-[1]">A tool for reconnecting dispersed collections</h3>
        <p>Ọkpan brings together records of artefacts scattered across museums worldwide, reconnecting them with the communities, knowledge, and histories they were separated from.</p>

        <Dialog>
	        <Dialog.Trigger class="btn preset-filled bg-primary-800 px-32 py-16 gap-8 hover:gap-12">
                Download
                <IconChevronDown class="size-18 transition" stroke="1.5"/>
            </Dialog.Trigger>
            <DownloadModal />
        </Dialog>
    </div>

</section>


<style>
    .hero{
        background: linear-gradient(var(--color-primary-100), var(--color-primary-300));
    }
</style>
