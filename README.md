# speedlimit-api

## [POST] `/user`

Send

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

Receive

```
200 OK
```

## [PATCH] `/user`

Send

```js
{
    password(string, 255)
}
```

Receive

```
200 OK
```

## [GET] `/members`

Send

```js
```

Receive

```
200 OK
[
    {
        realname(string, 255),
        relative(string, 255),
        address(string, 255),
        birthday(string, 255, 'YYYY-MM-DD'),
        gender(string, 'male', 'female')
    }
]
```

## [POST] `/member`

Send

```js
{
    realname(string, 255),
    relative(string, 255),
    address(string, 255),
    birthday(string, 255, 'YYYY-MM-DD'),
    gender(string, 'male', 'female')
}
```

Receive

```
200 OK
```

## [PUT] `/member`

Send

```js
{
    realname(string, 255),
    relative(string, 255),
    address(string, 255),
    birthday(string, 255, 'YYYY-MM-DD'),
    gender(string, 'male', 'female')
}
```

Receive

```
200 OK
```

## [DELETE] `/member`

Send

```js
{
    id(int)
}
```

Receive

```
200 OK
```
