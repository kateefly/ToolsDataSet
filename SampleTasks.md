# Sample Tasks

## Check metadata against a controlled vocabulary

### Scenario
You receive a set of records for open access ebooks, and you discover that the subjects are all uncontrolled index terms. You would like to convert them to a controlled vocabulary. 

#### Suggested Tools to Use
* [OpenRefine](http://openrefine.org/) 
* [MarcEdit](http://marcedit.reeset.net/)

#### Suggested Tools to Use
* ProjectGutenberg_Set026000 [[Excel](https://github.com/kateefly/ToolsDataSet/SampleData/ProjectGutenberg_Set026000.xslx) or [CSV](https://github.com/kateefly/ToolsDataSet/SampleData/ProjectGutenberg_Set026000.csv)]
* [ProjectGutenberg_Set02600.mrc](https://github.com/kateefly/ToolsDataSet/SampleData/ProjectGutenberg_Set02600.mrc)

## Check for spelling errors and cases where spelling does not match local standards

### Scenario

Your institution has digitized a collection of maps, which will be shared through your digital collections. You’ve created records based on the original MARC records. The metadata contains abbreviations from AACR2, which you do not use in your digital collections. 

#### Suggested Tools to Use
* [Catmandu](http://librecat.org/Catmandu/)
* [OpenRefine](http://openrefine.org/)

#### Suggested Data Sets to Use
* [LOC_OpenAccessMaps_subset.xml](https://github.com/kateefly/ToolsDataSet/SampleData/LOC_OpenAccessMaps_subset.xml)
* LOC_OpenAccessMaps_subset [[Excel](https://github.com/kateefly/ToolsDataSet/SampleData/LOC_OpenAccessMaps_subset.xlxs) or [CSV](https://github.com/kateefly/ToolsDataSet/SampleData/LOC_OpenAccessMaps_subset.csv)]

## Check that required elements are present

### Scenario

You’ve created a new set of guidelines for your metadata and created a new set of required elements and now need to check to see if they are present in your legacy metadata (hint: you can try using the requirements found the documents found at the Metadata Application Profile Clearinghouse Project as guide for this task)

#### Suggested Tools to Use
* [Metadata Breakers](https://github.com/vphill/metadata_breakers)
* [MarcEdit](http://marcedit.reeset.net/)

#### Suggested Data Sets to Use
* [uic_cul.oai.qdc.xml](https://github.com/kateefly/ToolsDataSet/SampleData/uic_cul.oai.qdc.xml)
* [nby_chicago.oai.qdc.xml](https://github.com/kateefly/ToolsDataSet/SampleData/nby_chicago.oai.qdc.xml)

## Checking that the meaning of the field remains consistent

### Scenario

You are going over a collection that were first digitized 10-15 years ago and has since had content added to it. You want to check each field to make sure that each field has remained consistent, even as new content was added.

#### Suggested Tools to Use
* [OpenRefine](http://openrefine.org/) 

#### Suggested Data Sets to Use
* [uic_cul.oai.qdc.xml](https://github.com/kateefly/ToolsDataSet/SampleData/uic_cul.oai.qdc.xml)
* [ProjectGutenberg_Set026000_CSV.csv](https://github.com/kateefly/ToolsDataSet/SampleData/ProjectGutenberg_Set026000_CSV.csv)

## Batch edit a field

### Scenario

Your institution is digitizing a collection of ebooks. You have a set of records for the originals, which you need to use to create records for the digitized version. Add and/or edit fields. Some examples of changes can be found here: https://www.oclc.org/bibformats/en/specialcataloging.html#CHDCIDAF

#### Suggested Tools to Use
* [MarcEdit](http://marcedit.reeset.net/)
* [Catmandu](http://librecat.org/Catmandu/)

#### Suggested Data Sets to Use
* [LOC_Books_subset.mrc](https://github.com/kateefly/ToolsDataSet/SampleData/LOC_Books_subset.mrc)

## Transform metadata

### Scenario
You’ve gotten a set of .mrc files from your technical services department but need to convert them to MARCXML format to submit to your local consortium.

#### Suggested Tools to Use
* [MarcEdit](http://marcedit.reeset.net/)

#### Suggested Data Sets to Use
* [ProjectGutenberg_Set026000_MARC.mrc](https://github.com/kateefly/ToolsDataSet/SampleData/ProjectGutenberg_Set026000_MARC.mrc)