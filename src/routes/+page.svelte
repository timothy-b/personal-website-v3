<div class="center-column-wrapper">
    <div class="center-column">
        <h1>🚧 Under Construction 🚧</h1>

        <header>
            <h3>Timothy Baumgartner</h3>
        </header>

        <section class="header-tagline">
            <h2>Full-stack developer, recreational athlete, and lifelong tinkerer.</h2>
            <!-- TODO: resume9  -->
            <a href="../downloads/TGB_Resume.pdf" rel="external">Hire me</a>
        </section>

        <section class="tv-section">
            <h3>Tech</h3>
            <p>A very brief overview: The last several years I've primarily worked on a templated ecommerce solution, checkout and payment integrations, online giving, and a social media site.</p>
            <div class="tv-row">
                <div class="tv">
                    <!-- TODO: backend image -->
                    <p class="tv-title">Backend</p>
                    <p class="tv-blurb">I have broad experience with C#, though I'm also interested in opportunities to explore other modern languages such as Go, Rust, and Scala.</p>
                </div>

                <div class="tv">
                    <p class="tv-title">Frontend</p>
                    <p class="tv-blurb">I'm a fan of React + Typescript, and I'm interested in opportunities to explore other modern frontend tools such as Svelte, Elm, Ember, and Vue.</p>
                </div>

                <div class="tv">
                    <p class="tv-title">OS & Cloud</p>
                    <p class="tv-blurb">I have experience with Windows, Linux, Arduino, GCP, and Azure.</p>
                </div>
            </div>
        </section>

        <section class="blurb-section">
            <h2>I'm an independent problem-solver who takes responsibility to make projects work.</h2>
            <p>If you're looking to hire a cog in the machine to crank out spec work, I can do that, but I'll inevitably become more than that as I take on more responsibility and ownership.</p>
            <a href="/engineering-principles" rel="external">Read about engineering principles that have influenced me</a>
        </section>

        <section class="tv-section">
            <h3>Selected Projects</h3>
            <p>I don't spend as much of my free time as I'd like to on writing software, but I'd like to change that eventually :)</p>
            <div class="tv-row">
                <div class="tv">
                    <p class="tv-title">3D Printing</p>
                    <p class="tv-blurb">Hardware, firmware, software, and drafted designs made physical. True full-stack development😄. Check out some of the stuff I've done in this domain over the last few years.</p>
                </div>
                <div class="tv">
                    <p class="tv-title">IOT-SEC</p>
                    <p class="tv-blurb">A DIY security system using a Raspberry Pi and a glorified ESP32.</p>
                </div>
                <div class="tv">
                    <p class="tv-title">DRZ-400s</p>
                    <p class="tv-blurb">I've taken a cheap, common dual-sport motorcycle and turned it into a lightweight adventure touring motorcycle.</p>
                </div>
            </div>
        </section>
    </div>
</div>

<!-- TODO: footer w/ links & stuff -->
<!-- TODO: omage to urbit -->

<style>
    
    section {
        padding-top: 5rem;
    }

    .center-column-wrapper {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .center-column {
        display: flex;
        flex-direction: column;
        align-items: center;
        max-width: 1536px;
    }

    .header-tagline {
        width: 66%;
    }

    section.blurb-section {
        width: 50%;
    }

    section.tv-section {
        width: 66%;
    }

    .tv-title {
        font-weight: 600;
    }

    .tv-blurb {
        font-size: .875rem;
    }

    .tv-row {
        display: flex;
        flex-direction: row;
    }

    .tv {
        border-radius: 0.75rem;
        --tw-bg-opacity: 1;
        display: flex;
        flex-direction: column;
        flex: 1 1 0%;
        background-color: rgb(var(--colors-wall-100)/var(--tw-bg-opacity));
        padding: 1rem;
    }

    .tv:not(:first-child) {
        margin-left: 1rem;
    }
</style>