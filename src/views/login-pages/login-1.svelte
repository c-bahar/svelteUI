<script>
	let email = null;
    let password = null;
</script>

<div class="min-h-screen flex items-center pb- pb-32 px-5 sm:px-10 bg-gradient-to-b from-blue-500 to-blue-900">
   <form action="" class="w-full sm:w-10/12 md:w-8/12 2xl:w-5/12 mx-auto">
        <div class="shadow-xs">
            <div class="flex-1 flex-col items-center">
                <div class="pl-2 mb-1">
                    <label for="email" class="text-white text-lg">Email</label>
                </div>
                <div class="bg-blue-500 bg-opacity-75 rounded-lg">
                    <input bind:value={email} class="w-full p-4 bg-transparent placeholder-blue-200 outline-none text-white" type="email" id="email" name="email" placeholder="Type your email">
                </div>
            </div>
            <div class="flex-1 flex-col items-center mt-5">
                <div class="pl-2 mb-1">
                    <label for="password" class="text-white text-lg">Password</label>
                </div>
                <div class="bg-blue-500 bg-opacity-75 rounded-lg">
                    <input bind:value={password} class="w-full p-4 bg-transparent placeholder-blue-200 outline-none text-white" type="password" id="password" name="email" placeholder="Type your password">
                </div>
            </div>
        </div>

        <button class="block w-full rounded-xl bg-blue-900 py-3 text-white font-bold shadow mt-10">Login</button>
   </form>
</div>
