# Web-dev
### Live Demo Links
* [Open Assignment 1](./Assingment%201/index.html)
* [Open Assignment 2](./Assingment%202/index2.html)
* [Open Assignment 3](./Assignment%203/index.html)
# Assignment #3
Name: Zhabaikhan Ali | Group: IT 2503 | 

### Task 0. Responsive Typography
Created headings and paragraphs that dynamically scale their `font-size` across mobile (`<768px`), tablet (`768px–991px`), and desktop (`>=992px`) breakpoints using CSS `@media` rules.

**Screenshots:**
- Mobile View:
<img width="526" height="896" alt="Screenshot 2026-10-04 at 23 50 43" src="https://github.com/user-attachments/assets/49650f66-88b8-40fe-88ca-2a0bd9ff5b4a" />
- Tablet View:
<img width="1127" height="908" alt="Screenshot 2026-10-04 at 23 51 02" src="https://github.com/user-attachments/assets/f75ed2fe-11f0-4752-a42d-56f418f6497f" />



- Desktop View:
<img width="1431" height="908" alt="Screenshot 2026-10-04 at 23 51 31" src="https://github.com/user-attachments/assets/2b5e2d64-825f-4f98-8448-7ce28b2f2e64" />


---

### Task 1. Responsive Layout with Media Queries
Built a 3-box layout using pure CSS Flexbox and Media Queries (without Bootstrap). 
- **Desktop:** 3 boxes side by side (`calc(33.333% - 16px)`).
- **Tablet:** 2 boxes on the first row, 1 box on the second row (`calc(50% - 16px)`).
- **Mobile:** Stacked vertically (`100%`).

---

## Part 2. Bootstrap Grid System

### Task 2. Bootstrap Responsive Columns
<img width="1430" height="359" alt="Screenshot 2026-10-04 at 23 52 18" src="https://github.com/user-attachments/assets/8338af29-0ddb-4a86-b3f9-f5fcf3938dc4" />



---

## Part 3. Combined Project

### Task 3. Responsive Portfolio Page
Combined Bootstrap's 12-column grid (`col-lg-8` for the project showcase and `col-lg-4` for the personal info sidebar) with custom CSS media queries to control typography scaling, section padding, and a desktop-only availability badge (`.desktop-status-banner`).


- <img width="1437" height="888" alt="Screenshot 2026-10-04 at 23 52 46" src="https://github.com/user-attachments/assets/a6bdc312-b774-4552-b4bb-0715704bfc72" />



---

## Summary of Work Process
1. **Mobile-First Setup:** Established base styles in `style.css` targeting mobile screens (`<768px`), setting compact typography and vertical stacking (`flex: 1 1 100%`) for Task 0 and Task 1.
2. **Media Query Breakpoints:** Added `@media (min-width: 768px)` for tablet layouts and `@media (min-width: 992px)` for desktop layouts to align with standard responsive design breakpoints.
3. **Bootstrap 5 Integration:** Linked Bootstrap 5.3 CSS and JS via CDN to build the collapsible navigation bar (Task 3) and the 12-column responsive layout (Task 2).
4. **Portfolio Synthesis:** Designed the Task 4 portfolio by nesting a `col-md-6` card grid inside a `col-lg-8` main container alongside a `col-lg-4` sticky personal sidebar, reusing existing project imagery.









