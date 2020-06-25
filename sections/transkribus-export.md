### Transkribus Export functions

File format

* Page XML [https://github.com/PRImA-Research-Lab/PAGE-XML](specs) as base file format
* bundled in METS containers
* tags saved in @custom="{json-stuff with offsets}"

+++

### Export file formats

* .docx exports tags in MSO index entries (?)
* PDF with/out text|images
* TEI export
    * does not know semantics of page
    * post-processing required
    * customize https://github.com/dariok/page2tei

+++

### API

* https://transkribus.eu/wiki/index.php/REST_Interface
* https://github.com/Transkribus/TranskribusPyClient
* https://gist.github.com/psychemedia/e2d3bc46e7a6e069323e2490a2d05a09 sample notebook
