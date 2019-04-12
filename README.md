# PicassoMetaInformation
Implementation for ConML MetaInformation proposal and real cases with Digital Humanitites data (Picasso's artworks)

We have considered 2 scenarios for illustrating MetaInformation:

- Scenario 3: Integration scenario: Metainformation refers to different information sources.
- Scenario 4: Metainformation is used for generating new knowledge based on the imported sources.


This repository contains an specific implementation for the validation of the conceptual proposal for MetaInformation in Digital Humanities repositories as part of the ConML modelling language. Each .rar. includes: 
- a .db sqlite version 3 file with a relation database for each scenario described above. We recomend SQLite Studio (https://sqlitestudio.pl/index.rvt) for managing the files.
- SQL files with SQL queries for exempliying how the systems employes metainformation.

For more information about implementation details, please see [1] and [2].
- [1] C. Gonzalez-Perez, Information Modelling for Archaeology and Anthropology: Software Engineering. Principles for Cultural Heritage. Springer, 2018.
- [2] C. Gonzalez-Perez, P. Martin-Rodilla, An Alternative Approach to Metainformation Conceptualisation and Use, in: H.C. Mayr, G. Guizzardi, H. Ma, O. Pastor (Eds.) Conceptual Modeling: 36th International Conference, ER 2017, Valencia, Spain, November 6–9, 2017, Proceedings, Springer International Publishing, Cham, 2017, pp. 92-105.


Attribution: Data sources employed in the implementation:

- MET Metropolitan Museum of Art's CC0 select datasets. https://github.com/metmuseum/openaccess, 2019.
- MoMA The Museum of Modern Art (MoMA) Collection, https://github.com/MuseumofModernArt/collection, 2019.
- Europeana project, web site at http://www.europeana.eu/, API's at https://pro.europeana.eu/resources/apis

- ConML modelling language, Copyright © 2010-2019 Instituto de Ciencias del Patrimonio (Incipit), Consejo Superior de Investigaciones Científicas (CSIC): http://www.conml.org/
