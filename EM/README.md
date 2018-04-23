#AFSC_Survey_Uncertainty/EM

### Directory for simplifed age-structured assessment model.

Directory contains a simple ADMB single-sex, age-structured assessment model for propagating survey uncertainty through a general representation of the assessment process.

### Model Types

Name          | Model Type                          | Description                          | Data
--------------|-------------------------------------|--------------------------------------|----------------------------
pella.tpl     | Surplus Production                  | Pella-Tomlinson surplus production model, which is a generalized version of Schaefer if estimation of p is turned OFF (phase =-1 in .ctl file). | **1** Catch, **2** survey.
simpleASA.tpl | Simple Age-structured Assessment    | Simple single-sex age-structured assessment model with fixed natural mortality (M). | **1** Catch, **2** Index, **3** Age proportions of catch and index. From Arni Magnusson.
fullASA.tpl   | Full Age-structured Assessment      | Modified MESA rockfish assessment model | **1** Catch, **2** Index, **3** Agecomp-Fishery, **4** Agecomp-Survey. From GOA Northern Rockfish.

