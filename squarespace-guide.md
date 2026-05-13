# Squarespace Setup Guide — MicroCore Electronics

---

## STEP 1: Choose a Template

Log in to squarespace.com → go to your site → Pages → Start Editing

**Recommended templates (search these by name):**
- **Hatch** — dark, technical, modern — BEST for electronics/engineering
- **Forma** — clean, minimal, professional
- **Calder** — bold, strong visual hierarchy

Go to: Design → Template → Browse Templates → search "Hatch"

---

## STEP 2: Global Settings

### Colors (Design → Site Styles → Colors)
- Background: #0d1b2a (dark navy)  OR  #ffffff (white — cleaner for services)
- Accent / Buttons: #00b4d8 (electric blue)
- Text: #0d1b2a (dark navy on white bg) or #ffffff (white on dark bg)
- Secondary text: #7a8fa8

**Recommendation: Use WHITE background** — easier to read service descriptions, more professional for B2B.

### Fonts (Design → Site Styles → Fonts)
- Headings: **Montserrat Bold** or **Inter Bold**
- Body: **Inter** or **Source Sans Pro**
- Both are free Google Fonts available in Squarespace

### Logo
Upload the file: logo.svg
Go to: Design → Logo & Title → Upload Image → select logo.svg

---

## STEP 3: Create Pages

Go to Pages → + Add Page for each:

| Page Name | URL slug | Type |
|-----------|----------|------|
| Home | / | Regular page |
| Services | /services | Regular page |
| Portfolio | /portfolio | Gallery page |
| About | /about | Regular page |
| Contact | /contact | Regular page |

---

## STEP 4: Build Each Page

### Home Page
Add these blocks (+ button → Add Block):

1. **Banner / Cover** block
   - Headline: "End-to-End Electronics Engineering"
   - Subtext: "From initial concept to final product — PCB design, IoT, RF, and full manufacturing support."
   - Button: "Get a Free Quote" → link to /contact

2. **3-Column layout** (use "Summary" or "Cards" block)
   - Design | Prototype & Test | Manufacture
   - Use icons from Squarespace's built-in icon library

3. **Text block** — "Why MicroCore" section
   - Copy text from website-content.md

4. **Banner block** — contact teaser at bottom

---

### Services Page
1. **Heading block** — "From Idea to Product — I Handle It All"
2. **Accordion block** (perfect for services list!) — one accordion item per service
   - Title = Service name
   - Body = service description from website-content.md
3. **Button block** — "Get in Touch"

---

### Contact Page
1. **Heading block** — "Let's Build Something Together"
2. **Form block** — add these fields:
   - Name (Text, Required)
   - Email (Email, Required)
   - Phone (Phone, Optional)
   - Company/Project (Text, Optional)
   - Message (Textarea, Required)
   - Submit button text: "Send Message"
3. **Text block** — email, phone, response time

**Form settings → Storage:**
- Check "Send to Email" → enter your email address
- This sends every form submission directly to your inbox

---

### Portfolio Page
Use a **Gallery** page type.
- Upload photos of your PCBs/projects
- Add title and description to each

---

### About Page
1. **Image + Text block** — your photo on left, bio on right
2. **Text block** — "What I work with" list
3. **Button block** — "Work With Me"

---

## STEP 5: Navigation

Pages → Navigation → drag pages into order:
Home / Services / Portfolio / About / Contact

---

## STEP 6: SEO Settings

For each page: Pages → gear icon → SEO

| Page | SEO Title | SEO Description |
|------|-----------|-----------------|
| Home | MicroCore Electronics — End-to-End PCB & Hardware Design | Electronics engineering services: PCB design, IoT, RF, prototyping, and manufacturing. 5+ years experience. |
| Services | Electronics Engineering Services — MicroCore | PCB design, schematic capture, prototype development, testing, and full product development services. |
| About | About — MicroCore Electronics | 5+ years hardware engineer specializing in IoT, RF, and full product development. |
| Contact | Contact MicroCore Electronics | Get a free quote for your electronics engineering project. |

---

## STEP 7: Extensions to Install

Go to: squarespace.com/extensions

### Must-have (free or low cost):
| Extension | What it does | Cost |
|-----------|--------------|------|
| **Acuity Scheduling** | Let clients book a consultation call directly | Free plan available |
| **Tidio Live Chat** | Chat widget on your site — clients can message you instantly | Free plan available |
| **Google Analytics** | Track visitors, where they come from, which pages they visit | Free |

### How to add Google Analytics:
Settings → Advanced → External API Keys → paste your Google Analytics ID (G-XXXXXXXX)

### How to add Acuity:
Extensions Marketplace → Acuity Scheduling → Connect → add a "Schedule a Call" button to your contact page

---

## STEP 8: Domain

Settings → Domains → your domain microcoreelectronics.com should already be connected.
If not: Settings → Domains → Use a Domain I Own → follow DNS instructions.

---

## STEP 9: Go Live

Settings → Site Availability → change from "Password Protected" / "Coming Soon" to **Public**

---

## Quick Checklist Before Going Live

- [ ] Logo uploaded
- [ ] All 5 pages have content
- [ ] Contact form tested (submit a test message, check your email)
- [ ] Mobile view looks good (Preview → Mobile)
- [ ] SEO titles filled in for all pages
- [ ] Your real email and phone added to contact page
- [ ] Acuity Scheduling connected (optional but recommended)
- [ ] Site set to Public
