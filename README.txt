                   ===============================
                          Support Files from
                        the MIT book site for
                     Structure and Interpretation
                                  of
                          Computer Programs
                   ===============================

This is a personal copy of sample problems and code for the
text _Structure_and_Interpretion_of_Computer_Programs. Usually
known as SICP.

Downloaded January 2025 from:

https://mitp-content-server.mit.edu/books/content/sectbyfn/books_pres_0/6515/sicp.zip/index.html

The files were posted with the following license:

Structure and Interpretation of Computer Programs by Harold Abelson
and Gerald Jay Sussman with Julie Sussman is licensed under a Creative
Commons Attribution-ShareAlike 4.0 International License by the MIT
Press.

I like having local copies instead of web hunting, so these are the
files that looked useful to me as I work through the text. Any changes
I make will be minor, probably highlighted, and fall under the same CC
BY-SA 4.0 International License.

https://creativecommons.org/licenses/by-sa/4.0/

Troy Brumley, BlameTroi@gmail.com
January 2025
So let it be written,
So let it be done.

                               ========
                               Contents
                               ========

Many of the source files were originally suffixed '.scm.html' but I
trimmed off the '.html'. Documentation for the Sample Problems was
available in both TeX and PostScript formats. I don't often use TeX so
I only downloaded the PS files and used ghostscript to convert them to
PDF.

The files, with comments as appropriate.

.
├── LICENSE                    CC BY-SA 4.0 Intl.
├── README.txt                 This file
├── SICP_2e.html               Full HTML text
├── complete_code_2ed          The supporting code for the book
│   ├── ch1.scm
│   ├── ch2.scm
│   ├── ch2support.scm
│   ├── ch2tests.scm
│   ├── ch3.scm
│   ├── ch3support.scm
│   ├── ch4-ambeval.scm
│   ├── ch4-analyzingmceval.scm
│   ├── ch4-leval.scm
│   ├── ch4-mceval.scm
│   ├── ch4-query.scm
│   ├── ch4.scm
│   ├── ch5-compiler.scm
│   ├── ch5-eceval-compiler.scm
│   ├── ch5-eceval-support.scm
│   ├── ch5-eceval.scm
│   ├── ch5-regsim.scm
│   ├── ch5-syntax.scm
│   ├── ch5.scm
│   ├── complete_code_2ed.html  text about code from site
│   ├── load-eceval-compiler.scm
│   └── load-eceval.scm
├── errata.html                 
├── sample_programming_assignments     All the assignments
│   ├── 00_sample_programming_assignments.html
│   ├── 01_introductory_assignment
│   │   ├── ps1_1.pdf
│   │   └── ps1_1.scm
│   ├── 02_the_game_of_twenty_one
│   │   ├── ps2tw1.pdf
│   │   └── ps2tw1.scm
│   ├── 03_graphing_with_high_order_procedures
│   │   ├── curves.scm
│   │   ├── drawing.scm
│   │   ├── notes.txt
│   │   ├── ps2.pdf
│   │   └── utils.scm
│   ├── 04_continued_fractions
│   │   ├── _no_code_for_assignment_
│   │   └── ps2cnt.pdf
│   ├── 05_rsa_encryption
│   │   ├── diagrams.pdf
│   │   ├── figure1.pdf
│   │   ├── notes.txt
│   │   ├── ps3rsa.pdf
│   │   └── rsa.scm
│   ├── 06_prisoners_dilemma
│   │   ├── ps4prs.pdf
│   │   └── ps4prs.scm
│   ├── 07_picture_language
│   │   ├── _no_ps_file_just_tex_
│   │   ├── einstein.pgm
│   │   ├── fovnder.pgm
│   │   ├── hend.scm
│   │   ├── hutils.scm
│   │   ├── notes.txt
│   │   ├── prmpnt.scm
│   │   ├── ps4hnd.tex
│   │   └── psgo.scm
│   ├── 08_term_rewriting_evaluator
│   │   ├── notes.txt
│   │   ├── ps4.pdf
│   │   ├── smeval.scm
│   │   ├── smfresh.scm
│   │   ├── smscope.scm
│   │   ├── smstep.scm
│   │   ├── smsyntax.scm
│   │   ├── temp.scm
│   │   ├── tests.scm
│   │   └── trnotes.pdf
│   ├── 09_automatted_freshman_advisor
│   │   ├── adv.pdf
│   │   ├── adv.scm
│   │   └── notes.txt
│   ├── 10_generic_arithmetic
│   │   ├── ps5-code.scm
│   │   ├── ps5.pdf
│   │   ├── put-get.scm
│   │   └── types.scm
│   ├── 11_oo_adventure_game
│   │   ├── exercise1.pdf
│   │   ├── game.scm
│   │   ├── meta-advent.pdf
│   │   ├── notes.pdf
│   │   ├── notes.txt
│   │   ├── ps6game.pdf
│   │   └── world.scm
│   ├── 12_concurrency
│   │   ├── gauss.scm
│   │   ├── nikkei.scm
│   │   ├── notes.txt
│   │   ├── parallel.scm
│   │   └── ps7.pdf
│   ├── 13_streams_and_series
│   │   ├── ps9.pdf
│   │   └── ps9code.scm
│   ├── 14_evaluators
│   │   ├── analyze.scm
│   │   ├── evdata.scm
│   │   ├── meval.scm
│   │   ├── ps8-ans.scm
│   │   ├── ps8.pdf
│   │   ├── ps8defs.scm
│   │   └── syntax.scm
│   ├── 15_languages_for_oop
│   │   ├── mod.scm
│   │   ├── notes.txt
│   │   ├── ps7oop.pdf
│   │   └── teval.scm
│   └── 16_register_machines_and_compilation
│       ├── assemble.scm
│       ├── compdata.scm
│       ├── compiler.scm
│       ├── eceval.scm
│       ├── evdata.scm
│       ├── naivecom.scm
│       ├── notes.txt
│       ├── ps10.pdf
│       ├── regsim.scm
│       └── syntax.scm
└── tree.txt

19 directories, 108 files
