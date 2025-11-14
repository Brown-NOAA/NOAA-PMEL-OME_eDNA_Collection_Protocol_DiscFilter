---
# MIOP terms
methodology_category: sample collection
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323], Lake Washington [GAZ:00008722], South Pacific Ocean [GAZ:00002418]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater lake biome [ENVO:01000252], estuary [ENVO:00000045]
environmental_medium: sea water [ENVO:00002149], fresh water [ENVO:00002011], planktonic material [ENVO_01000063]
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: Shannon Brown, Han Weinrich, Kenna Dailey
materials_required: filtration [OBI:0302885], vacuum manifold [OBI:0001116]
skills_required: sterile technique, pipetting skills, standard molecular technique, field research experience
time_required: 90
personnel_required: 1
language: en
issued: 2025-11-14
audience: scientists
publisher: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies
hasVersion: 1.1.0
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
env_local_scale: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater lake biome [ENVO:01000252], estuary [ENVO:00000045]
env_medium: sea water [ENVO:00002149], fresh water [ENVO:00002011], planktonic material [ENVO_01000063]
habitat_natural_artificial_0_1: 0
samp_collect_method:  DOI
samp_collect_device: CTD Niskin rosette, ROV, plankton net tow, bucket
samp_size: not applicable
samp_size_unit: mL
---

# NOAA PMEL OME eDNA Collection Protocol with Disc Filters and a Vacuum Manifold

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
| ------------ | ------------ | ------------ | --------- |
|Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2025-08-06|
|Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2025-08-06|
|Kenna Dailey | Ocean Molecular Ecology, NOAA PMEL & UW CICOES; UW School of Aquatic and Fishery Sciences | 0009-0008-5542-5336 | 2025-08-07
|Sean McAllister	|Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|0000-0001-6654-3495	|2025-08-06|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|0000-0003-0490-7630	|2025-08-06|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_GravityBag | https://github.com/Brown-NOAA/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_GravityBag_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_GravityBag.md |1.1.0|2025-11-14  | Internal |
| NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump | https://github.com/marinednadude/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump.md |  1.1.1  | 2025-11-14 | Internal |
| NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge | https://github.com/HanWeinrich/NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge.md |  1.1.1  | 2025-11-14 | Internal |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalized.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-08-06 | Initial beta release with FAIRe and MIOP terms |
| 1.1.0 | 2025-11-14| Formalized draft with background and detailed protocol |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|BSC	|Biosafety cabinet |
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies|
| CTD | Conductivity Temperature Depth |
|DNA	|Deoxyribonucleic acid|
|Disc | Flat, thin, round object (interchangeable with disk |
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|NOAA|National Oceanic and Atmospheric Administration|
|OME	|Ocean Molecular Ecology|
|PES|Polyethersulfone|
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE| Personal protective equipment |
|PVDF| Polyvinylidene Flouride|
|qPCR|Quantitative Polymerase Chain Reaction|
|RO| Reverse Osmosis|
|ROV| Remotely Operated Vehicle|
|UW| University of Washington|

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Conductivity, Temperature, Depth (CTD) sensor | Sensor used to measure temperature, conductivity, and pressure. Additional sensors are often attached to the frame of the deployable CTD frame (oxygen, chlorophyll, pH, etc.) to collect additional data. Often, Niskin bottles are attached to the same deployable metal frame as the CTD and ancillary sensors so that water parameter data are collected alongside Niskin water samples. Deployments of this suite of instruments and sensors on the same frame are often referred to as a "CTD cast". |
| Field blank | Sampling negative control. Typically, distilled or reverse osmosis water is run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| Niskin bottle  | Plastic cylindrical bottle of varying volumes for collecting discrete water samples. A stopper at each end of the bottle can be "cocked" open with an electronic or weight-triggered release mechanism, causing the stoppers to snap shut. This is remotely triggered, so the bottle closes at a prescribed depth. Often, multiple bottles are arranged on the same frame as a CTD and other sensors in a "rosette". |

## BACKGROUND

### Summary

Sample collection and filtration protocol using disc filters to collect environmental DNA from marine ecosystems or preserved net tow samples. The methods detailed in this protocol are applicable no matter the mesh size; however, NOAA PMEL Ocean Molecular Ecology (OME) Group employs this protocol with a 0.22 µm sterile disc filter as the set standard.

This collection and filtration protocol is used by the NOAA PMEL Ocean Molecular Ecology (OME) Group.

### Method Description and Rationale

This protocol describes the collection and filtration of samples through a disc filter to capture eDNA and DNA-containing particulates. DNA will later be extracted from these samples for multi-locus metabarcoding and qPCR analysis. The protocol is intended for water collected with a Niskin bottle mounted on a ship-deployed CTD rosette sampler; however, it can also be used for filtering water collected by bucket or aliquoted ethanol from preserved plankton tow samples.

### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to filter eDNA for hundreds of ethanol aliquots taken from preserved plankton tow samples collected off the western coast of North America in the Northeastern Pacific Ocean, Bering Sea, and Arctic Ocean (primarily off California, Oregon, Washington, and Alaska). In addition, it has been used to filter eDNA from water samples ranging in depth from the surface ocean (epipelagic biome) to just off bottom (benthic biome) at varying distances from shore (coastal to off-shelf).

### Personnel Required

One person with pipetting experience. Recommend field research experience, but not required.

### Safety

This protocol uses bleach and ethanol, both of which are classified as hazardous chemicals. Appropriate PPE must be worn, and standard safety procedures should be followed to avoid skin and eye exposure.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique and pipetting technique) is required to conduct this protocol. Experience with going to sea and sample collection under seagoing conditions is encouraged; at a minimum, personnel should be trained in the filtering protocol in a laboratory/docked ship setting beforehand.

