### Hi there 👋

<!--
**giovanbarreira/giovanbarreira** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<div id="clock"></div>
<style>
  #clock {
    font-family: Arial, sans-serif;
    font-size: 32px;
    color: #ffffff;
    background-color: #000000;
    padding: 10px;
    border-radius: 10px;
  }
</style>
<script>
  // Get the clock element
  var clock = document.getElementById("clock");

  // Define a function to update the clock
  function updateClock() {
    // Get the current date and time
    var date = new Date();

    // Format the date and time as a string
    var dateString = date.toLocaleString();

    // Set the clock element's inner HTML to the date string
    clock.innerHTML = dateString;
  }

  // Update the clock every second
  setInterval(updateClock, 1000);
</script>
