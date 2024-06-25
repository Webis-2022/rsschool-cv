# Jevgeni Verjovkin

## Junior Frontend Developer

----------

## **Contact information:**

Phone: +372 56220216

E-mail: verjovkin.jevgeni@gmail.com

Telegram: @Judgin82

Discord rs school: Jevgeni Verjovkin (Webis-2022)

## **Summary:**

I started learning web development 3 years ago. At first I studied and created several sites on Wordpress, and later I studied other content management systems, such as Joomla, Opencart, Prestashop. Later I studied HTML5 and CSS, and last year I started learning programming languages. I have a great interest in the field of web development and I hope that my desire to keep learning will help me become a good front-end developer.

## **Skills:**

* HTML5, CSS - intermediate level
* Javascript, NodeJS, PHP - basic level
* MySQL - intermediate level
* Git, Github
* Photoshop, GIMP, Illustrator 
* Sublime text 3, Visual Studio Code
* Windows 10, Windows 7
* SEO optimization
* Google Ads, Facebook Ads 

## **Code Example:**

*Adding unique elements to an array:*

```javascript
function pushIfUnique (inputArray, newElement) {
    if (inputArray.includes(newElement)) {
        return console.log(`${newElement} already in the array`)
    }
    inputArray.push(newElement)
}

const myNumbers = [123, 50, 27]

pushIfUnique(myNumbers, 50) // "50 already in the array"
console.log(myNumbers) // [123, 50, 27]

pushIfUnique(myNumbers, 80)
console.log(myNumbers) // [123, 50, 27, 80]

pushIfUnique(myNumbers, 80) // "80 already in the array"
console.log(myNumbers) // [123, 50, 27, 80]

pushIfUnique(myNumbers, 77)
console.log(myNumbers) // [123, 50, 27, 80, 77]
```