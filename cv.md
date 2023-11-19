# **Oleh Helgi**
## ___Contacts___
* Location: Kyiv, Ukraine
* Phone: +380 88 344 56 78
* e-mail: povicolo@gmail.com
* GitHub: https://github.com/OlehHelgi
* Discord: olehhelgi
## ___About Me___
I learn quickly and easily, I interact well with the team, I am mobile, enterprising, I adequately respond to criticism.
## ___Skills___
* HTML5
* CSS3
* SASS
* JavaScript (Fundamentals)
* Git/GitHub/GitLab
* VS Code
* Figma
## ___Code Example___
Given an array of integers. Return an array, where the first element is the count of positives numbers and the second element is sum of negative numbers. 0 is neither positive nor negative.If the input is an empty array or is null, return an empty array.

```
function countPositivesSumNegatives(input) {
  if (input === null || input.lenght == 0){
    return [ ];
  }
  let posCount = 0;
  let negSum = 0;
  for (let i = 0; i < input.length; i ++){
    if (input [i] > 0){
      posCount ++;
      }
       else if (input [i] < 0){
        negSum += input [i];
      }
 
  }
  if (posCount === 0 || negSum === 0 || posCount === null || negSum === null){
       return [ ];
  }
  return [posCount, negSum];
  }
  ```
## ___Experience___
Design, administration and maintenance of video surveillance systems, access control systems, various computer and electronic equipment
## ___Education___
* EPAM University
    - Front-End Self-Paced Online Program
* Prometheus online learning platform (_courses_)
  - Web programming with Python and JavaScript CS50
  - Basics of Web UI development
  - Basics of Linux
* National Technical University of Ukraine
“Igor Sikorsky Kyiv Polytechnic Institute”
  - electronics engineer
## ___English___
* Ukrainian, Russian - native speaker
* English - B1