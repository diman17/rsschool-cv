# Dmitriy Pavlov

![My photo](img/avatar.jpg)

## Contacts:

- **tel:** _+375291936754_
- **skype:** _+375291936754_
- **telegram:** _https://t.me/diman170492_
- **e-mail:** _dmitriy.pavlov.17.04@gmail.com_

## About me:

I am a junior frontend developer from Belarus.  
My goal is to become a demanded specialist in this field.

## Skills:

- **HTML5**
- **CSS3 (SCSS)**
- **JavaScript (ES6)**
- **Git**
- **Photoshop, Figma**

## My code:

```
var encryptThis = function(text) {
  return text.split(' ').map(item => {
    let num = item.charCodeAt(0)
    return item.replace(/^\w/, num)
  }).map(item => {
    let numbers = item.match(/\d/g).join('')
    let letters = item.match(/\D/g) || []
    let firstLetter = letters[0]
    let lastLetter = letters[letters.length - 1]
    letters[0] = lastLetter
    letters[letters.length - 1] = firstLetter
    return numbers + letters.join('')
  }).join(' ')
}
```

## Work experience:

## Education:

1. HTML, CSS on htmlacademy.ru
2. Javascript on learn.javascript.ru

## English:

Pre-intermediate ([2English](2english.by) school)
