<script>
    import LinkWithIcon from "$lib/components/LinkWithIcon.svelte";
</script>

<section>
    <h1>Lolcats</h1>
    <p>
        Lolcats is an app that I made as an excuse to set up a'my own home server.
        It's a simple file sharing utility, and one of few projects which I actually
        occasionally use.
    </p>
    <p>
        This is the first dynamic app I finished. I made a file sharing service first
        because it was a fairly quick and easy project, but still served as a good
        introduction to developing dynamic apps in Sveltekit. I even made a full auth
        system with JWTs, but then I disabled account registration because I wanted
        better control over who could make accounts. So that might have been a bit
        unnecessary, but it was fun and I did learn a fair amount (previously I had
        only ever done "real" auth in PHP).
    </p>
    <p>Link:</p>
    <LinkWithIcon
        src="/icons/lolcats.svg"
        href="https://share.khenr.se"
        target="_blank">Lolcats</LinkWithIcon
    >
    <p>Link to an uploaded example file:</p>
    <LinkWithIcon
        src="/icons/lolcats.svg"
        href="https://share.khenr.se/iRTOJ2EYtu3nh6Ka/view"
        target="_blank">Example - Lolcats</LinkWithIcon
    >
</section>
