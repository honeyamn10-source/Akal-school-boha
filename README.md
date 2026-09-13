# Akal School Boha — School Website

A single-page school website presenting school information, facilities, admissions, faculty, contact forms, and student learning resources.

**Stage:** Website project. Hosting, form delivery, and published school information should be verified for each deployment.

## Included

- School overview, mission, facilities, and faculty sections.
- Admissions and online registration interfaces.
- Contact forms with an EmailJS browser integration.
- General knowledge, maths, and English learning content.

## Preview locally

From the repository directory, run:

```bash
python -m http.server 8000
```

Open http://localhost:8000. External services and assets require internet access. Previewing the page does not confirm email delivery.

## Repository

| Path | Purpose |
| --- | --- |
| `index.html` | Website markup, styling, content, and browser logic |
| Root image and PDF files | Supporting website assets |
| `.github/` | Repository automation |

## Customization

Update school text, admissions dates, asset references, and form configuration in `index.html`. Verify delivery using test data before relying on the contact or registration forms.

## Feedback

For layout or navigation issues, include the browser and reproduction steps. Keep student details and registration submissions out of public issues.
