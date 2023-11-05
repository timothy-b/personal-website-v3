<script>
    import { dev } from '$app/environment';
    import ListSubItem from '../../components/ListSubItem.svelte';
</script>

<h1>DRZ-400s mods</h1>

I've had more fun modifying this bike than riding it 😅

Here's what I've done so far.

<h2>Critical</h2>
<ul>
    <li>Add crankcase covers</li>
    <li>Round off the inside of the shifter</li>
    <li>Add skid plate</li>
    <li>Add bark busters</li>
    <li>Add radiator guards (Unabiker)</li>
    <li><a href="https://www.thumpertalk.com/forums/topic/541623-charging-system-diagnoses-plus-the-free-power-mod/">Free power mod</a></li>
    <li>Add voltage meter to handlebars</li>
</ul>

<h2>Nice to have</h2>
<ul>
    <li>Add ACT wide ratio gears</li>
    <li>Do 3x3 mod</li>
    <li>Re-jet with JD kit (I'm at 160 main jet at sea level, should back down to 155)</li>
    <li>Replace exhaust with FMF Power Bomb header and Q4 slip-on exhaust</li>
        <ListSubItem>
            Add custom baffle to spark arrestor
        </ListSubItem>
        <ListSubItem>
            Shim where header meets slip-on
        </ListSubItem>
    <li>Add lower power LED headlight, blinkers (requires replacing flasher module), taillight</li>
    <li>Add custom extra-cushioned seat (Corbin)</li>
    <li>Add sheepskin seat cover</li>
    <li>Add heated grips</li>
    <li>Add auxiliary light</li>
    <li>Add larger gas tank</li>
    <li>Add custom rear shock</li>
</ul>

<h2>Additional resources</h2>
<ul>
    <li>
        <a href="https://www.thumpertalk.com/forums/forum/215-drz400-faq/">ThumperTalk DRZ400 FAQ</a>
    </li>
    <li>
        <a href="https://www.createfixshare.com/fix/">create.fix.share</a>
    </li>
</ul>

<div class="imageBox">
    <img src="DRZ_minus_engine.jpg" alt="DRZ-400s minus its engine" class="imageBoxSingleImage">
    <p class="imageBoxFooter">The pony in the stable, minus its tank, carburator, engine, radiator, exhaust, and seat.</p>
</div>
<br/>

<div class="imageBox">
    <a href="DRZ_crankcase_internal.jpg" target="_blank" class="imageBoxSingleImage">
        <img src="DRZ_crankcase_internal.jpg" alt="DRZ-400 crankcase internals" />
    </a>
    <p class="imageBoxFooter">The inside of my DRZ's crank case. I opened it up to install ACT wide ratio gears, which spreads the gear ratio by 27%, thereby eliminating one of the most common complaints about the DRZ.</p>
</div>
<br/>

<div class="imageBox">
    <div class="imageBoxDoubleImageWrapper">
        <a href="DRZ_crankcase_hole.jpg" target="_blank">
            <img src="DRZ_crankcase_hole.jpg" alt="DRZ-400 crankcase hole" />
        </a>
        <a href="DRZ_crankcase_patched.jpg" target="_blank">
            <img src="DRZ_crankcase_patched.jpg" alt="DRZ-400 crankcase patch" />
        </a>
    </div>
    <p class="imageBoxFooter">The previous owner clearly snapped a chain, which ripped off the chain guard and tore a hole in the crank case. They unsuccessfully tried to fix it two or three times with epoxy. While I had the crankcase open, I cleaned off the old epoxy, taped off the inside, roughed up the outside, and crafted and applied a patch from a can of Rockstar. A year later and Master Chief is still holding up fine 😄</p>
</div>

<br/>

{#if dev}
    <a href="/" rel="external">back</a>
{:else}
    <a href="/v3/" rel="external">back</a>
{/if}

<style>
    .imageBox {
        display: grid;
        max-width: 750px;
    }

    .imageBoxSingleImage {
        display: flex;
        max-width: 100%;
    }

    .imageBoxSingleImage img {
        max-width: 100%;
    }

    .imageBoxDoubleImageWrapper {
        display: flex;
        max-width: 750px;
    }

    .imageBoxDoubleImageWrapper a {
        display: flex;
        max-width: 50%;
    }

    .imageBoxDoubleImageWrapper img {
        max-width: 100%;
    }

    .imageBoxFooter {
        background-color: lightgray;
        font-size: 0.875rem;
        padding: 1em;
        margin: 0;
    }
</style>