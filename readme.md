# Basic Geometry – Area Calculator (HTML, CSS, JavaScript)
Live link:-
https://simran-2024581.github.io/Areaweb/


This project is a simple **Basic Geometry Area Calculator** web page.  
It lets the user calculate the **area** of four two-dimensional shapes:

- Circle  
- Triangle  
- Square  
- Rectangle  

The page uses **internal CSS** and **internal JavaScript**, as required in the assignment.

---

## 1. How to Open the Project

1. Make sure the file is saved as `index.html`.
2. Right click on `index.html` and choose **Open with** → your web browser  
   (for example: Chrome, Edge, Firefox).
3. The page will open and show the title **“Basic Geometry”** and the shapes list.

You do **not** need any server or extra software. Only a browser is required.

---

## 2. How the Page Works

### Navigation

- At the top, there are links: **Circle, Triangle, Square, Rectangle**.
- Clicking a link scrolls directly to that shape’s section.
- Each section also has a **“Go to top”** link to scroll back to the title.

### Shape Sections

Each shape section:

- Asks the user to enter one or two values (for example: radius, base, height).
- Has a **Calculate** button.
- Shows the **result** in a read-only text box.
- Uses a small blue glow animation when the result is updated.

---

## 3. JavaScript Functions

The page uses four main functions in internal JavaScript:

1. **`getCircleArea()`**
   - Reads the radius from the input.
   - Validates that the value is a number.
   - Uses the formula: `Area = π × r²`.
   - Shows the answer with 2 decimal places.

2. **`getTriangleArea()`**
   - Reads base and height from the inputs.
   - Validates both numbers.
   - Uses the formula: `Area = 0.5 × base × height`.
   - Shows the answer with 2 decimal places.

3. **`getSquareArea()`**
   - Reads the side length.
   - Validates the number.
   - Uses the formula: `Area = side × side`.
   - Shows the answer with 2 decimal places.

4. **`getRectangleArea()`**
   - Reads width and height.
   - Validates both numbers.
   - Uses the formula: `Area = width × height`.
   - Shows the answer with 2 decimal places.

There is also a helper function:

- **`highlightResult(id)`**  
  - Adds a short animation around the result field to show that a new value was calculated.

---

## 4. CSS and Layout (Assignment Requirements)

- The **main wrapper** (`.wrapper`) has:
  - `width: 70%`
  - Center alignment with `margin: auto`
  - Padding and rounded corners
  - A glassmorphism card style

- Each **shape section** (`section`) has:
  - `width: 65%`
  - `margin` around it
  - `padding`
  - `box-sizing: border-box`
  - A border and background color

- Basic styling is added for:
  - Headings and text
  - Input boxes and buttons
  - Navigation links
  - “Go to top” links

The background of the page uses a **soft gradient** to make it look modern and clean.

---

## 5. Possible Future Improvements

- Add perimeter formulas for each shape.
- Show error messages near the input instead of using `alert`.
- Add input placeholders with examples (for example: “e.g., 5.5”).
- Add reset buttons for each section.

