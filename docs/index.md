# LegalTech for Consumer Protection

Legal Technologies for Consumer Protection is a [Maastricht University](https://www.maastrichtuniversity.nl/) interdisciplinary research conducted by the Maastricht European Private Law Institute [(M-EPLI)](https://www.maastrichtuniversity.nl/M-EPLI), the Institute of Data Science [(IDS)](https://www.maastrichtuniversity.nl/research/institute-data-science), and the Authority for Consumer and Markets in the Netherlands [(ACM)](https://www.acm.nl/en). **This research aims to explore the legal and technical means for developing innovative and transparent LegalTech software for consumer protection purposes.**

------

<!-- ![](assets/network_consumers.png) -->
<img src="assets/network_consumers.png" alt="drawing" width="690"/>

---
### Background
---

The project builds up on work carried out for DJ Justice and Consumers **Exploring IT/AI tools for monitoring online markets for consumer policy purposes** JUST/2018/CONS/PR/CO01/0123 and a follow up project collabrating with the Dutch authority for consumers and markets. This endeavor got granted a [NWO-IDG](https://www.nwo.nl/onderzoeksprogrammas/nationale-wetenschapsagenda/vernieuwing-en-netwerken/ideeengenerator-nwa-idg-0) award by the research idea of **Using AI for Consumer Protection: creating AI based persona for mystery shopping**. The project aimed to create and improve methods for monitoring e-commerce and online advertising in view of the detection of infringements of existing legal rules and further policy development in the fields of **consumer law, antidiscrimination law and privacy protection** building on interdisciplinary **law and technology research**.

The 2019 Consumer protection regulation allows consumer authorities to conduct data analysis and online mystery shopping, meaning that a consumer authority may pretend to be a consumer with certain characteristics in order to find out how the (online) seller treats the consumer and, in particular, whether one consumer gets different prices or different advertising than another consumer based on her consumer characteristics eg. a "deal hunter", "negligent shopper" or "elderly female". These selling practices are made possible by algorithmic personalized content using data analytics and computer engineering that often cross the line of the prohibition of unfair commercial practices and infringe the rights of consumers.  

A new breed of legal technologies appears to be equipped to perform investigations on these issues. Not only consumer law enforcement bodies are primarily benefited by the development of these technologies but also scholars, the goal is to study challenging questions and implement prototypes both from a legal and technical perspectives.  

---
### Publications
---

‣ **A New Order: The Digital Services Act and Consumer Protection**  
European Journal of Risk Regulation - License CC BY 4.0  
Read the paper: [DOI: 10.1017/err.2021.8](https://www.researchgate.net/publication/350917767_A_New_Order_The_Digital_Services_Act_and_Consumer_Protection)  

‣ **An exploratory study of information technology (IT) and artificial intelligence (AI) tools for consumer protection in digital markets**  
Symposium Consumer and Data Privacy 2020: [Conference](https://www.maastrichtuniversity.nl/events/symposium-consumer-and-data-privacy-digital-revolution-legal-social-and-economic-interaction)  
Poster and Findings: [DOI: 10.13140/RG.2.2.10144.30724](https://www.researchgate.net/publication/348937412_An_exploratory_study_of_information_technology_IT_and_artificial_intelligence_AI_tools_for_consumer_protection_in_digital_markets_An_European_Commission_Tender)  
Read the report: [Public version](https://drive.google.com/file/d/1c628y57bWE9gPV27oFSPz8bU18kZ82-v/view?usp=sharing)

‣ **Researching algorithmic unintentional discrimination in online advertisement and e-commerce**  
Working paper: [Preprint](https://drive.google.com/file/d/1KbCoSF8WMNm96QwaRHSV_dIEf-Lb8m7_/view?usp=sharing)  
Presentation: [Slides](https://docs.google.com/presentation/d/e/2PACX-1vSf1i7VjWyRfFLa4Kyyc0LZjbuPnX2oZc1LZ3wI1cXr9B4FzTPqglC0drcGRhytPGfq7nGO6zVO4o6m/pub?start=false&loop=false&delayms=5000)  

---
### Software
---
By definition, online automated systems that use algorithmic personalization or recommendation techniques are trained on user internet browsing's data.
This internet browsing data comes from different sources (or a combination that normally is not disclosed by the tech industry). For example:

- Google Ads impressions are mainly based on user's browsing history or IP locations.
- Google Search results use hardware data (i.e. what OS are you using).
- Prices of products of some retail websites are based on the user-website interaction helped by cookies.   
- Social Media Ads are mainly based on the user's behaviour in that social media platform
- etc.

Therefore, as of 2021, there is no one-size-fits-all technique that can be used to create AI-based Personas for online mystery shopping. However, it is possible to implement separate LegalTech software for investigations and compose user interfaces that can unite them all.

‣ [Facebook Ads API](https://pedrohserrano.github.io/legaltech-consumer-protection/Facebook_Ads_API/)  
This technology is a ready-to-use **Ads Data Analysis Pipeline** written in Python that uses the official **Facebook Graph API** to access the Facebook Ads library and gather Ads data at scale. The methodology and limitations of the code were intensively tested, as a use case, we performed a pilot data analysis on more than **8,000 Facebook Ads from the Netherlands** getting key insights of **advertisement practices** on the 2021 Dutch General Elections.

‣ [PersonaBot for Facebook Ads](https://pedrohserrano.github.io/legaltech-consumer-protection/Facebook_PersonaBot/)  
The Facebook PersonaBot is an in-house build **Python library that simulates user-agent** browsing behaviour in the **Facebook news feed**. This library is based on the Selenium web-drivers family and aims to train user-agents on different consumer traits (e.g. middle-aged female gamer) and therefore get exposed to Facebook personalized advertisement. The methodology was tested in a small set-up where Ads screenshots were collected based on different Personas.

‣ [PersonaBot for Google Ads](https://pedrohserrano.github.io/legaltech-consumer-protection/PersonaBot/)  
The Google PersonaBot is an in-house build **Python library that simulates user-agent** browsing through a set of predefined websites that are proxy for certain consumer traits. This library is based on the Selenium web-drivers family and aims to train user-agents on the defined consumer traits (religious male elderly) and therefore get exposed to personalized advertisement Google Ads in neutral websites. The methodology was tested in a small set-up where Ads screenshots were collected based on different Personas.

‣ [Dutch Products Crawler](https://pedrohserrano.github.io/legaltech-consumer-protection/Dutch_Products_Crawler/)  
This technology is an automated web scrapper, highly configurable and integrated with CD/CI Github deployments. This library is a Python-based Selenium web-driver that neatly visits the most popular retail websites from the Netherlands and collects Dutch products information including products descriptions, prices and sellers. The methodology and limitations of the code were intensively tested, as a use case, we performed a pilot data analysis on more than **200 Dutch Products** getting key insights of **algorithmic pricing** from different sellers.

---
**Can these technologies be used in anonymity by consumer protection authorities to conduct investigations? Yes, [more info here.](https://pedrohserrano.github.io/legaltech-consumer-protection/Anonymity.md/)**

---
### Links
---
‣ **Webinar on Researching Discrimination in E-Commerce and Online Advertising:**  
4 and 5 March 2021: [Original event](https://www.maastrichtuniversity.nl/events/researching-discrimination-e-commerce-and-online-advertising-webinar)  
Webinar report: [Read the report](https://docs.google.com/document/d/e/2PACX-1vTmgfNMXLEvlQCYfF9jtB7Nc_a3n1qGQCNraPnkAweTsB6E8FDJXIn4fDtlrHOY3Q/pub)  

‣ **DSRI: Data Science Research Infrastucture**  
[Website](https://maastrichtu-ids.github.io/dsri-documentation/)  
All our software is build and tested at scale in the DSRI cluster for computer science research 

‣ **M-EPLI: Maastricht European Private Law Institue**  
[Website](https://www.maastrichtuniversity.nl/M-EPLI)  and [M-EPLI talks](https://www.maastrichtuniversity.nl/research/m-epli/m-epli-talks)   

---
### People
---
‣  [Pedro V Hernandez Serrano](https://www.maastrichtuniversity.nl/p.hernandezserrano) | **Data Scientist, Institute of Data Science**  
[p.hernandezserrano@maastrichtuniversity.nl](mailto:p.hernandezserrano@maastrichtuniversity.nl) 

‣  [Catalina Goanta](https://www.maastrichtuniversity.nl/nl/catalina.goanta) | **Assistant Professor in Private Law, Faculty of Law**  
[catalina​.​goanta​@​​maastricht​university​.​nl](mailto:catalina​.​goanta​@​​maastricht​university​.​nl)  

‣  [Caroline Cauffman](https://www.maastrichtuniversity.nl/caroline.cauffman) | **Associate Professor in Private Law, Faculty of Law**  
[caroline.cauffman@maastrichtuniversity.nl](mailto:caroline.cauffman@maastrichtuniversity.nl)   

**Research Assistants**  

* Kirill Shchervakov ‣ Computer Science Graduate  
* Pranav Bapat ‣ Computer Science Graduate  
* Laura Robinson ‣ Data Science Graduate 