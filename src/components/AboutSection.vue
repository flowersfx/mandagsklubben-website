<template>
    <div class="flex flex-wrap">

      <section class="m-5 flex-auto max-width-720">
        <img src="/images/nuts.jpg" />
      </section>

      <section class="m-5 flex-1 max-width-720 min-width-320">
        <h1>
          Afterwork ★ Activities ★ Geeks
        </h1>
        <p class="text-2xl">
          Welcome to Måndagsklubben - a friendly afterwork community on that dreadful of weekdays: <em>Monday</em>
        </p>
        <p class="text-2xl">
          During the summer we go for picnics whenever weather allows, keep an eye on our Facebook page every Monday. We're also inviting you to hang out in our <a href="https://discord.gg/4VwCann">Discord server</a> and sometimes we host a <a href="https://www.twitch.tv/mandagsklubben">Twitch stream</a>.
        </p>
        <p>
          Our events are self-organized and free to attend and takes place downstairs at Medeltidskrogen Sjätte Tunnan in Stockholm, Sweden, on <em>every</em> Monday evening.
        </p>
        <p>
          Måndagsklubben was started by the programmers Iona Rosin and Oskar Duveborn back in 2011. They wanted a place to hang out after work
          on Mondays where both introverts and extroverts could feel both welcome and engaged. We've spent four years at KGB Bar and another
          four years at Wokhouse.
        </p>
        <p>
          You'll feel just as home sitting in a corner hacking away on your latest project with a coffee or a beverage from the bar as 
          when you're participating in the latest big screen or table activity with your friends, coworkers, strangers or competitors.
        </p>
        <p>
          People usually arrive between 17:00 and 19:00 and the crowd varies from week to week. If there's a special event, it'll be posted here, but fret not - we're here every Monday even if there's nothing special posted!
          </p>
      </section>  

    </div>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
.min-width-320 {
  min-width: 320px;
}
.max-width-720 {
  max-width: 720px;
}
a {
  color: #FFFC00;
}
</style>