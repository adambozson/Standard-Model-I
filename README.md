# Standard Model I

These are my notes from the first half of a [course of lectures][course-page] taken Sep–Dec 2015.

## Building the notes
### Compiling with _pdfTeX_
`pdflatex` and `mpost` (usually in _/usr/texbin_ or _/Library/TeX/texbin_ on Mac) must be in the `PATH` environment variable.

As usual, we have to run the TeX compiler twice:
```shell
pdflatex -file-line-error -interaction=nonstopmode SM1.tex
pdflatex -file-line-error -interaction=nonstopmode SM1.tex
```
The output is in _SM1.pdf_.

### Cleaning the directory
To remove all the temporary files spewed out during compilation:
```shell
rm -f SM1.aux SM1.toc SM1.out *.log *.mp *.1 *.t1
```

## Acknowledgements
See the _Acknowlegements_ chapter.

## Contributing
Adjustments, corrections, extensions, and other contributions are very welcome and highly encouraged.

* Fork this repo and [create a branch][branch], if appropriate
* Add your name and email to AUTHORS
* Make and commit your changes
* Submit a pull request

If you're unsure about a particular improvement, create an issue and we can discuss it.

## License
This work is covered by the [unlicense][unlicense], meaning you can do whatever you like with it. The authors are listed in AUTHORS (and compiled in the document) for non-mandatory recognition.

[course-page]: http://www.hep.ucl.ac.uk/~campanel/Post_Grads/2015-2016/
[branch]: https://guides.github.com/introduction/flow/
[unlicense]: http://unlicense.org
