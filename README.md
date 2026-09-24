# Fable marketing site

The public product and pricing site for [Fable](https://fable-nu.vercel.app), an AI communication
coach for rehearsing difficult professional conversations.

**Live site:** [fable-landingpage.vercel.app](https://fable-landingpage.vercel.app)

## What this repository contains

- Responsive product positioning and scenario examples
- Interactive conversation preview
- Customer evidence and product pricing
- Links into Fable's free, monthly, and annual product flows
- Privacy and terms pages
- A Vercel serverless email-capture endpoint

The product application, model orchestration, authentication, and subscription logic live in the
separate [`Fable`](https://github.com/mubien15/Fable) repository.

## Run locally

This is a static site with one Vercel function. Any local web server can serve the page:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Reuse

The Fable name, copy, visual identity, testimonials, and commercial material are not licensed for
reuse. Contact [hello@mubienahsan.com](mailto:hello@mubienahsan.com) with questions.
