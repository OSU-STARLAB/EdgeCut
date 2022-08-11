Edge-based Heuristics for Optimizing Shortcut-Augmented Topologies for HPC Interconnects
========

This is the code repository of the proposed heuristic methods presented on the paper "Edge-based Heuristics for Optimizing Shortcut-Augmented Topologies for HPC Interconnects". 
Our proposed EdgeCut methods EdgeCut-Lite(ECL) and EdgeCut-Full(ECF) are compared with the state-of-the-art vertex-based randome shortcut(VRS)[^1] and simulated annealing algorithm[^2]. 


## Quick Start for our repository

If the software dependencies are met, then it is simple to run this repository. If you run cell by cell, you will get the results(total hop count, aspl, diameter, and time required) for a 8x8, 64 node ring network.
If you are interested to run all the different sizes of networks then you will need to uncomment the lines in the last cell.   

*Software dependencies*
* `Python 3.6 or higher`
* `Numpy 1.19.5 (should work with other versions too)` 



## References
 
[1] Koibuchi, M.; Matsutani, H.; Amano, H.; Hsu, D.F.; Casanova, H. A case for random shortcut topologies for HPC interconnects. 
In Proceedings of the 2012 39th Annual International Symposium on Computer Architecture (ISCA). IEEE, 2012, pp. 177–188.

[2] Kirkpatrick, S.; Gelatt, C.D.; Vecchi, M.P. Optimization by simulated annealing. science 1983, 220, 671–680.


## Contact Us
For any further questions please contact fuadk@oregonstate.edu