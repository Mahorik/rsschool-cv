# Boris Mikheev
<img src="https://camo.githubusercontent.com/6ca1bfcfc64bf7cb197ca0f4b61539d90822e0dd5375cacce19ca25c8b6cfe94/68747470733a2f2f7974332e67677068742e636f6d2f7974632f414b65644f4c54775636636c376b4179334c334b4d5f304c2d5a65355a58314e33784a364b7a76573433673473673d733930302d632d6b2d63307830306666666666662d6e6f2d726a" alt="drawing" width="200"/>

## Contacts
* Location: Moscow, Russian Federation
* Phone: +7(964) 622-41-79
* Email: borik.mahorik1@yandex.ru
* GitHub:https://github.com/Mahorik

## About 
Hello, my name is Boris.
Im 30 years old.

* https://htmlacademy.ru/profile/id233308
* https://www.codewars.com/users/Mahorik

## Skills
* HTML
* CSS
* Scss
* Javascript
* WEbpack
* React
* Redux
* Git


## Code Example
```
# The task was to write a function that takes a string and return a new string with all vowels removed.

function disemvowel(str) {
    const vowels = [ 'A', 'E', 'I', 'O', 'U']
    let arrFromStr = str.split('')
    let result = arrFromStr.filter((item) => {
        for(let i = 0; i < vowels.length; i++) {
            if(item.toLowerCase() == vowels[i].toLowerCase()) return false
        }
        return true
    })
    return result.join('')
}

# I am given a string of space separated numbers, and have to return the highest and lowest number.

function highAndLow(numbers){
    let result = []
    let arrFromString = numbers.split(' ')
    let max = arrFromString[0]
    let min = arrFromString[0]
    console.log(arrFromString)
    arrFromString.forEach(element => {
        max = (Number(element) >= Number(max))? element:max
        min = (Number(element) <= Number(min))? element:min
    });
    result[0] = max
    result[1] = min
    return result.join(' ')
}
```
## Work experience
Im just starting...

## Education
Pushkin Leningrad State University

## English
Pre-intermediate



