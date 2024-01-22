# What is this?
The input datasets for KGAT-pytorch: https://github.com/LunaBlack/KGAT-pytorch

## Datasets
* ```kg-all, kg-mal, kg-wikidata, none``` -> Section 4.2.1
* ```all-ablation_outX``` -> Section 4.2.2
  * ```outX``` means remapped id of each property excluded respectively.
  * Refer to ```relation_list.txt``` for property mappings.
* ```kg-all-text``` -> Section 4.2.3

##  Usage
1. Download this datasets
2. Clone https://github.com/LunaBlack/KGAT-pytorch
3. Replace ```KGAT-pytorch/datasets``` with  ```kgat-input-uec/datasets```
4. Run KGAT for recommendation

## Others
You can construct a knowledge graph loading ```rdf/kg-all-text_1204.ttl``` into GraphDB.
