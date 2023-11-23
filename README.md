# Harbour.Space-M3-PI2-Mulino-restaurant
Mulino Restaurant-Website using JavaScript, HTML, CSS


In the project, the following has been completed:

1) Home page:
   - Links for navigating to other pages (menu, join our team, social media, useful links, news)
     - Social media: Only the Instagram page is used, which is linked to the Instagram website.
     - Useful links: "About this website" and "Contact us" are pages with new windows with additional information. //wanted to make popups, but it             didn't want to work :/
     - News: I added a new text label where I put text inside it, which disappears when you start typing in the field.
               - The submit field does not work.

2) Menu page:
      *5 - Button to change background color (dark and light) colour palette*
   - NAVBAR: logo + background change using a switch + "Contact us" - link connected to the home page and opens the same page (wanted to make popups,       but it didn't want to work :/)
   - Slider with images (3 pictures) (slider has dots)
     *5 - Possible to **sort** data in grid view; 5 - Possible to **search** or **filter** grid view*
   - Search and sort fields for the menu
     *10 - Render image grids of some data.*
   - Menu: created using #tile-container with grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
          - Separated script with food-list.js connected to menu.html
          - In app.js, I created a function that allows me to display the title, description, and price of the meal in the table.
          - As we can see, all fields in the table are the same.
   - At the bottom of the page, we can see a button that takes us back to the home page.
  
4) Join the team:
  - The page is divided into two sections: left side and right side
     - Left side: an image without a scrollbar (fixed)
       *10 - Form to be able to create new content or to for example send emails*
     - Right side: form fields, where it is mandatory to fill in each field + date field + signature field + button to return to the home page
        - Form field: filling in each field is mandatory
        - Date field: also a mandatory field
          *5 - Possible to download CV (if portfolio)*
        - field when you can import file
        - Signature field: implemented using Canvas, which can be cleared or saved. If you clear it, you will only erase the window, but when you click          save, you can see the saved signature and the data you entered, as well as the URL for the signature.
        - Button that takes you back to the home page.

That's it, thank you for visiting my code.
