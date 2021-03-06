AdapterRemoval
==============

AdapterRemoval searches for and removes remnant adapter sequences from High-Throughput Sequencing (HTS) data and (optionally) trims low quality bases from the 3' end of reads following adapter removal. AdapterRemoval can analyze both single end and paired end data, and can be used to merge overlapping paired-ended reads into (longer) consensus sequences. Additionally, Additionally, AdapterRemoval can construct a consensus adapter sequence for paired-ended reads, if which this information is not available.

If you use AdapterRemoval v2, then please cite the paper:

    Schubert, Lindgreen, and Orlando (2016). AdapterRemoval v2: rapid adapter trimming, identification, and read merging. BMC Research Notes, 12;9(1):88
    http://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-016-1900-2

AdapterRemoval was originally published in Lindgreen 2012:

    Lindgreen (2012): AdapterRemoval: Easy Cleaning of Next Generation Sequencing Reads, BMC Research Notes, 5:337
    http://www.biomedcentral.com/1756-0500/5/337/


.. toctree::
    :maxdepth: 2
    :caption: Contents:

    installation
    getting_started
    examples
    manpage
    misc


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
