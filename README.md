## Accessibility Consideration of accordion-button/Toggle states
* The title of each accordion header assigned button role either with aria or native HTML tag.
* Header my assign a heading level either with aria-level or native HTML tag.
* When a content revealed, focus stay on the content that interacts with revealed content prevent focus getting lost.
* Accordion panel is set to display: none; or similar.
* States of interactive content update accordingly.

### Terminologies:
* aria-expanded=” true/false” toggle accordingly to exposed states to screen reader.
* aria-describedby=”id” provides name of region of region element.
* role=”region” To create a landmark region of accordion panel
* aria-controls=”id” Establish parent child relationship with accordion header and panel.
