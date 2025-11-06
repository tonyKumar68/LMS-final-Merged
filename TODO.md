# TODO: Add Navigation Links to Navbar

## Steps to Complete

- [x] Step 1: Add unique IDs to sections in Home.jsx
  - Add id="explore-courses" to the ExploreCourses component wrapper.
  - Add id="about-us" to the About component wrapper.
  - Add id="contact-us" to the Footer component wrapper.

- [x] Step 2: Modify Nav.jsx to add navigation links
  - Add three nav links ("Home", "About Us", "Contact Us") beside the logo in the navbar.
  - Style them appropriately (white text, hover effects, etc.).
  - Add onClick handlers to scroll to the respective sections using scrollIntoView.
  - Ensure responsive design: hide on mobile, or add to hamburger menu if needed.

- [ ] Step 3: Test the navigation
  - Run the frontend and verify that clicking the links scrolls to the correct sections.
  - Check on different screen sizes.

- [ ] Step 4: Handle edge cases
  - If not on Home page, navigate to "/" first, then scroll.
  - Adjust scroll position to account for fixed navbar height.
