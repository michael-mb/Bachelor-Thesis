[![pipeline status](/../badges/master/pipeline.svg)](../../pipelines)

* [Latest PDF online](/../-/jobs/artifacts/master/file/thesis.pdf?job=build)
    * [Build Log](/../-/jobs/artifacts/master/file/build_thesis.log?job=build)
* [diff to last tag](/../-/jobs/artifacts/master/file/difftag_thesis.pdf?job=diff)
* [diff to last commit](/../-/jobs/artifacts/master/file/diffcommit_thesis.pdf?job=diff)


Helpful documents
* [(German) manual for the TU LaTeX template](http://mirrors.ctan.org/macros/latex/contrib/tudscr/doc/tudscr.pdf)
* [Ein Anwenderleitfaden für das Erstellen einer wissenschaftlichen Abhandlung](http://mirrors.ctan.org/macros/latex/contrib/tudscr/doc/tutorials/treatise.pdf)


Für die Litteratur Compilierung

Run Thesis script
biber --input-directory=D:/uni/bachelor/software_testing/Bachelorarbeit thesis
makeindex -s thesis.ist -o thesis.gls thesis.glo
Run Thesis script
