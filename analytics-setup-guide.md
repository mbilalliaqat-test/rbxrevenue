# Analytics / GTM Setup Guide

The site includes `/assets/analytics-hooks.js`.

It pushes these events to `window.dataLayer`:

- `calculator_tab_click`
- `copy_result_click`
- `copy_share_link_click`
- `planner_direct_download_click`
- `planner_form_submit`
- `calculator_input_change`
- `internal_guide_click`

## Recommended GA4 Events

Create GA4 custom events from these dataLayer events:

| Event | Use |
|---|---|
| `calculator_tab_click` | Which calculator module users open |
| `copy_result_click` | Strong engagement signal |
| `copy_share_link_click` | Share intent |
| `planner_direct_download_click` | Lead magnet interest |
| `planner_form_submit` | Email/lead conversion |
| `internal_guide_click` | Content navigation |

## Debugging

Open browser console and run:

```js
localStorage.setItem("debugAnalytics", "true")
```

Then interact with the calculator. Events will appear in the console.

To disable debug logging:

```js
localStorage.removeItem("debugAnalytics")
```

## Brutal warning

Do not drown the site in tracking scripts. Use one analytics stack first:
GA4 + Search Console is enough for launch.
