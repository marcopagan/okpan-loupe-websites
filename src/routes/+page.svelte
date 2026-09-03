<script>
	import FeaturesSection from '$lib/components/FeaturesSection.svelte';
	import Hero from '$lib/components/Hero.svelte';
    import TopNav from '$lib/components/TopNav.svelte';
	import { IconArrowUpRight } from '@tabler/icons-svelte';
</script>



<TopNav />

<main class="grid grid-cols-1 mt-8 lg:mt-24">
    


    <Hero />



    <section class="container mx-auto grid grid-cols-12 gap-16 py-24 lg:py-48 px-16">
        <div class="col-span-12 lg:col-span-5 flex justify-center flex-col gap-16 lg:pr-48">
            <h2 class="h2">What is it?</h2>
            <p class="text-surface-600">
                Ọkpan is a platform for reconnecting dispersed collections. Import artefact records from any source, enrich them with situated knowledge such as Indigenous designations, oral histories, and cultural context, and publish a unified catalogue that brings a scattered collection back together, wherever the objects themselves remain.
            </p>
        </div>
        <img class="col-span-12 lg:col-span-7" src="/okpan/img-wrapper.png" alt="Overview of the software">
    </section>



    <FeaturesSection />




    <section class="py-24 lg:py-120 bg-primary-100">
        <div class="container mx-auto grid grid-cols-12 gap-16 px-16">
        <div class="col-span-12 lg:col-span-5 flex justify-center flex-col gap-16 lg:pr-48">
            <h2 class="h2">About the project</h2>
            <p class="text-surface-600">
                Vivamus eget consequat justo. Quisque hendrerit augue eu dignissim bibendum. Fusce ut est sed nibh bibendum auctor in et urna. Praesent et tincidunt elit.
            </p>
        </div>
        <div class="col-span-12 lg:col-span-7 flex flex-col md:flex-row gap-16">
            <div class="card p-16 preset-outlined flex flex-col gap-16 bg-neutral-50" style="border: 1.5px solid var(--color-surface-100)">
                <img src="/okpan/card-db.svg" width="48" height="48" alt="Digital Benin logo">
                <h4 class="font-semibold">Digital Benin</h4>
                <p class="text-sm">Digital Benin brings together all objects, historical photographs and rich documentation material from collections worldwide to provide a long-requested overview of the royal artefacts from Benin Kingdom looted in the late nineteenth century. </p>
                <a href="https://digitalbenin.org" target="_blank" rel="noopener" class="btn preset-filled-brand text-white p-16 hover:gap-12">
                    Go to the website
                    <IconArrowUpRight stroke="1.5" class="size-18" />
                </a>
            </div>
            <div class="card p-16 preset-outlined flex flex-col gap-16 bg-neutral-50" style="border: 1.5px solid var(--color-surface-100)">
                <img src="/okpan/card-loupe.svg" width="48" height="48" alt="Loupe logo">
                <h4 class="font-semibold">Loupe</h4>
                <p class="text-sm">Loupe is a platform for provenance research. Structure an object's ownership history event by event, link each step to its supporting evidence, and visualize the full timeline, turning scattered archival research into a clear, shareable record.</p>
                <a href="https://digitalbenin.org" target="_blank" rel="noopener" class="btn preset-filled-brand text-white p-16 hover:gap-12">
                    Discover it
                    <IconArrowUpRight stroke="1.5" class="size-18" />
                </a>
            </div>
        </div>
        </div>
    </section>






    <section class="container mx-auto grid grid-cols-12 gap-16 py-24 lg:py-96 px-16">
        <div class="col-span-12 lg:col-span-5 flex justify-center flex-col gap-16 lg:pr-48">
            <h2 class="h2">About the project</h2>
            <p class="text-surface-600">
                Vivamus eget consequat justo. Quisque hendrerit augue eu dignissim bibendum. Fusce ut est sed nibh bibendum auctor in et urna. Praesent et tincidunt elit.
            </p>
        </div>
        <div class="col-span-12 lg:col-span-7 flex flex-col md:flex-row gap-16">
            <div class="card p-16 preset-outlined flex flex-col gap-16" style="border: 1.5px solid var(--color-surface-100)">
                <img src="/okpan/card-db.svg" width="48" height="48" alt="Digital Benin logo">
                <h4 class="font-semibold">Digital Benin</h4>
                <p class="text-sm">Digital Benin brings together all objects, historical photographs and rich documentation material from collections worldwide to provide a long-requested overview of the royal artefacts from Benin Kingdom looted in the late nineteenth century. </p>
                <a href="https://digitalbenin.org" target="_blank" rel="noopener" class="btn preset-tonal-brand p-16 hover:gap-12">
                    Go to the website
                    <IconArrowUpRight stroke="1.5" class="size-18" />
                </a>
            </div>
            <div class="card p-16 preset-outlined flex flex-col gap-16" style="border: 1.5px solid var(--color-surface-100)">
                <img src="/okpan/card-loupe.svg" width="48" height="48" alt="Loupe logo">
                <h4 class="font-semibold">Loupe</h4>
                <p class="text-sm">Loupe is a platform for provenance research. Structure an object's ownership history event by event, link each step to its supporting evidence, and visualize the full timeline, turning scattered archival research into a clear, shareable record.</p>
                <a href="https://digitalbenin.org" target="_blank" rel="noopener" class="btn preset-tonal-brand p-16 hover:gap-12">
                    Discover it
                    <IconArrowUpRight stroke="1.5" class="size-18" />
                </a>
            </div>
        </div>
    </section>


</main>


<footer class="bg-blue-500 p-64">(footer)</footer>