### Time Required to Execute the Procedure

If this protocol is used for water sampling with a Niskin, the time needed varies widely based on the number and type of samples collected. For a majority of our sampling, Niskin bottles on a CTD rosette and/or ROV are triggered to collect at three depths (e.g., surface, 30m, and 10m off bottom). Then, pending the scientific questions and Niskin size, a singular sample or triplicate samples are collected from each Niskin. The depth of collection and number of samples affect the time required - for instance, a cast to 30 m may take 10 minutes, while a cast to 600 m may take over an hour. Collecting samples from the Niskins takes between 10-30 minutes, depending on access and whether the water is being used for other science. 

If this protocol is used to filter ethanol aliquoted from previously preserved plankton net tow or organismal samples, the removal of ethanol takes <5 min for every sample. Time is also influenced by the condition and organization of the samples, pre-sampling.

The vacuum manifold set-up takes 30-45 minutes due to sterilization, then pending the turbidity of the sample, the filtering takes between 5-15 minutes. With a triple vacuum manifold, three samples can be filtered simultaneously. Properly removing the filter from its setup and preserving it takes 5 minutes.

The total collection and filtering time for three samples, where ethanol preservative was aliquoted from a plankton net tow sample, and filtering is 90 minutes (1.5 hrs) on average. Set-up occurs once, and subsampling can be expedited with extra hands, so adding more samples will compound the filtering time but not other stages.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

