# Shubin Alexander

## Contacts

- Phone: +7 919 067-71-12
- Email: dopdoyq@gmail.com

## About me

Recently I hit the 15th year of my life and among the wide range of opportunities, already available for me, I search for the best place to realize my possibilities. I am a fast learner and always eager to practise.

Basics of some IT technologies are already known to me. I have taken part in developing some small-scale projects in Python, tried myself in web development.

## Skills

- HTML / CSS markup languages
- Basics of JavaScript
- Vite module bundler
- Python (object-oriented programming, Flask framework, telegram bots)
- Visual Studio Code, WebStorm
- Blender, Unreal Engine

## Code example

My first Codewars kata

```js
function isAValidMessage(message){
    if (message) {
        message = message.split('').slice(1).reduce((acc, val) => {
            const lastVal = '0123456789'.includes(acc[acc.length - 1][0])
            const currentVal = '0123456789'.includes(val)

            if ((!currentVal && lastVal) || (currentVal && !lastVal)) {acc[acc.length] = val}
            else {acc[acc.length - 1] += val}

            return acc;
        }, [message[0]]);

        if (message.length % 2 !== 0) {return false}
        if (!'0123456789'.includes(message[0][0])) {return false}

        console.log(message)

        for (let i = 0; i <= message.length / 2; i+=2) {
            if (message[i] != message[i + 1].length) {
                return false;
            }
        }
    }

    return true;
}
```

## Experience

- [Shop](https://github.com/LitCourage/Shop) - educational project that simulates the work of an online marketplace
- [Platformer](https://github.com/LitCourage/Platformer) - 2D platformer made in Python Pygame with use of OOP
- [Pairs](https://github.com/LitCourage/Pairs) - simple browser game made using HTML/CSS and JS
- [Flappy Bird](https://github.com/LitCourage/flappy-bird) - known to everybody game about a bird flying through green pipes

## Education

- Finished 8th grade
- Python developer course by Skysmart school
- Front end course by Skysmart school

## Languages

- Russian - native
- English - B1