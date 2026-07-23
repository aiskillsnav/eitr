# Elephant In The Room

A Microsoft AI Skills Navigator campaign microsite featuring five character-driven stories about professionals overcoming AI adoption challenges in the workplace.

Live at: https://aiskillsnav.github.io/eitr/

## About

*Elephant In The Room* is a short-form video series connected to the [Microsoft AI Skills Navigator](https://aiskillsnavigator.microsoft.com/). Each episode follows a real workplace persona — an IT Manager, Business Leader, Student/Athlete, IT Professional, and Sales Professional — as they move from AI avoidance to AI fluency.

The site features:
- Interactive persona selector with role-based AI learning playlists
- Five linked content pages (All Episodes, Who Is the Elephant, Meet the Characters, Learn More, Microskilling)
- Fully responsive design with mobile hamburger navigation
- WCAG 2.1 AA accessibility compliance
- Microsoft compliance footer (Privacy, Terms, Trademarks, Cookie Consent)

## Getting Started

No build step required. Serve locally with:

```bash
python3 -m http.server 3000
```

Then open http://127.0.0.1:3000/ in your browser.

## Compliance

This site meets the following Microsoft web compliance requirements:

- **Privacy**: WCP Cookie Consent banner, Privacy Choices, Consumer Health Privacy links
- **Analytics**: Microsoft Clarity (project ID: `ttqwpbrhaw`) — see Telemetry section below
- **Accessibility**: WCAG 2.1 AA — skip nav, focus rings, landmark regions, alt text, color contrast
- **Legal**: MIT license, Microsoft standard footer links

## Telemetry

This project collects usage data via **Microsoft Clarity** to help improve the experience.
Clarity records session replays, heatmaps, and interaction data sent to Microsoft's servers.

**To disable Clarity:** Remove or comment out the Clarity script block in each HTML file's `<head>`:

```html
<!-- Microsoft Clarity analytics -->
<script type="text/javascript">
  (function(c,l,a,r,i,t,y){ ... })(window,document,"clarity","script","ttqwpbrhaw");
</script>
```

Microsoft's privacy statement: https://privacy.microsoft.com/en-us/privacystatement

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply
Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party's policies.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

Copyright (c) Microsoft Corporation. Licensed under the [MIT License](LICENSE.txt).
