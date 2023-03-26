<template>
<div class="background-image">
  <div class="h-full">
    <h1 class="text-4xl font-bold flex items-center justify-center py-20">CAKARA</h1>
      <div class="container w-full mx-auto rounded-3xl border-4 py-4 sm:px-6 lg:px-9">
        <div class="flex mx-auto py-8 sm:px-6 lg:px-8">
        <input class="hover:shadow-md bg-gray-400 bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 w-full px-3 rounded-xl text-black placeholder-black" type="text" placeholder="Drop your link here">
        <button type="submit" @click="" class="px-6 py-3 bg-blue-600 text-white rounded-lg font-semibold hover:bg-blue-700 focus:outline-none">Convert</button>
      </div>
      <textarea
        id="text"
        type="text" 
        v-model="ketik"
        placeholder="Type your text here"
        class="hover:shadow-md bg-gray-400 bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10  w-full px-3 py-3 h-60 rounded-xl bg-amber-500 bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 text-xl focus:outline-none text-black placeholder-black">
      </textarea>
      <div class="mt-6 flex justify-evenly">
        <select name="bhs" id="bhs" class="p-2 rounded-lg bg-gray-100 focus:outline-none">
          <option value="en">ENGLISH</option> 
          <option value="id">INDONESIAN</option>
        </select>
        <button type="submit" @click="" class="px-6 py-2 bg-blue-600 text-white rounded-lg font-semibold hover:bg-blue-700 focus:outline-none">Speak</button>
        <button type="submit" @click="" class="px-6 py-2 bg-red-600 text-white rounded-lg font-semibold hover:bg-red-700 focus:outline-none">Clear</button>
        <button type="submit" @click="" class="px-6 py-2 bg-blue-600 text-white rounded-lg font-semibold hover:bg-blue-700 focus:outline-none">Pause</button>
        <button type="submit" @click="" class="px-6 py-2 bg-red-600 text-white rounded-lg font-semibold hover:bg-red-700 focus:outline-none">Stop</button>
        <button type="submit" @click="" class="px-6 py-2 bg-green-600 text-white rounded-lg font-semibold hover:bg-green-700 focus:outline-none">Add File</button>
      </div>
      <h1 class="text-4xl font-bold flex items-center justify-center pt-10">Translate</h1>
      <div class="h-fit pt-5 flex space-x-4 items-center justify-start">
      <div class="container mx-auto rounded-3xl border-4 px-4 py-8 sm:px-6 lg:px-8">
      <textarea
        id="text"
        type="text"
        v-model="type"
        placeholder="Type your text here"
        class="hover:shadow-md bg-gray-300 bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 w-full px-3 py-3 h-60 rounded-xl bg-fuchsia-300 bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-30 text-xl focus:outline-none text-black placeholder-black"> 
        </textarea>    
      <div class="mt-6">
        <select name="bhs" id="bhs" class="p-2 rounded-lg bg-gray-100 focus:outline-none">
          <option value="en">ENGLISH</option>
          <option value="id">INDONESIAN</option>
        </select>
      </div>
    </div>
    <div class="container mx-auto rounded-3xl border-4 px-4 py-8 sm:px-6 lg:px-8">
      <textarea
        id="text"
        type="text"
        v-model="ano"
        placeholder="Translation"
        class="hover:shadow-md bg-gray-300 bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 w-full px-3 py-3 h-60 rounded-xl bg-fuchsia-300 bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-30 text-xl focus:outline-none text-black placeholder-black"
        disabled>  
        </textarea>   
      <div class="mt-6 flex justify-evenly">
        <select name="bhs" id="bhs" class="p-2 rounded-lg bg-gray-100 focus:outline-none">
          <option value="en">ENGLISH</option>
          <option value="id">INDONESIAN</option>
        </select>
        <button type="submit" @click="" class="px-6 py-2 bg-blue-600 text-white rounded-lg font-semibold hover:bg-blue-700 focus:outline-none">Translate</button>
        <button type="submit" @click="" class="px-6 py-2 bg-red-600 text-white rounded-lg font-semibold hover:bg-red-700 focus:outline-none">Speak</button>
      </div>
      </div>
    </div>
    </div>
  </div>
</div>
</template>

<style>
  .background-image {
    background-image: url('@/assets/BackgroundWeb.png');
    background-size: cover;
    background-position: center center;
  }
</style>

<script>
  
</script>