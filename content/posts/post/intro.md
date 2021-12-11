---
title: "Intro"
date: 2021-12-10T22:19:49+03:00
---

# H1
### H2 ne
new
**Bold** text
---
list of things to do:
---
That is so funny! :joy:
X^2^
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses
hfad
```python 
import numpy as np
for i in range(1,10):
print(i)
```
{{ .Title }}
{{ $address }}

and the code is like this:
```javascript
var add2 = function(number) {
  return number + 2;
}
```

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
---
ol {
  list-style-type: lower-greek;
}

___
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        | 

---
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
---

| Tables        | Are           | Cool  |
| ------------- |:------------- | ----- |
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
---
$-b \pm \sqrt{b^2 - 4ac} \over 2a$
$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$
$\forall x \in X, \quad \exists y \leq \epsilon$
$$
\int f
$$
{{- $image := resources.Get "images/logo.jpg" -}}
[title](https://www.example.com)
> blockquote thisi afaf

![alt text](../image.jpg)

~~The world is flat.~~
### My Great Heading {#custom-id}
 	term
: definition

aa 	Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