For a singular cast with three unique samples taken (one sample per Niskin) or three EtOH aliquots taken from previous preserved net tow or organismal samples:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
|BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted with generic; internal UV light required.|
| Wash bottles  | Safety wash bottles 500 mL for EtOH, bleach, and RO water | VWR | 3 | Can be substituted with generic; recommend purchasing different colored bottles for each reagent. Must be sterilized before use. |
| Nalgene bottles | 1 L Nalgene wide-mouth lab quality amber HDPE bottles | Thermo Scientific | 3 | Can be substituted with generic; must be opaque, well-sealing and sterilizable. Only required if sampling water in the field. |
| Pipettor: 100-1000 μL | Pipetman P1000 | Gilson | 1 | Can be substituted with any accurate pipettor. Only required if sampling water in the field.|
| Bungee cords | Bungee cords | Generic | 5 | Varying sizes recommended.  |
|UV crosslinker | UV crosslinker AH (115V), 234100 | Boekel Scientific  | 1 | Can be substituted with generic. Recommended, not required. |
|-20°C freezer|TSX high-performance -20°C manual defrost freezer |Fisher Scientific|1|Can be substituted with generic; recommend temperature display.|
|Serological pipette controller |United Scientific pinPoint pipette controller|Fisher Scientific|1|Can be substituted with generic. Only required for EtOH aliquoting.|
|Forceps | Steel forceps | Generic|2 |Must have tips small enough to fit in a 5 mL tube and safely handle the filter, must be flame sterilizable.|
|Lighter| Long utility lighter| Generic|1 | Must have a metal wand, must be sterilizable by wiping with 10% bleach and EtOH.|
| 4-way tube racks | 4 way interlocking tube rack| Cole-Parmer | 4 | Can be substituted with generic; must fit 12 x 5 mL tubes and 50 mL tubes. |
| Vacuum manifold |  PVC vacuum manifold, 3-Position, standard cup, 2-way valve  | Sterlitech | 1 | Can be substituted with generic; must fit 3/8” ID vacuum tubing. | 
| Stoppers | Neoprene stoppers, size #08 | Generic | 1 | Can be purchased with a hole, or use a drill to create an appropriately sized hole for the filter cup adaptors. |
| Pump | Standard vacuum pump | Generic | 1 |  |
| Vacuum waste bottle | Heavy-duty carboy | Millipore Sigma | 1 | Can be substituted with generic; recommend at least 5 L to support the filtering of multiple samples. |
| Nalgene quick disconnect port lid | Quick filling/venting closures | Millipore Sigma | 1 | Must fit 3/8' ID tubing and vacuum bottle. |
| Tubing | Non-phthalate PVC vacuum tubing (10 ft) | Fisher Scientific | 1 | Can be substituted with generic if appropriate diameter for pump. |
| **Consumable equipment** |
| 5 mL tubes | DNA LoBind 5 mL PCR clean centrifuge tube | Eppendorf | 3 | Can be substituted with generic; must be sterile/PCR clean. |
| Kimwipes | Delicate task wipes | Kimtech | 1 | Can be substituted with generic. Must be lint-free.|
| Nitrile gloves | Powder free nitrile gloves | Fisher Scientific | 3 | Can be substituted with generic nitrile gloves. Does not come sterile; it must be sterilized before use.|
| Parafilm | Parafilm  | Sigma Aldrich |60 cm | |
| Filter cups | Disposable filter funnel, sterile, 100 ml | Sterlitech | 4 | Can be substituted with generic. If not purchased with a 0.2 µm PVDF filter, it must be replaced before filtering the sample. |
| 0.2 µm PVDF or PES filter | PVDF or PES membrane filters, 0.2 µm, 47mm, 100/Pk | Sterlitech | 4| Can be substituted with generic; must cover entire surface area of filter cup with no leaks. |
|Serological pipettes |25 mL serological pipettes|Fisher Scientific|1|Only required for EtOH aliquoting.|
| Lab notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to the lab space.|
| Writing utensils | Sharpies and pens | Generic | 2 | Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH.  |
| **Chemicals** |
| DNA Away | DNA AWAY surface decontaminant | Fisher Scientific | 10 mL| |
| 100% molecular grade EtOH | 200 proof molecular biology grade ethanol | Fisher Scientific | 20 mL|Can be substituted with generic, must be 200 proof and molecular biology grade. |
| 70% EtOH | Molecular biology grade ethanol || 10 mL | For cleaning, can be substituted with generic. |
| 10% bleach | Hypochlorite bleach | Clorox | 100 mL| Remake every ~5 days as bleach decomposes quickly at 10% concentration. The majority is used in bottle/tube sterilization.|
## STANDARD OPERATING PROCEDURE

### Preparation

