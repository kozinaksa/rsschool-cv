# Galina Moroz #
### Frontend Developer ###

---

### Contact Info ###
* __Location__ Saint Petersburg, Russia (GMT +3)
* __E-mail__ <kozinaksa@gmail.com>
* __Phone number__ +7-981-721-45-92 
* __Github__ [kozinaksa](https://github.com/kozinaksa)
* __Discord__ Lin_Moro#8613
* __Telegram__ [@kozinaksa](https://t.me/kozinaksa)

---
### About me ###
My goal is to create convenient interfaces for users, to make people's stay on the Internet easier and more enjoyable. I graduated from a publishing college, which means I can choose the appropriate font, arrange the elements on the page, and build a modular grid. I independently studied the basics of working with color, Adobe PhotoShop and Illustrator. I understand the principles of the Internet, networks, browsers. 

I am sure that enthusiasm, perseverance, the ability to read, understand and clarify (if necessary) the requirements for the task, as well as the ability to plan my working time will help me become a good frontend developer.

---

### Skills ###
__Languages:__ JavaScript, HTML, CSS \
__Version Control System:__ Git \
__Tools:__ VS Code \
__Adobe:__ InDesign, PhotoShop, Illustrator

---

### Code Example ###
'Replace With Alphabet Position' on [Codewars](https://www.codewars.com/kata/546f922b54af40e1e90001da/javascript).

> __Description:__ \
Welcome. In this kata you are required to, given a string, replace every letter with its position in the alphabet. \
If anything in the text isn't a letter, ignore it and don't return it. "a" = 1, "b" = 2, etc. \
__Example:__ \
alphabetPosition("The sunset sets at twelve o' clock.") \
Should return "20 8 5 19 21 14 19 5 20 19 5 20 19 1 20 20 23 5 12 22 5 15 3 12 15 3 11" ( as a string ) 

__Solution:__

```javascript
function alphabetPosition(text) { 
  let nums = []; 
  const alphabet = 'abcdefghijklmnopqrstuvwxyz'; 
  for (let i = 0; i < text.length; i++) { 
    let symb = alphabet.indexOf(text[i].toLowerCase()); 
    if (symb !== -1) { 
      nums.push(symb + 1); 
    } 
  } 
  return nums.join(' '); 
}
```