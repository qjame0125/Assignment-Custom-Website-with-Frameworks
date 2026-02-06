# My Bootstrap Art Page 

## Custom CSS Usage
Most of the page styling was handled using **Bootstrap utilities**. The images are flex into column.

## Most Challenging Component
The **carousel with cards and captions also apply scrollspy** was the most challenging component to implement.  
**Reasons:**
- Correct nesting of `.carousel-inner` and `.carousel-item` elements was crucial; initial attempts had items outside the inner container, breaking the carousel functionality.
- Combining Bootstrap cards inside carousel items required careful class management and custom widths to ensure images and captions aligned properly.
- Carousel controls initially referenced an incorrect ID, which prevented navigation.
- The target sections for Scrollspy were the "Fun Facts" of each art picture inside the carousel.
- Since carousel items are shown and hidden, Scrollspy could not consistently detect or access these targets, making it difficult to highlight the correct navigation link while scrolling.
- Additional adjustments were required to make the sections scrollable and accessible to the Scrollspy container.
## Easiest Component
The **accordion** was the easiest component to implement.  
**Reasons:**
- Bootstrap provides a fully functional accordion with minimal HTML.  
- Only required proper IDs and `data-bs` attributes, and Bootstrap handled the collapsing behavior automatically.

## How Bootstrap Improved the Code
Using Bootstrap significantly improved the project in several ways:
- **Rapid styling:** Most layout, spacing, and alignment was handled with utility classes, reducing the need for verbose custom CSS.
- **Responsive design:** Components automatically adapted to different screen sizes with minimal effort.
- **Prebuilt components:** Carousel, modal, and accordion functionalities were implemented without writing custom JavaScript, saving time and avoiding potential bugs.

## Framework Features Liked / Disliked
**Liked:**
- Utility classes for spacing, colors, and flex layouts made quick design adjustments very easy.
- Prebuilt components like carousel, modal, and accordion worked out-of-the-box.
- Responsiveness was easy to achieve using Bootstrap grid and flex utilities.

**Disliked:**
- Multiple `class` attributes can be tempting but break code if miss place.
