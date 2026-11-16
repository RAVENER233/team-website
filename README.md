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
- **Extension challenge(s) completed:** E1 – Added a fourth page (`faq.html`) containing four frequently asked questions using HTML `<details>` and `<summary>` elements. Added the FAQ navigation link to all pages and set `aria-current="page"` correctly on the FAQ page.Also added photos using the `<img>` tag

## Reflection

1. We learned how to build a website from scratch using HTML, and how to use semantic elements to give our pages real meaning and structure.

2. We got better at CSS by designing layouts that work on different screen sizes, picking colours that fit together, and adding both light and dark themes.

3. We learned how JavaScript brings a website to life — things like the navigation toggle, filtering projects, and checking form inputs before submission.

4. We came to understand why accessibility matters, from using proper buttons and labels to adding alt text and making sure everything works with just a keyboard.

5. We learned how important teamwork is — splitting up tasks, helping each other solve problems, and testing the site together before handing it in.

6. We got hands-on experience with Git and GitHub, using them to share our code, keep track of changes, and work together as a team.


You would lose keyboard support (no tab/Enter/Space) and screen reader support (no "button" role announced). Keyboard users and screen reader users would be affected.


The page would pause while the script loads, and the script might run before the HTML elements exist. It could then fail to find elements like the menu toggle.


A visitor could type in HTML or JavaScript, and the page would run it. This is a security risk called XSS (cross-site scripting). textContent treats everything as plain text

JavaScript can be turned off or bypassed. The server must check the data again to keep it safe and correct before storing or using it.


localStorage is tied to an origin. Live Server pages share one origin, so the theme carries over. A double-clicked file uses file://, a different origin, so it can't see the saved theme.


The navigation bar and footer are copied on every page. Changing them means editing every file, and it's easy to miss one. A template system or shared components would fix this.
