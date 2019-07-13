<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Run, Volodimir,  Run</div>
        <div class="text-green-700 leading-tight">I'm running half-marathons &amp in the future marathons</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/developer.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">How to find out where your limits are? And if they do not exist at all. Previously, I thought it would be difficult to run 21 km, but in fact
      I simply need to train and sometimes train a lot. The same thing to overcome 42 km. And if you can more? then why not try</p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/visual_data.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/finish_line.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="projects">Starts in which I participated::</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl">
        <li class="checkmark mb-6">
          <div><a href="https://runstyle.net/events/rivne-st-mykolas-run-2018/"> Rivne St.Mykolas Run 2018 16.12.2018</a>(8K 34:29  Place 8 Pace 4:19)</div>
          <div class="text-lg text-gray-600">ІІІ-ий Благодійний забіг RIVNE ST.MYKOLAS RUN 2018 – це традиційний забіг Святого Миколая, який ставить за мету зібрати кошти на купівлю шприцевих насосів для Рівненської обласної дитячої лікарні.</div>
        </li>
          <li class="checkmark mb-6">
            <div><a href="https://runstyle.net/events/pokrova-half-marathon-2018/">POKROVA HALF MARATHON 14.10.2018</a>(21K 1:32:11  Place 10 Pace 4:23)</div>
            <div class="text-lg text-gray-600"> І-й благодійний забіг, приурочений до Дня захисника України та свята Покрови Пресвятої Богородиці.</div>
          </li>
          <li class="checkmark mb-6">
            <div>XXXII традиційний забіг "Сильні духом 2018 (21K 1:43:07 Place 4 Pace 4:48)</div>
            <div class="text-lg text-gray-600">ХХХІІ легкоатлетичний  забіг «Сильні духом – 2018» в м. Рівне проводиться з метою:
-    популяризації здорового способу життя;
-	залучення до активного способу життя, занять фізичною культурою і спортом;</div>
          </li>
          <li class="checkmark mb-6">
            <div><a href="https://runstyle.net/events/rivne-night-run-2018/">Rivne Night Run 2018 14.07.2018</a>(6K 22:32 Place 13 Pace 3:57)</div>
            <div class="text-lg text-gray-600">Rivne Night Run 2018.</div>
          </li>
          <li class="checkmark mb-6">
          <div><a href="https://runstyle.net/events/rivne-euro-run-2018/">Rivne Euro Run 2018 19.05.2018</a>(6K 26:13  17 Place Pace 4:22)</div>
          <div class="text-lg text-gray-600">RivneEuroRun 2018 – це ІІ-ий традиційний забіг, присвячений Дню Європи.</div>
          </li>


        </ul>
      </div> <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6" id="about">Get to know me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="../../static/avatar-1.jpg" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">I love to write the code and  actively spend time on the journeys and discover new routes for running</div>
        </div>

      </div> <!-- end get-to-know me -->
    </div>

    <div class="overflow-x-hidden">
      <div class="contact-me bg-gray-100 pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6" id="contact">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>

          <p class="mb-12">You want to run away with me or ask questions. Write</p>

          <div class="text-lg sm:text-lg mb-16">
            <form action="#" class="mb-12">
              <div class="flex flex-wrap mb-6 -mx-4">
                  <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                      <label class="block mb-2 text-gray-800" for="name">
                          Name
                      </label>

                      <input type="text" name="name" id="name" placeholder="Jon Snow" class="block w-full border shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>

                  <div class="w-full px-4 md:w-1/2">
                      <label class="block text-gray-800 mb-2" for="email">
                          Email Address
                      </label>

                      <input type="email" name="email" id="email" placeholder="email@example.com"  class="block w-full border shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>
              </div>

              <div class="w-full mb-12">
                  <label class="block text-gray-800 mb-2" for="message">
                      Message
                  </label>

                  <textarea id="message" rows="5" name="message" class="block w-full border shadow rounded outline-none appearance-none focus:border-green-700 mb-2 px-4 py-4" placeholder="Enter your message here." required></textarea>
              </div>

              <div class="flex justify-end w-full">
                  <input type="submit" value="Submit" class="block bg-green-700 hover:bg-green-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3">
              </div>
          </form>
          </div>
        </div>
      </div> <!-- end contact-me -->
    </div>




  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Run | Volodimir Martuniyk | Runner'
  }
}
</script>
