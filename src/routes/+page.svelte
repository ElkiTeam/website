<script>
    import { GradientButton } from "flowbite-svelte";
    import { GithubSolid, MessageCaptionSolid, DiscordSolid } from "flowbite-svelte-icons";
    import "../app.css";
    import Icon from "@iconify/svelte";    
</script>

<svelte:head>
    <title>Elki Team</title>
</svelte:head>

<div class="min-h-10/12">

    <h1 class="text-5xl text-center font-bold mt-20 flex *:items-center justify-center gap-2">
        <Icon icon="tabler:christmas-tree-filled" />
        Elki Team
    </h1>
    <h2 class="text-2xl text-center mt-5 opacity-50 px-10">A small team of Geometry Dash Hackers/Exposers.</h2>

    <div class="text-lg flex flex-col items-center justify-center my-20 w-full *:max-w-4xl px-10">
        <div>
            We are a small team of Geometry Dash <b>hackers</b> and <b>exposers</b>, 
            dedicated to improving the game and its community.
            Our goal is to <b>expose cheaters</b>, promote fair play, and provide tools for players to enhance their <b>gaming experience</b>. 
            We believe in transparency and integrity within the Geometry Dash community.
        </div>
    </div>

    <div class="text-center mt-10 flex flex-col gap-6 items-center w-full *:max-w-2xl px-10">
        <GradientButton color="cyan" size="xl" class="transition-all w-full" href="https://t.me/elkibotnews" target="_blank" rel="noopener noreferrer">
            <MessageCaptionSolid class="me-2 h-6 w-6" />
            Join Telegram
        </GradientButton>
        <GradientButton color="teal" size="xl" class="transition-all w-full" href="https://discord.gg/VgMua283nH" target="_blank" rel="noopener noreferrer">
            <DiscordSolid class="me-2 h-6 w-6" />
            Join Discord
        </GradientButton>
        <GradientButton color="green" size="xl" class="transition-all w-full" href="https://github.com/ElkiTeam" target="_blank" rel="noopener noreferrer">
            <GithubSolid class="me-2 h-6 w-6" />
            See GitHub
        </GradientButton>
    </div>

</div>

<div class="min-h-screen bg-zinc-900 pt-20 mt-20">

    <h1 class="text-5xl text-center font-bold px-10">
        Achievements
    </h1>
    <h2 class="text-2xl text-center mt-5 opacity-50 px-10">
        We have made some important contributions to the Geometry Dash community, including:
    </h2>

    <div class="text-lg flex flex-col items-center justify-center my-20 w-full *:max-w-4xl px-10">
        <ul class="list-disc list-inside *:py-4">
            <li>Developed the <b>Elki Bot</b>, simple yet powerful IRL Geometry Dash bot.</li>
            <li>Created a simple software suit (codename is <b>Apple in a glass</b>) to detect some shenanigans on cheater's PC.</li>
            <li>Exposed numerous cheaters.</li>
            <li>Created a <b>junior team</b> to train newcomers, helping them develop skills and prepare for <b>joining the main team.</b></li>
        </ul>
    </div>

</div>