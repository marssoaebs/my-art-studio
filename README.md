# my-art-studio

Website for **The Little Picasso Art Studio** — kids' painting classes in Colindale, London.

**Live:** Deployed on Vercel

## Stack

- Single-page HTML + inline CSS + vanilla JS
- No build step, no dependencies, no framework
- Deployed on Vercel (static site config)
- Google Search Console verified + sitemap for SEO

## Structure

```
.
├── index.html                  # Single-page site (all sections)
├── vercel.json                 # Vercel static deployment config
├── sitemap.xml                 # SEO sitemap
├── google7b148d3fe3fb9ed7.html # Google Search Console verification
├── .gitignore
├── logo.svg                    # Studio logo
├── profile_pic.JPG             # Instructor photo
├── ClassPhoto1-9.JPG           # Class gallery (9 photos)
└── Image1-8.JPG                # Portfolio gallery (8 images)
```

## Sections

| Section | Content |
|---------|---------|
| Hero | Studio name, tagline, CTA |
| Class Photos | Gallery of kids in action |
| About | Instructor bio — software engineer + 6yr fine arts training + govt certification |
| Portfolio | Student artwork gallery |
| Programs | 3 age groups: Tiny Tots (4-6), Young Painters (6-8), Junior Artists (8-10) |
| Schedule | Sat 10am-2pm, Sun 10:30am-2:30pm |
| Events | Upcoming sessions, holiday specials, 1-on-1 availability |
| Testimonials | Parent reviews |
| Contact | WhatsApp link + contact form |

## Programs

| Program | Ages | Focus |
|---------|------|-------|
| Tiny Tots Art | 4-6 | Colors, shapes, basic brush techniques |
| Young Painters | 6-8 | Watercolor & acrylic fundamentals, color mixing |
| Junior Artists | 8-10 | Advanced techniques, perspective, personal style |

**Mediums:** Watercolor, acrylic, sketching, nature art, mixed media

## Local Development

```bash
git clone https://github.com/nageshbo/my-art-studio.git
cd my-art-studio

# Serve locally
python3 -m http.server 8000
# or
npx serve .

open http://localhost:8000
```

## Deployment

Push to `main`. Vercel auto-deploys via GitHub integration. Config in `vercel.json` routes all non-asset requests to `index.html`.

## Location

London