To minimize the risk of cross-contamination, it is important to prepare a sterile workspace and equipment before beginning the protocol.

**Glove Sterilization:**

When sterilizing any equipment for filtering, sterile nitrile gloves must be used. Gloves directly from the box are not considered sterile. To sterilize, squirt 10% bleach solution from a squirt bottle onto a new pair of gloves and rub hands together, then squirt with EtOH to get rid of bleach residue. Nitrile gloves should be worn at all times during the sterilization, sampling, filtering, preservation, and storage steps.

**Bottle Sterilization:** - Only required if sampling water in the field.
One sterile bottle is required for each sample and each field blank.

Bottle Sterilization Method (RO Available):

1. Create a 10% bleach solution in one of the buckets (6-10 L total, depending on needs).
2. Fill 4-6 bottles at a time with 10% bleach solution; fill to the top and seal with a lid. Allow to sit for 7 minutes, then flip the bottle upside down. Allow to sit for 7 more minutes.
3. Pour 10% bleach from these bottles into the next set of bottles or reuse bleach for further sterilization needs.
4. Each bottle needs to be rinsed with RO. Fill each Nalgene bottle with ~200 mL of RO, and then shake for 30-45 seconds. Repeat process 2x (= three rinses in total).
5. Shake out excess RO dumped (doesn’t need to be entirely dry), close it with the cap, and then wrap the top with parafilm to maintain sterility. Always wrap in the direction the cap tightens, so clockwise.

Bottle Sterilization Method (RO Not Available):

1. Complete Steps 1-3 from Bottle Sterilization Method (RO Available)
2. Close it with the cap, then wrap the top with parafilm to maintain sterility. **This shouldn’t be done more than 24 hours in advance of sampling.**
3. Once the CTD is on deck, take a bleached 1 L Nalgene bottle and dispense ~250 ml of the sample from the Niskin into the bottle; close the lid and shake vigorously. Dump. This will rid the container of residual bleach. Repeat process 2x (= three rinses in total). Water must come from the same Niskin that will be the source of the actual sample; otherwise, there will be cross-contamination.

**Bench Space Preparation:**
If filtering seawater after collection, complete this vacuum filtration in a dry, sterile area. If filtering aliquoted EtOH samples, perform this work in a sterilized Biosafety Cabinet (BSC).

* Sterilize the workstation by wiping surfaces with kimwipes and a 10% bleach solution, followed by 70% before every sampling event. If the workspace surface is wood, use the tabletop covering to cover the sample processing area.
    * If using a BSC, run the UV light for 30 min prior to setting up the vacuum manifold.
    * If filtering at sea, the vacuum pump, bottle, and manifold should be secured on the ship bench using screws/eye bolts and bungee cords. Items that will move in rough seas should also be properly stored to prevent falling and/or contamination.
* Prepare and label the filter cups and corresponding 5 mL tubes ahead of time.
    * Store labeled 5 mL tubes in a tube rack for easy access during filtration.
* In preparation for filter removal, lay down a kimwipe and place 2–3 sterilized forceps on top. Keep a lighter, ethanol, and all tubes within easy reach on your workbench.

**Vacuum Manifold Sterilization:**

1. Wipe the outside surfaces of the vacuum manifold with 10% bleach solution, followed by 70% EtOH.
2. Run 10% bleach through the inside of the manifold.
3. Rinse the inside of the manifold with RO water three times to remove any residual bleach.

**Filter Cup Preparation:**
If filter cups are purchased with the designed mesh size, skip this step. In several cases, the filter cups purchased by OME came with 0.45 µm filters, so we manually replaced the filters with the desired 0.2 µm PVDF filters in batches of 50-100 before beginning the filtration protocol. This whole filter replacement procedure should take place in a BSC.

1. Put on a pair of sterilized gloves. Then, sterilize the BSC by wiping with 10% bleach, followed by 70% EtOH. Prepare a workspace by laying down two large kimwipes.
2. Wipe down forceps with DNAaway, then flame sterilize with EtOH. Place cooled forceps on kimwipe.
3. Carefully open the filter cup's bag and remove the filter cup. 
    + Do not damage the bag, as you will be resealing the prepared filter in here.
