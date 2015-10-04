# PAF the project

> Boilerplate generators to kickstart new projects, fueled by best practices


## Generators

- [Go][1]


## Getting started

First install [yeoman][yeoman]. It's this guy:

![](http://i.imgur.com/JHaAlBJ.png)

```bash
npm install -g yo
```

Yeoman travels light. He didn't pack any generators when he moved in. You can
think of a generator like a plug-in. You get to choose what type of application
you wish to create, such as a Backbone application or even a Chrome extension.

To install generator-paf from npm, run:

```bash
npm install -g generator-paf
```

Finally, initiate the generator:

```bash
yo paf
```


## Gears

Some strong assumptions are made regarding a project setup, like services for
continuous integration, and you're likely to have different ones. Fork the repo
to suit your need or open a Pull Request so we can discuss a smart way to
handle that.

- Continuous integration: [Circle CI][2]
- Code hosting: [Gitlab][3]

## Contributing

### [Build a generator][4]

```sh
npm install -g yo generator-generator
```


[1]: ./golang
[2]: https://circleci.com/
[3]: https://gitlab.com/
[4]: http://yeoman.io/authoring/
[yeoman]: http://yeoman.io
