# Dodecachordon Data Set

Collection of symbolic music files (.xml - MusicXML), and corresponding .pdf documents from Glarean's _Dodecachordon_. The files are organized according to books 1-3.<sup>[[1](#note-1)]</sup>

## Organization

The files are organized according to books 1-3, and whether they are:

+ Music Theory Examples
+ Music Literature Examples
  - full pieces
    - a mass movement is a full piece
    - m. 1 - final cadence
    - a larger part of a piece
      - for compositions in two or more parts
+ Music Literature Example Excerpts
  - few measures of a piece
    - e.g.: mm. 4-8

## Files

When uploading a file make sure to always upload a file pair (.pdf + .xml):
+ [De_profundis.xml](https://github.com/ELVIS-Project/Dodecachordon-Data-Set/blob/master/Book-III/Literature-Examples/Champion-Jos1511_De-profundis.xml)
+ [De_profundis.pdf](https://github.com/ELVIS-Project/Dodecachordon-Data-Set/blob/master/Book-III/Literature-Examples/Champion-Jos1511_De-profundis.pdf)

### Naming Conventions

File naming convention:
+ Include from which book it came
+ Include the name of the piece or example
+ If there are two examples of the same type on the same page append the file name with the next logical number.
+ Add the page number
  - If a piece or example is referenced in the text, and then shown in the appendix, look at the example below 

Thus a file name should look like:
- Book-1_Example-1_p-47.pdf
or
- Book-3_De-profundis_p-266_p-447.pdf (In the book, and the appendix)
or
- Book-1_Alma-redemptoris-mater-2_pp-57-58.pdf

## Monophonic Examples

### Time Signature and Bars
+ Make each line of the example one long bar
 

+ Enter the time signature as [number of notes in the line]/4
+ Hide the time signature and bar lines
  - In MuseScore2, you can do this from the Inspector pane.
+ Enter each note as a stemless quarter note
  - In MuseScore2, you can select this option in the Inspector pane.

### Clefs
+ Employ the same clefs as the example, if possible
  - Since the staffs only have 4 lines, ignore the uppermost line of the modern 5-line staff
    - E.g., A baritone clef (a C clef on the uppermost line) in Glarean will become a tenor clef in your example

### Ligatures
+ Enter ligatures as slurs
+ These slurs should always be placed above the note
  - In MuseScore2, select the slur and then press “x” to flip its orientation
+ Rules of thumb about ligatures:
  - Group connected notes into one ligature
  - A note with a tail followed by diamond notes is also one ligature
    - Exception: When there are repeated notes

### Barlines
+ Enter barlines as breath marks
  - In MuseScore2, you must be on the Advanced Workspace to see the Breaths & Pauses palette
+ Generally, barlines separate complete words, but only indicate a carline where one is indicated in the example

### Text
+ Include the text
+ Although the examples lack hyphens indicating melismas, transcribers should follow typical formatting conventions for lyrics: hyphens in between syllables of the same word
  - If MuseScore2 fails to show hyphens, change the horizontal offset for individual notes in the Inspector
+ Reproduce the spelling, punctuation, and capitalization of the example, even if there are errors or inconsistencies
+ Rules for text underlay:
  - Syllables do not change during neumes

## Polyphonic Examples

### Existing Polyphonic Examples

Many of the polyphonic examples already live in the [ELVIS database](http://database.elvisproject.ca) as _.pdf_, or _.xml_ files. Most of the times these examples still need some post editing, for example when only a _Pleni sunt_ from a _Sanctus_ of a mass is needed, the _Pleni sunt_ should be an isolated individual file. When creating this file use the following conventions, so the appropriate meta data is added to the resulting _.xml_ file:
+ Title: _Dodecachordon_
+ Subtitle: _Mass - Sanctus - Pleni sunt_ (for example)
+ Composer: _Josquin des Prez_
+ Description (or another logical field): _Hypodorian_ (associated mode, if any)

### Non-Existing Polyphonic Examples

When creating a polyphonic example from the Miller book use the same conventions as described above under _Existing Polyphonic Examples_. 

## Notes

<a name="note-1">[1]</a>: Book 1 is found in Clement Miller's English translation volume 1, ranging from pp. 37 to 103; book 2, also found in volume 1 of Miller's translation, ranges from pp. 103 to 223; and book 3, found in volume 2 of Miller's translation, ranges from pp. 224 to 285. Clement Miller also adds an appendix to volume 2 of his translation that includes the polyphonic music examples ranging from pp. 246 to 548.


