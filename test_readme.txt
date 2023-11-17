
BEGIN_REFERENCE_MATERIAL
******************************************************************
OCA_READ_ME/1.0
This is a human-readable schema, based on the OCA schema standard.

Reference for Overlays Capture Architecture (OCA): 
https://doi.org/10.5281/zenodo.7707467

Reference for OCA_READ_ME/1.0:
https://github.com/agrifooddatacanada/OCA_README

A schema describes details about a dataset.
In OCA, a schema consists of a capture_base which documents the attributes and their most basic features.
A schema may also contain overlays which add details to the capture_base.
For each overlay and capture_base, a hash of their original contents has been calculated and is reported here as the SAID value.

This README format documents the capture_base and overlays that were associated together in a single OCA Bundle.
OCA_MANIFEST lists all components of the OCA Bundle.
For the OCA_BUNDLE, each section between rows of ****'s contains the details of one "layer type/version" of the OCA Bundle.
******************************************************************
END_REFERENCE_MATERIAL

BEGIN_OCA_MANIFEST
******************************************************************
Bundle SAID: EMY8Z5PAJSJ4RknrB4FVHhslCAa2kecE_UuooZXHgocZ

capture_base: "EK2EbGdxi56FIUqT42NP2wl31eSCld97wJao9dhkDr9O"
meta (eng): "EAVr-Ma48cmqvrnGZ4eoIOP03nMLt6NOsZcemcwN7Eht"
meta (fra): "EIoASPl_R8FHv6pophCRBIRF6YPme00Gk1dwc4f7Ovba"
label (eng): "EHi1TwkHqdMRQoame69YSYAyiwZDvovaPqabqCbHdCSe"
label (fra): "ENwvm1CyJAmN2UTyz3fbdgRn-ZJ9Jr8opFNZZ9IU-OED"
information (eng): "EEB3Vioix69xnM0wvCtgXgomIRp9IIs4vkGXa5sEDpuy"
information (fra): "EIrCPpZVeuFEt3z9fJr4nkCOhzk6HQHqH3ZktHf-u_xQ"
unit: "EEqlOD-r3Kr2LIqgCcL-jGZHKbq-a1VyGz2zbUpLxV_e"
conformance: "ENRVpXal8XAm3XjFMczm2QIIlCUCCpWLVfVyx8Npdw8d"
character_encoding: "EGVQ6Wfpz_kQx1YgF4VdQEsip-bO3yunh3ABb0O5r4Tp"
format: "EK_Tm8FZ98uo5VQoTsPJKl4eOQMxbNYOfgSvXiHewy4v"
entry_code: "EHZvulY_pJ3W9bfIjdzUuHDf04QQkyvN4Dub2NOMWo1G"
entry (eng): "EKmiV3-xOJtNDXsXDNE6FpGKl3Yl_UglYpaQnQaseUBU"
******************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
******************************************************************
Layer name: capture_base/1.0
SAID: EK2EbGdxi56FIUqT42NP2wl31eSCld97wJao9dhkDr9O
Classification: 

Schema attributes: capture_base/1.0
    Age: Numeric
    BreastWt: Numeric
    Breed: Text
    Farm: Text
    Glucose: Numeric
    Lipase: Numeric
    LiveWt: Numeric

******************************************************************
Layer name: meta/1.0
SAID: EAVr-Ma48cmqvrnGZ4eoIOP03nMLt6NOsZcemcwN7Eht
Language: eng
Description:  Measurements of chicken gut health

Layer name: meta/1.0
SAID: EIoASPl_R8FHv6pophCRBIRF6YPme00Gk1dwc4f7Ovba
Language: fra
Description: Mesures de la santée intestinale des poulets

******************************************************************
Layer name: label/1.0
SAID: EHi1TwkHqdMRQoame69YSYAyiwZDvovaPqabqCbHdCSe
Language: eng
Schema attributes: label/1.0
    Age: Bird Age
    BreastWt: Breast Weight
    Breed: Type of breed
    Farm: Farm Letter Indentifier
    Glucose: Glucose Concentration
    Lipase: Lipase Content
    LiveWt: Live Weight

Layer name: label/1.0
SAID: ENwvm1CyJAmN2UTyz3fbdgRn-ZJ9Jr8opFNZZ9IU-OED
Language: fra
Schema attributes: label/1.0
    Age: Age de l'animal
    BreastWt: Poids de la poitrine
    Breed: type de race
    Farm: Lettre itenditifant la ferme
    Glucose: Concentration de glucose
    Lipase: Concentration de lipase
    LiveWt: Poids vif

******************************************************************
Layer name: information/1.0
SAID: EEB3Vioix69xnM0wvCtgXgomIRp9IIs4vkGXa5sEDpuy
Language: eng
Schema attributes: information/1.0
    Age: age of bird in days
    BreastWt: Breast weight in grams
    Breed: information on the type of breed
    Farm: a letter given to the farm for identification
    Glucose: glucose content in mmol/L
    Lipase: lipase content in U/L
    LiveWt: weight in grams at 28 days

Layer name: information/1.0
SAID: EIrCPpZVeuFEt3z9fJr4nkCOhzk6HQHqH3ZktHf-u_xQ
Language: fra
Schema attributes: information/1.0
    Age: Age de l'animal compté en jours
    BreastWt: Poids de la poitrine en gramme
    Breed: informations sur le type de race
    Farm: Letter assignee a chaque ferme pour identification
    Glucose: Concentration de glucose en mmol/L
    Lipase: Concentration de glucose en U/L
    LiveWt: Poids vif à 28 jours en gramme

******************************************************************
Layer name: unit/1.0
SAID: EEqlOD-r3Kr2LIqgCcL-jGZHKbq-a1VyGz2zbUpLxV_e
Measurement system: Metric

Schema attributes: unit/1.0
    BreastWt: Gram
    LiveWt: Gram

******************************************************************
Layer name: conformance/1.0
SAID: ENRVpXal8XAm3XjFMczm2QIIlCUCCpWLVfVyx8Npdw8d

Schema attributes: conformance/1.0
    Glucose: M
    Lipase: M

******************************************************************
Layer name: character_encoding/1.0
SAID: EGVQ6Wfpz_kQx1YgF4VdQEsip-bO3yunh3ABb0O5r4Tp

Schema attributes: character_encoding/1.0
    Age: utf-8
    BreastWt: utf-8
    Breed: utf-8
    Farm: utf-8
    Glucose: utf-8
    Lipase: utf-8
    LiveWt: utf-8

******************************************************************
Layer name: format/1.0
SAID: EK_Tm8FZ98uo5VQoTsPJKl4eOQMxbNYOfgSvXiHewy4v

Schema attributes: format/1.0
    Age: [0-9]{3}
    BreastWt: [A-Z0-9]{9}
    Breed: [A-Z]{15}
    Farm: [A-Z0-9]{9}
    Glucose: [A-Z0-9]{9}
    Lipase: [A-Z0-9]{9}
    LiveWt: [A-Z0-9]{9}

******************************************************************
Layer name: entry_code/1.0
SAID: EHZvulY_pJ3W9bfIjdzUuHDf04QQkyvN4Dub2NOMWo1G

Schema attributes: entry_code/1.0
    Breed: [B,S]

******************************************************************
Layer name: entry/1.0
SAID: EKmiV3-xOJtNDXsXDNE6FpGKl3Yl_UglYpaQnQaseUBU
Schema attributes: entry/1.0
    Breed: Brahma, Silkie

******************************************************************
