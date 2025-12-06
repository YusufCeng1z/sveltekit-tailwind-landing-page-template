<script>
    // No scripts needed for static layout
</script>

<svelte:head>
    <title>Sign Up - Simple</title>
    <meta name="description" content="Page description" />
</svelte:head>

<div class="mb-10">
    <h1 class="text-4xl font-bold">Create your account</h1>
</div>

<!-- Form -->
<form>
    <div class="space-y-4">
        <div>
            <label
                class="mb-1 block text-sm font-medium text-gray-700"
                for="name"
            >
                Full name
            </label>
            <input
                id="name"
                class="form-input w-full py-2"
                type="text"
                placeholder="Corey Barker"
                required
            />
        </div>
        <div>
            <label
                class="mb-1 block text-sm font-medium text-gray-700"
                for="email"
            >
                Email
            </label>
            <input
                id="email"
                class="form-input w-full py-2"
                type="email"
                placeholder="corybarker@email.com"
                required
            />
        </div>
        <div>
            <label
                class="mb-1 block text-sm font-medium text-gray-700"
                for="phone"
            >
                Phone
            </label>
            <input
                id="phone"
                class="form-input w-full py-2"
                type="text"
                placeholder="(+750) 932-8907"
                required
            />
        </div>
        <div>
            <label
                class="mb-1 block text-sm font-medium text-gray-700"
                for="password"
            >
                Password
            </label>
            <input
                id="password"
                class="form-input w-full py-2"
                type="password"
                autocomplete="on"
                placeholder="••••••••"
                required
            />
        </div>
    </div>
    <div class="mt-6 space-y-3">
        <button
            class="btn w-full bg-linear-to-t from-blue-600 to-blue-500 bg-[length:100%_100%] bg-[bottom] text-white shadow-sm hover:bg-[length:100%_150%]"
        >
            Register
        </button>
        <div class="text-center text-sm italic text-gray-400">Or</div>
        <button
            class="btn w-full bg-linear-to-t from-gray-900 to-gray-700 bg-[length:100%_100%] bg-[bottom] text-white shadow-sm hover:bg-[length:100%_150%]"
        >
            Continue with GitHub
        </button>
    </div>
</form>

<!-- Bottom link -->
<div class="mt-6 text-center">
    <p class="text-sm text-gray-500">
        By signing up, you agree to the{" "}
        <a
            class="whitespace-nowrap font-medium text-gray-700 underline hover:no-underline"
            href="#0"
        >
            Terms of Service
        </a>{" "}
        and{" "}
        <a
            class="whitespace-nowrap font-medium text-gray-700 underline hover:no-underline"
            href="#0"
        >
            Privacy Policy
        </a>
        .
    </p>
</div>
