# L1Menu_Collisions2022_v1_2_0

[![online preview](https://img.shields.io/badge/Online%20preview-click%20here-blue)](https://htmlpreview.github.io/?https://github.com/cms-l1-dpg/L1MenuRun3/blob/master/development/L1Menu_Collisions2022_v1_2_0/L1Menu_Collisions2022_v1_2_0.html)

**Comment:** 
New version of the menu for Run3 with 5 additional seeds [JIRA: https://its.cern.ch/jira/browse/CMSLITDPG-995]:
   - L1_ETMHF70 (bit 418) with PS = 0
   - L1_ETMHF80 (bit 419) with PS = 1
   - L1_ETMHF90 (bit 420) with PS = 1
   - L1_ETMHF70_HTT60er (bit 427) with PS = 0
   - L1_ETMHF80_HTT60er (bit 428) with PS = 1

In order to accomodate the new seeds preserving the order, the following seeds have been moved:
   - 428-432 -> 429-433

**NOTE**: The default behavior of the script sets the prescales of seeds using NotBptx or Bptx to zero. This is due to problems emulating NotBptx in ZeroBias. If you wish to include the prescale information for these seeds, use the --includeBptx option.

Few differences w.r.t. default PS table of menu v1_1_0:
   - L1_SingleLooseIsoEG26er1p5 (bit 176) enabled (as it was at the end of 2018)
   - L1_DoubleMu0er1p5_SQ_dR_Max1p4 (bit 59) with PS=50 (instead of 2)