# Remix Render template

[![CI/CD](https://github.com/pawelblaszczyk5/remix-render/actions/workflows/CI_CD.yml/badge.svg)](https://github.com/pawelblaszczyk5/remix-render/actions/workflows/CI_CD.yml) [![codecov](https://codecov.io/gh/pawelblaszczyk5/remix-render/branch/main/graph/badge.svg?token=Z27Y6J8D3Y)](https://codecov.io/gh/pawelblaszczyk5/remix-render)

Remix boilerplate for building modern web applications. As I plan to often use it, I decided to make this template.

## Remix + CT8

Remix is a full-stack web framework that lets you focus on the user interface and work back through web fundamentals to deliver a fast, slick, and resilient user experience. People are gonna love using your stuff. That's Remix description from their website.

Render is a modern PaaS solution that lets you host your apps and much more

## CT8 integration

- Add health check URL at `/healthz`
- Deploying app via webhook after CI completed via actions

## Other stuff

- TypeScript, I hope that doesn't need an explanation
- ESLint and Prettier for code style enforcement
- Testing pre-configured, with codecov integration
- Tailwind for styling with dark mode setup (check out `ThemeSetter` component), also PostCSS for auto-prefixing and minifying
- Storybook with essential addons for designing components in isolation
- Express used as node.js framework with strict caching configured
- Github Actions for CI/CD pipeline
