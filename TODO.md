For 0.12
--------

  - Better support for assembly mapping across fragmented alignments [DONE]
  - BAM rendering speedups [DONE]
  - More efficient BAM parsing?
  - Use web-workers for fetching [DONE]
  - Small BED/WIG support. [DONE]
  - Bulk addition of local files. [DONE]
  - Independent scrolling of tier-holder and tool panels [DONE]
  - Support for full screen mode [DONE]
  - Pinning tracks.
  - Keep selected track visible when track heights change (?)
  - Support for non-positional annotations
  - Search-by-name (or description) in track-adder.
  - Export track configuration for current browser state.
  - Documentation of plugin APIs

For 0.13
--------

  - Feature selection
  - Replace feature popups with inspector-like interface
  - Apply track-edit operations to multiple tracks at once.
  - Typeahead for search-by-gene-ID
  - Animate when leaping/toggling.
  - Overlay function plugin API
  - Clean up featureSource creation (make async?)

For 1.0
--------

  - Undo/redo.  
  - History of recently-viewed tracks.
  - Out-to-chromosome zooming
    + Probably needs a better set of semantic zoom hints in the
      stylesheet language.
  - Better zoom control
    + Show all toggle levels.
    + Some kind of feedback for toggling.
  - Try to preserve layout when expanding/collapsing variants.
  - More Tabix payloads (GFF/GTF)
  - Chromosome overviews.

Future
-------------

 - New stylesheet language
 - More incremental data fetching.
 - Construct as a web-component (polymer?)
 - Better tiling in renderer.
 - Better ways of loading alignments (HAL?)

Nice to have
------------

 - Tier groups
     + Should yZoom together.
     + Other configuration stuff?
     + Drag together when re-ordering????
 - Dedicated configuration/persistance language?
 - Distance between a pair of features.
 - Multiple configurations/session switching/etc?
- RDF/FALDO support?

Blue sky
--------
    
 - MultiContigView equivalent?
 - Client-side analysis of quantitative tracks.
 - Better presentation of gene models in the light of expression data.