| Number of Papers | Modeling Languages and Frameworks | Papers |
|----------------------------|:--------:|:--------:|
|10  | UML         |S1, S5, S8, S11, S18, S22, S23, S26, S28, S29   |
|9  | Cameleon Reference Framework   |S12-S14, S16, S19, S20, S22, S26, S27 |
|6  | Eclipse Modeling Framework (EMF)   |  S1, S5, S13, S16, S19, S23 |
|5  | User Interface eXtensible Markup Language (UsiXML)  |  S13, S14, S16, S19, S27 |
|5  | Meta Object Facility (MOF)       |  S5, S14, S19, S23, S28   |
|4  | UIML   |  S12, S16, S19, S21 |
|4  | EGOKI  |  S12, S14, S19, S21 |
|3  | Graphical Modelling Framework (GMF)   |  S13, S16, S19 |
|2  | SPA4USXML   |  S14, S19 |
|2  | MD<sup>2</sup> and Xtext  |  S2, S3 |
|1  | Xtend   |  S3 |
|1  |  ISATINE Framework   |  S4 |
|1   | WebML    |  S24 |
|1   | UseML   |  S27 |
|1   | Advanced Adaptation Logic Description Language (AAL_DL)   |  S20 |
|5  | Own DSL   |  S7, S9, S10, S17, S22 |
|4  | no details given   |  S6, S15, S25, S30 |

Some more details:

UML
- S5 describes accessible UIs, the interaction platform, and the execution platforms in a metamodel using UML Class Diagrams and presents the according models in the publication using UML Object Diagrams. 
- S23 describes models as UML Class Diagrams  using the Eclipse Graphical Modeling Project. 
- S11 and S22 use UML Use Case and Activity Diagrams to describe the usage of and navigation in a system and UML state chart diagrams to describe UI behavior.

- S4 relies on the ISATINE Framework, a framework for user interface adaptation. It decomposes user interface adaptation into seven adaptation stages.
- S27 uses UseML, an XML-based markup language for useware engineering which includes hardware and software components for the use of technical systems. It allows for user task modeling.

Developed DSLs
- S7, S9, and S10 rely on the same developed DSL which is based on XML and allows to define features, such as the screen, UI elements, and interaction, as well as workflows.
- S17 talks about an abstract user interface description language. They show a high-level graphical abstraction of one model but not any of the models explicitly.
- S22 created a modeling approach fitting to the Cameleon Reference Framework, e.g., extending UML class descriptions with events. Again, concrete details and model examples are missing.

Approaches using General-Purpose Languages (GPLs) or Domain-Specific Languages (DSLs)
- S3 extended their DSL, e.g. Xtext rule for integration of keyboard navigation. They used MD2, Xtext, and Xtend. 
- S7 described the screen, the user interface elements, and the interaction within the app using their own proposed DSL. 
- S2 extended their DSL (MD2, Xtext, Xtend) to include accessibility features and then incorporate alerts/indicators in the model editor. 
- S9 modeled app interaction (output, input, action, transition/navigation) in XML format.  This work is based on textual and their own XML-based DSL. 
- Similarly, S10 created a model in XML format based on textual and their own XML-based DSL. 
- S23 developed an information architecture from the namespaces (textual descriptions that are used to categorize pages and other media files such as PDFs, MP3 files, videos, XML files, etc.). They then proposed MDE to allow Wiki users to create their own metamodel to structure information. No details are provided on the DSL. 
- S18 focused on the earliest possible integration of accessibility requirements at the macro level during the development process of an e.g. Web application. They use UML in this paper. 
- S20 proposed a model-based capture of accessibility requirements and identified "essential" models as the task model, dialog model, and presentation model. They use the Cameleon reference framework. 
- S21 proposed a concept that comprises two parts (a) Generic Parallel Process (GPP) which is a supportive process that runs in parallel to the "typical development process" b) Accessibility-supportive Repository (ASR). This paper does not share DSL details and it remains at the level of requirements capture and modeling. 
- S22 used user interface description language, UIML, and ontologies for capabilities as input. The resource Selector module selects the most appropriate resource for each interaction element for the specific user and the specific service. 
- In S8, the user has to define accessibility requirements for a specific case, connect them to UML artifacts, and connect them to a WCAG ontology. This can be used to generate classes for the web application which include comments for accessibility guidelines to be followed. 
- S30 discussed the idea of changeover from universal to user-centered design and the extension of MDE for examining the possibilities of conceptual modeling to develop Web applications. This paper has not detailed any DSL and just provided high-level ideas, and discussed several related works. 
- S6 proposed the idea of decomposing the corresponding Android Application Package (APK) through reverse engineering utility to automatically extract the manifest file, layouts (XML), application code, user interface artifacts, and resources (picture and animation) in real-time. It then shows an interface (accessibility service) for blind users to customize their interface on the basis of i) context ii) screen layouts iii) interaction pattern (voice, haptic, touch, etc) and generates an interface for the mobile application. They use user information modeling, UI adaptation ontology, and context modeling but no language is mentioned. 
- S16 defined UsiXML models as Tasks and Concepts, Abstract User Interface (AUI), Concrete User Interface (CUI) and Final User Interface (FUI). They generate a graphical editor for the CUI design, and then the designer determines the accessibility requirements to be fulfilled and uses the UsiXML CUI model-based graphical editor.

