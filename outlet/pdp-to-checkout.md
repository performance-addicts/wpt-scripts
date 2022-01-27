Block i.js

setEventName	PDP
navigate	https://www.coachoutlet.com/products/city-tote-in-signature-canvas-with-heart-petal-print/C7616-IMBMC.html?frp=C7616%20IMBMC

setEventName	addToCart
execAndWait	document.querySelector('button.add-to-cart').click();

setEventName	shoppingBag
execAndWait	document.querySelector('a[href="https://www.coachoutlet.com/shopping-bag"]').click();

setEventName	checkout
execAndWait	document.querySelector('[data-qa="sb_btn_ptc"]').click();