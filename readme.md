# 👁️ Yannick Van den Brande's Portfolio 👁️

![peepoChat Image](https://cdn.7tv.app/emote/63438a743d1bc89e0ff9e400/4x.webp)

[GitHub Pages](https://nanioy.github.io/)

## Main Repository
- [GitHub Repository](https://github.com/NANIOY/DEV5-lab-portfolio)

## Projects

| **Name** | **Description**                     | **GitHub Repo**                        | **Codesandbox**                    |
| -------- | ----------------------------------- | -------------------------------------- | ---------------------------------- |
| Lab 1    | Voice controlled music player       | [Repo](https://github.com/Nvnchi/lab1) | [Sandbox](https://l4x4v6.csb.app/) |
| Lab 2    | Interactive random island generator | [Repo](https://github.com/NANIOY/lab2) | [Sandbox](https://jc48r3.csb.app/) |
| Lab 3    | N/A                                 | [Repo](#)                              | N/A                                |
| Lab 4    | N/A                                 | [Repo](#)                              | N/A                                |
| Lab 5    | N/A                                 | [Repo](#)                              | N/A                                |
| Lab 6    | N/A                                 | [Repo](#)                              | N/A                                |

## An interesting new feature of ES2018
Spread syntax, introduced in ES2018, is a useful feature in JavaScript that allows you to spread out the elements of an array, string, or key-value pairs of an object in various situations. It's like taking the contents of a container and placing them individually wherever they're needed.

For example:
- In function calls, you can use spread syntax to pass multiple arguments easily.
- In array literals, you can combine arrays or add elements to an existing array.
- In object literals, you can merge objects or add new key-value pairs to an object.

Spread syntax simplifies working with data by making it more flexible and readable in your code.

### [An example of this is from MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)

    const parts = ["shoulders", "knees"];
    const lyrics = ["head", ...parts, "and", "toes"];
    //Output: ["head", "shoulders", "knees", "and", "toes"]

### [Conditionally adding values to an array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
    const isSummer = false;
    const fruits = ["apple", "banana", ...(isSummer ? ["watermelon"] : [])];
    //Output: ['apple', 'banana']


![peepoChat Image](https://cdn.7tv.app/emote/62ec1cfdd2e11183867d8c3b/4x.webp)
