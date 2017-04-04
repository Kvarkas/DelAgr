// ==UserScript==
// @name         LJ dont acept agreement
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  Continue using LJ without acepting new terms
// @author       Kvark
// @match        http*://*.livejournal.com/*
// @grant        GM_log
// @run-at       document-idle
// ==/UserScript==
(function() {
    'use strict';
    var timer;
    function DelAgr() {
        var bodyhtml1 = document.getElementsByClassName("flatblue rutos")[0];
        if (bodyhtml1) {
            bodyhtml1.parentNode.removeChild(bodyhtml1);
        }
        var bodyhtml2 = document.getElementsByClassName("b-fader")[0];
        if (bodyhtml2) {
            bodyhtml2.parentNode.removeChild(bodyhtml2);
        }
    }
    // Podozdem i povtorim zacistku.
    timer = setInterval(DelAgr, 100);
})();
