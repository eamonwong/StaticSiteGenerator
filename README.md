# StaticSiteGenerator
A Python-powered tool that converts Markdown files into professional HTML pages with live portfolio embedding. Perfect for developers who want a lightweight way to showcase their work without complex frameworks.

# Features
- Markdown to HTML: Instantly transform your Markdown content (including code blocks) into clean HTML
- Live Portfolio Embedding: Seamlessly integrate your GitHub Pages portfolio via iframe (auto-updates)
- Customizable Templates: Change layouts/styles with Jinja2 templating
- JSON Configuration: Manage site metadata (title, author, etc.) without touching code

# Technologies Used
- Python: Core generator logic
- Markdown2: Markdown parsing with syntax highlighting
- Jinja2: Template engine for consistent layouts
- GitHub Pages: Hosting for live portfolio updates

# File Structure
```bash
.
├── script.py          # Main generator script  
├── layout.html        # Jinja2 template (with iframe)  
├── article.md         # Your Markdown content  
├── config.json        # Site configuration  
└── index.html         # Generated output (auto-created)
```

# JSON Configuration
Edit config.json to customize your site:
```bash
json
{
  "title": "My Portfolio",
  "description": "Developer showcase",
  "author": "Your Name",
  "code_link": "https://github.com/your-repo"
}
```

# Why I Built This
I wanted a minimalist way to:
- Showcase my portfolio with always-fresh content
- Practice Python file manipulation and templating
- Create something useful in <100 lines of code

https://github.com/user-attachments/assets/6235bfb7-212d-4560-bb22-a289b7f149bb

# Why You’ll Love It
- **Zero rebuilds needed**: Portfolio updates appear automatically (new portfolio below)
  *(Tested live: Changes to my GitHub Pages portfolio propagated instantly!)* 
- Write in Markdown: Focus on content, not HTML tags
- Deploy anywhere: Works with GitHub Pages, Netlify, etc.


https://github.com/user-attachments/assets/153c578b-27f7-45b5-ba08-6098bc3cf091




