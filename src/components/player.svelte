<script>
    import {
        Shuffle,
        SkipBack,
        Play,
        SkipForward,
        Repeat,
    } from "lucide-svelte";
</script>

<div class="flex items-center gap-6">
    <Shuffle size="20" class="text-zinc-200" />
    <SkipBack size="20" class="text-zinc-200" />
    <button class="w-10 h-10 flex items-center justify-center pl-1 rounded-full bg-white text-black">
        <Play />
    </button>
    <SkipForward size="20" class="text-zinc-200" />
    <Repeat size="20" class="text-zinc-200" />
</div>
<div class="flex items-center gap-2">
    <span class="text-xs text-zinc-500">0:31</span>
    <div class="h-1 rounded-full w-96 bg-zinc-600">
        <div class="bg-zinc-200 w-24 h-1 rounded-full" />
    </div>
    <span class="text-xs text-zinc-500">3:25</span>
</div>
