<script>
    import { Play } from "lucide-svelte";
    export let src;
    export let title;
</script>

<a
    href="/"
    class="bg-white/5 group rounded-md flex items-center gap-4 overflow-hidden transition-colors ease-linear hover:bg-white/10"
>
    <img {src} width="104" height="104" alt={title} />
    <strong>{title}</strong>
    <button
        class="w-12 h-12 flex items-center justify-center pl-0.5 rounded-full bg-green-400 text-black ml-auto mr-8 invisible group-hover:visible"
    >
        <Play />
    </button>
</a>
