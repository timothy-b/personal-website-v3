<script>
    import Tv from './Tv.svelte'
</script>

<div class="center-column-wrapper">
    <div class="center-column">
        <header>
            <h3>Timothy Baumgartner</h3>
        </header>

        <img src="portrait.jpg" alt="me" style="max-width: 200px; border-radius: 0.75rem;" />

        <section class="header-tagline">
            <h2>Full-stack developer, recreational athlete, and lifelong tinkerer.</h2>
            <a href="../downloads/TGB_Resume.pdf" rel="external">Hire me</a>
        </section>

        <section class="tv-section">
            <h3>Tech Experience</h3>
            <p>A very brief overview: The last several years I've primarily worked on
                a <a href="https://www.logos.com/">templated</a> <a href="https://es.logos.com/">eCommerce</a> <a href="https://faithlife.com/store">solution</a>,
                <a href="https://www.logos.com/cart">checkout</a> and payment integrations,
                <a href="https://support.faithlife.com/hc/en-us/categories/360000498332-Faithlife-Giving">online giving</a>,
                and <a href="https://faithlife.com/faithlife-giving/activity">a social media site.</a></p>
            <div class="tv-row">
                <div class="tv">
                    <p class="tv-title">Backend</p>
                    <img src="microsoft_net_logo.svg" alt="Microsoft .NET Logo" class="tv-icon tv-single-icon" />
                    <p class="tv-blurb">I have broad experience with C#, though I'm also interested in opportunities to explore other modern languages such as Go, Rust, and Scala.</p>
                </div>

                <div class="tv">
                    <p class="tv-title">Frontend</p>
                    <img src="react_and_typescript.png" alt="React and Typescript logos" class="tv-icon" style="width: 256px;">
                    <p class="tv-blurb">I'm a fan of React + Typescript, and I'm interested in opportunities to explore other modern frontend tools such as Svelte, Elm, Ember, and Vue.</p>
                </div>

                <div class="tv">
                    <p class="tv-title">OS & Cloud</p>
                    <div style="display: flex; align-self: center;">
                        <img src="tux.png" alt="Linux logo" class="tv-icon tv-single-icon" />
                        <img src="windows_logo.png" alt="Windows logo" class="tv-icon tv-single-icon" style="margin-left: -2px;" />
                    </div>
                    <p class="tv-blurb">I have experience with Windows, Linux, Arduino, GCP, Azure, Docker, and Kubernetes.</p>
                </div>
            </div>
        </section>

        <section class="blurb-section">
            <h2>I'm an independent problem-solver who takes responsibility to make projects work.</h2>
            <p>If you're looking to hire an assembly-line worker, I can do that, but I'll inevitably become more than that as I take on more responsibility and ownership.</p>
            <a href="engineering-principles" style="font-size: large;">Read about engineering principles that have influenced me</a>
        </section>

        <section class="tv-section">
            <h3>Selected Projects</h3>
            <p>I don't spend as much of my free time as I'd like to on writing software, but I'd like to change that eventually :) Here are some of the things I've worked on instead.</p>
            <div class="tv-row">
                <Tv title="3D Printing"
                    imgSrc="ender_5.jpg"
                    imgAlt="Ender 5 render"
                    blurb="Hardware, firmware, software, and drafted designs made physical. True full-stack development😄. Check out some of the stuff I've done over the last few years."
                    href="https://github.com/timothy-b/3d-printing/"/>
                <Tv title="IOT-SEC"
                    imgSrc="particle_photon.png"
                    imgAlt="A Particle Photon"
                    blurb="A DIY security system using a Raspberry Pi and a glorified ESP32."
                    href="https://github.com/timothy-b/iot-sec/"/>
                <Tv title="DRZ-400s"
                    imgSrc="drz_400s.png"
                    imgAlt="Suzuki DRZ-400s motorcycle"
                    blurb="I've taken a cheap, common dual-sport motorcycle and turned it into a lightweight adventure touring motorcycle."
                    href="drz400s" />
            </div>
        </section>

        <div class="footer">
            <div><a href="mailto:tim@timothy-b.com">tim@timothy-b.com</a></div>
            <div><a href="http://timothy-b.com/downloads/TGB_Resume.pdf">Resume</a></div>
            <div style="display: contents;"><a href="https://www.linkedin.com/in/timothy-baumgartner-759b7b123" style="display: contents;"><img src="LinkedIn_Logo_White.png" alt="LinkedIn logo" style="height: 2rem;" /></a></div>
            <div style="display: contents;"><a href="https://github.com/timothy-b" style="display: contents;"><img src="GitHub_Logo_White.png" alt="Github logo" /></a></div>
            <div><span style="display: flex; align-items: center;">Powered by&nbsp;<a href="https://svelte.dev/" style="display: flex; align-items: center;">Svelte&nbsp;<img src="Svelte_Logo.svg" alt="Svelte logo" style="max-width: 32px;"></a></span></div>
        </div>
    </div>
