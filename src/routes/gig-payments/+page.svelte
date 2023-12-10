<script>
    import 'iconify-icon'
</script>


<div class="grid grid-cols-2">
    <div class="col-span-1 p-4">
        <div class="flex justify-between">
            <div class="flex bg-gray-200 hover:bg-gray-300 cursor-pointer py-2 px-4 rounded-full">
                <iconify-icon icon="carbon:arrow-left" width="1.2rem" class="mr-2"></iconify-icon>
                <p class="text-sm">Back</p>
            </div>
            <div class="flex w-24 justify-between">

                <iconify-icon icon="carbon:search" width="1.2rem" class="mr-2 p-2 rounded-full bg-gray-200 hover:bg-gray-300 cursor-pointer"></iconify-icon>
                <iconify-icon icon="carbon:apps" width="1.2rem" class="mr-2 p-2 rounded-full bg-gray-200 hover:bg-gray-300 cursor-pointer"></iconify-icon>

            </div>
        </div>
        <div class="my-4">
            <label for="price" class="block text-xl font-medium leading-6 text-gray-900">Search</label>
            <div class="relative mt-1 rounded-md shadow-sm">
                <input type="text" name="price" id="price" class="block w-full rounded-md border-0 py-1.5 px-4 text-gray-900 ring-1 ring-inset ring-gray-600 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-gray-600 sm:text-sm sm:leading-6" placeholder="Search anything">
            </div>
        </div>
    </div>
    <div class="col-span-1 bg-gray-800 bg rounded-tl-3xl rounded-tr-3xl min-h-screen text-white  p-4">
        <div class="flex justify-between">
            <div class="flex px-4 py-2 bg-gray-900/40 rounded-full cursor-pointer hover:bg-gray-900/90">
                <iconify-icon icon="carbon:wallet" width="1.2rem" class="mr-2"></iconify-icon>
                <p class="text-sm">My Wallet</p>
            </div>
            <div class="flex w-25 justify-between">

                <iconify-icon icon="carbon:filter" width="1.2rem" class="mr-2 bg-gray-900/40 rounded-full p-2 cursor-pointer hover:bg-gray-900/90"></iconify-icon>
                <iconify-icon icon="carbon:notification-new" width="1.2rem" class="bg-gray-900/40 rounded-full p-2 cursor-pointer hover:bg-gray-900/90"></iconify-icon>

            </div>
        </div>
        <div class="w-100 py-4 flex items-end border-b">
            <h1 class="text-6xl font-bold">2,156.43</h1>
            <div class="bg-gray-900/40 rounded-full flex items-center px-2 py-1 ml-2 mb-1 ">
                Up 40%
            </div>
        </div>
        <div class="grid grid-cols-2 gap-4 border-b py-4 mb-4">
            <div class="bg-gradient-to-bl from-cyan-500 to-cyan-400 hover:from-cyan-400 hover:to-cyan-500 shadow-xl p-4 flex flex-col items-end justify-between rounded h-32 cursor-pointer ">
                <iconify-icon icon="carbon:filter"  class="rounded-full bg-gray-900/40  p-2"></iconify-icon>
                <div class="text-white font-semibold">
                    Transfer Funds
                </div>

            </div>
            <div class="bg-gradient-to-tl from-pink-500 to-pink-400 hover:to-pink-500 hover:from-pink-400 shadow-xl p-4 flex flex-col items-end justify-between rounded h-32 cursor-pointer">
                <iconify-icon icon="carbon:filter"  class="rounded-full bg-gray-900/40  p-2"></iconify-icon>
                <div class="text-white font-semibold">
                    Option 1
                </div>

            </div>
            <div class="bg-gradient-to-tr from-yellow-500 to-yellow-400 hover:from-yellow-400 hover:to-yellow-500 shadow-xl p-4 flex flex-col items-end justify-between rounded h-32 cursor-pointer">
                <iconify-icon icon="carbon:filter"  class="rounded-full bg-gray-900/40  p-2"></iconify-icon>
                <div class="text-white font-semibold">
                    Option 1
                </div>

            </div>
            <div class="bg-gradient-to-bl from-green-500 to-green-400 hover:from-green-400 hover:to-green-500 shadow-xl p-4 flex flex-col items-end justify-between rounded h-32 cursor-pointer">
                <iconify-icon icon="carbon:filter"  class="rounded-full bg-gray-900/40  p-2"></iconify-icon>
                <div class="text-white font-semibold">
                    Option 1
                </div>

            </div>
        </div>
        <div class="bg-gradient-to-bl from-purple-500 to-purple-400 hover:to-purple-500 hover:from-purple-400 shadow-xl p-4 flex flex-col items-end justify-between rounded h-32 cursor-pointer ">
            <iconify-icon icon="carbon:filter"  class="rounded-full bg-gray-900/40  p-2"></iconify-icon>
            <div class="text-white font-semibold">
                Option 1
            </div>
        </div>
        <div class="flex  justify-between">
            <div class="text-gray-900  text-sm flex items-center gap-2 py-2 px-4 justify-center max-w-content mt-4 rounded-full bg-white">
                <iconify-icon icon="carbon:filter"></iconify-icon>
                Some placeholder text
            </div>
            <div class="text-gray-900  text-sm flex items-center gap-2 py-2 px-4 justify-center max-w-content mt-4 rounded-full bg-white">
                <iconify-icon icon="carbon:filter"></iconify-icon>
                Some placeholder text
            </div>
        </div>

    </div>
</div>


