---
layout: test
title: test
permalink: /test/
breadcrumb: test page
<!-- collection_name: who-we-are -->
---
Test

<button onclick="myFunction('Demo1')" class="w3-button w3-block w3-left-align">
Open Section 1</button>

<div id="Demo1" class="w3-container w3-hide">
  <p>Some text..</p>
</div>

<script>
function myFunction(id) {
  var x = document.getElementById(id);
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else {
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>
