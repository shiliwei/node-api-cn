
URL 只被允许包含一个特定范围的字符串。
URL 对象的属性中的空格（`' '`）和以下字符会被自动转义。

```txt
< > " ` \r \n \t { } | \ ^ '
```

例如，ASCII 空格字符（`' '`）被编码成 `%20`。
ASCII 斜杠字符（`/`）被编码成 `%3C`。
