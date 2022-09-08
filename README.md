![PyPI](https://img.shields.io/pypi/v/PAMI)
![AppVeyor](https://img.shields.io/appveyor/build/udayRage/PAMI)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/PAMI)
![GitHub all releases](https://img.shields.io/github/downloads/udayRage/PAMI/total)
[![GitHub license](https://img.shields.io/github/license/udayRage/PAMI)](https://github.com/udayRage/PAMI/blob/main/LICENSE)
![PyPI - Implementation](https://img.shields.io/pypi/implementation/PAMI)
![PyPI - Wheel](https://img.shields.io/pypi/wheel/PAMI)
![PyPI - Status](https://img.shields.io/pypi/status/PAMI)
[![GitHub issues](https://img.shields.io/github/issues/udayRage/PAMI)](https://github.com/udayRage/PAMI/issues)
[![GitHub forks](https://img.shields.io/github/forks/udayRage/PAMI)](https://github.com/udayRage/PAMI/network)
[![GitHub stars](https://img.shields.io/github/stars/udayRage/PAMI)](https://github.com/udayRage/PAMI/stargazers)





# Introduction
PAMI stands for PAttern MIning. It constitutes several pattern mining algorithms to discover interesting patterns in transactional/temporal/spatiotemporal databases.
This software is provided under [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](https://www.gnu.org/licenses/quick-guide-gplv3.html).

1. The user manual for PAMI library is available at https://udayrage.github.io/PAMI/index.html
2. Datasets to implement PAMI algorithms are available at https://www.u-aizu.ac.jp/~udayrage/software.html
3. Please report issues in the software at https://github.com/udayRage/PAMI/issues
  
  
  __Contact us by Discord__ https://discord.gg/9WgKkrSJ
  
# Installation

       pip install pami
       
# Upgrade
      
       pip install --upgrade pami
       
# Details 
Total available algorithms: 70

Click on __"Basic"__ link to viewe the basic tutorial on using the algorithm. Similarly, click on __"Adv"__ link to view the advanced tutorial on using a particular algorithm.

1. Frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/frequent.pdf)
     
   | Basic | Closed | Maximal | Top-k | CUDA | pyspark |
   |-------|--------|---------|-------|------|--------|
   |Apriori [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/basic/Apriori-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/basic/Apriori-ad.pdf) |Closed [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/closed/CHARM-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/closed/CHARM-ad.pdf)|maxFP-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/maximal/MaxFPGrowth-st.pdf)|topK [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/topk/FAE-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/topk/FAE-ad.pdf)|cudaAprioriGCT|parallelApriori [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/pyspark/parallelApriori-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/pyspark/ParallelApriori-ad%20(1).pdf)|
   |FP-growth  [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/basic/FPGrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/basic/FPGrowth-ad.pdf)|    |   | |cudaAprioriTID|parallelFPGrowth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/pyspark/parallelFPGrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/pyspark/ParallelFPGrowth-ad%20.pdf)|
   |ECLAT  [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/basic/ECLAT-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/basic/ECLAT-ad.pdf)| | | |cudaEclatGCT|parallelECLAT [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/pyspark/parallelECLAT-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/pyspark/ParallelECLAT-ad.pdf)|
   |ECLAT-bitSet [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/basic/ECLATbitset-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentPattern/basic/ECLATbitset-ad.pdf)| | | | | |
   |ECLAT-diffset|  | | | |

2. Frequent pattern mining using other measures: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/frequentUsingOther.pdf)
    
    |Basic|
    |-----|
    |RSFP|


3. Frequent pattern with multiple minimum support: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/multipleMinSup.pdf)
    
    |Basic|
    |-----|
    |CFPGrowth|
    |CFPGrowth++|
    
    
        
4. Correlated pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/correlatePatterns.pdf)

    |Basic|
    |-----|
    |CP-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/correlatedPattern/CPGrowth-st.pdf) -[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/correlatedPattern/CPGrowth-ad.pdf) |
    |CP-growth++ [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/correlatedPattern/CPGrowthPuls-st.pdf)||ad](https://github.com/udayRage/PAMI/blob/main/sampleManuals/correlatedPattern/CPGrowthPlus-ad.pdf)|
    
5. Frequent spatial pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/frequentSpatial.pdf)

    |Basic|
    |-----|
    |spatialECLAT  [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentSpatialPattern/SpatialECLAT-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentSpatialPattern/SpatialECLAT-ad.pdf)|
    |FSP-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentSpatialPattern/FSPGrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/frequentSpatialPattern/FSPGrowth-ad.pdf)|
    
    
6. Fuzzy correlated pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/fuzzyCorrelated.pdf)

    |Basic|
    |-----|
    |FCP-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyCorrelatedPattern/FCPGrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyCorrelatedPattern/FCPGrowth-ad.pdf)|

7. Fuzzy Frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/fuzzyFrequent.pdf)

    |Basic|
    |-----|
    |FFI-Miner [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyFrequentPatterns/FFIMiner-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyFrequentPatterns/FFIMiner-ad.pdf)|
    
8. Fuzzy frequent spatial pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/fuzzySpatial.pdf)

    |Basic|
    |-----|
    |FFSP-Miner [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyFrequentSpatialPattern/FFSPMiner-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyFrequentSpatialPattern/FFSPMiner-ad.pdf)|
    
9. Fuzzy periodic frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/fuzzyPeriodic.pdf)

    |Basic|
    |-----|
    |FPFP-Miner [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyPeriodicFrequentPattern/FPFPMiner-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyPeriodicFrequentPattern/FPFPMiner-ad.pdf)|
    
9. Geo referenced Fuzzy periodic frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/fuzzySpatialPeriodic.pdf)

    |Basic|
    |-----|
    |FPFP-Miner [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyPeriodicFrequentPattern/FPFPMiner-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/fuzzyPeriodicFrequentPattern/FPFPMiner-ad.pdf)|

