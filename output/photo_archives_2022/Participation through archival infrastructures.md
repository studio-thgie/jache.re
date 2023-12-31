---
date: "2022-05-07"
tags:
	- "talk"
---
# Participation through archival infrastructures
There are several routes to think about how people can participate in an archive. Whereas designerly approaches often focus on the affordances of participation, technology has to look into the means of user engagement. Participation on a technical level is expressed by creating access to an archive. This calls for an infrastructural perspective.

This particular perspective is interested in three aspects:

- creating the means for participatory access
- enabling the means for designerly affordances 
- combatting bit rot through infrastructural diversification

The last aspect is not directly linked to participation. That said, the measurements to combat bit rot are are interwoven with creating the means to access. This particular aspect opens up to thoughts about the future of access and hence, participiation in an archive.

The infrastructure of a contemporary digital archives involves several non-human actants, such as server hardware, a lot of diskspace, data in various structures and many different media formats. There is also a range of different professions and people involved, who interact with the materiality of the archive on different level and intensities. From an infrastructural point of view, we're especially interested in those actants that feed, maintain and consume the archive, be they human or of machinic origin.

## Infrastructural problems of digital archives
In terms of the materiality of a digital archive, we're living in the worst of all possible times. Until recently conservation and restauration could focus solely on the materiality of the archived objects, whereas access to those was relatively easy from a technological perspective. Photos could be watched with bare eyes, negatives with the help of a little light, and the hardware to watch old film rolles isn't to complicated either. At least compared to the complexities introduced by digital technologies.

The problems of digital archives can be subsummed under bit or data rot. This problem is two-fold. Data is more sensitive in terms of damage. If part of a photo is damaged, the rest of the photo is still intact. This is helpfull in restorative processes, we can infer the part from the whole. If parts of a digital object get damaged, the whole can become unreadable. This becomes very problematic in regards of long-term storage of data. All material datastorage are prone to decay. Magnetic tapes, compact discs, and other storage media become damaged over time and these directly impact access to archival material.

The second problem of bit rot is that the reading of data is depent on digital technologies. These technologies can be read as stacks, whereas one layer is built on top of many others in order to abstract complexities. Interacting directly with the hardware of a computer is not easy. In order to facilitate problem solving, software development concentrates on reusing what is present. To the end of storing archival data on a server we need operating systems, databases, application frameworks, user interfaces and protocolls to read and write data between all those different systems. If just one of these parts fail, the whole system can become unusable. No programming language and no software ever has proven to be error-free. This means, that digital system are in need of constant maintenance, like all infrastructures. 

One of the structurally most sound approaches to solve these challenges is interwoven with creating the means of participation. By creating and giving access to archival material, sharing is facilitated and the translation of the material into other systems becomes easier. This enables the constitution of an archival diversification, which is a pluriversal approach [ref: Arthuro Escobar], creating the potential for resilient archives. The power of a digital archive, is the possiblity to generate identical copies of an object.

## Methods of infrastructural participation in PIA
In practice, anticipating participation regarding the means of access to the archive is difficult. Designerly approaches to user interaction often work with specific personas to create suitable affordances. From a technical perspective it is often clear who wants to feed the archive and who will maintain it. But regarding the consumation of archival material, the range of expertise in accessing the archive can range from people interesting in watching some images on a mobile device to researchers who want to quantitatively analyse several thousands landscape photos on their content.

We choose to tackle aformentioned challenges through the adoption of open-source practices as well as popular standards of interoperability. These approaches are not only considered from a technical perspective, but also as communicative measurements. Having a shared and widely used vocabulary regarding the technical means enables participation.

The Software Heritage Foundation deems source code its own epistemology[ref]. The software at the heart of digital archives contains a specific set on knowledge on how the digital objects of the archive can be accessed. This makes open-source practices crucial for the long-term survival of an archive. When software is built on top of open-source technologies and licenses, it is no longer directly linked to the fate of a research project, institute or company. It further creates the legal base on which infrastructural participation can happen. An interested and versed public can engage with the technological base, on which an archive is based.

The second important aspect regarding an open-source approach is documentation. Source code is human readable, but a software project can quickly expand beyond a single person's comprehension. [expand]

The most important and valuable aproach so far has been the implementation of open and standardized APIs, application programming interfaces. These enable the exchange and consumation of data or image material. We currently have two APIs implemented, a JSON based linked data system for metadata and the IIIF Image and Presentation interfaces. Via the later, third parties can consumate image material as well as their associated metadata. Both interfaces are linked to each other, in order for an easy discovery of the respective ressources.

The metadata interface is built on top of the JSON API standard[^1]. This type of API is able to serve our digital object ontology as simple but structured text files, after the Javascript Object Notation. Thus, the files are human-readable, but are optimized for the consumption through other software. The JSON API standard is also able to create and serve the relations that digital objects might have to one another. This relationships are included as hyperlinks in the textfiles. [expand]

The IIIF interface is specialised for the consumption of images as well as their metadata. This API has several sub-interfaces, of which the Image and the Presentation API are of special interested. The former is used to access images directly via an URI and the latter to receive a JSON file with the metadata. The speciality of the IIIF Image API is its base on a simple URL schema. The URL to access the image can contain all parameter which size, section, or format the image should be served. Amongst other parameters are also rotation or color-styles. Simply appending a keyword to the URL will serve the metadata JSON.

The ease and modularity of the IIIF APIs enable consumtion and thus participation on a very low level of technlogical expertise. Implementing IIIF into the PIA platform is also a way of communicating certain values about sharing and open data practices. It signals that we want to take part in an emerging network of cultural heritage institutions that want to overcome the digital hurdles profit-driven companies have built in the last decade in their practices of farming data out of users. It is another vision of caring and sharing data.

Interoperability doesn't only mean to use one single interface standard. It also means implementing a plurality of ways to get materials and data into and out of the archival system. If we want to build proper participative systems, we need to enable ways of exchange and collaboration that we can't anticipate. [ref: Arthuro Escobar]

[^1]: https://jsonapi.org, visited 2nd April 2022