#######################################			
## Metadata for caterpillar collections included as part of the Lepidoptera monitoring program in the Sierra Nevada and Great Basin, USA.	
#######################################			
			
Details below are for this data file: GBSNcaterpillars2009_2025.csv			
			
			
############################			
## GBSNcaterpillars2009_2025.csv			
############################			
			
This file contains the metadata for the caterpillar database associated with the collection of caterpillars at core Lepidoptera monitoring sites (2022–2025), along with previous and concurrent collections in the surrounding Sierra Nevada and Great Basin areas that were sampled opportunistically and with Earthwatch volunteers. Caterpillar collections are conducted biweekly at focal sites. The file represents parasitoid–caterpillar–plant records and links caterpillars to (1) plants at the site, plot, or individual level, and (2) parasitoids that were reared from them. It also documents important life-history information for each caterpillar. Each row in the linked CSV corresponds to a single individual caterpillar.
The data are available here:

			

Each row represents a single caterpillar individual, with associated plant, site, and parasitoid data. 
Column headers are in the order they appear below.

############Identification & Collection Metadata

ID – Unique number tied to each caterpillar collected.

tempID – Temporary ID used during field or lab processing.

Pinned – Indicates whether specimen was pinned.

Date – Date of collection (redundant columns also include Year, Month, Day).

Year, Month, Day – Redundant breakdown of date.

Site – Long-term monitoring site where caterpillar was collected.

Time – Time of collection.

coord_approx_exact – Flag for whether coordinates are approximate or exact.

Lat, Long, LatLong – Decimal latitude, longitude, and combined coordinate.

plot_num – Plot where caterpillar was collected.

Plot_by_day – Daily plot ID.

Location_Description – Text description of collection location.

time_per, n_coll, time_cum – Effort-related metadata (collection time, number collected, cumulative time).

tree_ID – Tree ID if collected from a particular tree.

elev – Elevation at collection site.

forest_type – Forest type of collection site.

###############Host Plant Information

order, family, subfamily, tribe, subtribe, genus – Taxonomic identity of host plant.

plant_cn – Common name of host plant.

Epiphyte – Boolean, TRUE if host plant is an epiphyte.

Epiphyte_of – Plant individual on which the epiphyte occurs.

HPlant – Full host plant name as identified (e.g., Ribes cereum or Salix sp.).

Plant_Genus, Plant_Sp – Host plant genus and species epithet.

PlantIND – Alias for plant individual/patch (e.g., Salix.1, Salix.plot_adjacent).

####################Caterpillar Information

MicroMacro – Indicates if specimen is a microlepidopteran, macrolepidopteran, or sawfly larva.

N_collected, Need_Recount – Counts associated with collection events.

life_stage – Instar stage at collection.

lep_fam, lep_subfam, lep_tribe, lep_genus, lep_sp – Caterpillar taxonomy.

lep_name, suspected – Best identity or suspected ID.

common_name – Morphotypic descriptive name if not fully identified.

Morpho, MORPHO – Phenotypic description (duplicate fields).

lep_cn – Caterpillar common name (taxonomic).

lep_determ, lep_voucher – Determination and voucher tracking.

lep_comment – Notes on identification.

LifeHistoryNote – Notes on caterpillar life history.

##############Caterpillar Defenses

color_morph, drop, thrash, bite, vomit, shelter_web, group, frass_thrower, ostemeria, hair, spiny, glabrous, urticate, mass, length, behav_comment – Columns documenting morphological and behavioral defenses.

###############Status & Fate

Status – Book-keeping status (e.g., “dead,” “parasitized”).

Host_unconfirmed – Flag if host association is uncertain.

Label_Tape, C.C.I – Labelling/processing notes.

Btoid – Boolean, 1 if parasitized.

pupal, toided, eme – Dates of pupation, parasitoid emergence, and moth emergence.

###########Parasitoid Data

toid_name – Most informative parasitoid name possible.

Parasitoid_Order, Parasitoid_Family, Parasitoid_Subfamily, Parasitoid_Tribe – Taxonomy of parasitoid.

toid_morpho – Morphotype notes for parasitoid.

toid_ID – Parasitoid identification code.

Identified_by – Person assigning parasitoid ID.

date_eclosed – Date parasitoid adult eclosed.

number eclosed – Number of adults emerged.

result – Outcome of rearing.

################Parasitoid Behavior / Voucher Tracking

p_endo_ecto, p_pupate_type – Parasitoid type (endoparasitoid/ectoparasitoid, pupation type).

p_larva_hostlarva_hostpupa, p_adult_hostlarva_hostpupa – Host life stage relationships.

p_date_pupate, p_date_eclosed, p_pupate_loc – Dates and location of parasitoid pupation.

num_psit – Number of parasitoids.

p_behav – Parasitoid behavior notes.

psit_fam, psit_subfam, psit_sp – Parasitoid taxonomy (redundant to above).

p_comment, p_voucher – Comments and voucher details.

############Collection Metadata

collector – Collector’s name.

p_determ – Determination authority.

photo_num – Associated photograph number.


