WingMorph.app
Mark W. Westneat and Stephanie Baumgart
University of Chicago 2019

Download the DMG to Mac and unarchive- you will prbably have to over-ride security settings to allow it to run.

This app loads a set of 40 coordinate points (landmarks and semi-landmarks) from geometric morphometric analysis of bird wing shape.
The pre-loaded data set is from a study of 136 waterbirds.
Data taken on other bird wings with exactly the same protocol and coordinate order can be loaded in place of the pre-loaded data.
User functionality includes:
- toggle forward and back through each wing to inspect wing geometry and calculate metrics of wing shape.
- raw coordinate (DrawRaw) view shows standard bird wing measures of wing span, wing areas, SL and WL metrics used in handwing index.
- rotated view (DrawVerticalBase) rotates all wings so that the wing base is oriented vertically.
- the DrawVertical view is used to compute the horizontal wing length to most distant primary feather.
- the DrawVertical view computes and shows 4 aerodynamic wing chords evenly spaced along the horizontal wing span.
Simple magnification and wing position buttons are provided for screen grab functions.

The SaveData button dumps a space-delimited file of all calculations for all wings, with the following variables:
wingL1- wing length to anteriormost primary feather (29-31)
wingL2- wing length to second-most anterior primary feather (29-32)
wingLH- wing length horizontal- distance from longest reaching primary (31 or 32) to vertical wingbase
arm- arm length (29-30)
hand- hand length (30-38)
limb- arm + hand
wristang- wrist angle, the angle formed by coordinates 29-30-31
wingWL- standard field measure handwing length, wrist to wing tip (30-31)
wingSL- standard field measure handwing width, wrist to fist secondary tip (30-36)
HWI- Hand Wing Index (wingWL-wingSL)/wingWL)*100
wingBase- wing base length (29-37)
kipps- standard field measure Kipp's distance (36-31)
chord1- aerodynamic wing chord from leading to trailing edge (closest to body)
chord2- aerodynamic wing chord from leading to trailing edge (mid wing next distal)
chord3- aerodynamic wing chord from leading to trailing edge (mid wing toward tip)
chord4- aerodynamic wing chord from leading to trailing edge (closest to tip)
wingAR- Aspect Ratio: wing span (29-31) squared/ total wing area
wingARH- Aspect Ratio: horizontal wing span squared/ total wing area
hwAR- HandWing Aspect Ratio: handwing span squared/ handwing area
baseAreaA- wing area of anterior wing base
baseAreaP- wing area of posterior wing base
midAreaA- wing area of posterior midwing
midAreaP- wing area of posterior midwing
tipArea- wing area of  wing tip
totalArea- total area of wing
handArea- area of handwing (midA + midP + tip)
