# gof

Go Fuzzy

![](http://i.imgur.com/TGZJyGV.gif)

## Installation

    $ go get github.com/mattn/gof

## Feature

* Faster and startup
* Working on windows

## Usage

* Glob files and edit the selected file with vim.

```sh
$ vim `gof`
```

* Run gof and type `CTRL-O`, then start to edit with editor.

```sh
$ gof
```

* Read from stdin

```sh
$ find /tmp | gof
```

## Key Assign

|Key              |Description                         |
|-----------------|------------------------------------|
|CTRL-K,ARROW-UP  |Move-up line                        |
|CTRL-J,ARROW-DOWN|Move-down line                      |
|CTRL-A,HOME      |Go to head of prompt                |
|CTRL-E,END       |Go to trail of prompt               |
|ARROW-LEFT       |Move-left cursor                    |
|ARROW-RIGHT      |Move-right cursor                   |
|CTRL-O           |Edit file selected                  |
|CTRL-I           |Toggle view header/trailing of lines|
|CTRL-L           |Redraw                              |
|CTRL-U           |Clear prompt                        |
|CTRL-W           |Remove backward word                |
|BS               |Remove backward character           |
|DEL              |Delete character on the cursor      |
|CTRL-Z           |Toggle selection                    |
|Enter            |Decide                              |
|CTRL-D,CTRL-C,ESC|Cancel                              |

## Options

|Option   |Description                      |
|---------|---------------------------------|
|-c       |Cat the selected file            |
|-e       |Edit the selected file           |
|-        |Remove the selected file         |
|-l       |Launcher mode                    |
|-x       |Exit code for cancel (default: 1)|
|-d [path]|Speciry root directory           |

## License

MIT

## Author

Yasuhiro Matsumoto (a.k.a mattn)
