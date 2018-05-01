# sails

Semantic analysis of image based learner sentences (SAILS) corpus

April 30, 2018

I'm excited to share this corpus with fellow researchers and anyone interested. Please contact me if you have any questions.

Levi King (leviking@indiana.edu)



SUPPLEMENTAL MATERIALS:

The PDT folder contains pdfs of the picture description tasks (four versions).

The annotation_guide folder contains the tex and pdf file of the annotation guide used to annotate the responses.

The figures folder contains all the images used in the task. Some of these are called by the annotation_guide tex file.



CORPUS:

The corpus folder contains the SAILS corpus. There are 60 files in the folder (one per item). There are 30 images, each presented as a *targeted* or *untargeted* item, for a total of 60 items. This should be clear from the filenames. For example, "I01T_master_anno.csv" and "I01U_master_anno.csv" are the files for item 1 (targeted) and item 1 (untargeted), respectively.

The corpus files are csv files. You may notice a lot of zeroes or empty cells in the files. That is because not all participants were given all items, but corpus file contains rows for every participant. Thus, the demographic columns of all corpus files should be identical, but the response and annotation content is not.

An explanation of the columns of each file follows:

RespondentID: This is a unique number generated for each respondent.

Purchased response: "Yes" indicates that the response was purchased via an online survey platform (Survey Monkey). These are the "crowdsourced" responses. "No" indicates that the participant was a volunteer.

L1 Eng?: "Yes" indicates that the respondent is a native speaker of English.

L1s: This indicates the participant's native language(s). Native English speakers who are childhood bilinguals may list other native languages here.

Other Ls: This is for any other language that the participant speaks.

Country: The participant's native country.

Age: Participant's age in years.

Gender: Participant's gender. 

years Eng: This indicates how long the participant has studied English.

Eng residence: This indicates how long the participant has lived in an English speaking country; it is the name of the country (or countries) and the length of time spent there.

1stOr2ndResponse: Some participants were asked to provide two responses to each item; "1" indicates that this is the first response by the participant; "2" is for a second response. Note that although some participants were only asked for a single response, there are two rows (for 2 responses) from all participants; these "2" rows contain all the same demographic info, but the response column contains only "0" and there is no annotation.

"What is ...?": The header of this column is the question that was presented; it varies slightly from item to item, (but is always "What is happening?" for untargeted items). The rest of the column are the responses from participants, exactly as entered.

The remaining columns are the feature annotations. "A1" is for Annotator 1. "A2" is for Annotator 2. For more info on the five features, see the Annotation Guide. For most items, the "A2" columns will be empty.

 

