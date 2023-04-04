<div>
   <div id="main">
      <h1>Corpus</h1>
      <p>This corpus includes Ground Truth data compiled considering the following feature:</p>
      <ol>
         <li>distinction of the selected print type or combinations</li>
         <li>compelexity of the layout (columns, footnotes,...)</li>
      </ol>
      <p>The data are also divided according to the time of creation or production.</p>
      <h2>Creation</h2>
      <p>The data were created according to the OCR-D Ground Truth Guideline (https://ocr-d.de/en/gt-guidelines/trans/).</p>
      <h2>Repositories</h2>
      <div id="data">
## Gothic/Blackletter 

### simple
- https://github.com/tboenig/16_frak_simple
- https://github.com/tboenig/17_frak_simple
- https://github.com/tboenig/18_frak_simple
- https://github.com/tboenig/19_frak_simple

### complex
- https://github.com/tboenig/16_frak_complex
- https://github.com/tboenig/17_frak_complex
- https://github.com/tboenig/18_frak_complex


## Antiqua

### simple
- https://github.com/tboenig/16_ant_simple
- https://github.com/tboenig/18_ant_simple

### complex
- https://github.com/tboenig/16_ant_complex
- https://github.com/tboenig/19_ant_simple


## FontMix (Antiqua and Blackletter)
- https://github.com/tboenig/17_fontmix_simple
- https://github.com/tboenig/18_fontmix_complex

</div>
   </div>
   <div>
      <h1>Analyzed collection</h1>
      <p>The GT data has been labeled. The labeling is based on an ontology defined by the Pattern Recognition 
                    and Image Analysis Research Lab (PRImA-Research-Lab) at the University of Salford. The labeling metadata 
                    is created for each available page. The following labeling metadata is available for the different collections.</p>
      <p>see: gt-labelling : semantic-labelling OCR ground truth data (https://github.com/OCR-D/gt-labelling)</p>
      <div>
         <h2>FontMix (Antiqua and Blackletter)</h2>
         <div>
            <h3>simple</h3>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/layoutAnalysis</summary>
               <p>In computer vision, document layout analysis is the process of identifying and categorizing the regions of interest in the scanned image of a text document. A reading system requires the segmentation of text zones from non-textual ones and the arrangement in their correct reading order.

Examples:
Page layout analysis (segmentation into regions, classification into text, graphic, table etc.)

Related:
"OCR": Often used as a synonym for layout analysis and text recognition, but strictly only the text recognition component.</p>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/ocr</summary>
               <p/>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/text</summary>
               <p>Translation of any kind of depicted symbols to machine readable format

Examples:
OCR
Mathematical equation recognition

Related:
Text processing (separate category)
Table recognition
Map reading</p>
            </details>
            <details>
               <summary>condition/acquisition/method-flaws/imaging/uneven-illumination</summary>
               <p>Uneven illumination leading to brightness or contrast variations</p>
            </details>
            <details>
               <summary>condition/production-related/document-characteristics/low-contrast</summary>
               <p>The contrast bwtween the paper and the page content is very low</p>
            </details>
            <details>
               <summary>condition/production-related/document-faults/ink-from-facing</summary>
               <p>Ink from facing page was transferred to this page</p>
            </details>
            <details>
               <summary>condition/wear/additions/informative/annotations</summary>
               <p>Annotations regarding the content</p>
            </details>
            <details>
               <summary>content-encoding/structured</summary>
               <p>E.g. XML</p>
            </details>
            <details>
               <summary>content-type/corpus</summary>
               <p>
Corpus: a collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject.

Examples:
A text corpus,
An image database</p>
            </details>
            <details>
               <summary>contentOfInterest/visual/graphical</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/graphical/separator</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/text</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/running-titles</summary>
               <p>Titles repeated each page</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/drop-caps</summary>
               <p>Drap capitals (large capitals at beginning of paragraph)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/font-sizes</summary>
               <p>More than one font size used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/typefaces</summary>
               <p>More than one typeface used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/antiqua</summary>
               <p>Antiqua font (more modern)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/blackletter</summary>
               <p>Blackletter, gothic, Fraktur</p>
            </details>
            <details>
               <summary>data-attributes/language/mixed</summary>
               <p>More than one language used</p>
            </details>
            <details>
               <summary>granularity/logical/document-related/paragraph</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/page</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/region</summary>
               <p>Region, zone, block</p>
            </details>
            <details>
               <summary>granularity/physical/document-related/text-line</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/word</summary>
               <p>Word or partial word, if separated by line break, for example</p>
            </details>
            <details>
               <summary>platform/platform-independent</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
         </div>
         <div>
            <h3>complex</h3>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/layoutAnalysis</summary>
               <p>In computer vision, document layout analysis is the process of identifying and categorizing the regions of interest in the scanned image of a text document. A reading system requires the segmentation of text zones from non-textual ones and the arrangement in their correct reading order.

Examples:
Page layout analysis (segmentation into regions, classification into text, graphic, table etc.)

Related:
"OCR": Often used as a synonym for layout analysis and text recognition, but strictly only the text recognition component.</p>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/ocr</summary>
               <p/>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/text</summary>
               <p>Translation of any kind of depicted symbols to machine readable format

Examples:
OCR
Mathematical equation recognition

Related:
Text processing (separate category)
Table recognition
Map reading</p>
            </details>
            <details>
               <summary>condition/acquisition/content-or-background/included-objects/preceeding-or-proceeding</summary>
               <p>Part of preceeding or succeeding object included (e.g. other page)</p>
            </details>
            <details>
               <summary>condition/acquisition/geometric/page-curl</summary>
               <p>Visible page curl (e.g. book scanning)</p>
            </details>
            <details>
               <summary>condition/acquisition/geometric/perspective-distortions</summary>
               <p>Perspective distortions (e.g. due to camera-based acquisition)</p>
            </details>
            <details>
               <summary>condition/acquisition/method-flaws/imaging/uneven-illumination</summary>
               <p>Uneven illumination leading to brightness or contrast variations</p>
            </details>
            <details>
               <summary>condition/production-related/document-characteristics/low-contrast</summary>
               <p>The contrast bwtween the paper and the page content is very low</p>
            </details>
            <details>
               <summary>condition/production-related/document-faults/ink-from-facing</summary>
               <p>Ink from facing page was transferred to this page</p>
            </details>
            <details>
               <summary>content-encoding/structured</summary>
               <p>E.g. XML</p>
            </details>
            <details>
               <summary>content-type/corpus</summary>
               <p>
Corpus: a collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject.

Examples:
A text corpus,
An image database</p>
            </details>
            <details>
               <summary>contentOfInterest/visual/graphical/separator</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/text</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/footnote-continued</summary>
               <p/>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/footnotes</summary>
               <p>Footnotes at bottom of page</p>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/running-titles</summary>
               <p>Titles repeated each page</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/drop-caps</summary>
               <p>Drap capitals (large capitals at beginning of paragraph)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/font-sizes</summary>
               <p>More than one font size used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/typefaces</summary>
               <p>More than one typeface used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/antiqua</summary>
               <p>Antiqua font (more modern)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/blackletter</summary>
               <p>Blackletter, gothic, Fraktur</p>
            </details>
            <details>
               <summary>data-attributes/language/mixed</summary>
               <p>More than one language used</p>
            </details>
            <details>
               <summary>granularity/logical/document-related/paragraph</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/page</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/region</summary>
               <p>Region, zone, block</p>
            </details>
            <details>
               <summary>granularity/physical/document-related/text-line</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/word</summary>
               <p>Word or partial word, if separated by line break, for example</p>
            </details>
            <details>
               <summary>platform/platform-independent</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
         </div>
      </div>
      <div>
         <h2>Gothic/Blackletter</h2>
         <div>
            <h3>simple</h3>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/layoutAnalysis</summary>
               <p>In computer vision, document layout analysis is the process of identifying and categorizing the regions of interest in the scanned image of a text document. A reading system requires the segmentation of text zones from non-textual ones and the arrangement in their correct reading order.

Examples:
Page layout analysis (segmentation into regions, classification into text, graphic, table etc.)

Related:
"OCR": Often used as a synonym for layout analysis and text recognition, but strictly only the text recognition component.</p>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/ocr</summary>
               <p/>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/text</summary>
               <p>Translation of any kind of depicted symbols to machine readable format

Examples:
OCR
Mathematical equation recognition

Related:
Text processing (separate category)
Table recognition
Map reading</p>
            </details>
            <details>
               <summary>condition/acquisition/geometric/page-curl</summary>
               <p>Visible page curl (e.g. book scanning)</p>
            </details>
            <details>
               <summary>condition/acquisition/geometric/perspective-distortions</summary>
               <p>Perspective distortions (e.g. due to camera-based acquisition)</p>
            </details>
            <details>
               <summary>condition/ageing/warping</summary>
               <p>Arbitrary warping (e.g. due to moisture)</p>
            </details>
            <details>
               <summary>condition/production-related/document-faults/ink-from-facing</summary>
               <p>Ink from facing page was transferred to this page</p>
            </details>
            <details>
               <summary>condition/wear/additions/informative/annotations</summary>
               <p>Annotations regarding the content</p>
            </details>
            <details>
               <summary>condition/wear/medium-damage/stains</summary>
               <p>Noticeable stains on medium</p>
            </details>
            <details>
               <summary>content-encoding/structured</summary>
               <p>E.g. XML</p>
            </details>
            <details>
               <summary>content-type/corpus</summary>
               <p>
Corpus: a collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject.

Examples:
A text corpus,
An image database</p>
            </details>
            <details>
               <summary>contentOfInterest/visual/graphical</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/graphical/separator</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/text</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/running-titles</summary>
               <p>Titles repeated each page</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/drop-caps</summary>
               <p>Drap capitals (large capitals at beginning of paragraph)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/font-sizes</summary>
               <p>More than one font size used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/typefaces</summary>
               <p>More than one typeface used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/antiqua</summary>
               <p>Antiqua font (more modern)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/blackletter</summary>
               <p>Blackletter, gothic, Fraktur</p>
            </details>
            <details>
               <summary>granularity/logical/document-related/paragraph</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/page</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/region</summary>
               <p>Region, zone, block</p>
            </details>
            <details>
               <summary>granularity/physical/document-related/text-line</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/word</summary>
               <p>Word or partial word, if separated by line break, for example</p>
            </details>
            <details>
               <summary>platform/platform-independent</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
         </div>
         <div>
            <h3>complex</h3>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/layoutAnalysis</summary>
               <p>In computer vision, document layout analysis is the process of identifying and categorizing the regions of interest in the scanned image of a text document. A reading system requires the segmentation of text zones from non-textual ones and the arrangement in their correct reading order.

Examples:
Page layout analysis (segmentation into regions, classification into text, graphic, table etc.)

Related:
"OCR": Often used as a synonym for layout analysis and text recognition, but strictly only the text recognition component.</p>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/ocr</summary>
               <p/>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/text</summary>
               <p>Translation of any kind of depicted symbols to machine readable format

Examples:
OCR
Mathematical equation recognition

Related:
Text processing (separate category)
Table recognition
Map reading</p>
            </details>
            <details>
               <summary>condition/acquisition/content-or-background/included-objects/preceeding-or-proceeding</summary>
               <p>Part of preceeding or succeeding object included (e.g. other page)</p>
            </details>
            <details>
               <summary>condition/acquisition/geometric/page-curl</summary>
               <p>Visible page curl (e.g. book scanning)</p>
            </details>
            <details>
               <summary>condition/acquisition/geometric/perspective-distortions</summary>
               <p>Perspective distortions (e.g. due to camera-based acquisition)</p>
            </details>
            <details>
               <summary>condition/acquisition/method-flaws/imaging/uneven-illumination</summary>
               <p>Uneven illumination leading to brightness or contrast variations</p>
            </details>
            <details>
               <summary>condition/ageing/warping</summary>
               <p>Arbitrary warping (e.g. due to moisture)</p>
            </details>
            <details>
               <summary>condition/production-related/document-characteristics/low-contrast</summary>
               <p>The contrast bwtween the paper and the page content is very low</p>
            </details>
            <details>
               <summary>condition/production-related/document-faults/ink-from-facing</summary>
               <p>Ink from facing page was transferred to this page</p>
            </details>
            <details>
               <summary>condition/wear/additions/informative/annotations</summary>
               <p>Annotations regarding the content</p>
            </details>
            <details>
               <summary>condition/wear/additions/informative/stamps</summary>
               <p>The medium was stamped</p>
            </details>
            <details>
               <summary>condition/wear/medium-damage/stains</summary>
               <p>Noticeable stains on medium</p>
            </details>
            <details>
               <summary>content-encoding/structured</summary>
               <p>E.g. XML</p>
            </details>
            <details>
               <summary>content-type/corpus</summary>
               <p>
Corpus: a collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject.

Examples:
A text corpus,
An image database</p>
            </details>
            <details>
               <summary>contentOfInterest/visual/composite/music</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/graphical</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/graphical/separator</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/text</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/footnotes</summary>
               <p>Footnotes at bottom of page</p>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/running-titles</summary>
               <p>Titles repeated each page</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/decorations</summary>
               <p>Decorations of some kind</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/illustrations</summary>
               <p>Illustrations in content</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/illustrations/multi-colour</summary>
               <p>Multi-colour illustrations in content</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/drop-caps</summary>
               <p>Drap capitals (large capitals at beginning of paragraph)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/font-sizes</summary>
               <p>More than one font size used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/typefaces</summary>
               <p>More than one typeface used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/antiqua</summary>
               <p>Antiqua font (more modern)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/blackletter</summary>
               <p>Blackletter, gothic, Fraktur</p>
            </details>
            <details>
               <summary>data-attributes/language/mixed</summary>
               <p>More than one language used</p>
            </details>
            <details>
               <summary>granularity/logical/document-related/paragraph</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/page</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/region</summary>
               <p>Region, zone, block</p>
            </details>
            <details>
               <summary>granularity/physical/document-related/text-line</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/word</summary>
               <p>Word or partial word, if separated by line break, for example</p>
            </details>
            <details>
               <summary>platform/platform-independent</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
         </div>
      </div>
      <div>
         <h2>Antiqua</h2>
         <div>
            <h3>simple</h3>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/layoutAnalysis</summary>
               <p>In computer vision, document layout analysis is the process of identifying and categorizing the regions of interest in the scanned image of a text document. A reading system requires the segmentation of text zones from non-textual ones and the arrangement in their correct reading order.

Examples:
Page layout analysis (segmentation into regions, classification into text, graphic, table etc.)

Related:
"OCR": Often used as a synonym for layout analysis and text recognition, but strictly only the text recognition component.</p>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/ocr</summary>
               <p/>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/text</summary>
               <p>Translation of any kind of depicted symbols to machine readable format

Examples:
OCR
Mathematical equation recognition

Related:
Text processing (separate category)
Table recognition
Map reading</p>
            </details>
            <details>
               <summary>condition/production-related/document-faults/ink-from-facing</summary>
               <p>Ink from facing page was transferred to this page</p>
            </details>
            <details>
               <summary>condition/wear/medium-damage/stains</summary>
               <p>Noticeable stains on medium</p>
            </details>
            <details>
               <summary>content-encoding/structured</summary>
               <p>E.g. XML</p>
            </details>
            <details>
               <summary>content-type/corpus</summary>
               <p>
Corpus: a collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject.

Examples:
A text corpus,
An image database</p>
            </details>
            <details>
               <summary>contentOfInterest/visual/graphical/separator</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>contentOfInterest/visual/text</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/drop-caps</summary>
               <p>Drap capitals (large capitals at beginning of paragraph)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/font-sizes</summary>
               <p>More than one font size used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/antiqua</summary>
               <p>Antiqua font (more modern)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/blackletter</summary>
               <p>Blackletter, gothic, Fraktur</p>
            </details>
            <details>
               <summary>granularity/logical/document-related/paragraph</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/page</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/region</summary>
               <p>Region, zone, block</p>
            </details>
            <details>
               <summary>granularity/physical/document-related/text-line</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/word</summary>
               <p>Word or partial word, if separated by line break, for example</p>
            </details>
            <details>
               <summary>platform/platform-independent</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
         </div>
         <div>
            <h3>complex</h3>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/layoutAnalysis</summary>
               <p>In computer vision, document layout analysis is the process of identifying and categorizing the regions of interest in the scanned image of a text document. A reading system requires the segmentation of text zones from non-textual ones and the arrangement in their correct reading order.

Examples:
Page layout analysis (segmentation into regions, classification into text, graphic, table etc.)

Related:
"OCR": Often used as a synonym for layout analysis and text recognition, but strictly only the text recognition component.</p>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/ocr</summary>
               <p/>
            </details>
            <details>
               <summary>activityDomain/computing/visual/analysisRecognition/text</summary>
               <p>Translation of any kind of depicted symbols to machine readable format

Examples:
OCR
Mathematical equation recognition

Related:
Text processing (separate category)
Table recognition
Map reading</p>
            </details>
            <details>
               <summary>condition/production-related/document-faults/ink-from-facing</summary>
               <p>Ink from facing page was transferred to this page</p>
            </details>
            <details>
               <summary>condition/wear/additions/informative/annotations</summary>
               <p>Annotations regarding the content</p>
            </details>
            <details>
               <summary>condition/wear/medium-damage/stains</summary>
               <p>Noticeable stains on medium</p>
            </details>
            <details>
               <summary>content-encoding/structured</summary>
               <p>E.g. XML</p>
            </details>
            <details>
               <summary>content-type/corpus</summary>
               <p>
Corpus: a collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject.

Examples:
A text corpus,
An image database</p>
            </details>
            <details>
               <summary>contentOfInterest/visual/text</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/footnote-continued</summary>
               <p/>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/footnotes</summary>
               <p>Footnotes at bottom of page</p>
            </details>
            <details>
               <summary>data-attributes/document-related/structural/running-titles</summary>
               <p>Titles repeated each page</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/drop-caps</summary>
               <p>Drap capitals (large capitals at beginning of paragraph)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/font-sizes</summary>
               <p>More than one font size used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/multi-font/typefaces</summary>
               <p>More than one typeface used</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/antiqua</summary>
               <p>Antiqua font (more modern)</p>
            </details>
            <details>
               <summary>data-attributes/document-related/visual/text/font/typeface/blackletter</summary>
               <p>Blackletter, gothic, Fraktur</p>
            </details>
            <details>
               <summary>data-attributes/language/mixed</summary>
               <p>More than one language used</p>
            </details>
            <details>
               <summary>granularity/logical/document-related/paragraph</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/page</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/region</summary>
               <p>Region, zone, block</p>
            </details>
            <details>
               <summary>granularity/physical/document-related/text-line</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
            <details>
               <summary>granularity/physical/document-related/word</summary>
               <p>Word or partial word, if separated by line break, for example</p>
            </details>
            <details>
               <summary>platform/platform-independent</summary>
               <p>
                        Description coming soon.
                    </p>
            </details>
         </div>
      </div>
   </div>
</div>
