
# CLI for Password
Basic CLI tool for generating passwords.

## Usage

Install dependencies

```
npm install
```
See Commands
```
node index -h OR passgen -h (if you have linked it already)
```

Run file

```
node index (options)
```

To create a symlink to run "passgen" from anywhere

```
npm link

# Now you can run
passgen (options)

# To remove symlink
npm unlink
```

## Options

| Short | Long              | Description                     |
| ----- | ----------------- | ------------------------------- |
| -l    | --length <number> | length of password (default: 8) |
| -s    | --save            | save password to passwords.txt  |
| -nn   | --no-numbers      | remove numbers                  |
| -ns   | --no-symbols      | remove symbols                  |

This project is a copy of Traversy Media's project\
[Youtube](https://www.youtube.com/watch?v=3Xx83JAktXk)\
[GitHub](https://github.com/bradtraversy/passgen)
