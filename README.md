# ANU-finex

Final Examination template for ANU Final Examination papers.

* `LaTeX` package dependencies are packed away in `anu-exams-settings.sty`.
   * Users can further customize this.
* The design for the ANU-defined exam cover page is in `coverpage.tex`.
   * This is hardcoded, so users don't need to do anything here. 
* These two files are invoked in the preamble of the `main` exam paper file.
   * See example in `anu-finex-template-main.tex`.
* Individual questions are recommended to be written as modular files.
   * See examples stored in `questions/`.
* In the `main` file, a Boolean variable called `answers` can be activated (set to `true`). 
    * Re-typesetting would render the same exam paper file with examiner/solution guide.
    * A default `DO NOT DISTRIBUTE` watermark will appear on the cover sheet of the examiner/solution guide.
    * Authors can see examples of how to input solution guides in the question files under directory `questions/`.
*  In the `main` file, a Boolean variable called `arialfonts` can be activated (by setting its value to `true`).
   * This activates the `helvet` class of `LaTeX` fonts that is better suited for readers with reading difficulties.
