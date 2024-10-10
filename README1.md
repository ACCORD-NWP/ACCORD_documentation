# ACCORD DOCUMENTATION

## 1. Welcome to ACCORD 

All the general information about the **ACCORD consortium** is in the web page [https://www.umr-cnrm.fr/accord/](https://www.umr-cnrm.fr/accord/)

**BRIEF HISTORY:**

From the 1st of January 2021, 26 National Met Services joined their scientific research efforts towards developing the tools of excellence for NWP on Limited Area Domains and enter into a large partnership : the consortium ACCORD (**A** **C**onsortium for **CO**nvection-scale modelling **R**esearch and **D**evelopment).  
The ACCORD governance and organisation is defined in the [Memorandum of Understanding](https://www.umr-cnrm.fr/accord/?ACCORD-MoU-2021-2025). The strategy of the consortium and the common key objectives of the Members for the next five years are summarised in the [document 2021-2025 Strategy](https://www.umr-cnrm.fr/accord/?Strategy-2021-2025). Annual [Rolling Work Plans](https://www.umr-cnrm.fr/accord/?Rolling-Work-Plans-23) are derived from this strategy.



The **Assembly** of the Directors of the 26 NMSs Members of ACCORD is the upper governance body of ACCORD (**A** **C**onsortium for **CO**nvection-scale modelling **R**esearch and **D**evelopment).  

The **Programme Manager (PM)** is the highest executive officer of the management structure of the Consortium.: Claude Fischer from Météo-France.  

The **Policy Advisory Committee (PAC)** advises the Assembly on strategic and policy matters of the Consortium. It is chaired by Daniel Gellens (Belgium) and Florinela Georgescu (Romania). 

The **Scientific and Technical Advisory Committee (STAC)** advises the PM and the Assembly on scientific and technical issues. It is chaired by Saji Varghese (Ireland) and Christine Lac (France).  

The **Project team** is composed of staff provided by Members and Acceding Members to prepare and execute the RWP. It is led by a **Management Group (MG)**, chaired by the PM.

The Management Group is composed of the three **CSC leaders** (Arome, Alaro and Harmonie-Arome), the **Integration leader, the Area Leaders for Dynamics, Surface, Meteorological QA, EPS, Transversal activities, Physics, System, Data Assimilation.**  
The Project team also includes the position of **Coordinator for Network Activities (CNA)**.  

The **Support team** is composed of staff provided by Members and acceding Members to support the work of the Project team, including a **Consortium Scientific Secretary (CSS)** to assist the PM and the MG in their duties, a **Coordinator for the Data Assimilation starters KIT applications (DAsKIT coord.**) and **[Local Team Managers (LTM)](http://www.umr-cnrm.fr/accord/?LTMs)** to assure the good liaison between the Member and the project team.


![imagen](https://github.com/user-attachments/assets/7a5ac149-0b29-48d1-9b4e-113b49621934)


The NWP codes shared and developed in ACCORD use, to some extent, the IFS/ARPEGE global codes as backbone. Additional codes, not directly related to IFS/ARPEGE, are needed to form a full ACCORD model executable file (SURFEX surfaces cheme, Méso-NH physics package, specific surface assimilation codes etc.).

The full ACCORD NWP system is currently being developed along 3 main model configurations,the so-called **Canonical System Configurations** (“CSC”):

·         AROME (see [https://gmd.copernicus.org/articles/11/257/2018/gmd-11-257-2018.pdf](https://gmd.copernicus.org/articles/11/257/2018/gmd-11-257-2018.pdf))

·         HARMONIE-AROME (see [http://journals.ametsoc.org/doi/abs/10.1175/MWR-D-16-*0417.1](http://journals.ametsoc.org/doi/abs/10.1175/MWR-D-16-*0417.1))

·         ALARO (see [https://gmd.copernicus.org/articles/11/257/2018/gmd-11-257-2018.pdf](https://gmd.copernicus.org/articles/11/257/2018/gmd-11-257-2018.pdf))

The operational CSC running at ACCORD Partners are described in the article about [operational configurations](http://www.umr-cnrm.fr/accord/?Operational-configurations).

The aim in ACCORD is to progressively make a transition towards fully transversal, CSC-agnostic system configurations. This so-called “convergence” should be achieved by reaching a high degree of interoperability across the CSCs on various aspects such as physics, components of DA and EPS, scripting, and quite notably a common working environment and common work practice.

ACCORD codes are regularly updated with new R&D developments, technical code overhauls and phasing with the IFS/ARPEGE backbone codes. This evolution leads to the definition of new releases over time, aka as T-cycles. T-cycles are regularly defined by the successful integration and validation of code developments from the different partners (in ACCORD, including Météo-France contributions, and impact of the IFS/ARPEGE code changes on the LAM components when relevant).

The code evolution process is currently undergoing a modernization in terms of work environment, process and tools.The aim in ACCORD is to move to an incremental code integration with systematic evaluation of non-regression (of existing testing configurations), reproducibility of numerical results (unless otherwise stated by a contributor), new tests when appropriate. The intention is furthermore to make use of modern code configurations (e.g. like available with OOPS) and new testing tools (e.g. “DAVAÏ” [[1](http://www.umr-cnrm.fr/accord/?Canonical-System-Configurations-CSC#nb1 "The DAVAÏ testing system enables to test a code version (new development or (…)")]). All model configurations are addressed in the test procedure (ie IFS, ARPEGE and the LAMs).

The efforts devoted for code and system maintenance in ACCORD are described in the yearly updated [Rolling Work Plan](http://www.umr-cnrm.fr/accord/?Rolling-Work-Plans-23) and their staffing is regularly being reported (by the local teams) and monitored (by the Programme Management).


## 2. What do you need to know before starting to work 

Then, what you would have to do just to start is:

**Which group you belong to:**

- Specific weaknesses/problem/solution of AROME CSC
- Specific weaknesses/problem/solution of ALARO CSC
- Specific weaknesses/problem/solution of HARMONIE-AROME CSC
- Data Assimilation in the HARMONIE-AROME CSC
- **accord_da** : Data Assimilation
- **accord_dyn**: Dynamics
- **accord_eps** : EPS
- **accord_mqa** : Meteorological Quality Assurance
- **accord_phys**: Physics
- **accord_surf**: Surface
- **accord_syst**: System
- **accord_trans**: Transversal activities
- **accord_ml**: WG on Machine Learning (ML)
- **accord_vhr**: WG on Very High Resolution Modeling (VHR-MOD)
- **accord_sda**: WG on Seamless Data Assimilation, VHR-DA for NWP and Nowcasting (DA-SEAM)
- **accord_sea**: sea/ocean people connected to ACCORD
- **accord_forum_climate**: exchanges on Regional Climate Modeling between the ACCORD climate teams


Or if you belong to any of the Management groups:

- Management Group (MG)
- Management Group (MG) and Support Team (besides the LTMs), thus MG + CNA, DAsKIT coordinator and CSS
- Local Team Managers of the 26 Members (LTM)
- Local Team computer System Representatives (LTSR)
- Policy Advisory Committee (PAC)
- Scientific and Technical Advisory Committee (STAC)
- Representatives at the ACCORD Assembly (directors and delegations)

   
**Who your Area Leader is:** 

![imagen](https://github.com/user-attachments/assets/03c2db2e-28aa-4680-a387-8829052fa8b0)


## 3. Get into the code

Go to ACCORD GitHub  and get familiarized with all the common repositories etc

GitHub ACCORD is at:  [https://github.com/ACCORD-NWP](https://github.com/ACCORD-NWP)

General instructions about how to start and signs etc are at

[https://opensource.umr-cnrm.fr/projects/accord/wiki/Forge_and_contribution_instructions](https://opensource.umr-cnrm.fr/projects/accord/wiki/Forge_and_contribution_instructions)

**The repositories in ACCORD NWP GitHub**


**How to document the Code**


**Get into the more specific CSC Code and Documentation**

Go to the part of your own CSC you have all the specific information you can about your own code.

·         If you belong to ALARO:

[https://www.rclace.eu/alaro](https://www.rclace.eu/alaro)

·         If you belong to AROME:

[https://www.cnrm.meteo.fr/gmap/](https://www.cnrm.meteo.fr/gmap/)

and its Documentation is at :

 [http://www.umr-cnrm.fr/gmapdoc/](http://secure-web.cisco.com/1EbA3LEinR8xxx-WVK8d4s69RgSLAw28A5nQANykX5HCI9pXnP8GY0GvVSAD5oIsbJvS759gFkrU0UHMrWAIJyGAESDPLxhuRsEj2ok1Yjxo6JUKsdbw5k3QLpJqhkNGTmlk-RvMg1WOdVj1BZxiu6y92MsLjm6ItsyIoiFzr6h-yP0kZoak0gCPeflk5kyRGqMAXkkOj_gZz4eksDOir_NwUvfvc2Rr2ZG1cDFF0zyekZ1OJwloIOl5-77yXT6CA/http%3A%2F%2Fwww.umr-cnrm.fr%2Fgmapdoc%2F)

·         If you belong to HARMONIE-AROME:

Harmonie-AROME has its own GitHub at [https://github.com/Hirlam](https://github.com/Hirlam)

 where there is the code installed and also an attached GitHub wiki to explain there many instructions and the documentation attached to the code, that is cycle dependent.

The old Hirlam wiki page is here: [https://hirlam.org/trac/wiki/ACCORD](https://hirlam.org/trac/wiki/ACCORD)



