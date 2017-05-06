# speedlimit-api

## [POST] `/user`

```js
{
    username(string, 255),
    nickname(string, 255),
    email(string, 255),
    password(string, 255),
    birthday(string, 255, 'YYYY-MM-DD'),
    gender(string, 'male', 'female')
}
```

```
200 OK
```

## [PATCH] `/user`

```js
{
    password(string, 255)
}
```

```
200 OK
```

## [POST] `/member`

```js
{
    realname(string, 255),
    relative(string, 255),
    address(string, 255),
    birthday(string, 255, 'YYYY-MM-DD'),
    gender(string, 'male', 'female')
}
```

```
200 OK
```

## [PUT] `/member`

```js
{
    realname(string, 255),
    relative(string, 255),
    address(string, 255),
    birthday(string, 255, 'YYYY-MM-DD'),
    gender(string, 'male', 'female')
}
```

```
200 OK
```
