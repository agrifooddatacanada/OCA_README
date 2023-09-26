
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
Bundle SAID: unavailable

"capture_base" SAID: "EMMfWauTsYGgp5M-lnHQpQlCoJVZUAZcpzQZMs0BhSaE",
"character_encoding" SAID: "E2GPfjPkdaREcmIPSKATfVl0mYY9FkBH51qc2ne2GvuQ",
"information (en)" SAID: "E7BPqrJj3Tt_ktgiQ_6X71YhpZrS_Op0oDlsP8BX6NdY",
"label (en)" SAID: "EddB6bRI48zIK0HQfVlGuYZwv6LRbQ-8XEEfAmd7mZ_w",
"meta (en)" SAID: "EwnYgamepBtiRJ235k4yNkgIvbZjn5O8TtaSUHhdnaIo",
"unit" SAID: "EHdDiB3UhFNhHpxWA8M3oLT0nLGd1yJOMPLYP0Pg6bZU"
******************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
******************************************************************
Layer name: capture_base/1.0
SAID: EMMfWauTsYGgp5M-lnHQpQlCoJVZUAZcpzQZMs0BhSaE
classification: CRDC:RDF40

Schema attribute: capture_base/1.0 
   animal_id: Text
   body_fat: Numeric
   bone_wt: Numeric
   date: Numeric
   decl_bull: Text
   decl_cow: Text
   decl_heifer: Text
   decl_steer: Text
   discrepancies: Text
   fat_color: Text
   fatclass_BGA: Numeric
   fatclass_UG: Numeric
   grade_fat: Numeric
   hotcarcass_wt: Numeric
   image_id: Text
   inter_fat: Numeric
   lean_color: Text
   lean_wt: Numeric
   leanyield_BGA: Numeric
   leanyield_UG: Numeric
   live_wt: Numeric
   liver_wt: Text
   marbling: Text
   muscleclass_BGA: Numeric
   muscleclass_UG: Numeric
   qualitygrade_BGA: Text
   qualitygrade_UG: Text
   rib_fat1: Numeric
   rib_fat2: Numeric
   rib_fat3: Numeric
   rib_wt: Numeric
   ribeyearea_sqin: Numeric
   ribeyearea_sqmm: Numeric
   ribeyelength_BGA: Numeric
   ribeyelength_UG: Numeric
   ribeyewidth_BGA: Numeric
   ribeyewidth_UG: Numeric
   sub_fat: Numeric
   yieldgrade_BGA: Text
   yieldgrade_UG: Text

******************************************************************
Layer name: character_encoding/1.0
SAID: E2GPfjPkdaREcmIPSKATfVl0mYY9FkBH51qc2ne2GvuQ
default_character_encoding: utf-8

Schema attribute: character_encoding/1.0 
   animal_id: utf-8
   body_fat: utf-8
   bone_wt: utf-8
   date: utf-8
   decl_bull: utf-8
   decl_cow: utf-8
   decl_heifer: utf-8
   decl_steer: utf-8
   discrepancies: utf-8
   fat_color: utf-8
   fatclass_BGA: utf-8
   fatclass_UG: utf-8
   grade_fat: utf-8
   hotcarcass_wt: utf-8
   image_id: utf-8
   inter_fat: utf-8
   lean_color: utf-8
   lean_wt: utf-8
   leanyield_BGA: utf-8
   leanyield_UG: utf-8
   live_wt: utf-8
   liver_wt: utf-8
   marbling: utf-8
   muscleclass_BGA: utf-8
   muscleclass_UG: utf-8
   qualitygrade_BGA: utf-8
   qualitygrade_UG: utf-8
   rib_fat1: utf-8
   rib_fat2: utf-8
   rib_fat3: utf-8
   rib_wt: utf-8
   ribeyearea_sqin: utf-8
   ribeyearea_sqmm: utf-8
   ribeyelength_BGA: utf-8
   ribeyelength_UG: utf-8
   ribeyewidth_BGA: utf-8
   ribeyewidth_UG: utf-8
   sub_fat: utf-8
   yieldgrade_BGA: utf-8
   yieldgrade_UG: utf-8

******************************************************************
Layer name: unit/1.0
SAID: EHdDiB3UhFNhHpxWA8M3oLT0nLGd1yJOMPLYP0Pg6bZU

Schema attribute: unit/1.0 
   body_fat: kg
   bone_wt: kg
   grade_fat: mm
   hotcarcass_wt: kg
   inter_fat: kg
   lean_wt: kg
   leanyield_BGA: %
   leanyield_UG: %
   live_wt: kg
   liver_wt: kg
   rib_fat1: mm
   rib_fat2: mm
   rib_fat3: mm
   rib_wt: kg
   ribeyearea_sqin: sq in.
   ribeyearea_sqmm: sq mm.
   ribeyelength_BGA: in
   ribeyelength_UG: in
   ribeyewidth_BGA: in
   ribeyewidth_UG: in
   sub_fat: kg

******************************************************************
Layer name: label/1.0
SAID: EddB6bRI48zIK0HQfVlGuYZwv6LRbQ-8XEEfAmd7mZ_w
language: en