7. Working one at a time, twist and remove the top funnel component of the filter cup.
8. Using sterile forceps, remove the existing top filter and dispose of it. Do not remove the paper filter backing underneath.
9. Place a new 0.2 µm PVDF or PES filter inside the cup on top of the paper backing filter using the same sterilized forceps.
10. Gently tap along the edges with the forceps to ensure the filter is snugly in place at the bottom of the cup.
11. Resecure the top funnel component of the filter cup by pushing and twisting to ensure a tight seal.
12. Inspect the margins where the funnel component sits to ensure there are no gaps - or else the filter is not seated correctly and liquid will leak past it.
13. Return the filter cup to its original bag and seal securely with lab tape. 
    + Filter cups resealed with lab tape can be stored for no longer than 1 week.

**Field Sampling Records:**

When sampling in the field, there should be a corresponding record sheet or field notebook. On larger cruises where cruise CTD logs are kept after each cast, record the sample # in the logs in the corresponding Niskin row. Record additional information like the date, sample #, sample depth, cast #, filtering issues, etc., in your own records sheet or notebook. 

On smaller cruises where no CTD logs are kept or water is sampled without a CTD, more detail is required in the record sheet. Record the date, sample #, site name, lat/long, cast #, depth, and any other associated notes (e.g., filtering issues, sampling device, cast deployment time).

When aliquoting EtOH from net tow samples, a detailed record sheet denoting the sample name, volume aliquoted, filtering date/time, and any filtering issues should be kept.

### Sampling

#### Field eDNA Sampling
This protocol is designed for samples collected with a Niskin bottle - the samples are expected to be discrete and sealed masses of water that can be transferred to a 1 L Nalgene bottle without contamination (typically from the spout/spigot of the Niskin bottle). For our samples, Niskin bottles are remotely triggered to close at a specified depth and collected alongside complementary hydrographic data (using a CTD attached to the Niskin sampling rosette). 

Fill a 1 L Nalgene bottle with 1 L of sample water. It is important to do this before the sample has sat on the deck in the sun. After collecting, if you don’t have time to filter, label, and store bottles in the fridge (4˚C) for up to 12 hours (>4 hours is not ideal). Note the length of time a sample sits in the fridge in the field notebook.

These samples can be filtered via a vacuum manifold, as detailed below; however, the use of this protocol for eDNA sampling and filtering is no longer used by OME. For sterility and replicability reasons, we've transitioned to [eDNA Collection Protocol with Sterivex and a Peristaltic Pump](https://github.com/marinednadude/NOAA-PMEL-OME_eDNA_Collection_Protocol_Niskin/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_PeristalticPump.md) and [eDNA Collection Protocol with Sterivex and a Gravity Bag](https://github.com/Brown-NOAA/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_GravityBag_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_Collection_Protocol_Sterivex_GravityBag.md).

#### EtOH Subsampling from Preserved Samples

If this protocol is used to filter ethanol aliquoted from previously preserved plankton net tow or organismal samples, ethanol must first be subsampled from each original sample jar. This step of the protocol can be performed outside of the BSC.

1. Before starting, swirl each sample jar to homogenize the ethanol and any organismal material. Complete this at least 30 min before aliquoting to ensure particulates settle.
2. Put on a pair of sterilized gloves. Then, sterilize the bench space by wiping with 10% bleach, followed by 70% EtOH.
3. Pre-label 50 mL Falcon tubes with the sample ID number. 
    + The number of aliquots taken from each jar will depend on the desired aliquot volume, original sample volume, and the density of material within the sample.
5. Remove the cap from a pre-labeled Falcon tube and place it facing upwards on a clean bench surface.
6. Remove the lid from the corresponding sample jar and place it facing upwards on the bench.
     + Avoid splashing or creating ethanol droplets to minimize the risk of cross-contamination.
