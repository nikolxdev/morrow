# Morrow

![Tests](https://github.com/nikolxdev/morrow/actions/workflows/ci.yml/badge.svg)

One-page site for a made-up cold-pressed juice brand from the Morava valley. The cans are 3D, made in code with Three.js (no models or photos).

**Live:** https://nikolxdev.github.io/morrow/

You can click through the flavors, open a can to see its details, add things to the bag and check the harvest calendar.

## Run it

```
npm install
npm start
```

Then open http://localhost:4173 (it needs a server because of ES modules).

## Tests

```
npx playwright install chromium
npm test
```

Playwright tests on desktop and mobile, they run on every push.

## License

© 2026 Nikola Vojvodić. All rights reserved. The code is public so it can be read and evaluated as part of my portfolio; it is not open source. See [LICENSE](LICENSE) for what is and isn't allowed.
