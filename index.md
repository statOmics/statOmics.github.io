---
layout: default
title: StatOmics
---

The Statistical Omics Group, headed by Prof. [Lieven Clement](pages/about.md), is part of the [Department of Applied Mathematics, Computer Science and Statistics](https://www.ugent.be/we/twist/) of the [Faculty of Sciences](https://www.ugent.be/we/en) of [Ghent University](htpps://www.ugent.be), Belgium.

We develop novel statistical methods and tools for the interpretation of omics data.
Our research is structured according to three 'omics domain: Meta-genomics, Transcriptomics (RNA-seq and single cell RNA-seq) and Proteomics (Identification and Differential Analysis in Mass Spectrometry based Quantitative Proteomics). We also leverage expertise in experimental design and data analysis for omics to researchers in the life sciences and have a keen interest in 'omics data integration.


<div style="max-width: 100%;margin-left: auto ; margin-right: auto ;">

<script type="text/javascript" src="assets/js/jssor.slider-21.1.min.js"></script>
<!-- use jssor.slider-21.1.debug.js instead for debug -->
<script>
  jssor_1_slider_init = function() {

  var jssor_1_SlideshowTransitions = [
  {$Duration:1200,$Opacity:2}
  ];

  var jssor_1_options = {
  $AutoPlay: true,
  $SlideshowOptions: {
  $Class: $JssorSlideshowRunner$,
  $Transitions: jssor_1_SlideshowTransitions,
  $TransitionsOrder: 1
  },
  $ArrowNavigatorOptions: {
  $Class: $JssorArrowNavigator$
  },
  $BulletNavigatorOptions: {
  $Class: $JssorBulletNavigator$
  }
  };

  var jssor_1_slider = new $JssorSlider$("jssor_1", jssor_1_options);

  //responsive code begin
  //you can remove responsive code if you don't want the slider scales while window resizing
  function ScaleSlider() {
  var refSize = jssor_1_slider.$Elmt.parentNode.clientWidth;
  if (refSize) {
  refSize = Math.min(refSize, 600);
  jssor_1_slider.$ScaleWidth(refSize);
  }
  else {
  window.setTimeout(ScaleSlider, 30);
  }
  }
  ScaleSlider();
  $Jssor$.$AddEvent(window, "load", ScaleSlider);
  $Jssor$.$AddEvent(window, "resize", ScaleSlider);
  $Jssor$.$AddEvent(window, "orientationchange", ScaleSlider);
  //responsive code end
  };
</script>

<style>

  /* jssor slider bullet navigator skin 05 css */
  /*
  .jssorb05 div           (normal)
  .jssorb05 div:hover     (normal mouseover)
  .jssorb05 .av           (active)
  .jssorb05 .av:hover     (active mouseover)
  .jssorb05 .dn           (mousedown)
  */
  .jssorb05 {
  position: absolute;
  }
  .jssorb05 div, .jssorb05 div:hover, .jssorb05 .av {
  position: absolute;
  /* size of bullet elment */
  width: 16px;
  height: 16px;
  background: url('img/b05.png') no-repeat;
            overflow: hidden;
  cursor: pointer;
  }
  .jssorb05 div { background-position: -7px -7px; }
  .jssorb05 div:hover, .jssorb05 .av:hover { background-position: -37px -7px; }
  .jssorb05 .av { background-position: -67px -7px; }
  .jssorb05 .dn, .jssorb05 .dn:hover { background-position: -97px -7px; }

  /* jssor slider arrow navigator skin 12 css */
  /*
  .jssora12l                  (normal)
  .jssora12r                  (normal)
  .jssora12l:hover            (normal mouseover)
  .jssora12r:hover            (normal mouseover)
  .jssora12l.jssora12ldn      (mousedown)
  .jssora12r.jssora12rdn      (mousedown)
  */
  .jssora12l, .jssora12r {
  display: block;
            position: absolute;
  /* size of arrow element */
  width: 30px;
  height: 46px;
  cursor: pointer;
  background: url('assets/img/a12.png') no-repeat;
  overflow: hidden;
  }
  .jssora12l { background-position: -16px -37px; }
  .jssora12r { background-position: -75px -37px; }
  .jssora12l:hover { background-position: -136px -37px; }
  .jssora12r:hover { background-position: -195px -37px; }
  .jssora12l.jssora12ldn { background-position: -256px -37px; }
  .jssora12r.jssora12rdn { background-position: -315px -37px; }
</style>


<div id="jssor_1" style="position: relative; margin: 0 auto; top: 0px; left: 0px; width: 1100px; height: 500px; overflow: hidden; visibility: hidden;">
  <!-- Loading Screen -->
  <div data-u="loading" style="position: absolute; top: 0px; left: 0px;">
    <div style="filter: alpha(opacity=70); opacity: 0.7; position: absolute; display: block; top: 0px; left: 0px; width: 100%; height: 100%;"></div>
    <div style="position:absolute;display:block;background:url('pages/figs/loading.gif') no-repeat center center;top:0px;left:0px;width:100%;height:100%;"></div>
  </div>

  <div data-u="slides" style="cursor: default; position: relative; top: 0px; left: 25px; width: 1000px; height: 500px; overflow: hidden;">

  <div data-p="112.50" style="display: none;">
    <a href="https://www.ncbi.nlm.nih.gov/pubmed/29478411">
<img data-u="image" src="pages/figs/zinbwave-zingeR.png" title=""/>
    </a>
    </div>

    <div data-p="112.50" style="display: none;">
      <a href="https://www.ncbi.nlm.nih.gov/pubmed/28661493">
  <img data-u="image" src="pages/figs/saas.png" title=""/>
      </a>
</div>

    <div data-p="112.50" style="display: none;">
      <a href="https://www.ncbi.nlm.nih.gov/pubmed/26566788">
	<img data-u="image" src="pages/figs/msqrob.png" title=""/>
      </a>
    </div>

    <div data-p="112.50" style="display: none;">
      <a href="https://www.ncbi.nlm.nih.gov/pubmed/28350455">
  <img data-u="image" src="pages/figs/ddpcr.png" title=""/>
      </a>
    </div>

      <div data-p="112.50" style="display: none;">
        <a href="https://www.ncbi.nlm.nih.gov/pubmed/28784146">
    <img data-u="image" src="pages/figs/stageR.png" title=""/>
        </a>
      </div>
  </div>

  <!-- Bullet Navigator -->
  <div data-u="navigator" class="jssorb05" style="bottom:16px;right:16px;" data-autocenter="1">
    <!-- bullet navigator item prototype -->
    <div data-u="prototype" style="width:16px;height:16px;"></div>
  </div>
  <!-- Arrow Navigator -->
  <span data-u="arrowleft" class="jssora12l" style="top:0px;left:0px;width:30px;height:46px;" data-autocenter="2"></span>
  <span data-u="arrowright" class="jssora12r" style="top:0px;right:0px;width:30px;height:46px;" data-autocenter="2"></span>
</div>
<script>
  jssor_1_slider_init();
</script>

</div>
