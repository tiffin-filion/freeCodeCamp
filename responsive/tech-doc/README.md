# build a technical documentation page
- can see main element with a corresponding id of main-doc, which contains page's main content
- within the main-doc element, can see several section elements, each with a class of main-section. should be a minimum of 5
- first element within each main-section should be a header element which contains text that describes the topic of that section
- each section element with the class of main-section should also have an id that corresponds with the text of each header contained within it. any spaces should be repaced with underscores
- the main-section elements should contain at least 10 p elements total (not each)
- the main-section elements should contain at least 5 code elements total (not each)
- the main-section elements should contain at least 5 li items total (not each)
- can see a nav element with a corresponding id of navbar
- navbar element should contain one header element which contains text that describes the topic of the technical documentation
- navbar should contain link elements with the class of nav-link. should be one for every element with the class main-section
- header element in the navbar must come before any link elements in the navbar
- each element with the class of nav-link should contain text that corresponds to the header text within each section
- when a navbar element is clicked, page should navigate to the corresponding section of the main-doc selment
- on regular sized devices (laptop, desktop), the element with id of navbar should be shown on the left side of the screen and should always be visible
- technical documentation page should use at least one media query