- S4 developed an accessibility context ontology with concepts such as the user disability profile, the user situations, the user profile, the technical context, and the environment context. This ontology and its instances will act as input to the next PIM to PIM transformation. Accessibility ontology is one of their main contributions. For a given accessibility context, an ontology instance and the non-adapted PIM UI will be input. The resulting PIM will be an adapted UI model (i.e., BlindnessPIM-Metamodel, DeafnessPIM-Metamodel, LowVisionPIM-Metamodel). Finally, the adapted UI PIM is transformed into a PSM model depending on the platform (i.e., web, mobile, desktop)
- S17 describes an abstract UI description using a UIDL. They have developed a prototype using a custom UIDL but future plans indicate moving to USIXML. A runtime model of the UI is then constructed by processing the AUI description through an AUI engine. Afterwards, the abstract UI is translated into a concrete UI and a widget toolkit is then used to present the user with the final UI, by means of specific output devices. UI model that is constructed by the AUI engine serves as an information source for all the different rendering agents. Representation of the UI is delegated to modality-specific rendering agents that use the UI model at the information source.
- S24 proposes improvements to be made to WebML so that the adapted models become capable of mapping WCAG guidelines requirements. They propose the inclusion of WCAG 2.0 accessibility requirements in different models and code transformation templates of WebML. 
- S26 collects requirements through user-centered design and incorporates those in MDE for a semi-automatic UI generation. They model the application logic and generate abstract and concrete models of the user interface.
- S28 proposes a generic framework that describes all the issues involved in creating accessible e-learning content. It defines high-level requirements in a platform-independent model and instantiates it to respond to different accessibility objectives. 
- S11 integrates accessibility requirements through adaptation rules in model-based UI tools and then UI is automatically generated by incorporating the adaptation rules. This paper mainly focuses on the adaptation rules rather than the MDE tasks. It develops a graphical tool that further allows experts to include new language transformations and new adaptation rules in the Adaptation Integration System, and uses the AAL_DL language and Cameleon Reference Framework. 

Platform-Independent Model (PIM) and Platform-Specific Model (PSM) approaches
- S4, S27, and S29 use general DSL as well as both platform-independent model (PIM) and platform-specific model (PSM) approaches.
   - S4 proposed a set of three MOF-based metamodels for the modeling of (a) an accessible UI, (b) an interaction platform, and (c) an execution platform. They then proposed an adaptation of an accessible UI model to the specificities of the interaction platform model via model transformation. Accessible UI metamodel provides elements to describe a UI as a set of widgets and their content while imposing accessibility features. Interaction platform metamodel enables the description of hardware properties and input/output devices of a specific target platform (based on W3C Composite Capability/Preference Profiles 1.0). Execution platform metamodel supports the modeling of UI elements of a target language, e.g. XHTML, Java, Objective C. 
   - S27 defined a task model and use model. The task model describes the tasks to be carried out by the user and the use model extends the XML description of the task model with additional nodes and attributes. The Use model describes the workflow independent of technology like input, output, device, platform, etc. This work is based on the Cameleon reference framework, UsiXML, and UseML. 
   - S29 proposed the concept of mental models and their integration into the design process of accessible eLearning environments through extending MDE. This work uses UML. 

PIM approaches
- S13 uses MDE to identify and categorize requirements \jm{check - not found this way in the paper}, adapt abstract user interface based on requirements, and configure User Interface with adaptation rules based on user group accessing media player. They use UsiXML and the Cameleon Reference Framework.
- S14 focuses on the inclusion of WCAG requirements in the MDE process to face accessibility concerns early on in the development process.
- S15 defines a set of models (Accessibility Context Model, Ontology Model, Adaptation Rules, Interface Model, Interface Metamodel) to generate the adaptive target code.
- S19 uses both general DSL and a PIM approach. They describe a model editor that helps the developer to configure UI models more rapidly within the context of accessibility requirements. SPA4USXML and Egoki are used in this paper.
