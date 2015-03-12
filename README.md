# Haemato-oncology Project

## Editors
 - Dr Wai Keong Wong (Project Owner)
 - Dr Ian McNicoll

## Background and Aims
The management of patients with haematological malignancies is becoming increasingly complex and expensive. This is an area of active research and haematological malignancies are at the forefront of new biological treatments and diagnostic modalities.

However, the structured recording on diagnosis, interventions and clinical outcomes to inform routine clinical care and to facilitate secondary uses such as trials, registries, cross organisational benchmarking of outcomes and service planning seriously lags development in these other areas and in many cases holds them back. This is often quoted as the so-called lack of phenotypic data. 

Over the years, innovative hospitals have built their own databases and systems to facilitate this. However, the lack of a consistent data model expressed in a database and system agnostic matter in an well defined open modelling standard is sadly lacking.

    The aim of this project to explore to build a clinical data model of the practice of haemato-oncology using openEHR.

 
## Objectives

 - To create and identify archetypes to facilitate the creation a continuity of care record for patients with Haematological Malignancies
 - To create templates to present and interact with the underlying Archetypes:-
	3. **The continuity of care document** - One document to summarise the current state of the patient and their historical clinical information to date.
	4. Recording of patient encounters (where an interaction with the patient has taken place)
- Face to Face (eg. Ward Round/ Clinics/ Daycare/ Chemotherapy Unit)
- Telephone
5. Care planning (where one more patient(s) is/are discussed *without the patient being present*)
- MDTs
- Clinic Planning Meetings
- Adhoc Discussions (*corridor discussions*)

## Methodology
Real patient pathways will be used to ground the modelling on real life use cases. These will be drawn from the large haemato-oncology practice at UCLH. Archetypes and templates designed to maximise interoperability and will re-use an pre-existing resources that are available in the [UK](http://clinicalmodels.org.uk/ckm/) and [International CKM](http://www.openehr.org/ckm/). Models will also be informed by the existing DSTU definitions in [HL7-FHIR](http://www.hl7.org/implement/standards/fhir/index.html).