#############Table format of all columns in the database:
| Column                        | Description                                   |
| ----------------------------- | --------------------------------------------- |
| ID                            | Unique caterpillar identifier                 |
| tempID                        | Temporary ID during field/lab processing      |
| Pinned                        | Indicator if specimen was pinned              |
| Date                          | Date of collection                            |
| Year                          | Year of collection                            |
| Month                         | Month of collection                           |
| Day                           | Day of collection                             |
| Site                          | Monitoring site name                          |
| Time                          | Time of collection                            |
| coord\_approx\_exact          | Coordinate precision (approximate/exact)      |
| Lat                           | Decimal latitude                              |
| Long                          | Decimal longitude                             |
| LatLong                       | Combined coordinates                          |
| plot\_num                     | Plot where collected                          |
| Plot\_by\_day                 | Daily plot identifier                         |
| Location\_Description         | Text description of collection location       |
| time\_per                     | Time spent collecting per interval            |
| n\_coll                       | Number collected in that effort               |
| time\_cum                     | Cumulative collection time                    |
| tree\_ID                      | Tree ID if applicable                         |
| elev                          | Elevation (m)                                 |
| forest\_type                  | Forest type at site                           |
| order                         | Host plant order                              |
| family                        | Host plant family                             |
| subfamily                     | Host plant subfamily                          |
| tribe                         | Host plant tribe                              |
| subtribe                      | Host plant subtribe                           |
| genus                         | Host plant genus                              |
| plant\_cn                     | Host plant common name                        |
| Epiphyte                      | TRUE if host plant is epiphytic               |
| Epiphyte\_of                  | Host plant individual supporting epiphyte     |
| HPlant                        | Full host plant name                          |
| Plant\_Genus                  | Host plant genus                              |
| Plant\_Sp                     | Host plant species epithet                    |
| PlantIND                      | Alias for host plant individual/patch         |
| MicroMacro                    | Micro/macro lepidopteran or sawfly            |
| N\_collected                  | Number of larvae collected                    |
| Need\_Recount                 | Flag if count requires rechecking             |
| life\_stage                   | Instar at collection                          |
| lep\_fam                      | Caterpillar family                            |
| lep\_subfam                   | Caterpillar subfamily                         |
| lep\_tribe                    | Caterpillar tribe                             |
| lep\_genus                    | Caterpillar genus                             |
| lep\_sp                       | Caterpillar species                           |
| lep\_name                     | Caterpillar full taxon name                   |
| suspected                     | Suspected ID                                  |
| common\_name                  | Morphotypic descriptive name                  |
| Morpho / MORPHO               | Caterpillar phenotype description             |
| lep\_cn                       | Caterpillar common name (taxon)               |
| lep\_determ                   | Determination authority                       |
| lep\_voucher                  | Voucher specimen reference                    |
| lep\_comment                  | Taxonomic notes                               |
| LifeHistoryNote               | Notes on life history                         |
| Status                        | Book-keeping status (e.g., dead, parasitized) |
| Host\_unconfirmed             | Host association uncertain                    |
| Label\_Tape                   | Label or tape notes                           |
| C.C.I                         | Lab record notes                              |
| Btoid                         | 1 if parasitized                              |
| pupal                         | Date of pupation                              |
| toided                        | Date of parasitoid emergence                  |
| eme                           | Date of moth emergence                        |
| toid\_name                    | Parasitoid name                               |
| Parasitoid\_Order             | Parasitoid order                              |
| Parasitoid\_Family            | Parasitoid family                             |
| Parasitoid\_Subfamily         | Parasitoid subfamily                          |
| Parasitoid\_Tribe             | Parasitoid tribe                              |
| toid\_morpho                  | Parasitoid morphotype notes                   |
| toid\_ID                      | Parasitoid ID                                 |
| Identified\_by                | Person assigning ID                           |
| date\_eclosed                 | Date parasitoid adult eclosed                 |
| number eclosed                | Number of adults emerged                      |
| result                        | Rearing outcome                               |
| color\_morph                  | Caterpillar color morph                       |
| drop                          | Caterpillar dropped when disturbed            |
| thrash                        | Thrashing defense                             |
| bite                          | Biting defense                                |
| vomit                         | Regurgitation defense                         |
| shelter\_web                  | Built silk/web shelter                        |
| group                         | Gregariousness                                |
| frass\_thrower                | Frass throwing                                |
| ostemeria                     | Osmeterium everted                            |
| hair                          | Hairy covering                                |
| spiny                         | Spiny body                                    |
| glabrous                      | Smooth body                                   |
| urticate                      | Urticating hairs present                      |
| mass                          | Caterpillar mass                              |
| length                        | Caterpillar length                            |
| behav\_comment                | Notes on behavior/defenses                    |
| photo\_num                    | Photo reference number                        |
| p\_endo\_ecto                 | Endo-/ectoparasitoid type                     |
| p\_pupate\_type               | Parasitoid pupation type                      |
| p\_larva\_hostlarva\_hostpupa | Host stage during larval parasitism           |
| p\_adult\_hostlarva\_hostpupa | Host stage during adult parasitism            |
| p\_date\_pupate               | Date of parasitoid pupation                   |
| p\_date\_eclosed              | Date parasitoid adult eclosed                 |
| p\_pupate\_loc                | Pupation location                             |
| num\_psit                     | Number of parasitoids                         |
| p\_behav                      | Parasitoid behavior                           |
| psit\_fam                     | Parasitoid family (duplicate)                 |
| psit\_subfam                  | Parasitoid subfamily (duplicate)              |
| psit\_sp                      | Parasitoid species (duplicate)                |
| p\_comment                    | Parasitoid notes                              |
| p\_voucher                    | Parasitoid voucher                            |
| collector                     | Collector name                                |
| p\_determ                     | Parasitoid determination authority            |


