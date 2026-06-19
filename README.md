# Grand-Egyptian-Museum-Website
Grand Egyptian Museum Website Using HTML &amp; CSS

================================================================================
          GRAND EGYPTIAN MUSEUM - FAMOUS ARTEFACTS (WEB DESIGN)
================================================================================

--------------------------------------------------------------------------------
1. PROJECT OVERVIEW
--------------------------------------------------------------------------------
This is a responsive, grid-based gallery webpage designed for the Grand Egyptian 
Museum to showcase top famous ancient Egyptian artefacts. The project is built 
using standard web technologies: HTML5 for layout structure, CSS3 for advanced 
styling and grid distribution, and native JavaScript for user interactivity.

--------------------------------------------------------------------------------
2. TECHNICAL ARCHITECTURE & COMPONENTS
--------------------------------------------------------------------------------

2.1 HTML5 Structure (Semantic Layout)
 * <header>: Displays the main prominent title of the museum gallery.
 * <section class="gallery">: Acts as a flexible grid container that dynamically 
   holds all item cards.
 * <div class="card">: The structural component for each artefact. It groups 
   the asset's image (<img>) and its title text (<h3>).
 * <footer>: Displays the copyright year (2025) and provides recognition to 
   the design and development team.

2.2 CSS3 Styling & Visual Effects
 * Fixed Background: The body uses 'background-attachment: fixed' combined with 
   'background-size: cover' to keep the background image stationary while scrolling.
 * Modern Grid Layout: Uses the following configuration:
   'grid-template-columns: repeat(auto-fit, minmax(300px, auto));'
   This allows the webpage to be fully responsive, automatically adjusting the 
   number of columns based on screen size (Mobile, Tablet, or PC) without complex 
   media queries.
 * Hover Animations: Individual cards have a smooth hover effect ('transition: 
   transform 0.3s ease'). When a user hovers over a card, it scales up slightly 
   (1.05x) and changes opacity from 0.8 to 1.0 for a more engaging feel.
 * Color Theme: Uses an elegant sand/gold color tone (#c49a6c) for the header 
   and footer backgrounds to reflect the museum's identity.

2.3 JavaScript Interactivity
 * The page utilizes a clean, reusable function called 'openPage(page)'.
 * It uses the Browser Object Model (BOM) command 'window.open(page, '_blank')' 
   to seamlessly open the corresponding historical page in a new browser tab.
 * The function is triggered directly from the HTML using the 'onclick' attribute 
   on each card.

--------------------------------------------------------------------------------
3. FEATURED MUSEUM ARTEFACTS
--------------------------------------------------------------------------------
The webpage is currently structured to showcase and link to five main pieces:
 1. Statue of Ramses II            -> Opens: Pages/Statue of Ramses II.html
 2. Statue of Khafre               -> Opens: Pages/Statue of Khafre.html
 3. Golden Mask of Tutankhamun     -> Opens: Pages/Golden Mask of Tutankhamun.html
 4. Statue of Amenhotep III & Tiye -> Opens: Pages/Statue of Amenhotep III and Tiye.html
 5. Statue of Akhenaten            -> Opens: Pages/Statue of Akhenaten.html

--------------------------------------------------------------------------------
4. DEVELOPMENT TEAM
--------------------------------------------------------------------------------
This project was conceptualized, structured, and coded by:
 * Mahmoud Hassan
 * Amr Hossam
 * Ezzeldin Marouf
================================================================================
