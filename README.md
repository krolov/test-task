# Test task

## Description
The archive contains the basic version of our monorep
There are several projects for now. You need to use projects `stocks-2` for the backend part and `web` for the frontend part. We use nx.dev to control this repository.
## Setup
We use yarn package manager. If you have not, you need to install it.

```
yarn install
```

To start project you need to type this commands in different terminals
```
yarn nx run graph:serve
```

```
yarn nx run web:serve
```

After start project will be available here http://localhost:4200/

## Task

`web` contains two buttons "Test form" and "Another form". 
"Another form" is just an example of how to use GraphQL in this project and you need to remove it.
"Test form" is just an example of how to import components from the library.

You need to develop a login form that would handle success and fault login attempts inside `@richland/ui/auth` library. Its form must use GraphQL query to backend. You can't insert GraphQL components inside the library.

Good luck!
