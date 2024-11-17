# Vasilev Alexandr
### Junior Frontend Developer

----

### Contacts information
**Phone:** +79822839068<br>
**E-mail:** vs.t4werka2004@gmail.com<br>
**Telegram:** @vasilievAlexandr<br>

---

### Briefly About Myself:
At the moment I am a junior fronted developer in a company for the production of commercial products.

My path as a fronted developer started in college, before college I studied some design and tried to make sites on tilda.<br>
In college I got acquainted with HTML and became interested in the field of website development.<br>
Studied JavaScript and the framework Vue.js. In college I also taught php and the framework Laravel.<br>
I have 1 year of commercial development, and decided that you need to continue learning so as not to stand still.<br>
Before that I mostly studied independently through youtube and articles.<br>
In choosing a place to study there was several options and on the advice of a friend decided to choose rs-school

### Skills and Proficiency:

- HTML5, CSS3, scss, sass
- JavaScript, PHP, TypeScript basics
- Vue.js, Laravel, Nuxt
- Tailwindcss, Bootstrap
- Docker
- Webpack, Vite, Axios, Vuex, Pinia, element plus, apexcharts, lodash, vueuse, dayjs
- Eslint
- Git, GitHub, GitLab
- VS Code, IntelliJ IDEA
- FSD, SOLID, DRY

---

### Code example:

**word is a palindrome from LeetCode:**

```javascript
function checkPalindrome(str) {
  const strToArr = str.toLowerCase().split('');
  let i = 0;
  let lastIndexOfEnd = strToArr.length - 1;
  let isPalidrome = true;
  while (i <= strToArr.length / 2 && isPalidrome) {
    if (strToArr[i].match('[a-z]') && strToArr[lastIndexOfEnd].match('[a-z]')) {
      isPalidrome = strToArr[i] === strToArr[lastIndexOfEnd];
      i += 1;
      lastIndexOfEnd -= 1;
    } else if (!strToArr[i].match('[a-z]')) {
      i += 1;
    } else {
      lastIndexOfEnd -= 1;
    }
  }
  return isPalidrome;
}
```

---

### Work Experience:

Mostly engaged in supporting Ecom products, performing both big and small tasks.
Example of tasks for certain tasks:
- integatinon yandex map
- Sliders connection and customization
- Makes forms
- Functional Stories
- Yandex metric
- settins config of webpack

---

### Courses:

- HTML/CSS/JS Tutorials on the [HTMLacademy](https://htmlacademy.ru/) (completed)<br>
![HTMLacademy Score](/images/html-academy-score.png)<br>
- JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/)<br>
- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)<br>
- Watch youtube [UlbiTv](https://www.youtube.com/@UlbiTV) / [JavaScriptNinja](https://www.youtube.com/@JavaScriptNinja) expamle task config webpack (https://github.com/Kyrluk-Kyrlukovich/monoreto-module-federation)

### Languages:

- English \- Intermediate
- Russian \- Native
