<script>
    import Playlist from "./playlist.svelte";
    import ContextMenu from "./context_menu.svelte";
    import SidebarButtons from "./sidebar_buttons.svelte";
</script>

<aside class="w-72 bg-zinc-950 p-6">
    <ContextMenu />

    <nav class="space-y-5 mt-10">
        <SidebarButtons />
    </nav>

    <nav class="mt-10 pt-10 border-t border-zinc-800 flex flex-col gap-4">
        <Playlist name="Hot Takes Brasil" />
        <Playlist name="Aniver Funk" />
        <Playlist name="Daily Mix" />
        <Playlist name="My Playlist #13" />
        <Playlist name="Top Brasil" />
    </nav>
</aside>
