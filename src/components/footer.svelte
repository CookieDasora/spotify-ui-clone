<script>
    import Player from "./player.svelte";
    import Artist from "./artist.svelte";
    import {
        Mic2,
        LayoutList,
        Laptop2,
        Volume,
        Maximize2,
    } from "lucide-svelte";
</script>

<footer class="bg-zinc-800 border-t border-zinc-700 px-6 py-4 flex items-center justify-between">
    <div class="flex items-center gap-3">
        <Artist />
    </div>

    <div class="flex flex-col items-center gap-2">
        <Player />
    </div>

    <div class="flex items-center gap-4">
        <Mic2 size="20" />
        <LayoutList size="20" />
        <Laptop2 size="20" />
        <div class="flex items-center gap-2">
            <Volume size="20" />
            <div class="h-1 rounded-full w-24 bg-zinc-600">
                <div class="bg-zinc-200 w-10 h-1 rounded-full" />
            </div>
        </div>
        <Maximize2 size="20" />
    </div>
</footer>
