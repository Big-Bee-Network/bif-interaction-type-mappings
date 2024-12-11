[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/Big-Bee-Network/bif-interaction-type-mappings/)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/Big-Bee-Network/bif-interaction-type-mappings)

# BIF Interaction Type Mappings 

Millions of species interaction claims are describe in datasets registered with  global and national biodiversity infrastructures like Global Biodversity Information Facility (GBIF, https://gbif.org) and Integrated Digitized Biocollections (iDigBio, https://idigbio.org). 

This dataset is compiled by José Augusto Salim using [Elton](https://globalbioticinteractions.org/elton), [Preston](https://preston.guoda.bio), a version of the [GIB](https://linker.bio/#use-case-3-studying-pine-pests-caused-by-weevils-curculionoidea) dataset, and workflows described in [Biodiversity Interaction Finder (BIF, pronounced Bifi)](https://github.com/big-bee-network/bif) and includes a manually curated list of terms used to describe species interactions in these datasets. 

This is a work in progress.

# Cite as 

José Augusto Salim et al. 2024. BIF Interaction Type Mappings https://github.com/big-bee-network/bif-interaction-type-mappings hash://sha256/8ef13bf5d333445f94683a952fca2fe9e830af536898b0dfc99c73c634a98247

# Content 

 | name | description | content id 
 | [```data/```](./data/) | versioned [Preston](https://preston.guoda.bio) package of this dataset | [hash://sha256/8ef13bf5d333445f94683a952fca2fe9e830af536898b0dfc99c73c634a98247](https://linker.bio/hash://sha256/8ef13bf5d333445f94683a952fca2fe9e830af536898b0dfc99c73c634a98247)
 | [interaction_types_mapping.csv](./interaction_types_mapping.csv) | latest version of mapping in comma-separated values | [hash://sha256/f0a0837ee4949eac8105bef40825afdfda4b12a84c09086f7c03783822e810e2](https://linker.bio/hash://sha256/f0a0837ee4949eac8105bef40825afdfda4b12a84c09086f7c03783822e810e2) 
 | [interaction_types_mapping.tsv](./interaction_types_mapping.tsv) | latest version of mapping in tab-separated values | [hash://sha256/a2538e6e3487cf2c16a032a5d03eb8b145b02ef85dc8ad2da2bbd1d22004ce70](https://linker.bio/hash://sha256/a2538e6e3487cf2c16a032a5d03eb8b145b02ef85dc8ad2da2bbd1d22004ce70) |

## Preview 

The first 5 lines 



# Methods

## Tracking

```
preston track 'https://docs.google.com/spreadsheets/d/1HSqMhe0e7nmwf3rpgfIp0utSl4GL8FRCAdj_oeq7BDQ/edit?gid=0#gid=0'
preston head | preston cat | grep hasVersion | grep tsv | preston cat > interaction_types_mapping.tsv
preston head | preston cat | grep hasVersion | grep csv | preston cat > interaction_types_mapping.csv
```

## Versions

```bash
preston history
```

yielded

```
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://purl.org/pav/hasVersion> <hash://sha256/8ef13bf5d333445f94683a952fca2fe9e830af536898b0dfc99c73c634a98247> .
```

with ```preston head```

producing the signature of the latest version ```hash://sha256/8ef13bf5d333445f94683a952fca2fe9e830af536898b0dfc99c73c634a98247```.

## Aliases

The content aliases (aka names associated with content), are:

```bash
cat\
 <(echo -e "alias\trelation\tcontent id\tactivity uuid")\
 <(preston alias -l tsv)\
 | mlr --itsvlite --omd cat
```

| alias | relation | content id | activity uuid |
| --- | --- | --- | --- |
| https://docs.google.com/spreadsheets/d/1HSqMhe0e7nmwf3rpgfIp0utSl4GL8FRCAdj_oeq7BDQ/edit?gid=0#gid=0 | http://purl.org/pav/hasVersion | hash://sha256/ac738f063270f99f63df6bc038b2c3e60145e68a526f70c4665201e73da3b722 | urn:uuid:c90ebdb8-1325-4400-b0d8-bea4482e4e0a |
| https://docs.google.com/spreadsheets/u/0/export?id=1HSqMhe0e7nmwf3rpgfIp0utSl4GL8FRCAdj_oeq7BDQ&format=xlsx | http://purl.org/pav/hasVersion | hash://sha256/b6641c2cb480583a6f1e7fe9dfc204069e8fa9a1a2115cdfc4ea8b250be7a4e5 | urn:uuid:d35f2244-8b24-474f-9d6b-6bba615036a8 |
| https://docs.google.com/spreadsheets/u/0/export?id=1HSqMhe0e7nmwf3rpgfIp0utSl4GL8FRCAdj_oeq7BDQ&format=ods | http://purl.org/pav/hasVersion | https://deeplinker.bio/.well-known/genid/2d43e768-1749-3ce0-ac6a-5bbbe9638010 | urn:uuid:1b1a505f-7858-4508-9472-4dd59fdc87a5 |
| https://docs.google.com/spreadsheets/u/0/export?id=1HSqMhe0e7nmwf3rpgfIp0utSl4GL8FRCAdj_oeq7BDQ&format=pdf | http://purl.org/pav/hasVersion | https://deeplinker.bio/.well-known/genid/8f74014a-ce4f-3e01-9dde-cf2dab16ac1d | urn:uuid:4e15c3f1-946c-4801-af70-887495375aa6 |
| https://docs.google.com/spreadsheets/u/0/export?id=1HSqMhe0e7nmwf3rpgfIp0utSl4GL8FRCAdj_oeq7BDQ&gid=0&format=csv | http://purl.org/pav/hasVersion | hash://sha256/f0a0837ee4949eac8105bef40825afdfda4b12a84c09086f7c03783822e810e2 | urn:uuid:4497ea01-0f3d-45ad-9ef1-9ea4fa74eb0c |
| https://docs.google.com/spreadsheets/u/0/export?id=1HSqMhe0e7nmwf3rpgfIp0utSl4GL8FRCAdj_oeq7BDQ&gid=0&format=tsv | http://purl.org/pav/hasVersion | hash://sha256/a2538e6e3487cf2c16a032a5d03eb8b145b02ef85dc8ad2da2bbd1d22004ce70 | urn:uuid:7c5db6fc-6f18-4235-8a2d-036c78575262 |
| https://docs.google.com/spreadsheets/u/0/export?id=1HSqMhe0e7nmwf3rpgfIp0utSl4GL8FRCAdj_oeq7BDQ&format=zip | http://purl.org/pav/hasVersion | hash://sha256/ccc4f03575c27be044486f12ad1b3ca31178d0e89d4937541ab70198cece8809 | urn:uuid:ed4ba325-058a-47da-aa0c-eae8b5253d7d |
```
