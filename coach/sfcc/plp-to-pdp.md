setEventName	loadPLP
navigate	%URL%

setEventName	clickProduct
exec	const allLinks = document.querySelectorAll('.link');
execAndWait	allLinks[1].click();