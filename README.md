```

\# EcoDrone Mini-Site



\## Seed

Fictional service: EcoDrone - Eco-friendly drone delivery service using sustainable, solar-powered drones for fast and green package transport.



\## Design Rationale

I chose EcoDrone as the seed to create a themed site around sustainability. The main layout uses CSS Grid for the overall structure (header, main, footer in rows, with columns adjusting for desktop), and Flexbox for internal components like navigation and feature cards to ensure flexible alignment. For interactivity, I implemented three CSS-only components: an accordion for expanding details (using :checked on a hidden checkbox), hover zoom effects on feature articles (with transform: scale), and tooltips on nav links (via :hover and ::after). The form is a pre-order form styled with custom checkboxes and radios using appearance: none and pseudo-elements for visual customization, plus required attributes for basic validation. Accessibility is handled with proper labels for all form elements, semantic HTML tags throughout, ARIA not strictly needed but keyboard focus is enhanced with :focus outlines. The design is consistent with CSS variables for colors (green primary for eco theme, dark secondary, yellow accent). Responsiveness uses mobile-first approach with media queries at 600px (tablet: adjust flex directions) and 900px (desktop: side nav via grid areas). I added a custom SVG logo and images for visual appeal, ensuring originality with a unique UI flow.



\## Screenshots

\- Mobile view:  

&nbsp; !\[Mobile View](screenshots/mobile.png)  

\- Tablet view:  

&nbsp; !\[Tablet View](screenshots/tablet.png)  

\- Desktop view:  

&nbsp; !\[Desktop View](screenshots/desktop.png)  

\- Form demo:  

&nbsp; !\[Form View](screenshots/form.png)  



\## Validator Proofs

\- HTML: W3C valid - no errors.  

&nbsp; !\[HTML Validation](screenshots/html-valid.png)  

\- CSS: W3C valid - no errors.  

&nbsp; !\[CSS Validation](screenshots/css-valid.png)  

```

