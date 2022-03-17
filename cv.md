![My photo](/photo.jpg)

# **Shishkina Anna**
## Junior Frontend Developer
***********************************************

### **Contact information:**

Phone: +7 905 666 47 15  

E-mail: [shishkina_annet@mail.ru](shishkina_annet@mail.ru)

Github: [AnikaLis](https://github.com/AnikaLis)

### **About me:**

During the last nine years I was warking as a sport instructor. Due to this job I have developed high organisational skills. I am a good team worker, I have good listening and communication skills. I am sure that these features will help me to build strong relationships at my future work. 
I have a creative mind and I am always enthusiastic to learn and undertake new challenges.
I am very interested in Front-end web development because it gives the opportunity to interact with new tools and learn new skills. This sphere is constantly changing and always keeps your mind sharp.

### **Skills:**
* HTML5
* CSS3
* JavaScript (Basic)
* Git
* VS Code
* Adobe Photoshop

### **Code Examples:**
```js
function towelSort (matrix) {
  let result = [];
  let sum;
  if (!matrix) {
    return [];
  }
  for(let i = 0; i < matrix.length; i++) {
    if (i % 2 !== 0) {
      for (let n = matrix[i].length - 1; n >= 0; n--) {
        sum = matrix[i][n];
        result.push(sum);
      }
    } else {
      for(let n = 0; n < matrix[i].length; n++) {
        sum = matrix[i][n];
        result.push(sum);
      }
    }
  } 
  return result;
}
```