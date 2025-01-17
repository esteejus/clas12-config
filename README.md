# clas12-config

The standard run-group configuration files for GEMC, COATJAVA, chef workflow configurations, etc.

## Standard Combinations

Run Group | Period     | Set     | Coatjava Version | GEMC Version(s)
--------- | ---------- | --------| ---------------- | ----------------
RG-A      | Fall '18   | Pass-2  | 10.0.2           | 5.3
RG-A      | Spring '19 | Pass-2  | 10.0.2           | 5.3
RG-B      | Spring '19 | Pass-2  | 10.0.2           | 5.3
RG-B      | Fall '19   | Pass-2  | 10.0.2           | 5.3
RG-K      | Fall '18   | Pass-2  | 10.0.2           | 5.3
RG-M      | Fall '21   | Pass-1  | 10.0.2           | 5.3

Run Group | Period     | Set     | Coatjava Version | GEMC Version(s)
--------- | ---------- | --------| ---------------- | ----------------
RG-A      | Fall '18   | Pass-1  | 6.5.6.1          | 4.4.2
RG-A      | Spring '19 | Pass-1  | 6.5.6.1          | 4.4.2
RG-B      | Spring '19 | Pass-1  | 6.5.9            | 4.4.2
RG-B      | Fall '19   | Pass-1  | 6.5.9            | 4.4.2
RG-K      | Fall '18   | Pass-1  | 6.5.6.1          | 4.4.2

Run Group | Period     | Set     | Coatjava Version | GEMC Version(s)
--------- | ---------- | --------| ---------------- | ----------------
RG-C      |  |         | 10.0.2           | 5.3
RG-D      |  | | |
RG-E      |  | | |
RG-F      |  | | |
RG-L      |  | | |

## Notes

* _Regardless of your GEMC/COATJAVA versions, as of MM/DD/YYYY, running simulations can require changes to GEMC and/or COATJAVA configuration files._
  * ***The preferred approach is to just start with configuration files from this repository!***
  * For details and other options, [see this](rf.md).
* _GEMC versions prior to 5.3 do not fully support binary magnetic field maps, only ASCII._
* _GEMC versions prior to 5.4 do not support CCDB for RF configuration._
* _COATJAVA versions prior to 9.0.1 do not support AI- denoising or track-finding._
