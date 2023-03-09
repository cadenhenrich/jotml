# jotml
> Jotting down notes made simple with this markup language.

## Purpose

This is a markup language for notetaking built to be ***blazingly fast*** and
efficient while still being easy to learn. This is not your next Markdown
replacement, or your next LaTeX. Programs for the markup of web journals,
scientific papers, and simple notes should be and are drastically different.
This is also a personal project first, and a product second. JotML will be
updated as and when I am able to.

The primary output of this markup language is PDF. Anything other than that is
secondary. Users are welcome to create other output formats and submit a PR.
For now, I will be focusing on PDF and Text support.

## Features

+ [ ] Parser
  + [ ] Basic Text
  + [ ] Tufte Formatting
    + [ ] Font
    + [ ] Left/Right layout
      + [ ] Optional fullwidth
    + [ ] Footnotes
    + [ ] Margin notes
  + [ ] Headers
    + [ ] Level 1
    + [ ] Level 2
    + [ ] Level 3
  + [ ] Lists
    + [ ] Bullet
    + [ ] Check
    + [ ] Ordered
  + [ ] Tables
    + [ ] Headers
    + [ ] Content
    + [ ] Merged cells
    + [ ] Text alignment within tables
  + [ ] Code Blocks
  + [ ] Quote Blocks
  + [ ] Definition blocks
  + [ ] Math Blocks
  + [ ] Images
    + [ ] Figure markings/captions
    + [ ] Diagram ML
      + [ ] PlantUML
      + [ ] Mermaid\*
      + [ ] Others\*
  + [ ] Footnotes
  + [ ] Hyperlinks
    + [ ] URLs
    + [ ] Intra-file links
    + [ ] Inter-file links
  + [ ] Other MLs\*
    + [ ] Lilypond—Scores
    + [ ] TikZ—Diagrams
    + [ ] Pic—Diagrams
    + [ ] Chem—Chemistry diagrams
    + [ ] Others\*
+ [ ] Output
  + [ ] PDF
  + [ ] Text
  + [ ] HTML\*
  + [ ] SVG

\* = Maybe

## Class Diagram

<!-- Class Diagram Src -->
```plantuml
class JotML
class JotModel
class JotView
class TextView
class PDFView
class JotController
```
<!-- -->

## See Also

<!-- TODO: Add Links -->
+ [Markdown]()
+ [AsciiDoc]()
+ [AsciiMath]()
+ [PlantUML]()
+ [Mermaid]()
+ [TufteCSS]()
  + The works of ET more generally are worth looking at as well
