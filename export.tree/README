## A Polish Electroencephalography, Alzheimer’s Risk-genes, Lifestyle and Neuroimaging (PEARL-Neuro) Database 

IMPORTANT NOTE: The dataset contains no errors (BIDS-1). The numerous warnings currently displayed are a result of OpenNeuro updating its validator to BIDS-2. The OpenNeuro team is actively working on refining the validator to display only meaningful warnings (more information on OpenNeuro GitHub page). At this time, as dataset owners, we are unable to take any action to resolve these warnings.

### Data Descriptor:
* doi.org/10.1038/s41597-024-03106-5 (https://www.nature.com/articles/s41597-024-03106-5)

### Please cite the following reference if you use these data:
* Dzianok P, Kublik E. PEARL-Neuro Database: EEG, fMRI, health and lifestyle data of middle-aged people at risk of dementia. Sci Data 11, 276 (2024). DOI: https://doi.org/10.1038/s41597-024-03106-5

### Publications related to this dataset, reporting & additional data

* https://github.com/PTDZ/PEARL-Neuro — updates, additional study details, and list of research outputs related to this dataset.

IMPORTANT: Please inform us of any research outputs related to the shared data, including publications, preprints, posters, abstracts, talks, and any commercial usage. This is crucial for ensuring transparency and informing users about the analyses already performed on this dataset. Additionally, such information can foster collaboration.

### Description of the database:

Full cohort: 192 healthy middle-aged (50-63) individuals, balanced female and male ratio. 

* Genetic data (N = 192):
	* Apolipoprotein E (APOE) 
	* Phosphatidylinositol binding clathrin assembly protein (PICALM)
* Basic demographic and health data
* Psychometric data (memory, intelligence, mood, personality, stress coping strategies)

Cohort subgroup: 79 healthy middle-aged (50-63) individuals, balanced female and male ratio.

* Neuroimaging data:
	* Functional data — electroencefalography (EEG) and functional magnetic resonance imaging (fMRI):
		* Resting-state protocol (with two conditions: eyes open and eyes closed) 
		* Cognitive tasks: multi-source interference task (MSIT) and Sternberg’s memory task
* Blood tests data (blood count, lipid profile, HSV virus)

### Release history:
* 10/2023: Initial release
* 02/2024: Public release
* 06/2025, version: 1.1.0 — marker corrections in .tsv and .vmrk EEG resting-state files

During EEG data acquisition, technical issues led to missing starting markers for the eyes-open and/or eyes-closed conditions in the resting-state protocol for some participants. As described in the Data Note, the S1 marker indicates the end of the instruction phase—when the participant presses "Enter" to begin a condition (either eyes-open or eyes-closed). Consequently, the first S1 marker coincides with the S2 marker (start of the eyes-open condition), and the second S1 marker aligns with the S4 marker (start of the eyes-closed condition).

To ensure consistency with Table 5 in the released Data Note, the missing markers were added to the relevant files (.tsv and .vmrk) for the following participants: 08, 09, 11, 12, 14, 15, 21, 22, 25, 35, 42, 54, 62, 64, 65, 67, 70, 71, 73, 75, and 79.

For participants 19 and 30, the S11 marker (indicating the end of the task and accompanying sound effect) was not saved, resulting in a slightly shorter eyes-closed recording duration (by approximately 30–60 seconds).

For participant 34, the S11 marker was also not recorded because he/she forgot to press "Enter" to mark the start of the eyes-closed condition, pressing it only after the condition had ended. However, he/she followed the instructions and kept his/her eyes closed during the condition. Therefore, the relevant markers (S1/S4) were manually adjusted to reflect the correct start time.