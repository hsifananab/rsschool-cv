# Ian Iusov

## Frontend Developer

### Contact Information

**Phone:** +7 (911) 843-59-36
**E-mail:** hsiv.dev@gmail.com
**Telegram:** @hsifananab

---

### About me

Frontend developer with over a year of commercial experience. Specializing in the development of user interfaces using React and TypeScript. Possessing a deep understanding of modern web technologies and committed to continuous professional growth.

### Skills

- HTML, CSS
- JavaScript/TypeScript
- React, Redux Toolkit

---

### Code example

[Duplicate encoder ](https://www.codewars.com/kata/54b42f9314d9229fd6000d9c)

```javascript
// The goal of this exercise is to convert a string to a new string
// where each character in the new string is  `"("`  if that character
// appears only once in the original string, or  `")"`  if that
// character appears more than once in the original string. Ignore
// capitalization when determining if a character is a duplicate.

const duplicateEncode = (word) => {
    return word
        .toLowerCase()
        .split('')
        .map((char, i, word) => word.indexOf(char) === word.lastIndexOf(char) ? '(' : ')')
        .join('')
	}
}
```

---

### Work Experience

**Todo App**
_React, Redux Toolkit, Scss_
[Demo](https://todo-app-tau-roan.vercel.app/) / [Source code](https://github.com/hsifananab/todo-app)

**Space Tourism**
_React, TailwindCss, Framer Motion_
[Demo](https://space-tourism-website-hsifananab.vercel.app/) / [Source code](https://github.com/hsifananab/space-tourism-website/tree/master)

**Countries**
_React, Axios, Styled Components_
[Demo](https://rest-countries-api-with-color-theme-switcher-wheat.vercel.app/) / [Source code](https://github.com/hsifananab/REST-Countries-API-with-color-theme-switcher)

---

### Education

**Saint Petersburg State University of Cinema and Television**
Bachelor's degree, Finance and Financials Management Services
_Sep 2012 - Jun 2016_

---

### Languages

- English **B1**
- Russian **Native**
