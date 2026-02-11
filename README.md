
# techconsult-website

##  Project Overview

This project is a multi-page corporate website built using HTML5.  
It demonstrates structured layout design, semantic HTML usage, accessible forms, and proper Git version control workflow.

The website includes informational pages, service descriptions, detailed forms, and accessibility-focused implementation.

---

##  Page Descriptions

###  Home Page (index.html)
- Company introduction
- Navigation menu
- Call-to-action sections

###  About Page (about.html)
- Company history and mission
- Team section (5 members with roles and bios)
- Company values
- Timeline of major milestones

###  Services Page (services.html)
- Services overview
- 4 detailed services including:
  - Description
  - Benefits
  - Technologies used
  - Deliverables
  - Pricing tier
- Service comparison table using:
  - `<table>`
  - `<thead>`
  - `<tbody>`
  - `<th>`
  - `<td>`
  - `scope`, `caption`, and `headers` attributes for accessibility

###  Quote Request Page (quote-request.html)
- Advanced project quote form
- Client information
- Project scope selection
- Feature checkboxes
- Budget range with visual feedback
- Timeline validation
- HTML5 validation implemented with `novalidate`

###  Careers Page (careers.html)
- Why work with us section
- 3 fictional job listings
- Job application form including:
  - Resume upload
  - Cover letter
  - Experience input
  - Salary expectations

###  Privacy Policy Page (privacy-policy.html)
- Table of contents with anchor links
- Proper heading hierarchy
- Clearly structured legal sections

---

## Form Functionality Documentation

All forms implement:

- Required field validation
- Proper input types (`email`, `url`, `date`, `number`, `range`)
- Min/max constraints where necessary
- File upload restrictions (`.pdf`, `.doc`, `.docx`)
- Accessible labels for all inputs
- Logical grouping using `<fieldset>` and `<legend>` where applicable

Validation includes:
- Required fields marked clearly
- Completion date must be after start date
- Budget range displays current value
- Use of `novalidate` attribute to demonstrate understanding of custom validation
=======

