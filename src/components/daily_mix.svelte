<script>
    export let title;
    export let artist;
    export let src;
</script>

<a href="/" class="bg-white/5 p-3 rounded-md flex flex-col gap-2 transition ease-linear hover:bg-white/10">
    <img {src} class="w-full rounded" width="120" height="120" alt="Metaphorical Music" />
    <strong class="font-semibold">{title}</strong>
    <span class="text-xs text-zinc-400">{artist}</span>
</a>
