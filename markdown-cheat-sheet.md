# Python decorators

##### **Definition :**

The main role of [decorators]([Les décorateurs python](https://python.doctor/page-decorateurs-decorator-python-cours-debutants) is to modify the behavior of four functions. They are useful when wanting to add the same code to several existing functions.



##### Rating

```python
@decorator 
def function():
    pass
```

**Use case :**

Decorators apply to methods or functions to validate arguments, a way of saying that we explicitly modify the behavior of a function

Exemple de cas d'utilisation

soit deux fonctions ci-dessous

```python
Première fonction
def hello():
    print("hello world !")
    
hello()

Hello world !
```

```python
Definition du décorateur
language = True
def decorator(func):
    if language:
        print("Bonjour le monde !")
    return func
```

```python
@decorator
def hello():
    print("hello world !")
    
Bonjour le monde 
```

L'utilisation du décorateur sur les deu

## H2

### H3

### Bold

**bold text**

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

I need to highlight these ==very important words==.

### Subscript

H~2~O

### Superscript

X^2^
