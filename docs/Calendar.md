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

- What is the KakaoTalk calendar?
- Manage all your important events with a kakaotalk account: easy to edit, no need to separate account, reminders
- How do I invite my friends to an event in the calendar?
- Create an event and select “Invites” -> select a friend or a chatroom
- Select Calendar from your chatroom + menu -> invite all participants in the chatroom to the event
- Choose a chatroom -> all participants will be invited at once
- Select Calendar from the + menu -> create a new event -> participants in the chatroom will be automatically invited.
- How do I edit or delete an event in the calendar?
- Select an event you want to edit -> tap the three-dots icon on the top-right corner -> select “Edit”
- Select an event you want to delete -> tap the three-dots icon on the top-right corner -> select “Delete”
- If the event is edited or deleted, the responses of all invited members will  be reset and they will get notifications for the cancellation of the event automatically.



View this site's [_config.yml](https://github.com/pmarsceill/just-the-docs/tree/master/_config.yml) file as an example.

## What is the KakaoTalk calendar?

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
