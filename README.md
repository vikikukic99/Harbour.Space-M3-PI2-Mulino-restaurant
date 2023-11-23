# Harbour.Space-M3-PI2-Mulino-restaurant
Mulino Restaurant-Website using JavaScript, HTML, CSS


In the project, the following has been completed:

1) Home page:
   - Links for navigating to other pages (menu, join our team, social media, useful links, news)
     - Social media: Only the Instagram page is used, which is linked to the Instagram website.
     - Useful links: "About this website" and "Contact us" are pages with new windows with additional information.
     - News: I added a new text label where I put text inside it, which disappears when you start typing in the field.
               - The submit field does not work.

2) Menu page:
   - NAVBAR: logo + background change using a switch + "Contact us" link connected to the home page and opens the same page
   - Slider with images (3 pictures) (slider has dots)
   - Search and sort fields for the menu
   - Menu: created using #tile-container with grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
          - Separated script with food-list.js connected to menu.html
          - In app.js, I created a function that allows me to display the title, description, and price of the meal in the table.
          - As we can see, all fields in the table are the same.
   - At the bottom of the page, we can see a button that takes us back to the home page.
  
3) Postani deo tima:
   -Stranica je podeljena u dve celine: leva strana i desna strana
      -leva strana: slika bez skrolera(fiksirana je)
      -desna strana: polja za popunjavanje formulara, gde je obavezno popuniti svako polje + polje za datum + polje za potpisivanje + dugme za povratak       na pocetnu stranicu
         -polje za popunjavanje formulara -> obavezno je popunjavanje svakog polja
         -polje za datum -> takodje obavezno polje
         -polje za potpisivanje -> uradjeno preko Canvasa, koje moze da se obrise ili sacuva. Ako obrisete, samo cete ocistiti prozor, dok kada                   kliknemo da sacuvamo, mozemo ispod da vidimo sacuvan potpis i podatke koje smo uneli.
