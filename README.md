# PARROT
PARROT: Interactive Privacy-Aware Internet of Things Application Design Tool
LICENSE: Creative Commons Attribution-NonCommercial 4.0 International License

**Objective:**
The objective of this tool is to simplify the creation of privacy-aware IoT applications for developers. It provides a simple interface that allows dragging and dropping of objects, referred to as "nodes," from a diverse palette containing sensors, clouds, and other relevant components.

**Related papers to the current tool:**
1) [Demo paper] Nada Alhirabi, Omer Rana, and Charith Perera. (2022). Demo Abstract:
PARROT: Privacy by Design Tool for Internet of Things. Proceedings - 7th ACM/IEEE
Conference on Internet of Things Design and Implementation, IoTDI 2022, pages
107–108. https://doi.org/10.1109/IoTDI54339.2022.00023 Demo: https://www.youtube.com/watch?v=EFiujRyOjZs
   
2) [Poster paper] Nada Alhirabi, Stephanie Beaumont, Omer Rana, and Charith Perera.
(2022). Privacy-Patterns for IoT Application Developers. In Adjunct Proceedings of
the 2022 ACM International Joint Conference on Pervasive and Ubiquitous Computing
and the 2022 ACM International Symposium on Wearable Computers, UbiComp/ISWC
’22 Adjunct, page 7–9, New York, NY, USA. Association for Computing Machinery.
https://doi.org/10.1145/3544793.3560333

4) [Journal paper] Nada Alhirabi, Stephanie Beaumont, Jose Tomas Llanos, Dulani Mee-
deniya, Omer Rana, and Charith Perera. 2023. PARROT: Interactive Privacy-Aware In-
ternet of Things Application Design Tool. Proc. ACM Interact. Mob. Wearable Ubiqui-
tous Technol. 7, 1, Article 1 (March 2023), 37 pages. https://doi.org/10.1145/3580880


**Code description:**
The PARROT tool has been developed and implemented using Eclipse Sirius (https://eclipse.dev/sirius/), a renowned platform known for its exceptional domain-specific modelling capabilities.
In the Sirius framework, the graphical representation of the domain-specific models in PARROT is made up of both declarative and imperative specifications. The declarative section focuses on defining the appearance and layout of the graphical elements, while the imperative section specifies their dynamic behaviours and interactions.

**How to use the tool:**
1) Yo need to have Eclipse Sirius. To download the desktop version use: https://eclipse.dev/sirius/download.html
2) Install Ecore tools. (If you are using Obeo Designer or Eclipse Modeling packages, Ecore Tools is already installed. Otherwise, you can find it here: [EcoreTools site ](https://eclipse.dev/ecoretools/)
3) Uploading PARROT Metamodel. To import the project from an archive file into an existing project (file> Import> General> project from folder or Archive). Select the folder called PARROT2023.zip. (for detailed instruction follow: Import the projects containing the sample Domain Model at https://wiki.eclipse.org/Sirius/Tutorials/StarterTutorial).
4) Launch a new runtime from your Eclipse. To launch a new eclipse application click on Run / Run Configurations and double click on Eclipse Application.
5) After running the metamodel, new window will open. Install a sample model called PARROTDesign.zip using File> Import.

Then the tool can be used to drag, drop and cngigure the privacy configuration. 

More detailed about how to upload and test the metamodel:https://wiki.eclipse.org/Sirius/Tutorials/DomainModelTutorial



