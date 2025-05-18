# Security Policy

## Supported Versions

This is a personal portfolio site and does not contain any backend services or user authentication mechanisms. However, we are committed to keeping the source code and hosted site as secure as possible.

| Version     | Supported          |
|-------------|--------------------|
| Latest (main branch) | ✅ |
| Older branches        | ❌ |

## Reporting a Vulnerability

If you discover a vulnerability or a security issue related to this website or its codebase, please report it responsibly.

### Contact

Please email [your_email@example.com] with:

- A clear description of the vulnerability
- Steps to reproduce it (if applicable)
- Suggested remediation (if you have any)

We aim to respond within **48 hours**.

## Security Best Practices

This project adheres to general frontend security guidelines:

- **No user input** is processed.
- **HTTPS enforced** via hosting platform (e.g. Vercel).
- All dependencies are audited regularly (`npm audit`).
- Codebase uses modern frameworks (Next.js) which follow strict security conventions.

## Technologies Used

- Next.js (React-based framework)
- Tailwind CSS
- GitHub for version control and CI/CD
- Vercel for secure deployment

## Additional Measures

- [x] Strict Content Security Policy (CSP) headers via `next.config.js`
- [x] XSS and injection protections (no `dangerouslySetInnerHTML`)
- [x] Automatic dependency updates enabled via Dependabot (on GitHub)
- [x] Code linting with ESLint to prevent common security issues

---

**Note**: This site is static and does not collect any user data. If future updates introduce forms or APIs, this policy will be updated accordingly.
