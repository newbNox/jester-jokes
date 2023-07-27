# Jester Jokes
Jester Jokes is simple NPM package that provides you with list of prewritten jokes that you can easily add to your project. No need to figure out jokes on your own.

## Installing
1. Install the package
    ```bash
    npm i jester-jokes
    ```
2. Fetch random joke
    ```javascript
    const jester = require('jester-jokes');
    
    const joke = jester.getJoke();
    console.log(joke);
    ```
3. **Profit!**

## Contributing
All contributions are welcome to the project, if you find good jokes to be added, you can add them by first forking the repo, and then adding them to `src/jokes.json`.