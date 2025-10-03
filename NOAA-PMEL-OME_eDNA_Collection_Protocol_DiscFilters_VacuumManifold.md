---
# MIOP terms
methodology_category: sample collection
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323], Lake Washington [GAZ:00008722]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater lake [ENVO:00000021]
environmental_medium: sea water [ENVO:00002149], fresh water ENVO:00002011 [ENVO:00002011]
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: Shannon Brown, Han Weinrich, Zachary Gold
materials_required: filtration [OBI:0302885]
skills_required: sterile technique, pipetting skills, standard molecular technique, field research experience
time_required: 60
personnel_required: 1
language: en
issued: 2025-08-06
audience: scientists
publisher: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
env_local_scale: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater lake [ENVO:00000021]
env_medium: sea water [ENVO:00002149]
habitat_natural_artificial_0_1: # 0
samp_collect_method: # DOI
samp_collect_device: Niskin bottle, plankton net tow, bucket
samp_size: # not applicable (variable)
samp_size_unit: # mL
---

# Protocol Template - Sampling

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
|Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2025-08-06|
|Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2025-08-06|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump | https://github.com/marinednadude/NOAA-PMEL-OME_eDNA_Collection_Protocol_Niskin/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump.md |  1.1.1  | 2025-10-03 | Internal |
| NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_GravityBag | https://github.com/Brown-NOAA/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_GravityBag_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_GravityBag.md |2025-10-03  |1.0.0  | Internal |
| NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge | https://github.com/HanWeinrich/NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge.md | 1.1.0 | 2025-08-22 | Internal|

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-08-06 | Initial incomplete draft release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies|
| CTD | Conductivity Temperature Depth |
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|NOAA|National Oceanic and Atmospheric Administration|
|OME	|Ocean Molecular Ecology|
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE| Personal protective equipment |
|RO| Reverse Osmosis|
|ROV| Remotely Operated Vehicle|
|UW| University of Washington|

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Conductivity, Temperature, Depth (CTD) sensor | Sensor used to measure temperature, conductivity and pressure. Additional sensors are often attached to the frame of the deployable CTD frame (oxygen, chlorophyll, pH, etc.) to collect additional data. Often, niskin bottles are attached to the same deployable metal frame as the CTD and ancilliary sensors so that water parameter data are collected alongside Niskin water samples. Deployments of this suite of instruments and sensors on the same frame are often referred to as a "CTD cast". |
| Field blank | Sampling negative control. Typically, distilled or reverse osmosis water run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| Niskin bottle  | Plastic cylindrical bottle of varying volumes for collecting discrete water samples. A stopper at each end of the bottle can be "cocked" open with an electronic or weight-triggered release mechanism, causing the stoppers to snap shut. This is remotely triggered, so the bottle closes at a prescribed depth. Often, multiple bottles are arranged on the same frame as a CTD and other sensors in a "rosette". |

## BACKGROUND

### Summary

Sample collection and filtration protocol using disc filters to collect environmental DNA from marine ecosystems or previously preserved net tow samples. This collection and filtration protocol is used by the NOAA PMEL Ocean Molecular Ecology (OME) Group.

### Method Description and Rationale

This protocol describes the collection and filtration of samples through a 0.22 µm sterile disc filter to capture eDNA and DNA-containing particulates. DNA will later be extracted from these samples for multi-locus metabarcoding. The protocol is intended for water collected with a Niskin bottle mounted on a ship-deployed CTD rosette sampler; however, it can also be used for filtering aliquoted ethanol from preserved plankton tow samples.

### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to filter eDNA for thousands of ethanol aliquots taken from preserved plankton tow samples collected off the western coast of North America in the Northeastern Pacific Ocean, Bering Sea, and Arctic Ocean (primarily off California, Oregon, Washington, and Alaska). In addition, it has been used to filter eDNA from water samples in depth from the surface ocean (epipelagic biome) to just off bottom (benthic biome) at varying distances from shore (coastal to off-shelf).

### Personnel Required

One person with pipetting experience. Recommend field research experience, but not required.

### Safety

