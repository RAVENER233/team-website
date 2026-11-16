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

1. What would you lose by using a clickable <div> instead of a <button>?

A <div> lacks built-in keyboard support and button semantics. Keyboard and screen-reader users would be affected.

2. What would happen if you removed defer from the script?

The browser could execute JavaScript before the HTML finishes loading, causing elements not to be found.

3. Why use textContent instead of innerHTML?

innerHTML could allow malicious scripts to run, causing XSS attacks. textContent displays input as plain text.

4. Why does the server still need to validate form data?

JavaScript validation can be bypassed or disabled. The server must independently check submitted data.

5. Why doesn't the theme preference transfer from file:// to Live Server?

They have different origins, and localStorage is separated by origin.

6. What is duplicated across your HTML pages, and why is that a problem?

The navigation bar and footer are duplicated. Updating them requires changing every page, which can cause inconsistencies.