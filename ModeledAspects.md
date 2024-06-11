| Modeled aspect | Sum | Papers |
|----------------------------|:--------:|:--------:|
| UI general/ screen | 20 | S4, S7-S11, S14-S20, S24-S30 |
| interaction/ action/ function/ service | 12 |  S4-S7, S11, S17-S19, S21, S24, S26, S29 |
| appearance/ look and feel | 8 | S1-S3, S5, S17-S19,  S28 |
| UI components/ elements | 8 | S1-S5, S13, S28, S29  |
| workflows/ navigation/ transition | 7 |  S2, S6, S7, S12, S13, S24, S29 |
| user groups, specifics, capabilities | 6 | S2, S13, S21, S24, S25, S30 |
| input/ output | 5 | S2, S6, S11, S21, S29  |
| requirements | 5 |  S13, S22, S23, S25, S29 |
| data structure | 4 |  S13, S22, S26, S29 |
| presentation | 3 | S2, S13, S24  |
| context information (device usage, functions of images, contextual recommendations) | 3 | S24, S25, S30  |
| adaptation rules | 2 | S8, S30 |
| information architecture (data, wiki content) | 1 |  S12 |

Some more details:
-  S3 models UI concepts in detail, but a concrete connection to standards such as WCAG and concrete developer support is missing. They have highlighted a set of attributes  that are important for accessibility, such as a caption, in a table  but the paper lacks descriptions on how developers should handle this caption, e.g., what ranges should be provided for which user groups, and detailed models representing accessibility requirements are not provided.
- S2 models context concepts in an ontology, e.g., a disability profile, device information, or about the user identity, and provides a UI meta-model and a meta-model for representing concepts relevant to low vision. The connection between low vision requirements and interfaces is not explicitly modeled but described in algorithms for mappings and the relationship from requirements to standards such as WCAG is missing.
- S8 and S9 provide examples for modeling user tasks in a very abstract way but they lack explicit models providing accessibility information. 
- S20 and S8 describe some rules to follow if certain events occur, e.g., if the user is color blind to change the foreground color to black and the background color to white, or if the UI is activated and the user has any kind of visual impairment the menu related to captions is disabled. A challenge in these approaches is that the rules are informal as they provide no connection to WCAG or other standards, and some of the rules are again too specific, e.g., changing the text size to 14 if the size of the text of the UI is smaller than 14 points and the user has low vision does not help all people with low vision - it might again be too small for certain user groups. 
- S10 lists context dimensions in a table but lacks (1) information on how to change the information based on personal profiles and (2) relation to concrete WCAG guidelines and other standards. 
- S13 lists the relation between WCAG guidelines and model types of WebML in the text but without providing examples for concrete models.
- S21 describes the problem domain and maps different barrier types in UIs to different types of users but the paper lacks details on how to map concrete UI concepts in models to accessibility concepts.
- S19 suggests the use of an accessibility-supportive repository but without mentioning any concrete model, it lacks a mapping from accessibility requirements to the generation process, there is no link to WCAG or other standards in concrete models, and it provides no functional requirements for accessibility in the shown use case or activity diagram. 
-S22 attaches concrete guidelines as requirements to models and generates them as comments in the code. In addition, they use a framework to submit HTML code and obtain as output accessible code. This approach seems to be quite mature in comparison to the other approaches, however, it lacks details on how to model certain aspects to be reusable for other developers in another tooling, and the generated code comments seem to be only usable in combination with their tooling, e.g., it generated cryptic IDs which have to be interpreted to show developers which WCAG, Web Service or Mobile Best Practice guideline was mentioned. 
- S26 provides a mapping between concrete user functions and accessibility guidelines as well as a mapping between user functions and concrete UI concepts. In comparison to other publications, this was already a good start which works well for their described use case. What it lacks is how to generalize this approach beyond concrete user functions. Moreover, a mapping to concrete users and their needs is missing.
