# Testing and Test Mode

## Open test mode

```text
index.html?test=1
```

Alternative:

```text
index.html?mode=test
```

The test panel can:

- load a fully completed fictional assessment;
- open the completed results page;
- run the built-in self-tests;
- download a sample PDF report in the active language.

## Open completed sample results

```text
index.html?test=1&sample=1
```

Expected deterministic sample result:

| Result | Value |
|---|---:|
| Overall score | 76/100 |
| Maturity | Managed / Gestionado |
| Risk | Green / Verde |
| Completion | 100% |
| Power Platform module | Enabled |
| Copilot Studio module | Enabled |

## Automatically request the sample PDF

```text
index.html?test=1&sample=1&autopdf=1
```

Browser download policies may block automatic downloads. The test panel always
provides a manual download button.

## Test API

Test mode exposes:

```javascript
window.__coeTestApi.loadSample();
window.__coeTestApi.downloadSamplePdf();
window.__coeTestApi.runSelfTests();
window.__coeTestApi.getState();
```

## Validated behavior

- Spanish Argentina and English USA localization.
- Six scored domains and 24 core questions.
- Domain weights total 100%.
- Conditional Power Platform and Copilot Studio modules.
- Deterministic sample scoring and risk calculation.
- Responsive layout without horizontal overflow.
- Keyboard and touch carousel navigation.
- Local sample PDF download.
- Public version remains `v1.0`.

The sample data is fictional and must not be interpreted as an organizational assessment.

## Centered hero validation

The centered initial hero was validated in Spanish Argentina and English USA,
at desktop width and at a 390 px mobile width.

The checks confirm:

- exactly one H1 on the initial screen;
- 900 px maximum container width;
- 2.6 rem vertical padding;
- local 78 × 78 px SVG;
- no filter, box shadow, decorative background, or animation;
- Aptos Display title typography;
- Aptos description with a 650 px maximum width;
- no horizontal overflow.

## Preview-safe CoE Toolkit icon

The hero embeds the exact vector paths from the canonical local
`assets/icons/favicon.svg` file. The SVG opening tag is normalized to a single
`width="78"` and `height="78"` pair, with the original `viewBox` preserved.

This allows the standalone HTML preview to display the hero icon without
requiring sibling asset folders. The GitHub Pages package still includes and
references the local favicon assets.
