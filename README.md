# frontendpro-hw-69
Написати фцнкцію генератор яка при виклику .next() будеповертати кожну окрему властивість обєкту. З цього масиву обєктів (без вкладеності) 

https://jsonplaceholder.typicode.com/users

тобто в цьму випадку я при першому виклику .next() отримую щось типу
````json
{"id": 1}
````
при другому викдику .next()
````json
{"name": "Leanne Graham"}
````
І так далі поки не пройду по всім властивостям всіх обєктів в масиві (першого рівня вкладеності)

Додатково, після виконання першої функції можете написати скріп котрий буде кожні пів секунди виводити на сторінку в елемент ul підобєкти які ми отримуємо піся виклику .next() 
