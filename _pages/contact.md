---
title: "Contact"
permalink: /contact/
layout: single
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/dublinbridge.jpg
---

<style>.athere:before {content: '@'; }</style>
<script type="text/javascript">
function init(){
    var x = document.getElementsByClassName('contactaddr');
    for (var i = 0; i < x.length; i++){
        var sp = x[i];
        var mt = sp.innerHTML;
        mt = mt.replace(/<span.*\/span>/, '@');
        sp.innerHTML = '<a href="mailto:' + mt + '">' + mt + '</a>';
    }
}
window.addEventListener("load", init, false);
</script>
For questions and comments regarding the workshop please contact [the organizers](/organisation) at <span class="contactaddr">evalnlg.inlg<span class="athere"></span>gmail.com</span>. 