10. High utility frequent pattern mining:  [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/highUtiltiyFrequent.pdf)

    |Basic|
    |-----|
    |HUFIM|
    
11. High utility frequent spatial pattern mining:  [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/highUtiltiyFrequentSpatial.pdf)

    |Basic|
    |-----|
    |SHUFIM|
 
12. High utility pattern mining:   [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/highUtility.pdf)

     |Basic|
     |-----|
     |EFIM|
     |HMiner|
     |UPGrowth|
     
13. High utility spatial pattern mining:  [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/highUtilitySpatial.pdf)

     |Basic|topk|
     |-----|----|
     |HDSHIM|TKSHUIM|
     |SHUIM|
     
14. Local periodic pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/localPeriodic.pdf)

     |Basic|
     |-----|
     |LPPGrowth|
     |LPPMBreadth|
     |LPPMDepth|
    
15. Partial periodic frequent pattern:

    |Basic|
    |-----|
    |GPF-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicFrequentPattern/GPFgrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicFrequentPattern/PPF_DFS-ad.pdf)|
    |PPF-DFS [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicFrequentPattern/GPFgrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicFrequentPattern/PPF_DFS-ad.pdf)|
    
16. Periodic frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/periodicFrequent.pdf)

    |Basic| Closed | Maximal |
    |-----|--------|---------|
    |PFP-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/basic/PFPGrouth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/basic/PFPGrouthPlus-ad.pdf)|CPFP [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/closed/CPFPMiner-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/closed/CPFPMiner-ad.pdf)|maxPF-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/maximal/MaxPSGrowth-st.pdf)|
    |PFP-growth++ [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/basic/PFPGrouthPlus-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/basic/PFPGrouthPlus-ad.pdf)| | |
    |PS-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/basic/PSGrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/basic/PSGrowth-ad.pdf)| | |
    |PFP-ECLAT [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/basic/PFECLAT-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicFrequentPattern/basic/PFECLAT-ad.pdf)| | |
    
17. Geo referenced Periodic frequent pattern mining:[Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/periodicFrequentSpatial.pdf)

     |Basic|
     |-----|
     |GPFPMiner|
    
18. Partial periodic pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/partialPeriodic.pdf)

    |Basic|Closed|Maximal|topk|
    |-----|-------|------|----|
    |3P-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicPattern/basic/ThreePGrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicPattern/basic/ThreePGrowth-ad.pdf)|3P-close [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicPattern/closed/PPPClose-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicPattern/closed/PPPClose-ad.pdf)|max3P-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicPattern/maximal/Max3PGrowth-st.pdf)|Topk_3Pgrowth|
    |3PECLAT [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicPattern/basic/PPP_ECLAT-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/partialPeriodicPattern/basic/PPP_ECLAT-ad.pdf)| | | | |
    

19. Periodic correlated pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/periodicCorrelated.pdf)
    
    |Basic|
    |-----|
    |EPCP-growth [Basic](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicCorrelatedPattern/EPCPGrowth-st.pdf)-[Adv](https://github.com/udayRage/PAMI/blob/main/sampleManuals/periodicCorrelatedPattern/EPCPGrowth-ad.pdf)|
    

20. Uncertain correlated pattern mining: 
    
    |Basic|
    |-----|
    |CFFI|
    
21. Uncertain frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/uncertainFrequent.pdf)
    
    |Basic| top-k |
    |-----|-----|
    |PUF|TUFP|
    |TubeP| |
    |TubeS| | 
    |UVEclat| |
    
22. Uncertain periodic frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/uncertainPeriodicFrequent.pdf)
     
     |Basic|
     |-----|
     |UPFP-growth|
     
23. Recurring pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/RecurringPatterns.pdf)

     |Basic|
     |-----|
     |RPgrowth|
     
24. Relative High utility pattern mining: 
    
    |Basic|
    |-----|
    |RHUIM|
 
25. Stable periodic pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/stablePeriodic.pdf)
    
    |Basic|
    |-----|
    |SPP-growth|
    |SP-ECLAT|
    
26. Weighted frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/weightedFrequentPatterns.pdf)
    
    |Basic|
    |-----|
    |WFIM|
    
27. Uncertain Weighted frequent pattern mining: [Sample](https://github.com/udayRage/PAMI/blob/main/sampleManuals/mainManuals/weightedUncertainFrequentPatterns.pdf)
    
    |Basic|
    |-----|
    |WUFIM|
    
28. Weighted frequent regular pattern mining: 
    
    |Basic|
    |-----|
    |WFRIMiner|
    
    
29. Weighted frequent neighbourhood pattern mining: 
    
    |Basic|
    |-----|
    |SSWFPGrowth|
 
 
     
 
     
     
