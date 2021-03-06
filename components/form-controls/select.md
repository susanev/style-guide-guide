---
layout: component-detail
group: components
subgroup: form-controls
permalink: /components/form-controls/select.html

title: Select menu
description: Select menu description

variations:
- title: Text field
  description: Text field description
  styleModifier: c-text-field
  includeClassification: molecules
  includeCategory: 02-blocks
  includeName: card

usage:
- title: When to use
  description: Usage description.
- title: When to consider an alternative
  description: Alternative usage.

classes:
- className: c-hero
  required : yes
  description: Apply to the hero block's containing HTML element. This class sets up the background-image handling and text color for the unit. The `c-hero` element should have just one immediate child, the `c-hero__body` element. Note, too, that the unit's hero image should be applied as a background image to this `c-hero` element.
- className: c-hero--bare
  modifier : yes
  description: Add to the `c-hero` element to remove the default gradient overlay from the hero image.
- className: c-hero--tinted
  modifier : yes
  description: Add to the `c-hero` element to replace the default gradient overlay with a solid, uniform tint.
- className: c-hero__body
  required: yes
  description: Apply to the container for the card body, Which typically includes a title and description (see below) but can include any arbitrary markup including buttons for a call to action. The class manages the card's background gradient.
- className: c-hero__title
  recommended: yes
  description: Apply to the card's heading inside the card body. The recommended element for this class is `<h1>`.
- className: c-hero__desc
  recommended: yes
  description: Apply to the card's description text inside the card body. The recommended element for this class is `<p>`.

fine-print:
- version: 0.3
  update: April 27, 2017
  owner: Jane Doe
---

### Select menu
```html
<label for="workflow-state">Workflow state</label>
<select id="workflow-state" name="select">
<option value="1">Created</option>
<option value="2">Reviewed</option>
<option value="3">Approved</option>
<option value="4">Rejected</option>
<option value="5">Annotated</option>
<option value="6">Retired</option>
</select>
```
