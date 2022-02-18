# dec-diagrams

When DEC manuals are transcribed to HTML on VT100.net,
I sometimes choose to clean up the scanned diagrams by
creating SVG versions. This repository includes diagrams
created in Inkscape and diagrams generated programmatically
with some bits of Perl.

These diagrams were, for the most part, present in DEC manuals produced between about 1978
and 1988. They were catalogued with a drawing number of the form MA-ssss-dd, where 'ssss'
is generally 4 digits and possibly a letter, and '-dd', where present is either two digits
that seem to be the year the diagram was created, again possibly followed by a letter.

In both cases, the letters refer to variants of the diagram. The "base" diagram without
variant letters may not appear in any publication.
Variants might appear for a number of reasons:

* Slightly different legend text
* Country-specific text on a diagram that is largely similar to the base, which
appears particularly appropriate to character set and keyboard layout diagrams
* Corrections to a diagram in an earlier version of a document.

What _doesn't_ cause a new number to be generated for a diagram is a difference in
appearance to do with how the diagram is coloured overall, or how particular sections
might be highlighted, which I refer to as the diagram's _treatment_.

When drawing an SVG version of these diagrams, I have attempted to move as many
aspects of the diagram's treatment as possible into an embedded style element.
I am interested in producing diagrams that work in dark or light mode, but this
is a work in progress; for the most part, diagrams are light mode (i.e. as they
appeared on paper.)
