<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Volodimir Martuniyk</div>
        <div class="text-green-700 leading-tight">Laravel developer</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/developer.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">Hello! I’m Volodimir. I spend my days developing web applications.
       I specialize in the Laravel PHP framework on the backend, Vue.js on the frontend and CSS for styling.</p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/mind_map.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/code_review.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="projects">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl">
          <li class="checkmark mb-6">
            <div>Active Box</div>
            <div class="text-lg text-gray-600">Convert PSD Layout to HTML and CSS files.<a href="https://github.com/vmartuniyk/activebox.git" target="_blank">Github link</a> or <a href="https://vactivebox.netlify.com/" target="_blank">Live link</a></div>
          </li>
          <li class="checkmark mb-6">
            <div>Lace of travel</div>
            <div class="text-lg text-gray-600">A site for a travel company where I developed frontend and backend <a href="https://merezhyvo-mandriv.com.ua/" target="_blank"></a></div>
          </li>
          <li class="checkmark mb-6">
            <div>Mafia travel</div>
            <div class="text-lg text-gray-600">This is a site with travel tips for traveling to Ukraine and the world. Budget tips, helpful laughs and lots of information for future travelers <a href="http://mafia-travel.com.ua/" target="_blank">Live link</a></div>
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

          <p class="mb-12">If you have questions or suggestions for cooperation, send your data in this form</p>

          <div class="text-lg sm:text-lg mb-16">
            <form name="contact" method="POST" data-netlify="true" class="mb-12">
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
    title: 'Home | Volodimir Martuniyk - portfolio site'
  }
}
</script>
