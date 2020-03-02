# Web Programming with __Dart__

_Author: Moises Belchin, Patricia Juberias, thanks!_

## 0. Dart's Flightpath So Far (till year 2015)

### What is Dart?

Dart is an open-source, structured, and flexible programming language developed by Google, particularly oriented for web develoopment, but not exclusively.

Behind Dart are __Lars Bak__ and __Kasper Lund__, two of the authors of the V8 Javascript engine for Google Chrome.

__Gilad Bracha__ was also involved in the creation of Dart. Barcha is the author of Newspeak Programming Language, co-author or Java Specifications and the 2nd edition of the Java Virtual Machine Development.

Dart code runs over DartVM (Dart Virtual Machines), which is 2 times faster than JavaScript.

### Advantages of Using Dart?

- Its high performance
- Its simplicity and clarity when you use it and most importantly when you have to learn it
- Google Dart developers and the open-source community have created great documentation, including tutorials and samples.
- Its ability to use a full IDE just out of the box, which is known as Dart Editor
- Asynchronous Programming
- You can use Dart to develop web applications, but in addition, you can use Dart to develop command-line applications and server-side applications as well.

### Coverting from Other Programming Language

#### Dart vs JavaScript: the Names

| __Javascript__ | __Dart__ |
| --- | --- |
| HTMLElement | Element |
| ownerDocument | document |
| XMLHttpRequest | HttpRequest |
| CSSStyleSheet | CssStyleSheet|

#### Dart vs. JavaScript and jQuery: DOM elements (Dart has real Data Collections)

| __Javascript__ | __jQuery__ | __Dart__ |
| --- | --- | --- |
| getElementsById('id') | $('#id') | querySelector('#id') |
| getElementsByTagName('tag') | $('tag') | querySelectorAll('tag') \
| getElementsByName('name') | $('[name="name"]') | querySelectorAll('[name="name"]') |
| getElementsByName('name') | $('.class') | querySelectorAll('.class') |

Sample using `dart:html`:

```Dart
import dart:html
void main() {
  List<Element> my_divs = document.querySelectorAll('div');
}
```

#### Dart vs. JavaScript and jQuery: New DOM element

| __Javascript__ | __jQuery__ | __Dart__ |
| --- | --- |
| document.createElement('div') | $(document).add('div') \n $(document).append('div') | new DivElement() \n new InputElement(type:'checkbox') |


## 1. Getting Started

## 2. Dart Tools

## 3. The Dart Languages: Basics

## 4. The Dart Languages: Advanced

## 5. Dart and Other Web Technologies

## 6. Dart and the Web Server

## 7. Dart's Future
