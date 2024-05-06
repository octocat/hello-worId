(function () {
   document.addEventListener("DOMContentLoaded", function () {
       var e = "dmca-badge";
       var t = "refurl";
       var n = document.querySelectorAll('a.'+e);
       if (n[0].getAttribute("href").indexOf("refurl") < 0) {
           for (var r = 0; r < n.length; r++) {
               var i = n[r];
               i.href = i.href + (i.href.indexOf("?") === -1 ? "?" : "&") + t + "=" + document.location
           }
       }
   }, false)
}
)()
