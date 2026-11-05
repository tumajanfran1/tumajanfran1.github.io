# AGENTS.md — Rules for AI agents working on this site

This repository is Fran Tumajan's personal website (`tumajanfran1.github.io`), served by GitHub Pages.
Every file committed here is **public**. Any agent working in this folder must follow these rules.

## 1. Never publish

- **Phone numbers.** The CV includes a personal mobile number. It must never appear on the site, in the HTML source, in comments, or in metadata.
- **Home or mailing addresses.** City-level locations (e.g., "New York, NY", "Dubai, UAE") are fine.
- **Government IDs, passport or visa details, date of birth, or immigration status.** Listing nationality as written in the CV is fine.
- **Compensation, salary expectations, offer details, or performance reviews.** Exception: ratings already in the CV, such as "top 5% of cohort".
- **Confidential client information.** Do not name clients, countries, or deals that the CV leaves anonymous (e.g., "a country in the MENAP region"). Do not add figures, names, or details that are not in the CV.
- **Grades, transcripts, or documents** beyond what the CV already states.
- **Raw source files** such as the CV PDF. Do not link to it or commit it unless Fran explicitly asks.
- **Secrets**: API keys, tokens, passwords, or `.env` files.
- **Third-party tracking**: analytics, ad pixels, or tracking scripts.

## 2. Ask Fran first before

- Pushing, committing, or deploying anything to GitHub (`git push`, creating repos, enabling Pages).
- Publishing any personal contact detail beyond the Columbia email, LinkedIn, and GitHub.
- Adding, removing, or rewording CV content: titles, dates, numbers, accomplishments. The site should mirror the CV exactly. Never invent or embellish.
- Adding new sections such as a blog, projects, or testimonials, or using new photos.
- Deleting or overwriting existing files.
- Adding external dependencies, frameworks, build tools, or CDNs.
- Anything that sends content to an outside service.

## 3. Style

- **Tone:** professional, concise, and factual. Write in the third person or use neutral headings, with no hype words.
- **Content order:** follow the CV: Education → Experience → Additional Information.
- **Colors (Columbia blue palette):**
  - Columbia Blue `#B9D9EB` (primary accent)
  - Columbia Navy `#002B5C` (text and headers)
  - Mid blue `#1D4F91` (links and hover states)
  - Light background `#F4F8FB`, white cards `#FFFFFF`
- **Typography:** one clean sans-serif system font stack, with clear hierarchy and generous whitespace.
- **Navigation:** a sticky top nav with anchor links to every section, plus quick-jump tiles near the top. Every section must be reachable in one click.
- **Code:** plain HTML and CSS in one `index.html` with no build step. JavaScript is optional and kept minimal. The site must work without JS.
- **Accessibility:** semantic HTML (`header`, `nav`, `main`, `section`), alt text on images, sufficient color contrast, and visible focus states.
- **Responsive:** the site must read well on phones (no horizontal scroll) and desktops.
