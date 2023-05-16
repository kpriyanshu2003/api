# API - Readme

This is an API built by me using cloudflare worker. Cloudflare Workers provides a serverless Open external link execution environment that allows you to create new applications or augment existing ones without configuring or maintaining infrastructure.

|URL|Function|Parameters|
|`/`|Access homepage|none|
|`/time`|Get current time | `?zone=timezone`. Default: `aisa/kolkata`|
|`/date`|Get current date|`?zone=timezone`. Default: `asia/kolkata`|
|`/fact`|Get a random fact|none|
|`/advice`|Get a random advice|none|
|`/joke`|Get a random joke (not in service)|none|
|`/quote`|Get a random quote|none|
|`/bully`|Get a random insuly|none|
|`/greet`|Greet the user|`?name=user_name`. Default: `user`|
|`/convert`|Convert any of them to any other of them. Binary, Decimal, Hexadecimal, Octal| `?bin=number`, `?dec=number`, `?hex=number`, `?oct=number`. Paramenter `REQUIRED`|
|`/dictionary`|Get definition of a word| `?query=word`. Parameter `REQUIRED`|
