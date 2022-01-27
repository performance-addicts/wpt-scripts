Block i.js


Production

setEventName	PLP

navigate	https://www.coach.com/shop/women/view-all?&srule=DA-4-ATS-5&moov_rt=MW

setEventName	PDP

execAndWait	document.querySelector('[data-qa=cm_tile_link_pt_img]').click();

Pre Prod

setEventName	PLP

navigate	https://tapestry-coach-pwa-preproduction.layer0.link/shop/men/view-all

setEventName	PDP

execAndWait	document.querySelector('[data-qa="cm_tile_link_pt_img"]').click();