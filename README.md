# Autoclicker-for-particle-clicker
An autoclicker for the clicker game Particle clicker

So there is another autoclicker for this game so I decided to cut the code a bit and remove the autobuy because it was annoying! so here it is:

/*
  Cheat code for http://particle-clicker.web.cern.ch/particle-clicker/
Made by Xtorbit & Jon2017
 */

(function(angular) {
  var e = angular.element;

  function c() {
    e('#detector').scope().dc.click();
  }
    setInterval(c, 10);
  setInterval(u, 100);
})(angular);
