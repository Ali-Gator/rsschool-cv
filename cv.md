# Oleg Gordienov

| Photo                                          | Contact info                                                                                                                                                                                                                                                                                                                                                        |
|------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="./1.jpg" width="200" height="200" /> | Telegram: [@oleg_ily](https://t.me/oleg_ily) <br> Skype: [@oleg_ily](https://join.skype.com/invite/ibnfXBKy5BqP) <br> Phone: [+79052463325](tel:+79052463325) <br> E-mail: [ogordienov@yandex.ru](mailto:ogordienov@yandex.ru) <br> GitHub: [Ali-Gator](https://github.com/Ali-Gator "пупкп") <br> Codewars: [Ali-Gator](https://www.codewars.com/users/Ali-Gator)  |

## About me

I fall in love with the front-end when, as a customer, I encountered difficulties in understanding business tasks by
performers and their formal approach to development. I like to create clean code and see the result.

I follow the news from the world of Frontend, listen to podcasts, read articles and educational literature. Participated
in the final of the Digital Hackathon 2019 in Kazan.

I love to travel, visited 15 countries.

## Skills

* HTML
* CSS (including BEM methodology)
* JavaScript (Fundamentals, Functional Programming, OOP, Asynchronous JavaScript, ES6+, DOM)
* JSON
* React JS
* Version control: Git (remote service GitHub)
* Module Bundlers: Webpack
* Figma (for web development)
* Editors: VSCode, WebStorm

## Code sample

```
function listSquared(m, n) {
  let result = [];
  
  while(m <= n) {
   let divisors = [];
   for (let i = 1; i <= m; i++) {
     if (m % i === 0) {
       divisors.push(i) 
       }
    } 
    let squaringSum = divisors.map(el => el * el).reduce((sum, el) => sum += el, 0);
    if (Number.isInteger(Math.sqrt(squaringSum))) {
      let arr = [];
      arr.push(m, squaringSum);
      result.push(arr);
    }
    m++;
   }
  return result;
}
```

[Codewars: "Integers: Recreation One", 5 kyu](https://www.codewars.com/kata/reviews/55aa0d71c1eba8a65a000132/groups/621d1cfed1c8c8000157b1c6)

## Experience

| Project                                                       | Description                                                                                       | Technologies                                                                |
|:--------------------------------------------------------------|:--------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------|
| [Portfolio](https://github.com/Ali-Gator/portfolio)           | Landing page describing educational projects                                                      | HTML5, CSS3                                                                 |
| [How to learn](https://github.com/Ali-Gator/how-to-learn)     | Landing page "How to learn"                                                                       | HTML5, CSS: flexbox layout, @keyframes animation, BEM Nested                |
| [Russian Travel](https://github.com/Ali-Gator/russian-travel) | Project about travels                                                                             | HTML: grid + flexbox, media quaries, retina graphic, font's smoothiong, BEM |
| [Mesto](https://github.com/Ali-Gator/mesto)                   | Single page application (SAP) where you can add/delete and like/dislike photos, edit your profile | HTML5, CSS3, JS (classes, modules, form validation), React.js               |
| [Mortal Combat](https://github.com/Ali-Gator/zarmarathon)           | Browser game "Mortal Combat":  [on netlify](https://mortalbyoleg.netlify.app/)                    | HTML5, CSS3, JS (classes, modules, fetch)                                   |

## Education

| Year | Course                 | Educational institution |
|:-----|:-----------------------|:---|
| 2021 | Frontend developer     |Yandex Practicum|
| 2021 | Javascript             |learn.javascript.ru|
| 2021 | Computer Science, CS50 |Harvard Online|
| 2019 | HTML, CSS              |HtmlAcademy|

## Languages

* Russian: native
* English: B1 (Intermediate) by EPAM training system
