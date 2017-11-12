# Inclusive Design Checklist

Aims to be the **biggest** checklist of inclusive design considerations ever. Includes items for accessibility, performance, device support, interoperability, and language. Pull requests welcome!

- [ ] [Minify CSS and JS, and remove unused/redundant code](https://developers.google.com/speed/docs/insights/MinifyResources)
- [ ] [Use screen reader and keyboard accessible HTML](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
- [ ] [Compress raster images](https://www.html5rocks.com/en/tutorials/speed/img-compression/)
- [ ] [Optimize SVG path data](https://web-design-weekly.com/2014/10/22/optimizing-svg-web/)
- [ ] [Make sure heading levels describe a logical section/subsection structure](https://webaim.org/techniques/semanticstructure/)
- [ ] Only include heading elements where they introduce sections of content
- [ ] [Remove potentially insensitive or uninclusive language (use 'singular they')](http://alexjs.com/)
- [ ] Give video content captions and transcripts
- [ ] [Make sure main body (paragraph) text is no smaller than the default (user agent) size](https://www.smashingmagazine.com/2011/10/16-pixels-body-copy-anything-less-costly-mistake/)
- [ ] Support 'pinch zoom' (remove `user-scalable=no` if present)
- [ ] Use relative units (`em`, `rem`, and `ch`), especially for font metrics
- [ ] Make sure styles and scripts are not render blocking
- [ ] Install a service worker and cache all applicable assets
- [ ] Use content-based, not device-specific, media queries
- [ ] Provide alternatives and/or descriptions for complex visualizations
- [ ] Include only clear, meaningful animations
- [ ] Make sure controls do not elicit unexpected or jarring behavior
- [ ] Do not include third parties that compromise user privacy
- [ ] Do not recreate supported and expected browser behaviors with bespoke scripts
- [ ] Support Windows high contrast mode (use images, not background images, if salient)
- [ ] Provide alternative text for salient images
- [ ] Apply `alt=""` or `aria-hidden="true"` to decorative images
- [ ] Make sure text and background colors contrast sufficiently
- [ ] Provide `<title>`s that name the site and the specific page
- [ ] Provide large touch 'targets' for interactive elements
- [ ] Use data tables (`<table>`) for data, not layout
- [ ] Make scrollable elements focusable for keyboard users
- [ ] Do not rely on color for differentation of visual elements
- [ ] Use the same design patterns to solve the same problems
- [ ] Ensure keyboard focus order matches visual layout
- [ ] Lazy load large image assets
- [ ] Translate / spell out acronyms the first time you use them
- [ ] Do not hijack standard scrolling behavior
- [ ] Move focus between dialogs and the controls that invoked them
- [ ] Give all form elements permanently visible labels
- [ ] Give grouped form elements group labels
- [ ] Provide status and error messages as WAI-ARIA live regions
- [ ] Provide clear, unambiguous focus styles
- [ ] Employ well-balanced, highly legible fonts (not too complex or elaborate)
- [ ] Do not use very thin font faces
- [ ] Ensure states (pressed, expanded, invalid, etc) are communicated to assistive software
- [ ] When component behaviour changes across breakpoints, ensure its presentation and state are described differently to assistive software
- [ ] Provide a default language and use `lang="[ISO code]"` for subsections in different languages
- [ ] Make controls look like controls; give them strong perceived affordance
- [ ] Underline links — at least in body copy
- [ ] Make sure all content belongs to a landmark element (`<header>`, `<footer>`, `<nav>`, `<main>`, etc)
- [ ] In visual designs, avoid pure white or pure black
- [ ] Mark invalid fields clearly and provide associated error messages
- [ ] Ensure content is not obscured through zooming (no fixed widths)
- [ ] Provide a `manifest.json` file for identifiable homescreen entries
- [ ] Indicate swipe gesture support clearly, and provide simple tap-based alternatives
- [ ] Make sure data tables wider than their container can be scrolled horizontally
- [ ] Avoid time constraints where possible; provide a clear warning and option to extend where not possible 
- [ ] Label and describe the same things with the same terminology
- [ ] Ensure disabled controls are not focusable
- [ ] Do not instate 'infinite scroll' by default; provide buttons to load more items
- [ ] [Avoid justified body text](https://www.w3.org/TR/WCAG20-TECHS/F88.html)
- [ ] [Provide enough spacing between lines of text (`line-height`)](https://www.w3.org/TR/WCAG20-TECHS/C21.html)
- [ ] [Ensure content is accessible when printed out our saved as PDF](https://uxdesign.cc/i-totally-forgot-about-print-style-sheets-f1e6604cfd6). 
- [ ] [Provide a skip link if necessary](https://webaim.org/techniques/skipnav/) 
- [ ] [Avoid all-caps text](https://github.com/humanmade/hm-pattern-library/issues/75)
- [ ] [Ensure that content is written as clearly and simply as possible](https://www.w3.org/TR/UNDERSTANDING-WCAG20/meaning-supplements.html)
- [ ] Provide descriptive captions for figures
- [ ] Warn users of links that have unusual behaviors, like linking off-site, or loading a new tab
- [ ] [Make content easier to find and improve search results with structured data](https://developers.google.com/search/docs/guides/prototype)
- [ ] Use textual labels to make voice activation cues obvious
- [ ] Subheadings / straplines are not separate headings and should not use separate heading elements