opencontext-eol-zooarch
=======================

Open Context GitHub Data Repository for EOL Zooarch

This repository has data relating to the the EOL computable data challenge project. 
The project involves Linked Data anotation and publication of zooarchaeological data from 
Epipaleolithic - Neolthic sites in Anatolia. For semantic annotation, Open Context 
editors linked data to the Encyclopedia of Life (http://eol.org),
UBERON (http://uberon.org), and a Zooarchaeology specific ontology maintained by Open Context
(http://opencontext.org/vocabularies/open-context-zooarch).

The directory "Integrated-Datasets" includes data aligned to various controlled vocabularies and shared conventions to
facilitate comparison across projects. Datasets include additional metadata, including chronological (date ranges),
and geospatial information as well as other annotations supplied by Open Context editors to facilitate
interoperability.

Use the Open Context URI as the "primary key" to relate these data
with data in other tables or other sources. Web URIs provide additional related data including links to data
documentation and definitions of vocabulary terms. The first row of each CSV file has the field names.

These data are published under a Creative Commons Attribution <http://creativecommons.org/licenses/by/3.0/> license
by Open Context (http://opencontext.org).

Citation and links to additional information, and notes for each data table are below:

(1) "EOL-primary-1.csv", "EOL-primary-2.csv", "EOL-primary-3.csv", "EOL-primary-4.csv", "EOL-primary-5.csv", "EOL-primary-6.csv", "EOL-primary-7.csv", "EOL-primary-8.csv" (Data in 8 files, smaller than GitHub filesize limits)
Nerissa Russell, Katheryn Twiss, Hijkle Buitenhuis, Sheelagh Frame, Lisa Yeomans, Louise Martin, Arek Marciniak, Kamilla Pawlowska, Claire Christensen, David Orton, Arzu Demirergi, Benjamin S. Arbuckle, Stephanie Meese, Levent Atıcı, Canan Çakırlar, Sarah Whitcher Kansa, Liz Henton, Banu Aydinuloglu, Alfred Galik, Adam Watson, Denise Carruthers, Ian Cameron, Rhian Mayon-White, Amanda Erwin, Vesna Dimitrijevic, Rebecca Daly, Nobs Symmons, Serkan Yeni, Chris Hills, Hijlke Buitenhuis, Leola Leblanc, Dusan Boric, Adrienne Powell (2013-08-18) "EOL Computational Data Challenge: Primary Zooarchaeology Dataset" Benjamin S. Arbuckle, David Orton, Hijkle Buitenhuis, Arek Marciniak, Levent Atici, Canan Çakırlar, Alfred Galik, Denise Carruthers, Sarah Whitcher Kansa (Eds). Open Context. <http://opencontext.org/tables/f07bce4fb08cfe926505c9e534d89a09> <http://dx.doi.org/10.6078/M75H7D6D>

(2) "EOL-metrics.csv"
Benjamin S. Arbuckle, Hijkle Buitenhuis, Nerissa Russell, Sheelagh Frame, Sarah Whitcher Kansa, Katheryn Twiss, Levent Atıcı, David Orton, Louise Martin, Kamilla Pawlowska, Arzu Demirergi, Arek Marciniak, Canan Çakırlar, Lisa Yeomans, Claire Christensen, Alfred Galik, Liz Henton, Stephanie Meese, Adam Watson, Rebecca Daly, Denise Carruthers, Serkan Yeni, Rhian Mayon-White, Ian Cameron, Nobs Symmons, Banu Aydinuloglu, Hijlke Buitenhuis, Amanda Erwin, Vesna Dimitrijevic, Chris Hills, Dusan Boric, Leola Leblanc, Adrienne Powell (2013-08-18) "EOL Computational Data Challenge: Zooarchaeology Metrics Dataset" Benjamin S. Arbuckle, David Orton, Hijkle Buitenhuis, Levent Atici, Arek Marciniak, Canan Çakırlar, Alfred Galik, Denise Carruthers, Sarah Whitcher Kansa (Eds). Open Context. <http://opencontext.org/tables/05f2db65ff4faee1290192bd9a1868ed> <http://dx.doi.org/10.6078/M71V5BW0>

(3) "EOL-summary-taxa.csv"
This is a dataset derived from the EOL-primary data <http://opencontext.org/tables/f07bce4fb08cfe926505c9e534d89a09> table. This table summarizes biological taxa for the different sites represeted in the EOL Computable Data Challenge project. For  Erbaba Höyük and Suberde Zooarchaeology data, only contexts with "All Taxa" sampled where included in this summary (see: http://opencontext.org/properties/59D0E59E-0104-4D2A-36A1-E256C35A97EC), and similarly for the Köşk Höyük Faunal Data (see: http://opencontext.org/properties/D7627CCA-5180-4D45-5953-3100251C65BF).

Please see here for more about this project:
http://alexandriaarchive.org/2012/09/25/aai-wins-eol-computable-data-challenge/
