## HT Docking Data
This site will be updated to include links to the data from our paper.


## Data
The data is avilable here via [Globus](https://app.globus.org/file-manager?origin_id=a386b552-6086-11ea-9688-0e56c063f437&origin_path=%2Fdata%2Fcleaned_docking_dat%2F)


### Top Level Files
The top level direcetory is accessible here: [https://app.globus.org/file-manager?origin_id=a386b552-6086-11ea-9688-0e56c063f437&origin_path=%2Fdata%2Fcleaned_docking_dat%2F](https://app.globus.org/file-manager?origin_id=a386b552-6086-11ea-9688-0e56c063f437&origin_path=%2Fdata%2Fcleaned_docking_dat%2F)
|Folder | Description| 
|------------ | -------------|
|2D | Contains CSV files for each protein indivuidal. They do not contain more data from the aggregated top level ORD and ORZ tables.| 
|3D | Contains all the SDF files organized by molecular dataset (ORZ or ORD) and protein receptor (in file name). These correspond directly 1-1 to CSV files.|
|Models | Contains all the pretrained model files referenced from the paper |
|Receptors | Contains all the pdb, receptors, and pdbqt (for AutoDock Vina) which corespond to models and proteins refererenced in filenames and columns from 2D, 3D, and Models folder. |

#### 2D Data
Filename | Description
------------ | -------------
ord_table.csv | Contains SMILES, TITLE, and docking score against all avilable proteins. Scores are based on Chemgauss4. Molecules from ORD (6M)
orz_table.csv | Contains SMILES, TITLE, and docking score against all avilable proteins. Scores are based on Chemgauss4. Molecules from ORZ (6M)

#### 3D structure complexes
The structures are avilable in SDF files here via [Globus](https://app.globus.org/file-manager?origin_id=a386b552-6086-11ea-9688-0e56c063f437&origin_path=%2Fdata%2Fcleaned_docking_dat%2F3D%2F)

#### Protein Receptors 
The protein receptors are available via [Globus](https://app.globus.org/file-manager?origin_id=a386b552-6086-11ea-9688-0e56c063f437&origin_path=%2Fdata%2Fcleaned_docking_dat%2FReceptors%2F)

#### Pretrained models

A portion of this data is backup on [FigShare](https://figshare.com/articles/dataset/Protein-Ligand_Docking_Surrogate_Models_SARS-CoV-2_Benchmark_for_Deep_LearningAccelerated_Virtual_Screening/14745234)


### Acknowledgements
* This research was supported by the Exascale Computing Project (17-SC-20-SC), a collaborative effort of the U.S. Department of Energy Office of Science and the National Nuclear Security Administration.

* We acknowledge other members of the National Virtual Biotechnology Laboratory (NVBL) Medical Therapeutics group. We acknowledge computing time via the COVID19 HPC Consortium.

* Research was supported by the DOE Office of Science through the National Virtual Biotechnology Laboratory, a consortium of DOE national laboratories focused on response to COVID-19, with funding provided by the Coronavirus CARES Act.  SJ also acknowledges support from ASCR DE-SC0021352.

* Many of the molecular datasets were collected in the following work:
*Data were collected Targeting SARS-CoV-2 with AI- and HPC-enabled Lead Generation: A First Data Release*
Yadu Babuji, Ben Blaiszik, Tom Brettin, Kyle Chard, Ryan Chard, Austin Clyde, Ian Foster, Zhi Hong, Shantenu Jha, Zhuozhao Li, Xuefeng Liu, Arvind Ramanathan, Yi Ren, Nicholaus Saint, Marcus Schwarting, Rick Stevens, Hubertus van Dam, Rick Wagner [cite this paper](https://arxiv.org/abs/2006.02431)


* Unless otherwise indicated, this information has been authored by an employee or employees of UChicago Argonne, LLC., operator of Argonne National Laboratory, with the U.S. Department of Energy. The U.S. Government has rights to use, reproduce, and distribute this information. The public may copy and use this information without charge, provided that this Notice and any statement of authorship are reproduced on all copies.
While every effort has been made to produce valid data, by using this data, User acknowledges that neither the Government nor operating contractors of the above national laboratories makes any warranty, express or implied, of either the accuracy or completeness of this information or assumes any liability or responsibility for the use of this information. Additionally, this information is provided solely for research purposes and is not provided for purposes of offering medical advice. Accordingly, the U.S. Government and operating contractors of the above national laboratories are not to be liable to any user for any loss or damage, whether in contract, tort (including negligence), breach of statutory duty, or otherwise, even if foreseeable, arising under or in connection with use of or reliance on the content displayed in this report.

* *Scientific and Technical Information Only For All Information.*

