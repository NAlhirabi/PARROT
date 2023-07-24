# PARROT
PARROT: Interactive Privacy-Aware Internet of Things Application Design Tool
LICENSE: Creative Commons Attribution-NonCommercial 4.0 International License


The objective of this tool is to simplify the creation of privacy-aware IoT applications for developers. It provides a simple interface that allows dragging and dropping of objects, referred to as "nodes," from a diverse palette containing sensors, clouds, and other relevant components.

Code description:
The PARROT tool has been developed and implemented using Eclipse Sirius (https://eclipse.dev/sirius/), a renowned platform known for its exceptional domain-specific modelling capabilities.
In the Sirius framework, the graphical representation of the domain-specific models in PARROT is made up of both declarative and imperative specifications. The declarative section focuses on defining the appearance and layout of the graphical elements, while the imperative section specifies their dynamic behaviours and interactions.

How to use the tool:
1) Yo need to have Eclipse Sirius. To download the desktop version use: https://eclipse.dev/sirius/download.html
2) Install Ecore tools. (If you are using Obeo Designer or Eclipse Modeling packages, Ecore Tools is already installed. Otherwise, you can find it here: [EcoreTools site ](https://eclipse.dev/ecoretools/)
3) Uploading PARROT Metamodel. To import the project from an archive file into an existing project (file> Import> General> project from folder or Archive). Select the folder called PARROT2023.zip. (for detailed instruction follow: Import the projects containing the sample Domain Model at https://wiki.eclipse.org/Sirius/Tutorials/StarterTutorial).
4) Launch a new runtime from your Eclipse. To launch a new eclipse application click on Run / Run Configurations and double click on Eclipse Application.
5) After running the metamodel, new window will open. Install a sample model called PARROTDesign.zip using File> Import.

Then the tool can be used to drag, drop and cngigure the privacy configuration. 

More detailed about how to upload and test the metamodel:https://wiki.eclipse.org/Sirius/Tutorials/DomainModelTutorial
