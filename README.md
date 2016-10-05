# [Arc 42](http://www.arc42.de/) template for [GitBook](https://toolchain.gitbook.com/)

## Why is this template here?

First: Because I wanted to learn GitBook and therefore I needed an example topic.

Second: Until now I could only find an arc42 template for Asciidoc. Of course you can use Asciidoc in combination with GitBook but I wanted to use the markdown version ;-\).

If you have/know a better template for arc42 using GitBook then just let me know.

The current content language is German.

## What can I use it for?

This is just a set of markdown files to have an easy start with documenting your systems's architecture using arc42 and GitBook.

## How do I use it?

* Install GitBook

  ```
  $ npm install gitbook-cli -g
  $ gitbook update
  ```

* Clone this git repo

  ```
  $ git clone https://github.com/nrekretep/arc42-gitbook-template.git
  $ mv arc42-gitbook-template/ my-arc-doc/
  $ cd my-arc-doc
  $ rm -rf .git
  ```


## What should I do next?

* Read everything about [Arc 42](http://www.arc42.de/)
* Download the [GitBook Editor](https://www.gitbook.com/editor)
* Start documenting your system
* Build your documentation as a set of html files

```
$ gitbook build
```
* Have a look at [generated html files in the _book folder](_book/index.html)

* View a live preview of your documentation in a browser

```
$ gitbook serve
```

