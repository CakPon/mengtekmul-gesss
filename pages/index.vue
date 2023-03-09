<template>
    <div class="h-screen backdrop-blur-3xl bg-gradient-to-r from-cyan-800 to-blue-800">
      <div class="bg-gray-100 rounded-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 rounded-3xl container mx-auto  translate-y-[30vh]">
        <div>
            <select name="bhs" id="bhs" class="px-5 mt-10 mx-10 rounded-3xl bg-gray-100 rounded-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 text-white">
                <option value="en">ENGLISH</option>
                <option value="id">INDO</option>
            </select>
        </div>
          <div class="py-5 px-10">
            <input id="text" class="p-5 min-w-full text-center rounded-xl bg-gray-100 rounded-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 focus:outline-none  text-white placeholder:text-gray-100" type="text" placeholder="type here" v-model="type"><br>
            
              <div>
            <select name="trans" id="trans" class="px-5 mt-10 mx-auto rounded-3xl bg-gray-100 rounded-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 text-white">
                  <option value="en">ENGLISH</option>
                  <option value="id">INDO</option>
                </select>
            <div class="py-5 px-10">
            <input id="text" class="p-5 min-w-full text-center rounded-xl bg-gray-100 rounded-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 focus:outline-none  text-white placeholder:text-gray-100" type="text" placeholder="type here" v-model="type"><br>
            
              </div>
            </div><br>
            <div class="flex justify-evenly ">
              <button type="submit" @click="" class="text-white font-semibold">Speak</button>
              <button type="submit" @click="" class="text-white font-semibold">Translate</button>
              <button type="submit" @click="" class="text-white font-semibold">Fusion</button>
              
            </div>
            <section id="translate" class="text-center pt-6 pb-2"></section>
          </div>
    </div>
</div>

</template>

<script>

</script>