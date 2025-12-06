<script>
    import PageIllustration from "./PageIllustration.svelte";
</script>

<section class="relative">
    <PageIllustration />
    <div class="mx-auto max-w-6xl px-4 sm:px-6">
        <!-- Hero content -->
        <div class="pb-12 pt-32 md:pb-20 md:pt-40">
            <!-- Section header -->
            <div class="pb-12 text-center md:pb-16">
                <div
                    class="mb-6 border-y [border-image:linear-gradient(to_right,transparent,--theme(--color-slate-300/.8),transparent)1]"
                    data-aos="zoom-y-out"
                >
                    <div class="-mx-0.5 flex justify-center -space-x-3">
                        <img
                            class="box-content rounded-full border-2 border-gray-50"
                            src="/images/avatar-01.jpg"
                            width="32"
                            height="32"
                            alt="Avatar 01"
                        />
                        <img
                            class="box-content rounded-full border-2 border-gray-50"
                            src="/images/avatar-02.jpg"
                            width="32"
                            height="32"
                            alt="Avatar 02"
                        />
                        <img
                            class="box-content rounded-full border-2 border-gray-50"
                            src="/images/avatar-03.jpg"
                            width="32"
                            height="32"
                            alt="Avatar 03"
                        />
                        <img
                            class="box-content rounded-full border-2 border-gray-50"
                            src="/images/avatar-04.jpg"
                            width="32"
                            height="32"
                            alt="Avatar 04"
                        />
                        <img
                            class="box-content rounded-full border-2 border-gray-50"
                            src="/images/avatar-05.jpg"
                            width="32"
                            height="32"
                            alt="Avatar 05"
                        />
                        <img
                            class="box-content rounded-full border-2 border-gray-50"
                            src="/images/avatar-06.jpg"
                            width="32"
                            height="32"
                            alt="Avatar 06"
                        />
                    </div>
                </div>
                <h1
                    class="mb-6 border-y text-5xl font-bold [border-image:linear-gradient(to_right,transparent,--theme(--color-slate-300/.8),transparent)1] md:text-6xl"
                    data-aos="zoom-y-out"
                    data-aos-delay="150"
                >
                    The website builder you're <br class="max-lg:hidden" />
                    looking for
                </h1>
                <div class="mx-auto max-w-3xl">
                    <p
                        class="mb-8 text-lg text-gray-700"
                        data-aos="zoom-y-out"
                        data-aos-delay="300"
                    >
                        Simple is a modern website builder powered by AI that
                        changes how companies create user interfaces together.
                    </p>
                    <div
                        class="relative before:absolute before:inset-0 before:border-y before:[border-image:linear-gradient(to_right,transparent,--theme(--color-slate-300/.8),transparent)1]"
                    >
                        <div
                            class="mx-auto max-w-xs sm:flex sm:max-w-none sm:justify-center"
                            data-aos="zoom-y-out"
                            data-aos-delay="450"
                        >
                            <a
                                class="btn group mb-4 w-full bg-linear-to-t from-blue-600 to-blue-500 bg-[length:100%_100%] bg-[bottom] text-white shadow-sm hover:bg-[length:100%_150%] sm:mb-0 sm:w-auto"
                                href="#0"
                            >
                                <span class="relative inline-flex items-center">
                                    Start Free Trial{" "}
                                    <span
                                        class="ml-1 tracking-normal text-blue-300 transition-transform group-hover:translate-x-0.5"
                                    >
                                        -&gt;
                                    </span>
                                </span>
                            </a>
                            <a
                                class="btn w-full bg-white text-gray-800 shadow-sm hover:bg-gray-50 sm:ml-4 sm:w-auto"
                                href="#0"
                            >
                                Learn More
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Hero image -->
            <div
                class="mx-auto max-w-3xl"
                data-aos="zoom-y-out"
                data-aos-delay="600"
            >
                <div
                    class="relative aspect-video rounded-2xl bg-gray-900 px-5 py-3 shadow-xl before:pointer-events-none before:absolute before:-inset-5 before:border-y before:[border-image:linear-gradient(to_right,transparent,--theme(--color-slate-300/.8),transparent)1] after:absolute after:-inset-5 after:-z-10 after:border-x after:[border-image:linear-gradient(to_bottom,transparent,--theme(--color-slate-300/.8),transparent)1]"
                >
                    <div
                        class="relative mb-8 flex items-center justify-between before:block before:h-[9px] before:w-[41px] before:bg-[length:16px_9px] before:[background-image:radial-gradient(circle_at_4.5px_4.5px,var(--color-gray-600)_4.5px,transparent_0)] after:w-[41px]"
                    >
                        <span class="text-[13px] font-medium text-white">
                            cruip.com
                        </span>
                    </div>
                    <div class="font-mono text-gray-500 [&_span]:opacity-0">
                        <span
                            class="animate-[code-1_10s_infinite] text-gray-200"
                        >
                            npm login
                        </span>{" "}
                        <span class="animate-[code-2_10s_infinite]">
                            --registry=https://npm.pkg.github.com
                        </span>
                        <br />
                        <span class="animate-[code-3_10s_infinite]">
                            --scope=@phanatic
                        </span>{" "}
                        <span class="animate-[code-4_10s_infinite]">
                            Successfully logged-in.
                        </span>
                        <br />
                        <br />
                        <span
                            class="animate-[code-5_10s_infinite] text-gray-200"
                        >
                            npm publish
                        </span>
                        <br />
                        <span class="animate-[code-6_10s_infinite]">
                            Package published.
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
