---
sidebar_label: 'Relatório'
sidebar_position: 1
---

# Relatório de Progresso

## Sprint 1

Presentation date: 31/10/2023

### Work done / results

* Read some standards and whitepapers regarding Network Function Virtualization (NFV) and network slicing, as defined by the ETSI, GSMA, 3GPP and 5GPPP organizations.​
* Gathered papers related to NFV and network slicing.​
* Started writing the SoA. ​
* Started experimentating with Openslice, and the features it currently supports.

### Future work / challenges

* Experimenting with OpenSource Management and Orchestration (OSM), which will communicate with Openslice for the provisioning of network slices.​
* Define the software to be used to emulate a 5G core (5GC), for the network slice instantiation.​
* Define the architecture that encompasses the needed final solution, defining the NBIs and SBIs for the communication between Openslice, OSM, and the 5GC, following ETSI standards.

## Sprint 2

Presentation date: 21/11/2023

### Work done / results

* Continued writing the SoA;
* Added MANO platform to Openslice (OSM 14);
* Added VIM to Openslice (OpenStack);
* Orchestrated the workflow between Openslice and OSM.
    * Onboarded NSD and VNFD to Openslice;
    * Provisioned (deployed) a testing Network Application from the previous descriptors.


### Future work / challenges

* Explore with more detail the features of Openslice, and how can Network Slicing be implemented on it;
* Define the software to be used to emulate a 5G core (5GC), for the network slice instantiation;
* Define the architecture of the solution.