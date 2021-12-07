# Setup

Make sure you have Python 3 installed on your system. This repository was built using:

```
$ python3 --version
Python 3.8.3
```

To run the contents of this project/repository's directory on a local web server, take the following steps:

1. launch a terminal instance

2. navigate into this project/repository's directory

3. start up a (static!) web server locally, by issuing:

    ```
    $ python3 -m http.server 5500
    ```

4. in your web browser, go to the URL `localhost:5500/index.html` (or simply `localhost:5500`)

5. when you no longer need the local(ly running) web server, stop it by pressing `Ctrl + C`

# Introduction to *Flexbox CSS*

1. What is it? It is a CSS 3 web layout model, which provides a(n easy and clean)way to arrange items within a container (in a  layout) *in a responsive manner*.

2. It was created for small-scale, 1-dimensional layouts, whereas the more recent CSS Grid standard is geared more towards larger-scale, 2-dimensional layouts.

3. In a nutshell:

    - we have a main container/wrapper HTML element, which we assign the `display: flex` property

    - inside the main container element, we have child elements or *flex items*

    - certain properties go on the container, whereas others go on the flex items