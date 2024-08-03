<template>
  <Head><Title>Fight For America CTO</Title></Head>
  <main class="relative bg-gray-900 text-white">
    <nav class="fixed top-0 w-full bg-gray-800 z-10">
      <div class="flex justify-between items-center w-full max-w-6xl mx-auto shadow-lg p-6">
        <NuxtLink to="/">
          <img src="/01.jpeg" width="50px" class="aspect-square rounded-lg" alt="">
        </NuxtLink>
        <ul class="md:flex items-center gap-8 hidden">
          <li>
            <nuxt-link class=" text-base font-medium block" to="/">Home</nuxt-link>
          </li>
          <li>
            <a class=" text-base font-medium block" href="/#about">About</a>
          </li>
          <li>
            <a class=" text-base font-medium block" href="/#targets">Targets</a>
          </li>
          <li>
            <a class=" text-base font-medium block" href="/#partners">Partner</a>
          </li>
          <li>
            <a href="https://dexscreener.com/solana/gmpqunt8rdwmyh6gxsqtddzdfpfy94jh8yun4wabtcke" target="_blank" class="bg-blue-800 hover:bg-red-600 duration-500 ease-in-out px-5 py-2 rounded-md text-base font-medium block"">Chart</a>
          </li>
        </ul>
      </div>
    </nav>

    <header class="max-w-6xl mx-auto py-20 px-6 flex lg:flex-row flex-col justify-between items-center relative z-0 gap-8">
      <img src="/01.jpeg" class="lg:w-1/2 w-full aspect-square rounded-lg" alt="">
      <div>
        <h1 class="font-bold text-5xl ">Welcome to Fight For America CTO</h1>
        <div class="flex gap-8 mt-8">
          <a href="https://t.me/fight4americasol" target="_blank" class="flex items-center gap-4 bg-blue-800 hover:bg-red-600 duration-500 ease-in-out px-5 py-2 rounded-md  text-base font-medium">
            <Telegram class="w-5 h-5" />
            Telegram
          </a>
          <a href="https://x.com/Fight_4AMERICA" target="_blank" class="flex items-center gap-4 bg-blue-800 hover:bg-red-600 duration-500 ease-in-out px-5 py-2 rounded-md  text-base font-medium">
            <Twitter class="w-5 h-5" />
            Twitter
          </a>
        </div>
      </div>
    </header>

    <ul class="max-w-6xl flex gap-8 justify-between items-center flex-wrap mx-auto px-6 pb-20">
      <li class=" text-base">✅ Based and safe Team</li>
      <li class=" text-base">✅ Low Tax Mechanism: 0/0</li>
      <li class=" text-base">✅ Liquidity Burnt</li>
      <li class=" text-base">✅ Revoked before launch</li>
      <li class=" text-base">✅ Expert Marketing Lead</li>
    </ul>

    <section id="about" class="max-w-6xl mx-auto py-20 px-6">
      <h2 class="font-bold text-3xl text-center">About Fight For America</h2>
      <div class="flex lg:flex-row-reverse flex-col justify-between items-center gap-8 mt-8">
        <img src="/01.jpeg" class="lg:w-1/2 w-full aspect-square rounded-lg" alt="">
        
        <div>
          <h2 class="font-bold text-3xl">Our Mission</h2>
          <p class="">Our target is getting the attention of the floki army, let them know it has a younger brother here.</p>
          <ul class="grid gap-4 mt-8">
            <li class=" text-base">✅ Based and safe Team</li>
            <li class=" text-base">✅ Low Tax Mechanism: 0/0</li>
            <li class=" text-base">✅ Liquidity Burnt</li>
            <li class=" text-base">✅ Revoked before launch</li>
            <li class=" text-base">✅ Expert Marketing Lead</li>
          </ul>
        </div>
      </div>

    </section>

    <section id="targets" class="max-w-6xl mx-auto py-20 px-6">
      <h2 class="font-bold text-3xl text-center">Our targets are:</h2>
      <ul class="mt-8 flex flex-col items-center text-center gap-4">
        <li style="list-style-type: circle;">DEXSCREENER</li>
        <li style="list-style-type: circle;">DEXTOOLS</li>
        <li style="list-style-type: circle;">DEX ADS</li>
        <li style="list-style-type: circle;">DELUGE TRENDING</li>
        <li style="list-style-type: circle;">SAFEGUARD TRENDING</li>
        <li style="list-style-type: circle;">COMMUNITY WILL DECIDE WHICH MARKETING WILL BE THE NEXT</li>
        <li style="list-style-type: circle;">COINGECKO</li>
      </ul>
    </section>

    <section id="partners" class="max-w-6xl mx-auto py-20 px-6">
      <h2 class="font-bold text-3xl text-center">Partners</h2>
      <div class="flex justify-evenly items-center mt-8">
        <img src="/dexscreener.png" alt="Dexcreener logo" class="w-1/3 h-fit">
        <img src="/dextools.png.webp" alt="Dextools logo" class="w-1/3">
      </div>
    </section>


    <section class="max-w-6xl mx-auto py-20 px-6">
      <h2 class="font-bold text-3xl text-center">HOW TO BUY $AMERICA</h2>
      <div class="grid lg:grid-cols-2 gap-8 mt-8">
        <div class="flex items-center gap-5">
          <button class="p-3 rounded-lg bg-blue-800">
            <img src="/download.svg" width="30px" height="30px" alt="">
          </button>
          <div>
            <h3 class="font-bold text-lg">Download & setup Phantom</h3>
            <p>Download <a href="https://phantom.app/" target="_blank" class="text-blue-800">Phantom</a> (a crypto wallet in form of a browser extension).</p>
          </div>
        </div>

        <div class="flex items-center gap-5">
          <button class="p-3 rounded-lg bg-blue-800">
            <img src="/dollar.svg" width="50px" height="50px" alt="">
          </button>
          <div>
            <h3 class="font-bold text-lg">Buy and send SOL to Phantom</h3>
            <p>Buy SOL on an exchange (i.e. Binance, Kraken, Coinbase etc.). Transfer the tokens to your Phantom wallet address.</p>
          </div>
        </div>

        <div class="flex items-center gap-5">
          <button class="p-3 rounded-lg bg-blue-800">
            <img src="/swap.svg" width="50px" height="50px" alt="">
          </button>
          <div>
            <h3 class="font-bold text-lg">Head on to Raydium and swap for $AMERICA</h3>
            <p>Click <a href=" https://raydium.io/" class="text-blue-800">Raydium</a> to head on over to Raydium and use this address (AHpRkrh28jZDxKZ18Xy751Z43Pa2P<br />ePhf5qd6KKdwsbz) to select $America.</p>
          </div>
        </div>
        
        <div class="flex items-center gap-5">
          <button class="p-3 rounded-lg bg-blue-800">
            <img src="/wallet.svg" width="50px" height="50px" alt="">
          </button>
          <div>
            <h3 class="font-bold text-lg">View $America and Hold</h3>
            <p>Swap Sol for $America now you need America to your phantom to view your America. <a href="https://dexscreener.com/solana/gmpqunt8rdwmyh6gxsqtddzdfpfy94jh8yun4wabtcke" class="text-blue-800">Click here to view.</a></p>
          </div>
        </div>
      </div>
    </section>

    <footer class="max-w-6xl mx-auto py-20 px-6">
      <h2 class="font-bold text-3xl text-center">Disclaimer</h2>
      <p class="text-center">The information provided on this website doesn't constitute financial advice or trading advice investing in $America be ready to take full responsibility of your investment.</p>

      <div class="flex justify-center gap-8 mt-8">
          <a href="https://t.me/fight4americasol" target="_blank" class="flex items-center gap-4 bg-blue-800 hover:bg-red-600 duration-500 ease-in-out p-5 rounded-md  text-base font-medium">
            <Telegram class="w-5 h-5" />
          </a>
          <a href="https://x.com/Fight_4AMERICA" target="_blank" class="flex items-center gap-4 bg-blue-800 hover:bg-red-600 duration-500 ease-in-out p-5  rounded-md  text-base font-medium">
            <Twitter class="w-5 h-5" />
          </a>
        </div>
    </footer>
  </main>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Public+Sans:ital,wght@0,100..900;1,100..900&display=swap');
* {
  box-sizing: border-box;
  font-family: "Public Sans", sans-serif;
}
</style>