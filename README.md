# SafeRoutes: Designing Safety without Ambiguity 📍

> **Course:** CS 549 - Human Computer Interaction, Sabancı University  
> **Date:** Fall 2025

## Project Team
* **Sarin İç** - Experimental User Study Testing
* **Aişe Özaytürk** - Experimental User Study Analysis
* **Mustafa Enes Özdel** - Interaction Prototype Development
* **Kadir Burak Tandoğan** - Iterative Prototyping

---

## Introduction
SafeRoutes is a mobile navigation interface that aims to reduce the feelings of insecurity and uncertainty experienced by users when choosing routes, especially when moving around the city at night. By making routes visible not only in terms of time and distance but also in terms of perceived safety, SafeRoutes aims to support users in making more informed, comfortable, and safer decisions. The interface allows the user to see three different route options after entering their starting and ending points. These options are categorized as “safest”, “balanced”, and “shortest”, and safety-related information is presented to the user in a calm, explanatory, and non-alarmist language. Thus, SafeRoutes aims to address the emotional and perceptual needs arising in the context of nighttime mobility while maintaining the functionality offered by classic navigation systems. In this section, we justify why the interface is necessary and what users expect from this system by explaining SafeRoutes' target users, the problem it addresses, and the context in which the interaction takes place.

SafeRoutes' target users are individuals walking alone in urban areas, especially at night. Within this group, women in particular experience heightened safety concerns in public spaces, leading to greater limitations on their movements (Erkan & Topcu, 2021). However, SafeRoutes is designed to encompass all urban users who experience safety concerns at night. For these users, safety isn't simply an objective risk assessment. How they perceive their surroundings, how much control they feel over their environment, and how they interpret uncertainty directly influences their route choice. Therefore, users often choose the route that makes them feel more comfortable and secure, rather than the shortest one.

Current navigation systems mostly rank routes based on objective criteria such as time, distance, and traffic (Kaur et al., 2021). However, for users moving around the city, especially at night, one of the most important factors determining route selection is perceived safety (Şenol, 2022). Dark streets, deserted areas, negative past experiences, and feelings of uncertainty about the environment deeply affect users' spatial behavior and shape their movement decisions not only based on efficiency but also on emotional and perceptual evaluations (Hamedanian & Ghadermazi, 2022). Despite this, current systems do not present this safety concern to the user as a visible, understandable, and manageable dimension. This leads to a two-way problem. On the one hand, users excessively restrict their movements by avoiding areas where they feel unsafe. On the other hand, because they lack sufficient and meaningful information about safety, they may unintentionally choose uncomfortable or stressful routes. SafeRoutes steps in precisely at this point, aiming to provide an interface that centers the user's perception of safety, makes safety-related information visible and explainable, and thus supports the user in making their own decisions more consciously, comfortably, and with greater control.

Therefore, the context in which interaction takes place in SafeRoutes should be considered differently than ordinary navigation use. Users often choose routes on their mobile devices, often while anxious to get somewhere on time, alone outdoors, or knowing they will soon be alone. This moment is not only about accessing information, but also about making decisions while trying to manage uncertainty. The user tries to anticipate their surroundings, intuitively weigh risks, and act quickly. Therefore, a quick and understandable interface becomes a critical requirement. Similarly, the amount of information presented must be balanced. Insufficient information creates distrust, while excessive information can cognitively exhaust the user, making decision-making impossible. User expectations are concentrated precisely between these two extremes, at a point of balance where they feel sufficiently informed but not overwhelmed.

To make these requirements more concrete, we structured the study around a single core use case. We assumed the user needed to travel from one point to another in the evening, for example, from Kadıköy to Beşiktaş. After entering the starting and ending points, the user is presented with three route options. These options are presented not only with efficiency metrics such as time and distance, but also with information that supports the perception of safety. If the user wishes, they can report any situation they anticipate encountering during the journey and express their experience with a brief evaluation at the end of the trip. This flow allowed us to integrate the safety dimension into the experience without disrupting basic navigation behavior such as route selection, and to transform safety from a passive score into a process where the user can contribute and feel more like an agent.

In conclusion, the fundamental element that necessitates SafeRoutes is that the perceptual and emotional burden users experience during nighttime mobility remains invisible in current navigation experiences. Users make decisions not only about where they are going, but also about how they will feel and how much control they will have during the journey. What people expect from SafeRoutes is that they can choose a route where they feel safer, understand the reasons behind that choice, and not be left alone when making a decision. We position this section as a foundation that connects the design principles and evaluation approach we use in subsequent stages to these requirements.

## References

Erkan, N. C., & Topcu, B. S. (2021). Gender-based differences in fear of crime in public spaces: An investigation of a safe district in Istanbul. Urbani Izziv, 32(2), 87–97. https://doi.org/10.5379/urbani-izziv-en-2021-32-02-02

Hamedanian, F., & Ghadermazi, S. (2022). Challenges for Iranian Women in Daily Urban Safety. Frontiers in Sociology, 7. https://doi.org/10.3389/fsoc.2022.790905

Kaur, R., Goyal, V ., Guntur, V . M. V ., Saini, A., Sanadhya, K., Gupta, R., & Ratra, S. (2021). A Navigation System for Safe Routing. Proceedings - IEEE International Conference on Mobile Data Management, 2021-June. https://doi.org/10.1109/MDM52706.2021.00047
Lazar, J., Feng, J. H., & Hochheiser, H. (2017). Research Methods in Human-Computer Interaction (2nd ed.). Morgan Kaufmann.
Norman, D. A. (2013). The design of everyday things (Revised and expanded edition). Basic Books.

Şenol, F. (2022). Gendered sense of safety and coping strategies in public places: a study in Atatürk Meydanı of Izmir. Archnet-IJAR: International Journal of Architectural Research, 16(3), 554–574. https://doi.org/10.1108/ARCH-08-2021-0213

