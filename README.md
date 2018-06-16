# Purpose

Reproduce issue [benmosher/eslint-plugin-import#1086](https://github.com/benmosher/eslint-plugin-import/issues/1086)

# Running

* Install dependencies

    ```
    npm install
    ```

* Run eslint

    ```
    npm start
    ```

    This will pass because it's only running the test, not trying or fix it.

* Reproduce issue

    ```
    npm start -- --fix
    ```

    This will run until it runs out of memory. This demonstrates the issue in [benmosher/eslint-plugin-import#1086](https://github.com/benmosher/eslint-plugin-import/issues/1086).