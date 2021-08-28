# Kaheet
# Original made by pxtrez

[![made with love](https://img.shields.io/badge/made%20with-%F0%9F%92%99-blue?style=for-the-badge)

### Cheat

1. Join Kahoot Game
2. Open console and paste script:

```ts
fetch("https://raw.githubusercontent.com/roib2010/kaheet/main/src/script.min.js")
.then((r) => r.text()
.then((t) => eval(t)))
```

3. Then enter the quiz ID.

* Wrong answers should be darker than the correct ones.

![image](./docs/example.png)

## Bugs

Known unpatched bugs.

1. When the teacher chooses: random answers, the kaheet is in trouble. Highlights wrong answers and themes do not work properly. Then you should read the correct answer in the upper left corner, in the Correct tab or check console.
2. Cheat doesn't work for private quizzes
