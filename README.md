# js-ComputedStyleOf


console.clear();

var ComputedStyleOf=window.getComputedStyle;
var element=document.body
var pseudoElt=null

var p,o=ComputedStyleOf(element,pseudoElt),i=o.length|0;
while(i--){
 p=o[i];
 console.log(p);
};