Schema attribute: label/1.0 
   animal_id: Alpha-numeric ID of carcass
   body_fat: Amount of adipose tissue in the live animal
   bone_wt: Weight of bones in carcass
   date: Date of sampling
   decl_bull: ID of declared bull
   decl_cow: ID of declared cow
   decl_heifer: ID of declared heifer
   decl_steer: ID of declared steer
   discrepancies: Recorded discrepancies
   fat_color: Level of colouring on fat
   fatclass_BGA: Level of fat on carcass
   fatclass_UG: Level of fat on carcass
   grade_fat: Amount of subcutaneous fat on ribeye muscle
   hotcarcass_wt: Weight of carcass
   image_id: Image ID
   inter_fat: Amount of inter muscular fat
   lean_color: Level of colouring on lean meat
   lean_wt: Weight of carcass
   leanyield_BGA: Amount of lean meat tissue
   leanyield_UG: Amount of lean meat tissue
   live_wt: Weight of animal
   liver_wt: Weight of liver
   marbling: Level of marbling
   muscleclass_BGA: Degree of muscling
   muscleclass_UG: Degree of muscling
   qualitygrade_BGA: Level of meat quality
   qualitygrade_UG: Level of meat quality
   rib_fat1: Amount of subcutaneous fat measurement 1
   rib_fat2: Amount of subcutaneous fat measurement 2
   rib_fat3: Amount of subcutaneous fat measurement 3
   rib_wt: Weight of rib section
   ribeyearea_sqin: Area of ribeye in square inches
   ribeyearea_sqmm: Area of ribeye in square millimetres
   ribeyelength_BGA: Length of ribeye
   ribeyelength_UG: Length of ribeye
   ribeyewidth_BGA: Width of ribeye
   ribeyewidth_UG: Width of ribeye
   sub_fat: Amount of subcutaneous fat
   yieldgrade_BGA: Percentage of carcass that is saleable at retail
   yieldgrade_UG: Percentage of carcass that is saleable at retail

******************************************************************
Layer name: information/1.0
SAID: E7BPqrJj3Tt_ktgiQ_6X71YhpZrS_Op0oDlsP8BX6NdY
language: en

Schema attribute: information/1.0 
   bone_wt: After removal of meat and other tissues
   decl_bull: Animals declared bull
   decl_cow: Animals declared cow
   decl_heifer: Animals declared heifer
   decl_steer: Animals declared steer
   discrepancies: Animals with discrepancies between input sheet and tracing data
   fatclass_BGA: Measured using BioGel application
   fatclass_UG: Measured using ultrasound
   grade_fat: Numerical score reflects the amount of subcutaneous fat covering the ribeye muscle at the 12th rib. Measured using a grading ruler.
   hotcarcass_wt: Hot/unchilled weight post slaughter\r\n& removal of head hide intestinal weight and organs. Used to determine yield grade and dressing percentage
   image_id: ID corresponding to image in tracings folder
   lean_wt: Weight of meat available for consumption or further processing after removal of fat and non-muscle tissues
   leanyield_BGA: Weight of lean meat  from a beef carcass after processing and trimming of external fat bone and other non-usable parts. Expressed as a percentage of total carcass weight. Used BioGel application
   leanyield_UG: Weight of lean meat  from a beef carcass after processing and trimming of external fat bone and other non-usable parts. Expressed as a percentage of total carcass weight. Used ultrasound grading
   live_wt: Prior to being slaughtered
   marbling: Amount of intramuscular fat in lean tissue
   muscleclass_BGA: Based on the relative contibution to the total lean meat yield of the carcass. Includes measurements on the round loin rib and chuck. Assessed using a 5 point scale for grading. Used BioGel application
   muscleclass_UG: Based on the relative contibution to the total lean meat yield of the carcass. Includes measurements on the round loin rib and chuck. Assessed using a 5 point scale for grading. Used ultrasound grading
   qualitygrade_BGA: Measured using Bio Gel Application
   qualitygrade_UG: Measured using ultrasound
   rib_fat1: Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib.  Assessed using a grading ruler
   rib_fat2: Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib.  Assessed using a grading ruler
   rib_fat3: Measured depth of subcutaneous fat over the quartered rib site between the 5th & 13th rib.  Assessed using a grading ruler
   rib_wt: Includes ribs and associated meat and fat
   ribeyearea_sqin: Measured using a grid system
   ribeyearea_sqmm: Measured using a grid system
   ribeyelength_BGA: Measured along the length of the ribeye muscle from anterior to posterior. Used BioGel application
   ribeyelength_UG: Measured along the length of the ribeye muscle from anterior to posterior. Used ultrasound grading
   ribeyewidth_BGA: Measured at the widest point of the ribeye muscle. Used BioGel application
   ribeyewidth_UG: Measured at the widest point of the ribeye muscle. Used ultrasound grading
   yieldgrade_BGA: BioGel application. Y1 having the highest estimated yield and Y5 having the lowest. Based on external fat depth ribeye area hot carcass weight and estimates of kidney pelvic and heart fat.
   yieldgrade_UG: Ultrasound. Y1 having the highest estimated yield and Y5 the lowest. Based on external fat depth ribeye area hot carcass weight and estimates of kidney pelvic and heart fat.

******************************************************************
Layer name: meta/1.0
SAID: EwnYgamepBtiRJ235k4yNkgIvbZjn5O8TtaSUHhdnaIo
language: en
name: Schema2010_Jan-Nov_CGRD
description: Schema of 2010 data file for beef carcass grading and rib dissection data.
******************************************************************
END_OCA_BUNDLE