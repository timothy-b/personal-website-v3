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
            <p>A very brief overview: The last several years I've primarily worked on
                a <a href="https://www.logos.com/">templated</a> <a href="https://es.logos.com/">eCommerce</a> <a href="https://faithlife.com/store">solution</a>,
                <a href="https://www.logos.com/cart">checkout</a> and payment integrations,
                <a href="https://support.faithlife.com/hc/en-us/categories/360000498332-Faithlife-Giving">online giving</a>,
                and <a href="https://faithlife.com/faithlife-giving/activity">a social media site.</a></p>
            <div class="tv-row">
                <div class="tv">
                    <!-- TODO: backend image -->
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
                    <img src="ender_5.jpg" alt="Ender 5 render" class="tv-icon" />
                    <p class="tv-blurb">Hardware, firmware, software, and drafted designs made physical. True full-stack development😄. Check out some of the stuff I've done in this domain over the last few years.</p>
                </div>
                <div class="tv">
                    <p class="tv-title">IOT-SEC</p>
                    <img src="particle_photon.png" alt="A Particle Photon" class="tv-icon" />
                    <p class="tv-blurb">A DIY security system using a Raspberry Pi and a glorified ESP32.</p>
                </div>
                <div class="tv">
                    <p class="tv-title">DRZ-400s</p>
                    <img src="drz_400s.png" alt="Suzuki DRZ-400s motorcycle" class="tv-icon" />
                    <p class="tv-blurb">I've taken a cheap, common dual-sport motorcycle and turned it into a lightweight adventure touring motorcycle.</p>
                </div>
            </div>
        </section>
    </div>
</div>

<!-- TODO: footer w/ links & stuff -->
<!-- TODO: homage to urbit -->

<style>

    section {
        padding-top: 5rem;
    }

    .tv-row {
        display: flex;
    }

    @media (min-width: 1024px) {
        .tv-row {
            flex-direction: row;
        }
    }

    @media (max-width: 1023px) {
        .tv-row {
            flex-direction: column;
        }
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

    @media (min-width: 512px) {
        .header-tagline {
            width: 66%;
        }

        section.blurb-section {
            width: 50%;
        }

        section.tv-section {
            width: 66%;
        }
    }

    @media (max-width: 511px) {
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
        --tw-bg-opacity: 1;
        display: flex;
        flex-direction: column;
        flex: 1 1 0%;
        background-color: rgb(var(--colors-wall-100)/var(--tw-bg-opacity));
        padding: 1rem;
        margin: 1rem;
        min-width: 256px;
    }

    .tv:not(:first-child) {
        margin-left: 1rem;
    }
</style>