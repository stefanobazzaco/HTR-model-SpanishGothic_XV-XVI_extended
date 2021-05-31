# HTR-model-SpanishGothic_XV-XVI_extended-DATASET
The following Transkribus platform (READ Coop) Dataset is available on Zenodo: 
***
## General information

The SpanishGothic_XV-XVI_extended DATASET is conceived to be uploaded inside Transkribus
platform (READ Coop) to perform a training and create an HTR+ model for the automated
recognition of printed Spanish documents in Gothic script published between XV-XVI Century.

For system requirements and information about Transkribus platform, go to:

https://readcoop.eu/transkribus/

https://readcoop.eu/transkribus/resources/

https://github.com/Transkribus
***
## Responsability
***
### Authors:
Stefano Bazzaco (coord.)

Nuria Aranda García

Ángela Torralba Ruberte

Pedro Monteiro

Giada Blasut

Federica Zoppi

Ana-Milagros Jiménez
***
### Projects:
#### Progetto Mambrino - Università degli Studi di Verona

resp. Anna Bognolo, Stefano Neri

https://www.mambrino.it/it

#### BIDISO (Biblioteca Digital Siglo de Oro) - Universidade da Coruña

resp. Sagrario López Poza, Nieves Pena Sueiro

https://www.bidiso.es/index.htm

#### COMEDIC (Catálogo de obras medievales impresas en castellano) - Universidad de Zaragoza

resp. María Jesús Lacarra

https://comedic.unizar.es/

#### Progetto di eccellenza: Le Digital Humanities applicate alle lingue e letterature straniere - Università degli Studi di Verona

resp. Paolo Frassi

https://www.dlls.univr.it/?ent=progetto&id=5327
***
### Publisher:
Stefano Bazzaco
***
## SpanishGothic_XV-XVI_extended DATASET description:

The dataset is based on the following Spanish books:

- *Historia de la linda Magalona*, Anónimo (Sevilla, Jacobo Cromberger, 1519)
- *Historia de la reina Sebilla*, Anónimo (Burgos, Felipe de Junta, 1551)
- *Historia del rey Canamor*, Anónimo (Valencia, Jorge Costilla, 1527)
- *Libro del conde Partinuplés*, Anónimo (Sevilla, Jacobo Cromberger, 1519)
- *Libro del conde Partinuplés*, Anónimo (Burgos, Herederos de Juan de Junta, 1558)
- *Libro del conde Partinuplés*, Anónimo (Burgos, Felipe de Junta, 1563)
- *Doctrinal de los Caballeros*, Alonso de Cartagena (Burgos, Fadrique Biel de Basilea, 1487)
- *La Fiameta*, Juan Boccaccio (Salamanca, [Impresor de la Gramática de Nebrija], 1497)
- *Crónica del Rey Don Rodrigo (Crónica Sarracina)*, Pedro de Corral ([Sevilla], [Meinardo Ungut y Estanislao Polono], 1499)
- *Silves de la Selva*, Pedro de Luján (Sevilla, Dominico de Robertis, 1549)
- *Leandro el Bel*, Pedro de Luján (Toledo, Miguel Ferrer, 1563)
- *Florando de Inglaterra*, Anónimo (Lisboa, Germán Gallarde, 1545)
- *Lisuarte de Grecia*, Feliciano de Silva (Sevilla, Jácome Cromberger, 1550)
- *Lisuarte de Grecia*, Juan Díaz (Sevilla, Jacobo y Juan Cromberger, 1526)
- *Tragicomedia de Calisto y Melibea*, Fernando de Rojas (Roma, Marcellus Silber, 1515).
- *Retablo de la Vida de Cristo*, Juan de Padilla (Sevilla, Juan Cromberger, 1510)
***
### Transcription criteria:

semi-diplomatic transcription

abbreviations: expanded

accents: mantained as in the source text

punctuation: mantained as in the source text
***
## How to upload SpanishGothic_XV-XVI_extended DATASET to Transkribus platform

**On your local machine:**

Extract HTR_TrainSet_SpanishGothic_XV-XVI_extended zip folder

Extract HTR_TrainSet_SpanishGothic_XV-XVI_extended zip folder
***
**Inside Transkribus platform:**


**1. Load TrainSet:**

Server > Document > Import document(s) > Upload single document

Local folder: [find and select the DataSet folder HTR_TrainSet_SpanishGothic_XV-XVI_extended]

Title on server: [choose a title]

Add to collection: [choose a collection]

Upload


**2. Load ValidationSet:**

Server > Document > Import document(s) > Upload single document

Local folder: [find and select the DataSet folder HTR_ValidationSet_SpanishGothic_XV-XVI_extended]

Title on server: [choose a title]

Add to collection: [choose a collection]

Upload


**3. Perform Training**

Tools > Text Recognition

Method: HTR (CITLab HTR+ & PyLaia)

Train...


**4. Add Training Details**

Model Name: [choose a name]

Language: [choose a language]

Description: [choose a description]

CITLab HTR+ - Nr. of Epochs: 300

select TrainSet from the document list > click +Training

select ValidationSet form the document list > click +Validation

Train
***
## SpanishGothic_XV-XVI_extended HTR+ model description

Document type: printed

Nr. of Words: 150˙137

Nr. of Lines: 16˙816

CER on Train Set: 0.45%

CER on Validation Set: 0.92%
***
## How to simply use SpanishGothic_XV-XVI_extended HTR+ model

If you want to perform automated text recognition using SpanishGothic_XV-XVI_extended
HTR+ model, just go inside Transkribus platform, import your image files and apply the
model (stored inside Public Models folder).
***
## How to add your own transcriptions to SpanishGothic_XV-XVI_extended HTR+ model

If you want to add your Ground Truth materials to SpanishGothic_XV-XVI_extended HTR+ model,
just create your own Ground Truth pages following the transcription criteria we used and
share that content with Dr. Stefano Bazzaco, e-mail: stefano.bazzaco.1@gmail.com
***
## Copyright statement
The SpanishGothic_XV-XVI_extended DataSet and model belongs to the authors.
Their usage is freely Open Access, but you have to give appropriate credits to authors and publisher.
Their remixing, changing and distribution for commercial use is not possible without authors
and publisher acceptance, as stated by the Creative Commons License CC BY-NC-ND 4.0
(Attribution-NonCommercial-NoDerivatives 4.0 International).

More information here: https://creativecommons.org/licenses/by-nc-nd/4.0/

