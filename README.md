# year_round_bombus_queens
This is a repository for data used for the manuscript: "The city bee that never sleeps: urban gardens foster year-round activity of bumble bee queens" submitted to the Scientific Naturalist

Data files:
The file "Urban_Bombus_Data2022_23.csv" contains raw data on queen observations from 2022 and 2023 in the San Francisco East Bay. These data were used to make Figure 2B.

    Route = Identifier of which of 15 routes around Berkeley were taken. See Erickson et al. 2025 (DOI 10.1002/ecs2.70259) for more details on the routes.
    
    Date = MM/DD/YY
    
    Time = HH:MM
    
    Address = Location of observation
    
    Species = Specific epithet written. While only B. vosnesenskii was used in these analyses because they were the most commonly observed species, we did observe other species occasionally. "Unk" means unknown species. Data for final presentation were filtered to only include Species == "Vosnesenskii"
    
    Caste = "Queen" was noted by large size and if nest-searching, distinct behavior; "Worker" was noted for female worker bees, noted by their smaller size and female morphology' "Male" was noted for males, noted for their distinct male morphology. "Unk" was noted if caste could not be determined. For this paper we filtered for Caste == "Queen" as other castes were seen in such low numbers. 
    
    Nest_search = 1 indicates nest-searching, 0 indicates not nest-searching
    
    Foraging = 1 indicates foraging, 0 indicates not foraging
    
    Other = 1 indicates bee was exhibiting a different behavior and 0 indicates the absence of another behavior. An example of "other" includes flying but not in a nest-searching pattern.
    
    Note = Any notes written in the field while making the observations



The file "inaturalist22.csv" contains downloaded iNaturalist observations from 2022 in Alameda and Contra Costa Counties including research grade and non-research grade observations. These data were then filtered to allowing a single user a single observation per day. Three columns were added to the iNaturalist data download:
    
    Verify = "yes" means the image was of quality to be able to verify caste and species, "unsure" means the image was not clear enough to make a judgement, "duplicate" refers to images that were clearly duplicate observations of another observation. Only observations marked as "yes" were used in the paper.
    
    Caste = refers to the designation given for caste based on relative size and distinct morphologies of males versus females. 
    
    Mating = "yes" for visible mating in the image, "no" for no mating observed
These data were used to make Figure 2C. 
