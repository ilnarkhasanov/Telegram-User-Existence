# Telegram User Existence

This Python script can check if Telegram user exisrs via his username.

## Usage
```
$ python3 script.py --username username
```

## How to see the answer
Open *answer.json*. You will see the dictionary with *result* key. The value under this key is an answer, if Telegram user with that username exists.

## Meanings of answer

**Exists** - means that some Telegram user has that username.

**Does not exist** - means that there is no any Telegram user with that username.

**Error** - means that some issues with yout Internet connection or Telegram servers occured.


### From Ilnar Khasanov with Love, 2020.
