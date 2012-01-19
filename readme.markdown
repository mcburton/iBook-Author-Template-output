## What is this?

This is the "Basic" template from Apple's iBook Author app, exported to iBooks format, and then unzipped.

## What format is this?

I am not entirely certain. If someone with more EPUB foo knows please drop some knowledge on twitter -> @mcburton

Update: Looks like it is EPUB3 markup with Apple's own CSS
http://www.baldurbjarnason.com/notes/the-ibooks-textbook-format/

### Output from EpubCheck

java -jar epubceck/epubcheck-3.0b4.jar test.epub // Renamed from .ibook
Epubcheck Version 3.0b4

ERROR: test.epub: Mimetype contains wrong type (application/epub+zip expected).
Validating against EPUB version 2.0

ERROR: test.epub/mimetype: Mimetype file should contain only the string "application/epub+zip".

ERROR: test.epub/OPS/content1.xhtml(3,928): element "object" not allowed here; expected the element end-tag or element "address", "blockquote", "del", "div", "dl", "h1", "h2", "h3", "h4", "h5", "h6", "hr", "ins", "noscript", "ns:svg", "ol", "p", "pre", "script", "table" or "ul" (with xmlns:ns="http://www.w3.org/2000/svg")

ERROR: test.epub/OPS/content1.xhtml(3,3062): element "object" not allowed here; expected the element end-tag or element "address", "blockquote", "del", "div", "dl", "h1", "h2", "h3", "h4", "h5", "h6", "hr", "ins", "noscript", "ns:svg", "ol", "p", "pre", "script", "table" or "ul" (with xmlns:ns="http://www.w3.org/2000/svg")

ERROR: test.epub/OPS/content1.xhtml(3,3554): element "object" not allowed here; expected the element end-tag or element "address", "blockquote", "del", "div", "dl", "h1", "h2", "h3", "h4", "h5", "h6", "hr", "ins", "noscript", "ns:svg", "ol", "p", "pre", "script", "table" or "ul" (with xmlns:ns="http://www.w3.org/2000/svg")

ERROR: test.epub/OPS/content2.xhtml(3,6132): element "object" not allowed here; expected the element end-tag or element "address", "blockquote", "del", "div", "dl", "h1", "h2", "h3", "h4", "h5", "h6", "hr", "ins", "noscript", "ns:svg", "ol", "p", "pre", "script", "table" or "ul" (with xmlns:ns="http://www.w3.org/2000/svg")

ERROR: test.epub/OPS/content2.xhtml(3,7732): element "object" not allowed here; expected the element end-tag or element "address", "blockquote", "del", "div", "dl", "h1", "h2", "h3", "h4", "h5", "h6", "hr", "ins", "noscript", "ns:svg", "ol", "p", "pre", "script", "table" or "ul" (with xmlns:ns="http://www.w3.org/2000/svg")

ERROR: test.epub/OPS/assets/tocConfig-1.xhtml(3,814): element "object" not allowed here; expected the element end-tag or element "address", "blockquote", "del", "div", "dl", "h1", "h2", "h3", "h4", "h5", "h6", "hr", "ins", "noscript", "ns:svg", "ol", "p", "pre", "script", "table" or "ul" (with xmlns:ns="http://www.w3.org/2000/svg")

ERROR: test.epub/OPS/assets/tocConfig-1.xhtml(3,1286): element "object" not allowed here; expected the element end-tag or element "address", "blockquote", "del", "div", "dl", "h1", "h2", "h3", "h4", "h5", "h6", "hr", "ins", "noscript", "ns:svg", "ol", "p", "pre", "script", "table" or "ul" (with xmlns:ns="http://www.w3.org/2000/svg")

ERROR: test.epub/OPS/assets/tocConfig-1.xhtml(3,1657): element "object" not allowed here; expected the element end-tag or element "address", "blockquote", "del", "div", "dl", "h1", "h2", "h3", "h4", "h5", "h6", "hr", "ins", "noscript", "ns:svg", "ol", "p", "pre", "script", "table" or "ul" (with xmlns:ns="http://www.w3.org/2000/svg")

Check finished with warnings or errors!
