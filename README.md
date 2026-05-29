# ANU-finex

Final Examination template for ANU Final Examination papers.

* Most `LaTeX` packages called are in `anu-exams-settings.tex`.
* This file is invoked in the preamble of the main exam paper file, `anu-finex-template-main.tex`.
* Individual questions are recommended to be written as modular files. See examples stored in `questions/`.
* In the main file, a Boolean variable called `answers` can be activated (set to `true`). 
    * Re-typesetting would render the same exam paper file with examiner/solution guide.
    * Authors can see examples of how to input solution guides in the question files under directory `questions/`.
