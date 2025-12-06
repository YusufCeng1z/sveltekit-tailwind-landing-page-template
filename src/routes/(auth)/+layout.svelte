<script>
    import Logo from "$lib/components/ui/Logo.svelte";
    let { children } = $props();
</script>

<header class="absolute z-30 w-full">
    <div class="mx-auto max-w-6xl px-4 sm:px-6">
        <div class="flex h-16 items-center justify-between md:h-20">
            <!-- Site branding -->
            <div class="mr-4 shrink-0">
                <Logo />
            </div>
        </div>
    </div>
</header>

<main class="relative flex grow">
    <div
        class="pointer-events-none absolute bottom-0 left-0 -translate-x-1/3"
        aria-hidden="true"
    >
        <div
            class="h-80 w-80 rounded-full bg-linear-to-tr from-blue-500 opacity-70 blur-[160px]"
        ></div>
    </div>

    <!-- Content -->
    <div class="w-full">
        <div
            class="flex h-full flex-col justify-center before:min-h-[4rem] before:flex-1 after:flex-1 md:before:min-h-[5rem]"
        >
            <div class="px-4 sm:px-6">
                <div class="mx-auto w-full max-w-sm">
                    <div class="py-16 md:py-20">
                        {@render children()}
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Right side -->
    <div
        class="relative my-6 mr-6 hidden w-[572px] shrink-0 overflow-hidden rounded-2xl lg:block"
    >
        <!-- Background -->
        <div
            class="pointer-events-none absolute left-1/2 top-1/2 -z-10 -ml-24 -translate-x-1/2 -translate-y-1/2 bg-blue-50"
            aria-hidden="true"
        >
            <img
                src="/images/auth-bg.svg"
                class="max-w-none"
                width="1285"
                height="1684"
                alt="Auth bg"
            />
        </div>
        <!-- Illustration -->
        <div class="absolute left-32 top-1/2 w-[500px] -translate-y-1/2">
            <div
                class="aspect-video w-full rounded-2xl bg-gray-900 px-5 py-3 shadow-xl transition duration-300"
            >
                <div
                    class="relative mb-8 flex items-center justify-between before:block before:h-[9px] before:w-[41px] before:bg-[length:16px_9px] before:[background-image:radial-gradient(circle_at_4.5px_4.5px,var(--color-gray-600)_4.5px,transparent_0)] after:w-[41px]"
                >
                    <span class="text-[13px] font-medium text-white">
                        cruip.com
                    </span>
                </div>
                <div
                    class="font-mono text-sm text-gray-500 transition duration-300 [&_span]:opacity-0"
                >
                    <span class="animate-[code-1_10s_infinite] text-gray-200">
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
                    <span class="animate-[code-5_10s_infinite] text-gray-200">
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
</main>
