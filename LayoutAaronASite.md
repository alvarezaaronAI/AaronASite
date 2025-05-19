──────────────────────────────────────────────────────────────
NAVIGATION BAR (sticky atop, full-width)
──────────────────────────────────────────────────────────────
• Logo: “Aaron Alvarez” (left)  
• Hamburger toggle (visible on small screens)  
• Links (hidden on small, inline md+):
    Home | About | Projects | Skills | Education | Testimonials | Blog | Contact  
• “Hire Me” button (always disabled, grayed out, right)  

──────────────────────────────────────────────────────────────
HERO SECTION (#hero)
──────────────────────────────────────────────────────────────
• Full-width background: “Brooklyn Bridge.jpg” with dark gradient overlay  
• Centered card (black/60):
    ├ Heading: “Turning Ideas into Interactive Digital Stories” (5xl/6xl, white)  
    ├ Subheading: “Elevating brands with clean code and creative design.” (lg/xl, gray-200)  
    └ Stats row (green pills, black text, flex wrap):
        • <i class="fas fa-code"></i> 5+ Projects  
        • <i class="fas fa-file-alt"></i> 3 Case Studies  
        • <i class="fas fa-clock"></i> 10k+ Hours  
        • <i class="fas fa-users"></i> 8+ Clients  
        • <i class="fas fa-globe"></i> 12+ Countries  

──────────────────────────────────────────────────────────────
ABOUT & TILES (#about)
──────────────────────────────────────────────────────────────
Layout: flex-col on mobile, flex-row on md+, gap-8, centered in 7xl container  
┌───────────────────┬───────────────────────────────────┬──────────────────────┐  
│ Left Pane (1/5)   │ Center “About Me” Card (3/5)      │ Right Pane (1/5)     │  
│ (hidden on sm)    │                                   │ (hidden on sm)       │  
│ • 3 Article Tiles │ • Portrait (circle, border & shadow)  
│   – Title (green) │ • “Hi, I’m Aaron” header (4xl)     │ • Spotify embed      │  
│   – Excerpt, “Read More →”  
│                   │ • Role badges (green pills)        │   – track “Go Hard 2.0” by Juice WRLD  
│                   │ • Bio paragraph (lg, center)      │   – border & subtle bg  
│                   │ • Fun fact line                   │  
│                   │ • Resume & Contact buttons        │  
│                   │ • “Vue/React conversion…” note    │  
└───────────────────┴───────────────────────────────────┴──────────────────────┘  

──────────────────────────────────────────────────────────────
PROJECTS SECTION (#projects-combined)
──────────────────────────────────────────────────────────────
Container: 7xl, bg-[#222326], rounded, px-4 py-12  
• Title: “Projects” (3xl, green, bold, center-md)  
• Two-column flex (col on sm, row md+, gap-12):
  
  Left (Featured Project):
    ├ Background card (black/90, blur, rounded):  
    │  • Image (wide, rounded, shadow)  
    │  • Title: “Project Title” (2xl, green)  
    │  • Description (gray-200)  
    │  • Meta (Role & Date, gray-200/green)  
    │  • Bulleted features (gray-300)  
    │  • Tech badges (green pills)  
    │  • Links: Live Demo | GitHub Repo | Case Study | Blog Post  
  
  Right (More Projects Grid):
    ├ Subtitle: “More Projects” (xl, green)  
    └ Grid: 1col sm→2, md→2, lg→3, gap-6:
       – 6 Mini cards (black/90, rounded, shadow):
          • Image (object-cover)  
          • Title (green)  
          • Text (gray-400)  

──────────────────────────────────────────────────────────────
SKILLS & TOOLS (#skills)
──────────────────────────────────────────────────────────────
Section bg[#222326], rounded, p-4, 7xl center  
Title: “Skills & Tools” (3xl, green)  
Grid: 1col sm→2, gap-4  

1. Languages & Frameworks (card):
    • Heading icon + text (fa-code, green, xl)  
    • Pills (green/20 bg, green text):
      – HTML (fa-html5), CSS (fa-css3-alt), JavaScript (fa-js), Vue.js (fa-vuejs), React (fa-react), Node.js (fa-node-js)  

2. Dev Tools (card):
    • Heading icon + text (fa-tools)  
    • Pills: Git (fa-git-alt), GitHub (fa-github), VS Code (fa-microsoft), Postman (fa-postman), Vite (fa-bolt), NPM (fa-npm), Jira (fa-jira)  

3. Design Tools (card):
    • Heading icon + text (fa-paint-brush)  
    • Pills: Figma, Adobe XD, Penpot (all green/20 bg with simple SVG icons)  

4. Soft Skills (card):
    • Heading icon + text (fa-smile)  
    • Pills: Communication (fa-comments), Collaboration (fa-handshake), Creative Problem Solving (fa-lightbulb)  

──────────────────────────────────────────────────────────────
EDUCATION & EXPERIENCE (#edu-exp)
──────────────────────────────────────────────────────────────
Title: “Education & Experience” (3xl, green)  

**Education**  
Grid flex-col→row, gap-6, mb-12:
• B.S. Computer Science (UCLA, May 2020) – card, fa-graduation-cap icon  
• M.S. in AI (planned, UT Austin, Spring 2026) – grayed card, fa-graduation-cap  

**Experience**  
Grid 1→3 cols, gap-6:

Row 1:
1. Manager II… (Jan 2023–Apr 2025) – fa-briefcase icon  
2. Manager I… (Apr 2021–Dec 2022) – fa-briefcase  
3. FC Associate I… (Dec 2020–Apr 2021) – fa-truck  

Row 2:
4. Delivery Associate I… (Jul 2018–Dec 2020) – fa-truck  
5. (empty placeholder)  
6. (empty placeholder)  

──────────────────────────────────────────────────────────────
TESTIMONIALS (#testimonials)
──────────────────────────────────────────────────────────────
Title: “What Clients & Peers Say” (3xl, green, center)  
Grid 1→2 cols, gap-8:

• Card 1 (Sarah J.) – avatar, name, role, quote, fa-quote-right icon  
• Card 2 (Mark L.) – similarly  
• Card 3 (Alex G., spans 2 cols)  

──────────────────────────────────────────────────────────────
BLOG / ARTICLES (#blog)
──────────────────────────────────────────────────────────────
Title: “Latest Articles” (3xl, green, center)  
Grid 1→2→3 cols, gap-8:

Cards: (3 shown)
– Image (h-40, rounded top)  
– Date (sm, gray-500)  
– Title (green, semibold)  
– Excerpt (gray-300)  
– “Read More →” link (green, underline on hover)  

──────────────────────────────────────────────────────────────
CONTACT SECTION (#contact)
──────────────────────────────────────────────────────────────
• Grayed out (50% opacity, pointer-events none)  
• Title: “Get in Touch” (3xl, green, center)  
• Subtitle text (gray-300, center)  
• Form (max-w-xl center, grid gap-6):
    – Name, Email inputs, Message textarea  
    – Send button (green bg)  

──────────────────────────────────────────────────────────────
FOOTER (relative)
──────────────────────────────────────────────────────────────
Container: bg-[#191414], text-gray-400, py-8, max-w-7xl center, flex col→row md, items-center, px-4  

• Left: “Back to Top” link (green)  
• Center: Social links: LinkedIn | GitHub | Email (hover white)  
• Right: Meta text (sm):
    – © 2025 Aaron Alvarez — Built with HTML + CSS  
    – “⚙️ Converting soon to Vue/React as part of my dev practice 💡”  
    – Mobile-only credits & theme notes (green xs, visible md:hidden)  
• Corner spans (hidden md:block):
    – bottom-left: Credits: Font Awesome | Tailwind CSS | Spotify Embed | GitHub  
    – bottom-right: Color theme inspired by Spotify — music to my code!  

──────────────────────────────────────────────────────────────