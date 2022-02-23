# How to ask a Question With Beryl

## Make sure u did your Research before asking
#

### Try to ask your question in one sentence
#
### For Example
#

Title: How to get random-colors to multiple buttons in Javascript

#
Introduction

" I am trying to get multiple buttons color with a random-color generator in Javascript but i dont get a result" 
#

show code

```javascript
const drinkButtons = () => {
    for (let i = 0; i < drinks.length; i++) {
        let button = document.createElement("button");
        button.id = [i];
        const main = document.querySelector("main");
        main.append(button);
        button.innerHTML = drinks[i].name;
    }
    console.log(drinks);
}
drinkButtons(drinks,i);


const buttonColors = () => {
     const randomColor = Math.floor(Math.random()*16777215).toString(16);

     const button = document.querySelectorAll("button");

     for (let c = 0; c < button.length; c++){
     }

    document.getElementById([i]).style.backgroundColor = randomColor;
    
}
buttonColors();
```
#
