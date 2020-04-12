# Portfolio

HTML files:

- Each of the three HTML files(index, portfolio, contact) are linked to bootstrap css(found in the head of each page), bootstrap javascript(found just above the closing body element) as well as an external css sheet(Homework2.css)

- Each of the HTML files also use a dark theme navbar taken from bootstrap. The navbar contains a brand(Jerry Forsberg) as well as 3 links in the dropdown(Home, portfolio, contact)
JF-Homework2\Portfolio\About-me.PNG
JF-Homework2\Portfolio\Navbar.PNG


- For the content of the HTML sheets, Containers were used 

- After the containers were set, the width of the content was set using bootstraps grid system. Aside from the contact page, Mostly col-sm-8 was used to take up 2/3 of the width of the pages.

-Index Notes: 
    - used the col-sm-6 to align the h1 to the left, in line with the rest of the content
    - Used hr to create a line to seperate the header from the main content
    - Used 2 seperate articles to seperate the 2 rows, one with the image, one with the bottom row of text
    - For the first row, Used col-sm-4 so the image would take 1/3 of the defined area, and the text would take the other 2/3
    - col-sm-12 was used tomake the bottom row take the entire width of the defined space

-Portfolio Notes
    - set a row to hold all the content with sub rows for the proper sizing and positioning
    - set the id portfoliobody so that it would take on the formatting from css stylesheet homework2
    - created seperate sections for each row of images.
    - The class image placeholder was necessary to be able to include the image in the css file. Repeated for each image

- Contact Notes:
    - Used col-sm-8 so that the content would only take up 2/3 of the width of the page
    - Put the header into its own row
    - Used the col class to help the header align on the left side with the content of section
    - used a section to define the area that will contain the form
    - Used a form from bootstrap that has fields for name email and message.