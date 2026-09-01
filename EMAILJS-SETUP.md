# Contact Form EmailJS Setup

The contact form uses EmailJS and does not open Gmail.

Configured in `src/main.jsx`:
- Service ID: `service_6mwalxe`
- Template ID: `template_uij7a3k`
- Public Key: configured in frontend code

## Required EmailJS template variables
Use these variables in the EmailJS template:

- `{{from_name}}`
- `{{from_email}}`
- `{{message}}`

The visitor remains on the portfolio after submitting the form.

## Run
```bash
npm install
npm run dev
```
