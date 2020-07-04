---
title: "Horrendous Markdown"
description: "Don't do this, pretty pretty please"
date: "Eternal"
---

## Horrendous Markdown

> Notice that header above is not h1 😱
> > Don't nest quotes so much
> > > I mean it
> > > > i mEaN It 😡

# H1 header, here it is!

## Links

- [Example.com](https://example.com/) – Uppercase
- [example.com](https://example.com/) – Lowercase
- [Example.com/](https://example.com/) – Uppercase, ending slash
- [example.com/](https://example.com/) – Lowercase, ending slash
- [www.example.com](https://www.example.com/) – www, also present in url 
- [www.example.com](https://example.com/) – www, but not present in url
- [https://example.com/](https://example.com/) – protocol
- [http://example.com/](https://example.com/) – protocol mismatch
- [example.com](http://example.com/) – protocol unsafe
- [example.com](https://not-example.com/) – different domain
- [example.com](https://elpmaxe.com/) – totally different domain
- [example.com](example.com) – no protocol
- [/r/webdev](https://www.reddit.com/r/webdev) – part of url
- https://example.com/
- <https://example.com/>

Lists are important to list
===

<small>Notice style or above header<small>

#### Mixed

1. Apple
  * bla
  * blo
1. Banana
    - indented with 4 spaces
  - blo
3. Coconut
  - bla
  * blo
  1. blu

#### Unordered: *

* Apple 
* Banana
* Coconut

#### Unordered: +

+ Apple
+ Banana
+ Coconut

#### Unordered: -

- Apple
- Banana
- Coconut

#### Ordered: 1, 1, 1

1. Apple
1. Banana
1. Coconut

#### Ordered: 1, 2, 3

1. Apple
2. Banana
3. Coconut

#### Ordered: 3, 2, 1 – because author is horrible human being

3. Apple
2. Banana
1. Coconut

## Quotes

> Important
> multiline
> quote

> ```js
> console.log()
> ```

> Lorem ipsum
>
> ```js
> console.log()
> ```
> 
> **bold** with `code` and [link](https://example.com)
> 
> ## Heading
> > ## Double quoted
> > > ## This is ridiculous

<details>
<summary>📥 Summary of following</summary>
Lorem ipsum but not really.
</details>

<details>
<summary>📥 Summary of following</summary>

Lorem ipsum but not really.
</details>

<details>
<summary>📥 Summary of following</summary>
```
Lorem ipsum but not really.
```
</details>
