# Introduction

SDARTS is a protocol for metasearching over document collections. You may consider using SDARTS if:

* You want to search (one or multiple) text or XML collections that you have from a single search interface.
* You want to search remote document collections that export their metadata under the Open Archives protocol.
* You want to search multiple web-based document collections from one, single search interface.

-----

SDARTS was developed as part of [PERSIVAL](http://persival.cs.columbia.edu/) (an NSF Digital Library Initiative--Phase 2 project) at the [Computer Science Department](http://www.cs.columbia.edu/) of [Columbia University](http://www.columbia.edu/).

SDARTS is a hybrid of two previously existing protocols, [STARTS](http://www-db.stanford.edu/~gravano/starts_home.html) and [SDLIP](http://www-diglib.stanford.edu/~testbed/doc2/SDLIP/). SDARTS is essentially an instantiation of the SDLIP protocol with a richer set of metadata, which can be effectively used for building sophisticated metasearchers. SDARTS makes a wide variety of collections with heterogeneous interfaces accessible under one uniform interface.

The SDARTS toolkit provides ready-to-use, configurable wrappers. They can be used directly for wrapping locally available  text and XML collections, and for wrapping web-accessible databases.

The SDARTS toolkit also contains two optional sets of applications: The [OAI SDARTS Cooperative Suite](http://sdarts.cs.columbia.edu/documentation/oai-sdarts.html), which can makes SDARTS OAI-compliant and enables SDARTS to access OAI-compliant collections. We provide the [SDARTS Automatic Content Summary Extraction](http://sdarts.cs.columbia.edu/documentation/sdarts-cse.html) for remote web databases, which extracts statistics about the vocabulary and the word frequencies of web databases over which SDARTS does not have immediate access.

-----

# Documentation


## Installation Instructions

* [SDARTS Server](http://sdarts.cs.columbia.edu/documentation/sdarts-server.html)
* [SDARTS Web Client](http://sdarts.cs.columbia.edu/documentation/sdarts-webclient.html)
* [DBSelection module](http://sdarts.cs.columbia.edu/documentation/sdarts-webclient-dbsel.html)
* [SDARTS Automatic Content Summary Extraction](http://sdarts.cs.columbia.edu/documentation/sdarts-cse.html)
* [SDARTS Web Client (with Collection Selection)](http://sdarts.cs.columbia.edu/documentation/oai-sdarts.html)
* [OAI-SDARTS Suite]

## Source code documentation

* [SDARTS documentation (in javadoc format)](http://sdarts.cs.columbia.edu/javadocs/index.html)

## Wrapper Configuration

SDARTS supports three types of collections: text "doc" wrapper, xml "doc" wrapper, and "www" wrapper, which is for local plain text documents, local xml documents and remote web-based collections fronted by CGI-based search engine, respectively.

* [Local Text Collections](http://sdarts.cs.columbia.edu/documentation/wrapper_text.html)
* [Local XML Collections](http://sdarts.cs.columbia.edu/documentation/wrapper_xml.html)
* [Remote Web Collections](http://sdarts.cs.columbia.edu/documentation/wrapper_www.html)

-----

# Download

## SDARTS Server Executables and Source

* [SDARTS Server 3.0](http://sdarts.cs.columbia.edu/download/sdarts.zip) (last updated on: Apr 2004)
* [SDARTS SOAP API](http://sdarts.cs.columbia.edu/soapsdarts_server.zip) (last updated on: Apr 2004)
* Optional Component:
    * [OAI Harvester 2.0 for SDARTS](http://sdarts.cs.columbia.edu/download/oaistart.zip) (last updated on: May 2003)
    * [SDARTS Indexer and Database Selection](http://sdarts.cs.columbia.edu/download/sdartsindex.zip) (last updated on: May 2004)

## SDARTS Clients Executables and Source

* [SDARTS Web Client 3.0](http://sdarts.cs.columbia.edu/download/sdartsclient.zip) (last updated on: April 2004)
* [SOAP API client Java classes](http://sdarts.cs.columbia.edu/download/sdartsclient.zip) (last updated on: April 2004)

## Sample Local Document Collections

(Note: These are the document collections themselves; the wrapping files are in the distribution)

* 20groups [(.tar.gz)](http://sdarts.cs.columbia.edu/download/collections/20groups.tar.gz) [(.zip)](http://sdarts.cs.columbia.edu/download/collections/20groups.zip) (2,000 newsgroup articles; free text with structured headers)
* Aides [(.tar.gz)](http://sdarts.cs.columbia.edu/download/collections/aides.tar.gz) [(.zip)](http://sdarts.cs.columbia.edu/download/collections/aides.zip) (66 XML documents)

-----

# SDARTS API

The SDARTS API provides a way to query the collections indexed by an SDARTS server directly from within an application. The SDARTS API is a web service over SOAP, and the WSDL description of the service is provided, so the developers can use the API using their favorite language.

To use the SDARTS API, developers can either:

* Download the [WSDL](http://sdarts.cs.columbia.edu:8080/axis/services/SdartsSearchService?wsdl) description of the service (and use for example [SOAP::Lite](http://www.soaplite.com/) for Perl, or Visual Studio .NET, or any other language that supports web services), or

* Download the necessary proxy files for Java from the "[Download](http://sdarts.cs.columbia.edu/download.html)" section.

-----

# Publications and Presentations

## Publications

* [Distributed Search over the Hidden-Web: Hierarchical Database Sampling and Selection](http://www.cs.columbia.edu/~pirot/publications/vldb2002.pdf),
  Panagiotis G. Ipeirotis and Luis Gravano,
  in Proceedings of the 28th International Conference on Very Large Data Bases (VLDB 2002), 2002.
* [Extending SDARTS: Extracting Metadata from Web Databases and Interfacing with the Open Archives Initiative](http://www.cs.columbia.edu/~pirot/publications/jcdl02.pdf),
  Panagiotis G. Ipeirotis, Tom Barry, and Luis Gravano,
  in Proceedings of the Second ACM+IEEE Joint Conference on Digital Libraries (JCDL 2002)
* [SDLIP + STARTS = SDARTS: A Protocol and Toolkit for Metasearching](http://www.cs.columbia.edu/~pirot/publications/jcdl01.pdf),
  Noah Green, Panagiotis G. Ipeirotis, and Luis Gravano,
  in Proceedings of the First ACM+IEEE Joint Conference on Digital Libraries (JCDL 2001)

## Presentations

* [Distributed Search over the Hidden WebHierarchical Database Sampling and Selection (.ppt)](http://sdarts.cs.columbia.edu/publications/sdarts-vldb2002.ppt) (VLDB 2002)
* [Extending SDARTS: Extracting Metadata from Web Databasesnd Interfacing with Open Archives Initiative (.ppt)](http://sdarts.cs.columbia.edu/publications/sdarts-jcdl2002.ppt) (JCDL 2002)
* [SDLIP + STARTS = SDARTS: Protocol and Toolkit for Metasearching (.ppt)](http://sdarts.cs.columbia.edu/publications/sdarts-jcdl2001.ppt) (JCDL 2001)
* [SDARTS - A Metasearching Protocol and Architecture for Digital Libraries (.ppt)](http://sdarts.cs.columbia.edu/publications/sdarts-dli2meeting.ppt) (internal DLI2-PERSIVAL meeting at Columbia)




-----

# People


* [Jiangcheng Bao](mailto:jb605@cs.columbia.edu)
* [Tom Barry](mailto:tjbarry@earthlink.net)
* [Alexander Besidski](mailto:ab2012@columbia.edu)
* [Yan Besidski](mailto:yb2005@columbia.edu)
* [Luis Gravano](mailto:gravano@cs.columbia.edu)
* [Noah Green](mailto:ngreen@cs.columbia.edu)
* [Panagiotis G. Ipeirotis (contact)](mailto:pirot@cs.columbia.edu)
* [Boyle M Lee](mailto:bml13@columbia.edu)
* [Mike Medric](mailto:mfm18@columbia.edu)
* [Sergey Sigelman](mailto:ss1792@cs.columbia.edu)

