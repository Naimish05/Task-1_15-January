Task 1: Semantic HTML Personal Profile Page

Project Overview

Here’s a personal profile page, crafted in semantic HTML as part of the Elevate Labs training program. It’s built to show off how to use HTML5’s semantic elements the right way—making the page accessible, good for SEO, and easy on the eyes with a modern teal-to-coral gradient.

Objectives

- Build a full personal profile page using semantic HTML.
- Structure everything with the right HTML5 elements.
- Make sure the page’s accessible—so alt text for images, ARIA labels, all that.
- Set up easy navigation with anchor links across the page.
- Keep the design clean, modern, and simple.
- Add a working contact form.

Technologies Used

- HTML5 for semantic structure.
- CSS3 for all the styling—gradients, animations, and making sure the design works on any device.
- Google Fonts: using Audiowide and Inter.
- Vanilla JavaScript, just enough for controlling scroll position.
- No frameworks—just pure HTML, CSS, and JS.

Features

1. Semantic HTML Structure

- Uses <header> for the main header with navigation built in.
- <nav> holds the menu.
- <main> carries the main content.
- Related content gets grouped with <section>.
- Each education entry sits in its own <article>.
- <footer> rounds things out with social links at the bottom.

2. Accessibility

- Every image has an alt attribute for screen readers.
- Headings use <h1>, <h2>, <h3> in the right order.
- Links have clear, descriptive text and ARIA labels where needed.
- Form labels are tied properly to their inputs.
- The structure meets WCAG standards.

3. Navigation

- The header sticks to the top—name on the left, nav links on the right.
- Anchor links jump to each main section: About, Education, Skills, Technology Stack, Contact.
- Hover effects are clean and simple.

4. Content Sections

- Header: name, tagline, and the horizontal navigation.
- About: short bio and a centered profile photo.
- Education: three detailed entries covering academic background.
- Skills: grid display of technical skills, each with a gradient background.
- Technology Stack: animated icons for HTML, CSS, JS, PHP, Canva, React, and Figma. The icons “jump” in a wave motion.
- Contact: working contact form with a gradient submit button.
- Footer: copyright plus social links (LinkedIn, GitHub, portfolio, email) shown as SVG icons.

5. Modern Design Elements

- The page uses a teal-to-coral gradient (#06b6d4 to #f97316).
- The whole look is clean, professional, and modern.
- Section headings have a colored border on the left for emphasis.
- Technology icons feature a jumping wave animation.
- Responsive grids for layouts.
- Forms have clear focus states.
- Gradients show up in the header, footer, skills, and buttons.

6. Responsive Design

- The design starts mobile-first.
- Layouts stretch or shrink to fit any screen.
- Navigation stacks vertically on smaller screens.
- Optimized for phones, tablets, and desktops.
- Media queries kick in at 768px for breakpoints.

Project Structure

Task-1-Profile/
│
├── index.html          # Main HTML file with clear, semantic structure
├── style.css           # Clean CSS with smooth animations
├── Passport.webp       # Profile photo
├── Icons/              # Icons for tech stack
│   ├── HTML.png
│   ├── CSS.png
│   ├── JS.png
│   ├── PHP.ico
│   ├── Canva.ico
│   ├── React.ico
│   └── Figma.png
└── README.md           # This guide

Design Features

Color Palette

- Primary Gradient: Teal to orange (#06b6d4 → #f97316)
- Accent: Teal (#06b6d4)
- Dark Background: Slate (#1e293b)
- Light Background: Mint tint (#f0fdfa)
- Text: Dark slate (#0f172a), medium gray (#475569)

Typography

- Headings use Audiowide (bold, display)
- Body text uses Inter (clean, modern sans-serif)

Animations

- Tech icons bounce in a wave with staggered timing
- Navigation and links have smooth hover effects
- Transitions feel clean and snappy

Layout

- Content sits in a centered container (75% width on desktop, 95% on mobile)
- Header runs horizontally with name on the left, navigation on the right
- Section titles get a colored border on the left
- Skills are organized in a grid
- Icons are centered and scale on different screens

Semantic Elements Used

Element      | Purpose                        | Why Not <div>?
-------------|-------------------------------|--------------------------------------------------
<header>     | Page header, title, nav        | Signals the intro content
<nav>        | Navigation menu                | Helps screen readers find links
<main>       | Main content                   | Marks what’s most important
<section>    | Groups related content         | Keeps the page organized by theme
<article>    | Each education entry           | Stands alone, can be reused
<footer>     | Page footer                    | Shows extra info and metadata
<form>       | Contact form                   | Semantically right for user input

Learning Outcomes

This project taught me quite a bit:

1. Why semantic HTML matters for both SEO and accessibility
2. How to break down a big web page using HTML5 semantic elements
3. Using modern CSS (gradients, animations, grids)
4. Designing simply, without overcomplicating things
5. Building responsive layouts from scratch, no frameworks needed
6. The real purpose behind alt text and ARIA labels
7. Making sticky headers with a horizontal nav
8. Form best practices for usability and accessibility
9. Using CSS variables to keep code tidy and maintainable
10. Getting animation timing right, especially when staggering wave effects

🔗 Key Technical Concepts

1. Why use semantic HTML?

Semantic HTML just makes things work better. Search engines can actually figure out your page, so your site shows up where it should. Screen readers can move around smoothly, which means real people with disabilities can use your site. The code’s easier to read, too—future you (or anyone else on your team) won’t get lost. Plus, browsers behave more predictably, so things look right everywhere.

2. What’s the difference between <div> and <section>?

A <div> is just a plain box. You use it when you need to group stuff for styling, but it doesn’t mean anything to the browser or a screen reader. On the other hand, a <section> tells everyone, “Hey, this is a real chunk of content.” If you use <section>, toss in a heading to explain what it’s about.

3. Why bother with CSS variables?

CSS custom properties (those :root variables) are a game changer. Change a color in one spot, and the whole site updates. Your design stays consistent. Want to try out a new color scheme? It takes seconds.

4. How do you handle responsive design?

Start with mobile in mind. Use media queries to adjust layouts as screens get bigger. Flexbox keeps the header neat—switches to a column on phones. The skills section uses CSS Grid, so it adapts automatically. Percentage widths make layouts feel fluid instead of boxed-in.

📝 JavaScript Usage

Honestly, JavaScript barely shows up here. It’s just there to stop the browser from saving your scroll spot, so every time you load the page, you start at the top. No heavy frameworks. No bloated libraries. Just the basics.

🤝 Contributing

This is just my personal learning project, but I’d love to hear your thoughts or ideas.

📄 License

I built this for Elevate Labs’ training program, mainly for learning and practice.

👤 Author

Naimish Dobariya

🙏 Acknowledgments

Thanks to Elevate Labs for the assignment and guidance, the web dev community for sharing their best tips, Google Fonts for the typefaces, and all the folks behind those handy SVG icons.