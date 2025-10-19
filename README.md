# Encoding-project-portfolio
This project is set up as part of the Master 2 TNAH course "Modeling Humanities Data with TEI-XML : Scholarly Editing and Manuscript Cataloguing in the Digital Age" It's purpose is to familiarize us not only with the collaboration tool Github, but also with encoding techniques such as TEI, in order to create a schematization of historical documents as structured XML files linked and validated by a DTD. Based on the course and the TEI guidelines, we have produced the following work.

We have chosen as the document corpus " Les lettres ardentes de Napoléon à Joséphine, 1796-1797" from BEER editions, available on the BnF catalog "GALLICA". Our work is based on three source files: the front cover, pages 9-10. The prohject aims to schematize in a structured way the skeleton of the letters found in the documents and to identify elements such as dates, sender, recipient, and the body of each letter. It includes a README.md file, three source documents, an XML file, and a DTD file. From technical perspective, the DTD defines the allowed elements and attributes, ensuring the standardization of the XML file structure.

In XML structure, for example, we will use : <recipient> (for recipient), <sender> (for sender), <date> (for the dates of the letters), and <body> (for the body of the text), with <p> for paragraphs inside the body. All of this is validated by the DTD. Each <letter> element in yhe XML template corresponds to one of the source files mentioned above.

This organization of the project is allows for an analysis of historical documents with the rigor of encoding and familiarizes us with Github. It also aims to develop future skills, such as adding metadata and additional annotations. 

Sources : https://gallica.bnf.fr/ark:/12148/bpt6k6304095n.texteImage
DTD (Document Type Description); XML (Extensible Markup Language); XML (Extensible Markup Language).
