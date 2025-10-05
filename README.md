# InsightFlow AI — AI-powered Post-Purchase Review Chatbot (Frontend Prototype)

This repository contains a complete, production-ready static website that showcases an AI-powered chatbot designed to collect post-purchase reviews from ecommerce customers. The site is built with Tailwind CSS (via CDN) and uses semantic HTML5 structure for accessibility.

What’s included
- index.html: Home page with hero, features, and overview of capabilities
- about.html: Company, approach, and team
- contact.html: Demo request form
- README.md: This documentation

Design & UX notes
- 100% Tailwind CSS classes (no external CSS files)
- Responsive, mobile-first layout
- Accessible markup (semantic tags, descriptive alt text)
- One primary H1 per page with a clear information architecture

How to run locally
1. Open any of the HTML files in a browser (index.html for the homepage).
2. No build step required — this is a static frontend prototype using Tailwind CDN.

How to customize
- Replace placeholder images with real assets by updating the https://images.unsplash.com/photo-1753596726281-8fd876febab8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHwzfHwuLi58ZW58MHwwfHx8MTc1OTU1NzMwNHww&ixlib=rb-4.1.0&q=80&w=1080 placeholders or swapping the image URLs in the hero section.
- Update page content in each HTML file to reflect your product’s features, pricing, and contact details.
- If you wish to add more pages, follow the same structure and update navigation links accordingly.

Accessibility tips
- All images include descriptive alt attributes (e.g., alt='AI chatbot interface over ecommerce dashboard').
- Logical heading order (H1, H2, H3).
- Ensure sufficient color contrast; use Tailwind utility classes to maintain readability.

Deployment suggestions
- Host on GitHub Pages, Netlify, Vercel, or any static hosting service.
- Ensure TLS (https) for security, especially if forms are enabled.
- Consider adding a lightweight analytics snippet to understand user interactions and form submissions.

Notes
- This is a frontend prototype. For a live SaaS product, you would integrate with a backend service to manage conversations, store responses, and provide analytics dashboards.