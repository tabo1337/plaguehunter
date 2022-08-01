var app = {
  $: {},
  init: function() {
    app.$.video = $(".js-hero__video");
    
    $(window).scroll(app.scroll);
    app.scroll(); 
  },
  scrollPosition: 0,
  scrollParallax: 0.5,
  scroll: function() {
    app.scrollPosition = $(window).scrollTop();
    app.$.video.css({"top": app.scrollPosition * app.scrollParallax });
  }  
}

$(window).ready(app.init);