This protocol does not involve any hazardous chemicals, although standard precautions, including wearing PPE, should be taken to avoid skin and eye exposure to bleach and ethanol.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique and pipetting technique) is required to conduct this protocol. Experience with going to sea and sample collection under seagoing conditions is encouraged, at a minimum personnel should be trained in the filtering protocol in a laboratory/docked ship setting beforehand.

### Time Required to Execute the Procedure


## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| **Consumable equipment** |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| **Chemicals** |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |

## STANDARD OPERATING PROCEDURE

### Preparation

Please specify the preparatory actions you took before you collected the samples and note what equipment was needed to do so (e.g. disinfection of work surfaces, preparations to the equipment you intend to use later on).

1. [Step 1]
2. [Step 2]

### Sampling

Please specify how you collected samples and note what equipment you used to do so (e.g. targeted water mass, volume, sampling equipment, replication).

1. [Step 1]
2. [Step 2]

### Filtration

Supplies:
Sterlitech filtering manifold
Waste bottle
Appropriate tubing
Pump
Filter cups with 0.2 µm PVDF filter
Sterile flat-edge forceps (3)
Squirt bottle with 10% bleach
Squirt bottle with 75% EtOH
Lighter and flaming ethanol
Kimwipes
Biosafety cabinet

Since our filter cups didn’t come with the correct filter size, we followed the below protocol and prepared them in batches of 50-100.
Sterilize the BSC with 10% bleach and 75% EtOH. Then lay down two large kimwipes on the working surfaces. 
Wipe down forceps with DNAway then use ethanol to flame-sterilize. Place on kimwipe.
One at a time, open the filter cup bag in a way that it can be resealed with lab tape.
Twist open the filter cup. Remove the top filter with sterile forceps. Don’t remove backing
No need to sterilize forceps between filters.
Add a new 0.2 µm PVDF filter and gently tap on the edges to secure it with the forceps.
Reseal with a push and twist approach.
Return to the bag and tape it shut with lab tape. Store for < 1 week.

EtOH Filtering Protocol
Wipe down the BSC with 10% bleach and 75% EtOH. Run UV light for 15 min.
Set-up the sterlitech manifold with the waste collection container and pump. You’ll need space to filter samples and to remove filters.
You’ll need pre-labeled 5 mL tubes with corresponding E#s for the filters.
Suggest labeling ahead of time and leaving in tube racks.
For filter removal, you’ll want to lay down a kimwipe and place 2-3 sterilized forceps on top. You’ll want easy access to a lighter and ethanol plus the necessary tubes.
To begin, remove filter cups from their plastic bag and connect to the manifold via stopper and connector piece. Set up three at a time. Turn on the pump; don’t exceed 10.
If there is a cap, place upwards on the BSC for later use - don’t throw it away!
Label the filter cup with the E#. Uncap, pour in the corresponding falcon tube contents, and recap. Then open the valve to start filtering.
If the filter is lifting up, quickly open and close the value to allow the filter to settle.
Allow the sample to filter until it’s dry and then turn off the valve.
Carefully remove the filter cup from the manifold, cap the bottom, and set aside.
Once all samples are filtered, one by one, twist open the filter cup and throw away the top plastic component. Then use the sterilized forceps to remove the filter and place it in the pre-labeled, corresponding 5 mL LoBind. Sterilize forceps between samples.
Store in -80 freezer.

### Sample Preservation

Please specify what steps you took to preserve the samples taken and note what equipment you used to do so (e.g., freezing in liquid nitrogen).

1. [Step 1]
2. [Step 2]

### Storage

Please specify how you stored your samples and note what equipment you used to do so (e.g., stored in -80°C freezer).

1. [Step 1]
2. [Step 2]

### Quality Control

A field blank consisting of sterile RO water in a pre-filled and sealed (prior to fieldwork) 1 L bottle is filtered at the start and end of a cruise using a new sterile peristaltic tube and fittings. If more than 50 samples are collected on a cruise, an additional field blank  is filtered every 50 samples. 

### Basic Troubleshooting Guide

- Identify known issues associated with the procedure, if any.
- Provide troubleshooting guidelines when available.

## REFERENCES

- Insert all references cited in the document.
- Please insert full DOI address when available, e.g. http://doi.dx.org/10.1007/s11258-014-0404-1.

## APPENDIX A: DATASHEETS

Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance. 
