# Resume of Sergey Sudakov
 *Personal data:*

  1. Email: mousecode99@gmail.com
  2. Phone number: 89684585742   
  3. Location: Dmitrov, Moscow region

## About me
I like to learn web development and net technologies. My favorite resourse to practise JS is Kata codewars (link to my profile https://www.codewars.com/users/Diccens5). I wrote some scripts to Melon (https://melon.su/), rybovodcentr.ru (http://rybovodcentr.ru/). Now I'm working on the Legion invest. I'll deploy it on my github soon.
Everyday I read habr(https://habr.com/), telegram channnels about web and documentation. 
## Skills:

   1. Html - medium level  
   2. CSS(SCSS) - medium level
   3. JS - basic level  
   4. Git - basic level  
   5. English - A2


## Code example:
  ```
  function greatestCommonDivider(number1, number2) {
    while (number2 !== 0) {
        let temp = number2;
        number2 = number1 % number2;
        number1 = temp;
    }
    return number1;
  }