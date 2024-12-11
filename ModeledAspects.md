| Modeled aspect | Sum | Papers |
|----------------------------|:--------:|:--------:|
| UI general/ screen | 20 | S6, S7, S10, S11, S13-S20, S22, S26-S28, S30 | 
| interaction/ action/ function/ service | 12 |  S2, S7, S9-11, S16-S18, S21, S22, S25, S30 | 
| appearance/ look and feel | 8 | S1-S5, S11, S18 S22, |
| UI components/ elements | 8 |  S1-S5, S7, S24, S25 |
| workflows/ navigation/ transition | 7 |  S4, S9, S10, S23-S25, S30 |
| user groups, specifics, capabilities | 6 | S4, S6, S12, S21, S24, S30 |
| input/ output | 5 | S4, S9, S17, S21, S25  |
| requirements | 5 | S6, S8, S24, S25, S29  |
| data structure | 4 | S8, S16, S24, S25  |
| presentation | 3 | S4, S24, S30 |
| context information (device usage, functions of images, contextual recommendations) | 3 |  S6, S12, S30 |
| adaptation rules | 2 | S12, S13 |
| information architecture (data, wiki content) | 1 | S23  |

Some more details:
- S5 models UI concepts in detail, but a concrete connection to standards such as WCAG and concrete developer support is missing. They have highlighted a set of attributes  that are important for accessibility, such as a caption, in a table  but the paper lacks descriptions on how developers should handle this caption, e.g., what ranges should be provided for which user groups, and detailed models representing accessibility requirements are not provided.
- S4 models context concepts in an ontology, e.g., a disability profile, device information, or about the user identity, and provides a UI meta-model and a meta-model for representing concepts relevant to low vision. The connection between low vision requirements and interfaces is not explicitly modeled but described in algorithms for mappings and the relationship from requirements to standards such as WCAG is missing.
- S13 and S14 provide examples for modeling user tasks in an abstract way but they lack explicit models providing accessibility information. 
- S11 and S13 describe some rules to follow if certain events occur, e.g., if the user is color blind to change the foreground color to black and the background color to white, or if the UI is activated and the user has any kind of visual impairment the menu related to captions is disabled. A challenge in these approaches is that the rules are informal as they provide no connection to WCAG or other standards, and some of the rules are again too specific, e.g., changing the text size to 14 if the size of the text of the UI is smaller than 14 points and the user has low vision does not help all people with low vision - it might again be too small for certain user groups. 
- S15 lists context dimensions in a table but lacks (1) information on how to change the information based on personal profiles and (2) relation to concrete WCAG guidelines and other standards. 
- S24 lists the relation between WCAG guidelines and model types of WebML in the text but without providing examples for concrete models.
- S22 describes the problem domain and maps different barrier types in UIs to different types of users but the paper lacks details on how to map concrete UI concepts in models to accessibility concepts.
- S21 suggests the use of an accessibility-supportive repository but without mentioning any concrete model, it lacks a mapping from accessibility requirements to the generation process, there is no link to WCAG or other standards in concrete models, and it provides no functional requirements for accessibility in the shown use case or activity diagram. 
- S8 attaches concrete guidelines as requirements to models and generates them as comments in the code. In addition, they use a framework to submit HTML code and obtain as output accessible code. This approach seems to be quite mature in comparison to the other approaches, however, it lacks details on how to model certain aspects to be reusable for other developers in another tooling, and the generated code comments seem to be only usable in combination with their tooling, e.g., it generated cryptic IDs which have to be interpreted to show developers which WCAG, Web Service or Mobile Best Practice guideline was mentioned. 
- S26 provides a mapping between concrete user functions and accessibility guidelines as well as a mapping between user functions and concrete UI concepts. In comparison to other publications, this was already a good start which works well for their described use case. What it lacks is how to generalize this approach beyond concrete user functions. Moreover, a mapping to concrete users and their needs is missing.