7. Using a sterile serological pipette and the pipette controller, carefully pipette ethanol from the surface layer of the sample jar, avoiding any visible planktonic or organismal material.
8. Dispense the collected ethanol into the pre-labeled 50 mL Falcon tube. Repeat this step as many times as necessary to fill the 50 mL tube and/or reach your desired aliquot volume.
8. Discard the used serological pipette and seal both the Falcon tube and the sample jar.
9. Wipe gloves and bench surfaces with 10% bleach followed by 70% ethanol between handling each sample jar.
10. Repeat steps 4–9 for all remaining ethanol-preserved sample jars.

### Filtration
Whether you are filtering seawater samples recently collected from a Niskin CTD rosette or you are filtering EtOH aliquots taken from preserved samples, the filtering protocol is as follows:

1. Remove filter cups from the plastic bag and connect them to the manifold using the stopper and connector piece. Set up three at a time. Turn on the pump.
   + Monitor the pump pressure to ensure it does not exceed the manufacturer's recommended pressure.
   + Do not dispose of the blue cap on the bottom of the filter cup - remove it and face it upwards for later use.

2. If not already labeled, denote the sample number on the filter cup. Remove the clear lid and then pour in the contents of the corresponding Falcon tube.
3. Add the clear lid back to the filter cup and turn the valve of the vacuum manifold from horizontal (closed) to vertical (open) to begin filtering.
   + When filtering, always place the lid on the filter cup to minimize external contamination. However, depending on the cup’s design, ensure that the lid does not form a tight seal, as this can create a vacuum and cause the cup to implode.
4. Allow the sample to filter completely until dry, then close the valve.
5. Carefully remove the filter cup from the manifold, add the previously set aside blue cap to the bottom, and set the filter cup aside.
6. In batches or once all the samples are filtered, twist and remove the top funnel component of the filter cup one at a time and discard the funnel.
7. Using sterilized forceps, remove the filter membrane, being careful not to remove the backing. Place the filter into the pre-labeled 5 mL tube.
8. Sterilize the forceps between filter membranes using 70% ethanol and flame. Sterilize gloves between samples using 10% bleach followed by 70% EtOH.

### Sample Preservation
If the samples were collected in the field and filtered for eDNA using a vacuum manifold (water samples), we used a 1000 μL pipette to add 4 mL of 100% molecular grade EtOH for long-term storage. The 5 mL tube was then sealed with parafilm before being stored permanently.

If the samples were EtOH aliquots from preserved organismal or net tow samples, no additional preservative was added to the filter in the 5 mL tube. To prevent any evaporation, each tube was sealed with parafilm after closing.

### Storage

Store filtered samples in a -20˚C freezer until extracted. Any storage issues should be noted. Samples may remain preserved if briefly thawed to refrigeration temperature (4˚C) and returned to freezing temperatures within 24 hours.

### Quality Control

A blank consisting of sterile RO water in a 50 mL Falcon tube is filtered at the start, middle, and end of the filtration process. 

### Basic Troubleshooting Guide

**Issue 1**: The filter of the filter cup is lifting during vacuum manifold filtration

**Solution 1**: First, double-check you are using the appropriate filter size. If the filter is improperly seated, consider transferring the sample contents to a new filter cup. If not feasible, briefly open and close the valve to allow the filter to settle before continuing. 

**Issue 2**: Liquid is draining from the filter cup much faster than expected.

**Solution 2**: The filter may not be seated or sealed correctly, allowing your sample to bypass the filter. Close the vacuum valve immediately, get a new filter cup, and set up on the vacuum manifold. Pour the rest of the sample from the leaking filter cup into the new one. Save both filters for later extraction and label tubes carefully to denote 2 filters from the same sample.

## REFERENCES

## APPENDIX A: DATASHEETS
[OME_Collection_eDNA_ProtocolSheet](https://docs.google.com/spreadsheets/d/1MKNcWcW8v8AlEfASEV-uqE-QKrhblGvU/edit?usp=sharing&ouid=112961731900530069948&rtpof=true&sd=true)
