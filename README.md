# Team Name: DynamoRaven

**Live site:** https://ravener233.github.io/team-websit

## Team
| Name               | Registration no.            | GitHub username |
|--------------------|-----------------------------|-----------------|
|Maurice Denzel      | COM/3496/26                 |    1200vsg             |
|Neville Kiprop      | COM/3463/26                 |     RAVENER233            |

## Who drove each part
Neville Kiprop- Part 0, 2, 4:
Maurice Denzel- Part 1, 3: 

## Personalisation

- **Our colours:** Light theme: `#2457A6` and `#174078`. Dark theme: `#65D6C5` and `#45B7A7`. We selected these colours to give our website a distinctive appearance while maintaining good text contrast.
- **Projects we added:** Team Website Repository and Android App Analysis, under the Git category. 
- **Extension challenge(s) completed:** E1 – Added a fourth page (`faq.html`) containing four frequently asked questions using HTML `<details>` and `<summary>` elements. Added the FAQ navigation link to all pages and set `aria-current="page"` correctly on the FAQ page.

## Reflection

**1. The menu toggle is a `<button>`, not a clickable `<div>`. Name two things you would lose with a `<div>`, and who would be affected.**

A `<div>` does not automatically support keyboard interaction or provide button semantics to assistive technologies. Keyboard users and people using screen readers would be affected because they might struggle to identify and operate the menu toggle.

**2. What would break if you removed `defer` from the `<script>` tag in `<head>`?**

Without `defer`, the browser would stop parsing the HTML while it downloads and executes the JavaScript file. The script might try to access HTML elements before they have been created, causing errors because those elements would not yet be available.

**3. `renderProjects` uses `textContent` rather than `innerHTML`. What could go wrong with `innerHTML` if project titles were typed in by visitors?**

Using `innerHTML` with visitor-provided titles could allow malicious HTML or JavaScript to be inserted into the page. This could lead to cross-site scripting (XSS), potentially allowing attackers to execute harmful scripts in another visitor's browser. `textContent` treats the input as ordinary text instead.

**4. Your form checks its input with JavaScript. Why will the server still need to validate the same data once the form is connected to one?**

JavaScript validation runs in the visitor's browser and can be disabled or bypassed. Server-side validation is necessary to ensure submitted information is safe, complete and correct before it is processed or stored.

**5. Your theme choice follows you from Home to Contact, but not from a double-clicked file to Live Server. Explain this using the idea of an origin.**

The browser stores our theme preference in `localStorage`, which is separated by origin. Home and Contact share the same origin when opened through Live Server, but a double-clicked file uses the `file://` origin, which is different from the Live Server address. Therefore, the saved theme preference is not shared between them.

**6. Name something duplicated across your HTML pages. What problem does that duplication cause, and how might it be avoided?**

The navigation bar and footer are duplicated across our HTML pages. This can make maintenance difficult because changing the navigation or footer requires updating every page, and forgetting one can make the website inconsistent.