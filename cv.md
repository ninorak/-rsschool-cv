# rsschool-cv
## Nino Rakviashvili
### Junior Frontend Developer
### Contact information:
**Phone:** +995 592 00 77 54

**Email:** n.rakviashvili11@gmail.com


## About Myself:
I started my career as a game presenter. In more than two years I got bored and now I want to become Frontend Developer. I am learning with online courses everything that I can and hope It will not take too long.

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.


## Skills:
* HTML5, CSS3
* JavaScript Basics
* Github, Git
* VS code
* Dealing cards fast 

## Code example:
**Peak array index KATA from CODEWARS:** Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.

```javascript
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
## Languages:
* Georgian - Mother language
* English - B2
* Russian - A2
