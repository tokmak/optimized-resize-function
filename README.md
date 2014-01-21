Smartresize jQuery Plugin
=========================

From Paul Irish: http://www.paulirish.com/2009/throttled-smartresize-jquery-event-handler/


Debounced Resize() jQuery Plugin

If you’ve ever attached an event handler to the window’s resize event, you have probably noticed that while Firefox fires the event slow and sensibly, IE and Webkit go totally spastic.

This isn’t exactly throttling, but it’s close. Basically debouncing will fire your function after a threshold of time (e.g. 100ms) has elapsed since the last time it’s tried to fire. Throttling would withhold subsequent firings, but debouncing waits for the last one and runs that.







// usage:

$(window).smartresize(function(){

  // code that takes it easy...
  
});
