# Loqelo pre-launch page (contest entry)

**Live:** https://rafa0071.github.io/loqelo-prelaunch/

Single-file, dependency-free landing page for the Loqelo pre-launch.

## Features

- Hero with the tagline "Everything your place needs", app preview and launch badge
- Promo video section (ready for the supplied video file)
- How it works in four steps, plus service areas
- Two waitlists: customers (email, country of residence, individual/business) and service providers (email, country of service, individual/business)
- Explicit consent checkbox, honeypot spam protection, confirmation message
- Automatic language detection (EN, ES, DE, PL, CS) with a manual switcher, country names localised automatically
- Countdown to the February 2027 launch
- Consent banner: analytics only run after consent; email addresses are never sent to analytics
- Analytics events ready for GA4: `form_start`, `form_tab`, `waitlist_signup` (with form type and country)
- Responsive, fast (no frameworks), basic SEO and Open Graph tags

## Going live (free tools)

- **Contacts:** connect the form to Brevo or MailerLite (free plans) with one list per group, which gives CSV export and launch emails
- **Analytics:** add the GA4 tag; the events above are already wired
- **Hosting:** any static hosting or the provided loqelo.com hosting; content lives in the `I18N` object for easy editing
- No paid licences required
