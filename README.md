# [Arc 42](http://www.arc42.de/) template for [GitBook](https://toolchain.gitbook.com/)

## Why?

Until now I could only find an arc42 template for Asciidoc. Of course you can use Asciidoc in combination with GitBook but I wanted to use the markdown version ;-\).

If you have\/know a better template for arc42 using GitBook then just let me know.

## What?

This is just a set of markdown files to have an easy start with documenting your systems's architecture using arc42 and GitBook.

## How?

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


## What next?

* Read everything about [Arc 42](http://www.arc42.de/)
* Download the [GitBook Editor](https://www.gitbook.com/editor)
* Start documenting your system
* Build your documentation as a set of html files

```
$ gitbook build
```

* View a live preview of your documentation in a browser

```
$ gitbook serve
```

