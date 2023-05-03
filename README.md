# Bootstrap-5-Navbar-and-hamburger-menu
Basic Navbar
With Bootstrap, a navigation bar can extend or collapse, depending on the screen size.

A standard navigation bar is created with the .navbar class, followed by a responsive collapsing class: .navbar-expand-xxl|xl|lg|md|sm (stacks the navbar vertically on xxlarge, extra large, large, medium or small screens).

To add links inside the navbar, use either an <ul> element (or a <div>) with class="navbar-nav". Then add <li> elements with a .nav-item class followed by an <a> element with a .nav-link class:
  
  Very often, especially on small screens, you want to hide the navigation links and replace them with a button that should reveal them when clicked on.

To create a collapsible navigation bar, use a button with class="navbar-toggler", data-bs-toggle="collapse" and data-bs-target="#thetarget". Then wrap the navbar content (links, etc) inside a <div> element with class="collapse navbar-collapse", followed by an id that matches the data-bs-target of the button: "thetarget".
