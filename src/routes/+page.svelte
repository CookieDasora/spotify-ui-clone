<script>
    import {ChevronLeft, ChevronRight} from "lucide-svelte";

    import Footer from "../components/footer.svelte";
    import Sidebar from "../components/sidebar.svelte";
    import RecentlyPlayed from "../components/recently_played.svelte";
    import Recommendation from "../components/recommendation.svelte";
</script>

<div class="h-screen flex flex-col">
    <div class="flex flex-1">
        <Sidebar />

        <main class="flex-1 p-6">
            <div class="flex items-center gap-4">
                <button class="rounded-full bg-black/40 p-2">
                    <ChevronLeft />
                </button>
                <button class="rounded-full bg-black/40 p-2">
                    <ChevronRight />
                </button>
            </div>

            <h1 class="font-semibold text-3xl mt-10">Good morning</h1>

            <div class="grid grid-cols-3 gap-4 mt-4">
                <RecentlyPlayed />
            </div>

            <h2 class="font-semibold text-2xl mt-10">For you</h2>

            <div class="grid grid-cols-5 gap-4 mt-4">
                <Recommendation />
            </div>
        </main>
    </div>

    <Footer />
</div>
