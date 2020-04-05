---
layout: default
title: Calendar
nav_order: 4
---

# Calendar
{: .no_toc }


DRAFT Calendar
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

KakaoTalk Calendar makes you manage all your events in easy and efficient way.
You can create events and invite your friends on KakaoTalk, or view important days such as national holidays and friends' birthdays all at once.
With a few taps and clicks, you can chat and discuss upcoming events when it is needed.
No need to worry about missing important events since reminders will be sent about your upcoming events autometically.



View this site's [_config.yml](https://github.com/pmarsceill/just-the-docs/tree/master/_config.yml) file as an example.

## How can I find all events after creating in the KakaoTalk calendar?

```yaml
# Set a path/url to a logo that will be displayed instead of the title
logo: "/assets/images/just-the-docs.png"
```

## How do I invite my friends to an event in the calendar?

```yaml
# Enable or disable the site search
# Supports true (default) or false
search_enabled: true

# Enable support for hyphenated search words:
search_tokenizer_separator: /[\s/]+/

```

## How do I edit or delete an event in the calendar?

```yaml
# Aux links for the upper right navigation
aux_links:
  "Just the Docs on GitHub":
    - "//github.com/pmarsceill/just-the-docs"
```

## I am invited by unknown user. What should I do?

```yaml
# Heading anchor links appear on hover over h1-h6 tags in page content
# allowing users to deep link to a particular heading on a page.
#
# Supports true (default) or false/nil
heading_anchors: true
```

## Footer content

```yaml
# Footer content appears at the bottom of every page's main content
footer_content: "Copyright &copy; 2017-2019 Patrick Marsceill. Distributed by an <a href=\"https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt\">MIT license.</a>"
```

## Color scheme

```yaml
# Color scheme currently only supports "dark" or nil (default)
color_scheme: "dark"
```
<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script type="text/javascript" src="{{ "/assets/js/dark-mode-preview.js" | absolute_url }}"></script>

See [Customization]({{ site.baseurl }}{% link docs/customization.md %}) for more information.

## Google Analytics

```yaml
# Google Analytics Tracking (optional)
# e.g, UA-1234567-89
ga_tracking: UA-5555555-55
```
