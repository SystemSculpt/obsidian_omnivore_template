# Obsidian Omnivore Template

This README provides guidance on setting up and using the Obsidian Omnivore template for integrating Omnivore content into Obsidian.

## Overview

Omnivore is a powerful tool for managing your digital reading and highlighting across various platforms. This README will help you integrate Omnivore with Obsidian, enhancing your note-taking and content management workflow.

## Useful Links
[Omnivore Homepage](https://omnivore.app/home)
[Create your Omnivore API key here](https://omnivore.app/settings/api)
[Connect with your Obsidian / Readwise](https://omnivore.app/settings/integrations)
[Don't have a Readwise? Click here for 60 days free trial](https://readwise.io/systemsculpt)

## The Template
To integrate Omnivore with Obsidian, you need to set up a specific template in the Omnivore settings within Obsidian. Here's the template that you should put in the Omnivore settings (within Obsidian settings) under `Article Template`:
```
# {{{title}}}

## Links
[Read on Omnivore]({{{omnivoreUrl}}})
[Read Original]({{{originalUrl}}})

{{#highlights.length}}
## Highlights

{{#highlights}}
> {{{text}}} [⤴️]({{{highlightUrl}}}) {{#labels}} #{{name}} {{/labels}} ^{{{highlightID}}}
{{#note}}

{{{note}}}
{{/note}}

{{/highlights}}
{{/highlights.length}}

## Content
{{{ content }}}
```

## Support

- Your support helps me, Mike, dedicate more time to creating and refining.

<p>
  <a href="https://www.patreon.com/SystemSculpt">
    <img
      align="left"
      src="https://indigenousx.com.au/wp-content/uploads/2017/03/patreon-medium-button.png"
      height="50"
      width="210"
      alt="Support on Patreon"
  /></a>
  <a href="https://www.buymeacoffee.com/SystemSculpt">
    <img
      align="left"
      src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png"
      height="50"
      width="210"
      alt="Buy Me A Coffee"
  /></a>
</p>
<br /><br />