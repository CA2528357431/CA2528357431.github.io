---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---



<div id="pdf-viewer"></div>
<script src="https://mozilla.github.io/pdf.js/build/pdf.js"></script>
<script>
  const url = '../files/An_Cao_Resume.pdf';
  const pdfjsLib = window['../files/An_Cao_Resume.pdf'];
  pdfjsLib.GlobalWorkerOptions.workerSrc = 'https://mozilla.github.io/pdf.js/build/pdf.worker.js';
  pdfjsLib.getDocument(url).promise.then(function (pdfDoc) {
    // Render logic here
  });
</script>


<iframe src="../files/An_Cao_Resume.pdf" width="600" height="800"></iframe>

