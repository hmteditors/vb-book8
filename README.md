# Venetus B, book 8

Edition of *Iliad* 8 with *scholia* in the Venetus B MS.

## Current coverage



- Book 8:  8.1-8.70 complete draft; **lacking** 8.71-8.565 beginning on page 104v (see [ICT](http://www.homermultitext.org/ict2/?urn=urn:cite2:hmt:vbbifolio.v1:vb_104v_105r))

## How to validate


#### Starting from the command line

From a terminal open in this directory, you can start the validating dashboard with:

    julia --project=dashboard dashboard/validatordashboard.jl


(Note that in VS Code, you can use `New Terminal` from the `Terminal` menu to open a terminal in the directory you're editing.)

#### Viewing the dashboard

Open a browser to `http://localhost:8051`.

1. Use the `Load/update data` button to load or reload the current data in your repository.  
2. Select a page from the drop-down menu.  If you have errors or incomplete work, repeat these two steps after making your corrections.


## URNs: quick reference


- **texts**
    - scholia: `urn:cts:greekLit:tlg5026.msB.hmt:` with passage identifiers like `9.115r_1` for *book/scholion*
    - *Iliad*:  `urn:cts:greekLit:tlg0012.tlg001.msB:`  with identifiers like `9.1` for *book/line*
    - *metrical summaries*: `urn:cts:greekLit:tlg7000.tlg001.msB:`
- **MS pages**: collection `urn:cite2:hmt:msB.v1:` with identifiers like `1r` identifying a single *page*
- **images**: collection `urn:cite2:hmt:vbbifolio.v1:` with identifiers like `vb_114v_115r` identifying images of *bifolio spreads*




 ## Previous editions


 A complete edition of book 8 was published by Wilhelm Dindorf in volume 3 of his *Scholia Graeca in Iliadem* series (available as pdf [here](http://www.homermultitext.org/pd-pdfs/Dindorf-v3.pdf)).

Hartmut Erbse published a selection of the scholia in his *Scholia Vetera in Iliadem*.  The text of Erbse's edition has been made available by the WordHoard project.  The book 8 selections are included in the `reference` directory in a readable HTML format.