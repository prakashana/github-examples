# Markdown example

- [Unordered lists](#unordered-lists)
- ordered lists
- text formatting
- code
- tables
- blockquote
- [links](#links)
- images
- autolists
- lists

https://github.github.com/gfm/

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

## Unordered lists

We can create unordered lists in markdown using hypens.

- foo
- bar
+ baz
+ baz

##Ordered lists

1. foo
2. bar
3) baz
3) baz
3) baz

## Text formatting

*italics*
_italics_
**bold**
__bold__
~~strikethrough~~

## code

### Inline code

You can print to the terminal using the `puts "hello world"` command.

### Multi line code

#### Without highlighting

```
def hello_world
    puts "hello world"
end
```
#### With Highlighting

```rb
def hello_world
    puts "hello wrold"
end
```

### Tables

| foo | bar |
| --- | --- |
| baz | bim |

| abc | defghi |
:-: | -----------:
bar | baz

| f\|oo  |
| ------ |
| b `\|` az |
| b **\|** im |

| abc | def |
| --- | --- |
| bar | baz |
> bar

| abc | def |
| --- | --- |
| bar | baz |
bar

bar

| abc | def |
| --- |
| bar |

| abc | def |
| --- | --- |
| bar |
| bar | baz | boo |

| abc | def |
| --- | --- |


## Blockquote
> # Foo
> bar
> baz

># Foo
>bar
> baz

   > # Foo
   > bar
 > baz

## Links
[github website](https://github.com)

[secret page](secret.md)

## tasklist

- [ ] foo
- [x] bar

- [x] foo
  - [ ] bar
  - [x] baz
- [ ] bim
