# React speed typing game

Test your typing speed with this small react project

![speed-typing game](https://user-images.githubusercontent.com/18181964/136147070-5b731103-b3a6-4a57-80be-fa899fbda4e1.PNG)

## how it works
- Click start button
	- The keyborad focus with automatically be in the input field
		- Input field will be enabled for typing
	- The time will start counting from deafult time which is 30 secs
	- At the end of the time you will see how many words you typed in as many seconds
		- input field will be disabled
		- ```javascript
			function calculateWordCount(text) {
        			const wordsArr = text.trim().split(" ")
        			return wordsArr.filter(word => word !== "").length
    			}
		```
		- The above function will return the word cunt

## React feautures covered

1. Hooks
	- useEffect
	- useState
	- useRef
	- custom hooks

2. Functional components

Quick start:

```
$ yarn # npm install
$ yarn start # npm start
````

 
Contact me <kdondidier@gmail.com>

Happy Coding!
