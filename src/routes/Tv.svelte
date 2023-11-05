<script>
	/** @type {string} */
    export let title;

     /** @type {string} */
    export let imgSrc;

    /** @type {string} */
    export let imgAlt;

    /** @type {string} */
    export let blurb;

    /** @type {string} */
    export let href;
</script>


<button class="tv" on:click={() => window.location.href = href}>
    <a href={href} class="tv-title">
        <p>{title}</p>
    </a>
    <a href={href} class="tv-icon">
        <img src={imgSrc} alt={imgAlt} class="tv-icon" />
    </a>
    <p class="tv-blurb">{blurb}</p>
</button>

<style>
    .tv {
        border-radius: 0.75rem;
        --tw-bg-opacity: 1;
        display: flex;
        flex-direction: column;
        flex: 1 1 0%;
        background-color: rgb(var(--colors-wall-100)/var(--tw-bg-opacity));
        padding: 1rem;
        margin: 1rem;
        min-width: 256px;

        cursor: pointer;
    }

    @keyframes pop-on-hover {
        100% {
            transform: scale(1.025);
            box-shadow: 2px 2px 6px 0px #000;
        }
    }

    .tv:hover {
        animation-name: pop-on-hover;
        animation-duration: 0.25s;
        animation-timing-function: ease;
        animation-iteration-count: 1;
        animation-fill-mode: forwards;
    }

    .tv-blurb {
        font-size: .875rem;
        text-align: left;
    }

    .tv-icon {
        align-self: center;
        height: 128px;
        object-fit: contain;
    }

    .tv-title {
        font-weight: 600;
        font-size: 1rem;
    }
</style>