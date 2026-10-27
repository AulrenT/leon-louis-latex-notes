# Louis' Exam Sheets For UoE Maths

LaTeX exam sheets for all Level 10 and Level 11 UoE Maths exams that I took (bar HDE), for anyone to use and customise :). Forked from [Leon's Notes](https://github.com/leon0241/leon-latex-notes/). Full credit to Leon for original template design and creation of the thmboxes package, my work has largely been adjusting and updating his to fit the 2-page era of maths exams. 

### :coffee: [(Optional) Buy Leon a coffee :)](https://ko-fi.com/leon024)

<!-- such a shameless self promotion u dickhead -->
<!-- ur lucky i didn't replace ur kofi with mine mate -->
## Links to 2-page Exam Sheets
<i> NB - These PDFs do not have sufficient margin for many printers and may be cropped, make sure to check/test your print margins </i>
### Honours Courses 
<li> <b>Honours Complex Variables</b> - <a href="exam-sheets/HCov/PDF/HCovExamNotes.pdf">click here!</a> </li>
<li> <b> Honours Algebra</b> - <a href='exam-sheets/HAlg/PDF/HAlgExamNotes.pdf'>click here!</a> </li>
<li> <b> Honours Analysis</b> - <a href='exam-sheets/HAna/PDF/HAnaExamNotes.pdf'>click here!</a> </li>

### Other Level 10s
<li> <b> Introduction To Number Theory </b> - <a href='exam-sheets/INT/PDF/INTExamNotes.pdf'>click here! </a>
<li> <b> Classical Mechanics For Mathematicians </b> - <a href='exam-sheets/CMM/PDF/ClaudialMechanics.pdf'>click here!</a> <i>(Not original content, just a condensed version of another sheet)</i> </li>
<li> <b> Statistical Methodology </b> - <a href='exam-sheets/StatsMeth/PDF/StatsMethExamNotes.pdf'>click here! </a> <i> WIP </i> </li>




## How To Use
These sheets rely on the thmboxes package and the preamble.sty file (through which all other packages are imported). All my notes rely on thmboxes_v5, Leon's use a variety of previous versions. Recompiling those with v5 is possible but requires a large amount of editing. See [leon-latex-thmboxes](https://github.com/leon0241/leon-latex-thmboxes) for more detail.  
In order to edit these sheets or create your own, you will need the `preamble.sty` and `thmboxes_v5.sty` files from <a href='Key-Files'>here </a>, and optionally the `template-2p` file <a href='template/template-2p'>here </a>. 
Call the packages in the beginning of your document via 

```

\usepackage{../../Key-Files/preamble}
\usepackage[separate]{../../Key-Files/thmboxes_v5}
```

Ensure that you use the appropriate relative file path, otherwise your LaTeX editor will not be able to find the files! See [here](https://www.w3schools.com/html/html_filepaths.asp) for an explanation if you are unsure of how to do this.  
For examples of how to write using this package, have a look at existing exam sheets such as <a href="exam-sheets/HAlg/HAlgExamNotes.tex">this one </a>


## Repository Structure
- `exam-sheets` contains all exam sheets, including raw `.tex` files and any other necessary components such as images, with each course in a separate folder
- `Key-Files` contains `preamble.sty` and `thmboxes_v5.sty`, both of which are necessary for creation and editing of exam sheets
- `Template` contains the template file for creating new exam sheets
- `Leon-Leegacy` contains all legacy files from Leon's work, though you are better off looking at it on [Leon's Notes](https://github.com/leon0241/leon-latex-notes/)

## A Note on LaTeX
I write all my exam sheets via TexStudio and rarely use any other LaTeX editor, in theory everything should work fine on any other system but no guarantees! I would also thoroughly recommend learning TexStudio or a similar program early in your LaTeX-writing career, and creating snippets/macros/etc which are customised to your tastes and intuition. Doing this has hugely increased the speed at which I can write these files and was well worth the initial time investment.


---

# [LEGACY] Archive of Leon's UoE Maths LaTeX Notes

<details>

<summary>
    Below is an archive of the previous readme from before I reorganised everything, saved here mostly for posterity, if you're curious about any legacy stuff then Leon's github is the best place to look. 
    
</summary>

LaTeX lecture notes and exam notes for a variety of courses in UoE CompSci and Maths. Feel free to use / fork / customise to your liking

### :coffee: [(Optional) Buy me a coffee :)](https://ko-fi.com/leon024)



### [LEGACY] Links to 6-page Exam Sheets
Outdated - SoM Exam Standard Is Now 2 Pages  
*Recompiling these with thmboxes_v5 and preamble.sty is possible, but requires some fiddling with packages and reformatting*


<details>
<summary>Year 2</summary>
<b>Fundamentals of Pure Mathematics</b> - <a href="exam-sheets/FPM/notes_colour.pdf">click here!</a>
</details>

<details>
    <summary>Year 3</summary>
    <ul>
        <li> <b>Geometry</b> - <a href="legacy-exam-sheets/Geometry/geometry_notes.pdf">click here!</a> <i>(they are terrible tho)</i> </li>
        <li> <b>Honours Algebra</b> - <a href="legacy-exam-sheets/algebra-6p/algebra-6p.pdf">click here!</a> </li>
        <li> <b>Honours Algebra</b> everything - <a href="legacy-exam-sheets/algebra-10p/algebra-10p.pdf">click here!</a> <i>(10 pages)</i> </li>
        <li> <b>Honours Analysis</b> - <a href="legacy-exam-sheets/analysis-6p/analysis-6p.pdf">click here!</a> <i>(without examples - basically 5 pages)</i> </li> 
        <li> <b>Honours Analysis</b> - <a href="legacy-exam-sheets/analysis-6p/analysis-6p-no-examples.pdf">click here!</a> <i>(without examples or applications - 5 and a bit pages)</i> </li>
        <li> <b>Introduction to Theoretical CS</b> - <a href="legacy-exam-sheets/ITCS/itcs_notes.pdf">click here!</a> <i>(Adapted from Chris Dalziel's LaTeX notes)</i> </li>
        <li> <b>Metric Spaces</b> - <a href="legacy-exam-sheets/metric-6p/metric-6p.pdf">click here!</a> </li>
    </ul>
</details>

<details>
    <summary>Year 4</summary>
    <ul>
        <li> <b>Algebraic Topology</b> - <a href="legacy-exam-sheets/algtop-6p/algtop-6p.pdf">click here!</a> </li>
        <li> <b>Galois Theory</b> - <a href="legacy-exam-sheets/galois-6p/galois-6p.pdf">click here!</a> </li>
        <li> <b>General Topology</b> - <a href="legacy-exam-sheets/gentop-6p/gentop-6p.pdf">click here!</a> </li>
        <li> <b>Group Theory</b> - <a href="legacy-exam-sheets/group-theory-6p/group-theory-6p.pdf">click here!</a> </li>
        <li> <b>Modelling Concurrent Systme</b> - <a href="legacy-exam-sheets/mcs-6p/mcs-6p.pdf">click here!</a> </li>
    </ul>
</details>

## Links to LaTeX Lecture Notes! (none of these are getting finished lol)
<details>
    <summary>Click Here</summary>
    <ul>
        <li> <b>Honours Algebra</b> (WIP) - <a href="algebra/algebra-notes.pdf">click here!</a></li>
        <li> <b>Metric Spaces</b> (WIP) - <a href="Metric%20Spaces/metric-notes.pdf">click here!</a></li>
        <li> <b>Foundations of Natural Language Processing</b> (BIG WIP) - <a href="FNLP/fnlp-notes.pdf">click here!</a></li>
    </ul>
    these probably also don't compile properly as well because I changed the file structure a while back and never updated them.
</details>


### Additional Information

#### 🎁 Theorem Boxes

Theorem boxes are created using various versions of `thmboxes_v*.sty`. Go to [leon-latex-thmboxes](https://github.com/leon0241/leon-latex-thmboxes) for more details

Additional Note: `\usepackage{../thmboxes_v*)` to import, but all of my notes will backreference by 1 level since they are in separate folders. If you want to fork and put them in the same folder you just need to `\usepackage{thmboxes_v*)`

#### 📁 Respository Structure
This repo is laid out in the following way
- `exam-sheets` for 2-page exam cheat sheets (Made by [Louis](github.com/AulrenT))
- `legacy-exam-sheets/` for 6-page exam cheat sheets. 
- `lecture-notes/` for lecture notes. 
- `legacy/` contains old files for legacy notes such old versions of `thmboxes.sty`.
- `other/` includes anything else such as a script to convert lecture notes to 6 page ones, or a script to convert obsidian callouts to thmboxes.
- `packages/` includes external latex packages.
- `rss/` includes the following LaTeX files:
    - `customs.sty` has custom definitions for commands such as page wide bars
    - `thmboxes_v5.sty` includes the definition for the custom theorem boxes
- `template/` includes templates for lecture notes, 2 page cheat sheets, and 6 page cheat sheets
- `preamble.sty` includes prerequisite imported packages for any 2 page notes.

#### ✏️ LaTeX File Structure
The following files are imported for a cheat sheet:

```

\usepackage{../../preamble}
\usepackage{symbols}
```

`preamble` is the master preamble for the repo (note the double layers of backreferencing), while `symbols` is a local sty file for any custom symbol definitions which would change per file. 

Additionally imported from within `preamble` is `rss/customs`.

#### ⌨️ Writing LaTeX

Currently using a NeoVim / VimTex / LuaSnip setup to write notes. [Link to nvim config](https://github.com/leon0241/nvim-leon). The actual snippets are in `lua/snippets/tex`. Using TeXLive full installation, but a mini one should work decent, I don't think I use that many obscure packages

nvim is mostly for more flexibility in terms of customising autocomplete (I use `jl` to navigate snippet tabs, `jp` to navigate back which afaik you can't do in VSCode and Obsidian). Obviously though the biggest advantage is the superiority complex and ego boost of using vim :) (i use arch btw 🤓)

Obviously inspired by the late Gilles Castel [Link to his setup](https://castel.dev/)

LuaSnip / UltiSnip on nvim setup guide: [Click Here!](https://ejmastnak.com/tutorials/vim-latex/intro/)

Documentation is not being made for my snippets any time soon, and probably will never be made. I recommend starting off with some basic snippets and find your own custom way of writing snippets :)

Other configs I've tried to use (the FPM notes were made entirely with VSCode, not entirely sure how I did it because I tried to use it again in third year and it wasn't nearly as smooth, might upload my DICE VSCode configs at some point)

- [VSCode with HSnips](https://github.com/leon0241/leon-latex-vscode-hsnip) - [Bonus video in action](https://youtu.be/LiLjxrPmJKo) (Quite possibly outdated)
- [LaTeX Suite with Obsidian](https://github.com/leon0241/latex-suite-config) - Very smooth, and obsidian has the potential to be a great cross-course note-taking app, just requires a lot of dedication and planning


## 🪦 Legacy Info

### FPM Notes Info

If you want to import into overleaf or anything, you will need `preamble.sty` and either `thmboxes_col.sty` or `thmboxes_white.sty` as well as the main `.tex` file

Included is a `template.tex` file if you want to start from scratch for another course :)

Dependencies that are not in a barebones TinyTeX installation are listed in the dependencies file, if you are using Overleaf / a larger TeX package they should be preinstalled already

If someone knows which package extarticle is included in then lmk :sob:, right now it's just sitting in the folder lol

(only for FPM) Any theorem number is the closest theorem to the lecture notes (some are taken from other sources)

</details>