</div>

<style>

    section {
        padding-top: 1rem;
    }

    .tv-row {
        display: flex;
        width: fit-content;
    }

    .footer {
        background-color: lightgray;
        width: 100%;
        padding: 1rem 0 1rem 0;
    }

    @media (min-width: 1024px) {
        .tv-row {
            flex-direction: row;
        }

        .footer div:not(:last-child)::after {
            content: " | ";
        }

        .footer {
            display: flex;
            align-items: center;
            justify-content: center;
        }
    }

    @media (max-width: 1023px) {
        .tv-row {
            flex-direction: column;
        }

        .footer {
            display: grid;
            gap: 1rem;
            grid-template-rows: repeat(5, 2rem);
            justify-items: center;
            align-items: center;
        }

        .center-column {
            min-width: 768px;;
        }
    }

   .center-column-wrapper {
        display: flex;
        flex-direction: column;
        align-items: center;

        height: max-content;
        width: 100%;
        left:0;
        right: 0;
        top: 0;
        bottom: 0;
        position: absolute;
        background-size: 1800% 1800% !important;

        background: linear-gradient(124deg, #1ddde8, #2b1de8);

        animation: rainbow 9s ease infinite;
    }

    @keyframes rainbow { 
        0% {background-position:0% 82%}
        50% {background-position:100% 19%}
        100% {background-position:0% 82%}
    }

    .center-column {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: min-content;
        background-color: white;
        box-shadow: 0 0 12px 4px #000;
    }

    .header-tagline a {
        display: flex;
        justify-content: center;
    }

    @media (min-width: 512px) {
        .header-tagline {
            width: 66%;
        }

        section.blurb-section {
            width: 66%;
        }

        section.tv-section {
            /* width: 66%; */
            width: min-content;
            padding: 2em;
        }
    }

    @media (max-width: 511px) {
        .center-column {
            align-self: flex-start;
            width: auto;
            min-width: auto;
        }

        .header-tagline {
            width: 90%;
        }

        section.blurb-section {
            width: 90%;
        }

        section.tv-section {
            width: 80%;
        }
    }

    .tv-title {
        font-weight: 600;
    }

    .tv-blurb {
        font-size: .875rem;
    }

    .tv-icon {
        align-self: center;
        height: 128px;
        object-fit: contain;
    }

    .tv-single-icon {
        width: 128px;
    }

    .tv {
        border-radius: 0.75rem;
        display: flex;
        flex-direction: column;
        flex: 1 1 0%;
        background-color: aliceblue;
        padding: 1rem;
        margin: 1rem;
        min-width: 256px;
    }

    .tv:not(:first-child) {
        margin-left: 1rem;
    }

    .blurb-section {
        background-color: lightblue;
        padding: 1rem;
        border-radius: 0.75rem;
    }

    
</style>