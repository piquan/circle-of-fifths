# Circle of Fifths

This is a little webpage I wrote back in 2011. It shows the [circle of fifths](https://en.wikipedia.org/wiki/Circle_of_fifths), a tool for Western musical composition and analysis. The circle of fifths is to musicians much what the [periodic table](https://ptable.com) is to chemists: a way to organize and consider the relationships between different notes. The SVG file is interactive, self-contained, and hand-written.

You can see this at http://piquan.github.io/circle-of-fifths

## Selecting a Key

By default, the circle is aligned for C major.  You can select a different key in one or two clicks.

First, click on a tonic: C, G, B♭, whatever.  The circle will spin to put the tonic at the top, in yellow.

Next, click on a [mode](https://en.wikipedia.org/wiki/Mode_(music)).  The default is Ionian (major), and you may also be interested in Aeolian (natural minor).  99% of users won’t need the other modes.

Harmonic and melodic minor modes aren’t supported; the circle of fifths doesn’t apply to those as neatly.

When clicking on the mode, be sure to click on the text (the cursor will become a +); clicking on the background will take you to the Wikipedia page about musical modes.

For using the [minor pentatonic scale](https://en.wikipedia.org/wiki/Pentatonic_scale), select the Ionian mode.  This is a bug; I’ll probably change that in a future revision.

## Reading the Circle

### In-key notes (major, minor, etc): red arc

The notes in the selected key are surrounded by the flame-orange arc, the one with the modes listed.  You can ignore the mode names when you’re looking at this.

### Relative major / minor key

With the Ionian (major) mode selected, look under the Aeolian (natural minor) listing to find the relative minor.  Similarly, you can select an Aeolian mode and look under Ionian to find its relative major.

### Pentatonic and blues keys: orange and blue arcs

The notes in the most common non-heptatonic scales (such as [pentatonic scales](https://en.wikipedia.org/wiki/Pentatonic_scale)) are marked:

* The major pentatonic scale is surrounded by the melon-yellow arc.
* The minor pentatonic scale is surrounded by the blue arc.
* The [blues scale](https://en.wikipedia.org/wiki/Blues_scale) (specifically, hexatonic blues scale) consists of the minor pentatonic scale, plus the [blue note](https://en.wikipedia.org/wiki/Blue_note) marked by the blue dot.

### Chords: green arrow

The triad chords [triads](https://en.wikipedia.org/wiki/Triad_(music)) in the chosen key are surrounded by a green arc with an arrow.

In the [Roman numeral chord names](https://en.wikipedia.org/wiki/Roman_numeral_analysis), upper case letters indicate a major triad, lower case indicates a minor triad, and a superscript “o” indicates a diminished triad (minor flattened fifth, not diminished seventh).

The [circle progression](https://en.wikipedia.org/wiki/Circle_progression) of chords in the key is marked with the green arrow.  The arrow points in the direction of the progression.

The most commonly-used chords in a major key are shown with a darker background; for instance, 
the [ii-V-I turnaround](https://en.wikipedia.org/wiki/Ii%E2%80%93V%E2%80%93I_progression) is extremely common in Western music, and is shown at the end of the arrow with the darkest background.

The indicators will change based on the mode selected, so that I (or i) is always the tonic.  For instance, in C major, the circle progression lists G-C-F as V-I-IV, but in C minor these are v-i-iv, and in A minor are VII-III-VI.

The previous paragraph notwithstanding, minor and modal progressions aren’t currently ideal: you’ll get chord symbols that match the mode, but there are no leading ♭ or ♯ signs (as some textbooks prefer), the darkened part of the circle stays towards the relative major, and the arrow is arguably not very meaningful.

This part of the tool is limited to triad chords, and only those that are in a diatonic scale.  Diminished sevenths and augmented chords are great, but the circle of fifths is the wrong tool to analyze them.
