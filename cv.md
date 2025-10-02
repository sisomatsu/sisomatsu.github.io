---
layout: page
title: CV
---
Click here to <a href="juri.jpg" target="_blank">view a picture of my dog</a>.<br>
Click here to <a href="juri.jpg" download>download a picture of my dog</a>.
<br>
<p id="last-modified"></p>

<script>
  const modified = new Date(document.lastModified);
  document.getElementById("last-modified").textContent =
    "Last updated: " + modified.toLocaleDateString();
</script>

<style>
  #last-modified {
    font-size: 0.9em;    /* optional: make it slightly smaller */
    color: #555;         /* optional: softer color */
    margin-top: 20px;    /* optional: spacing */
  }
</style>
