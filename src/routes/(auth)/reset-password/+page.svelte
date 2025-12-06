<script>
    // No scripts needed for static layout
</script>

<svelte:head>
    <title>Reset Password - Simple</title>
    <meta name="description" content="Page description" />
</svelte:head>

<div class="mb-10">
    <h1 class="text-4xl font-bold">Reset password</h1>
</div>

<!-- Form -->
<form>
    <div class="space-y-4">
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
    </div>
    <div class="mt-6">
        <button
            class="btn w-full bg-linear-to-t from-blue-600 to-blue-500 bg-[length:100%_100%] bg-[bottom] text-white shadow-sm hover:bg-[length:100%_150%]"
        >
            Reset Password
        </button>
    </div>
</form>
