# Extract 10x web summary errors 
The goal of this program is to extract 10x warnings and errors into a table in a text file.  Specifically this program has been written to deal with to parse through cellranger multi runs specifically with hashed together samples and vdj sequencing.

### Installation
----------------

```bash
git clone https://github.com/lwhitmore/Extract10xCellRangerErrors.git
cd Extract10xCellRangerErrors
python setup.py install
```

### Running Extract10xCellRangerErrors
--------------------------------------
```bash
extractwarninganderrors -indir="/directory/where/multiple/CellrangerMulti/runs/are/located/" -outdir="./"
```

### Output files
----------------
Output files

* libraryerrortable.txt - table of errors from pooled sample libraries 
* samplerrortable.txt - table of errors for individual samples 
