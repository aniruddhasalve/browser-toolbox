# Browser Toolbox

A private, offline-friendly collection of developer and tester utilities built with plain HTML, CSS, and JavaScript.

## Tools

- JSON formatter and validator
- Text diff
- Base64 encoder and decoder
- UUID generator
- Unix timestamp converter
- WCAG contrast checker
- Regular expression tester

## Why plain web standards

Browser Toolbox has no framework, build step, account system, analytics, or server. It uses semantic HTML, native dialog and form behavior, CSS custom properties, the Web Crypto API, a service worker, and progressive enhancement. The goal is to make useful tools that are easy to inspect, host, fork, and reuse.

## Run locally

Any static server works:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000>. A service worker requires HTTP or HTTPS, so opening the file directly is not the same as running the app from a local server.

## Privacy

Tool inputs are processed in the browser. This project does not upload tool content, require an account, or include analytics. Do not treat the JWT or Base64 tools as security validators: decoding a token is not verification, and encoding data is not encryption.

## Accessibility

The interface uses semantic headings, labels, native controls, visible focus behavior, keyboard-accessible dialogs, status announcements, responsive layouts, and reduced dependence on color alone. Test with the browser and assistive technology combinations relevant to your users.

## License

MIT. See [LICENSE](LICENSE).
