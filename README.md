# Jokester
Jokester is simple NPM package that provides you with list of prewritten jokes that you can easily add to your project. No need to figure out jokes on your own.

## Installing
1. Install the package
    ```bash
    npm i jokester
    ```
2. Fetch random joke
    ```javascript
    const jokester = require('jokester');
    
    const joke = jokester.getJoke();
    console.log(joke);
    ```
3. **Profit!**

## Contributing
All contributions are welcome to the project, if you find good jokes to be added, you can add them by first forking the repo, and then adding them to `src/jokes.json`.