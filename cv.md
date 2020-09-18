# Yuri Nesterov

## **Contact info**: 
  * *phone*: +380509705872
  * *e-mail*: <azmun.ra@gmail.com>
  * *telegram*: [@Azmun](https://t.me/Azmun)

## **Summary**

*Hello! My name is Yuri. I am a beginner programmer from Donetsk. I study HTML, CSS and JavaScript. I want to connect my life with programming.*

## **Skills**:
  * *HTML*
  * *CSS*
  * *JavaScript*
  * *Git basics*

## **Education**:

  * [*Donetsk National Technical University, Engineering mechanics*]
  
  **Online**:
  
  * *Codeacademy* - **HTML, CSS basics.**
  * *RSSchool* - **HTML, CSS, JavaScript.**
  * *HTML Academy*
  * *freeCodeCamp.org*
  
## **Code examples**

```javascript
    let input = document.createElement("input");
    input.addEventListener("focusout", (event) => {
      let input = event.target; // инпут берем из эвента а не используем переменную выше, потом что элемент создали но в дом еще его не добавили
      let p = document.createElement("p");
      p.innerText = input.value; // в параграф вставляем значение с инпута
      p.classList.add("header-value");
      input.replaceWith(p); // заменяем инпут параграфом
    });
```