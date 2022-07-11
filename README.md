# CMSSW Heavy Ion Forest Intructions
This repository was created for students that are starting analysis and would like to learn about Forest framework. This github page is more advanced. For basic CMSSW stuff, check: https://github.com/denerslemos/CMSSW_basic_instructions/blob/main/README.md

## Forest framework
In summary the forest is a code written in C++ and python that contain all the objects to perform a physics analysis in CMS. It is basicaly a CMSSW analyzer that create Ntuples/TTrees from ROOT with many branchs divided in different folders. The structure of the code is the kept similar since a long time ago and the high-pT group is usualy responsible for that. Usualy a contact person is designed to work on the code together with other groups. 

The version of the Forest code depends on the data-taking period. The intructions/codes for each period are in this twiki page here: https://twiki.cern.ch/twiki/bin/viewauth/CMS/HiForestSetup . We usually use the latest data measured for specific colliding system 
```
CMSSW_11_2_0 on SL7 --> for 2018 PbPb at 5.02 TeV --> miniAOD
CMSSW_9_4_10 on SL6 or SL7 --> for 2017 XeXe at 5.44 TeV or pp ref at 5.02 TeV --> AOD
CMSSW_8_0_28 on SL6 --> for 2016 pPb at 8.16 TeV --> AOD
Need to add pp UL
```

In general the forest code is divided as (e.g. pPb): https://github.com/CmsHI/cmssw/tree/forest_CMSSW_8_0_28/HeavyIonsAnalysis 

