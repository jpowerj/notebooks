---
{"publish":true,"title":"Welcome to Jeff's Second Brain","created":"2025-11-26T04:16:25.461-05:00","modified":"2026-03-01T01:37:56.774-05:00","published":"2026-03-01T01:37:56.774-05:00","cssclasses":""}
---


> [!faq]+  What Is This?
>  
> ## Second Brain
>
> My "first brain" gets tired if it thinks about one thing for more than ~5 minutes, which means that the attention required to complete a [full blog post](https://jjacobs.me/blog) is rare. Hence, this is:
> * Partially a shameless ripoff of Cosma Shalizi's [notebooks](http://bactra.org/notebooks/), and
> * Partially an attempt to force [Obsidian](https://obsidian.md/) to be a [Personal Information Management](https://en.wikipedia.org/wiki/Personal_information_management) engine,
> Where I'll post the fleeting thoughts that pop up as I read books and make connections between things 🙈.
> 
> To some extent they're separated into categories, but there are two things that Obsidian+Quartz gives me that I'm hoping will help organize my otherwise-chaotic ADHD brain: **Ontology** and **Cross-References**.
> 
> ## Ontology
> 
> At some point between high school/beginning of undergrad, I had my mind completely blown by [[Math/Object-Oriented_Programming]]. To me it was like, discovering the internal language that my brain had been using my whole life to store/organize information.
> 
> So far, the main issue with Obsidian is just... it's designed around a bunch of Markdown (`.md` format) files, which is great for a ton of reasons, but it just doesn't exactly match the OOP way of thinking that fires so many serotonins in my brain. It's the closest thing I can find, though, especially when combined with the [Metadata Menu](https://mdelobelle.github.io/metadatamenu/) and [Dataview](https://blacksmithgu.github.io/obsidian-dataview/) plugins!
> 
> ## Cross-References
> 
> Though there are a few top-level categories[^1], the exciting part is when there's a [[Crossover in Categories]], like my main math interest ([[Math/Insolubility_of_the_Quintic\|Insolubility of the Quintic]]) being solved by a 20-year-old [[Math/Evariste_Galois\|Evariste Galois]], who had just recently been released from prison for his participation in the [[The_World/July_Revolution\|July Revolution]] 😱. Or, even more straightforwardly, how I put [[Math/Bertrand_Russell\|Bertrand Russell]] in the [[Math/]] category because I linked to him in the context of [[Axiomatization of Mathematics]], but he also led a super inspiring campaign to hold the US accountable for War Crimes in Vietnam (the [[The_World/Russell-Sartre Tribunal]])!
> 
> I'm... still figuring out how in-text citations like [[Text_Notes/@wood_chechnya_2007]] work, so bear with me on that part!

## Top-Level Categories:

<!-- QueryToSerialize: TABLE length(rows) as Count 
WHERE contains(file.folder, "/") = false AND file.folder != "fileClass" AND file.folder != "templates" AND file.folder != ""
FLATTEN link(file.folder) AS Category
GROUP BY Category
SORT Category DESC -->
<!-- SerializedQuery: TABLE length(rows) as Count WHERE contains(file.folder, "/") = false AND file.folder != "fileClass" AND file.folder != "templates" AND file.folder != "" FLATTEN link(file.folder) AS Category GROUP BY Category SORT Category DESC -->

| Category                   | Count |
| -------------------------- | ----- |
| [[The_World]]   | 54    |
| [[Text_Notes]] | 20    |
| [[Misc]]             | 1     |
| [[Math]]             | 11    |
| [[Growth]]         | 2     |
| [[Art_Things]] | 1     |

<!-- SerializedQuery END -->

## Notebook Index

<!-- QueryToSerialize: TABLE WITHOUT ID
link(file.name) AS "Page", default(title,file.name) AS "Title", file.mtime AS "Last Updated"
WHERE index != "false" AND file.folder != "fileClass" AND file.folder != "templates"
SORT file.mtime DESC -->
<!-- SerializedQuery: TABLE WITHOUT ID link(file.name) AS "Page", default(title,file.name) AS "Title", file.mtime AS "Last Updated" WHERE index != "false" AND file.folder != "fileClass" AND file.folder != "templates" SORT file.mtime DESC -->

| Page                                                                                     | Title                                                                                  | Last Updated                |
| ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | --------------------------- |
| [[Text_Notes/@reader_africa_1999]]                               | Africa: A Biography of the Continent                                                   | 1:32 AM - March 01, 2026    |
| [[Text_Notes/@carr_mikhail_1975]]                                 | Mikhail Bakunin                                                                        | 1:04 AM - March 01, 2026    |
| [[Text_Notes/@williams_our_2015]]                                 | Our Enemies in Blue                                                                    | 1:03 AM - March 01, 2026    |
| [[Text_Notes/@kasy_means_2025]]                                     | The Means of Prediction                                                                | 6:50 PM - January 18, 2026  |
| [[Text_Notes/@hacking_taming_1990]]                             | The Taming of Chance                                                                   | 6:45 PM - January 18, 2026  |
| [[Text_Notes/@hare_language_1952]]                               | The Language of Morals                                                                 | 7:22 PM - December 23, 2025 |
| [[Text_Notes/@wolin_politics_1960]]                             | Politics and Vision                                                                    | 7:20 PM - December 23, 2025 |
| [[Text_Notes/@hodges_mexico_1983]]                               | Mexico, 1910-1982                                                                      | 7:06 PM - December 23, 2025 |
| [[Art_Things/Songs/CunninLynguists-Brain_Cell]]           | Brain Cell                                                                             | 3:37 AM - November 26, 2025 |
| [[Art_Things/Songs/CunninLynguists-Nothing_to_Give]] | CunninLynguists-Nothing_to_Give                                                        | 3:37 AM - November 26, 2025 |
| [[Art_Things/Artists/NENE]]                                                     | NENE                                                                                   | 3:37 AM - November 26, 2025 |
| [[Art_Things/Artists/Teddy_Faley]]                                       | Teddy Faley                                                                            | 3:37 AM - November 26, 2025 |
| [[Art_Things/Chipmunk_Soul]]                                           | Chipmunk_Soul                                                                          | 3:37 AM - November 26, 2025 |
| [[Art_Things/Songs/Camron-Oh_Boy]]                                     | Camron-Oh_Boy                                                                          | 3:37 AM - November 26, 2025 |
| [[Art_Things/Artists/Cam'ron]]                                               | Cam'ron                                                                                | 3:37 AM - November 26, 2025 |
| [[Art_Things/Artists/CunninLynguists]]                               | CunninLynguists                                                                        | 3:37 AM - November 26, 2025 |
| [[The_World/ZAPU]]                                                              | Zimbabwe African People's Union                                                        | 3:10 AM - November 26, 2025 |
| [[The_World/ZANU]]                                                              | Zimbabwe African National Union                                                        | 3:10 AM - November 26, 2025 |
| [[The_World/Zimbabwe]]                                                      | Zimbabwe                                                                               | 3:10 AM - November 26, 2025 |
| [[The_World/SWAPO]]                                                            | SWAPO (South West African People's Organization)                                       | 3:10 AM - November 26, 2025 |
| [[The_World/Southern_Africa]]                                        | Southern Africa                                                                        | 3:10 AM - November 26, 2025 |
| [[The_World/Soviet_Union]]                                              | Soviet Union                                                                           | 3:10 AM - November 26, 2025 |
| [[The_World/Second_Indochina_War]]                              | Second Indochina War                                                                   | 3:10 AM - November 26, 2025 |
| [[The_World/Ukraine]]                                                        | Ukraine                                                                                | 3:10 AM - November 26, 2025 |
| [[The_World/Terrorism]]                                                    | """Terrorism"""                                                                        | 3:10 AM - November 26, 2025 |
| [[The_World/Rhodesian_UDI]]                                            | Rhodesian UDI (Unilateral Declaration of Independence)                                 | 3:10 AM - November 26, 2025 |
| [[The_World/Russell-Sartre Tribunal]]                        | Russell-Sartre Tribunal                                                                | 3:10 AM - November 26, 2025 |
| [[The_World/Russian_Imperialism]]                                | Russian Imperialism                                                                    | 3:10 AM - November 26, 2025 |
| [[The_World/Russian_Federation]]                                  | Russian Federation                                                                     | 3:10 AM - November 26, 2025 |
| [[The_World/Population_Transfers]]                              | Population Transfers                                                                   | 3:10 AM - November 26, 2025 |
| [[The_World/Portugal]]                                                      | Portugal                                                                               | 3:10 AM - November 26, 2025 |
| [[The_World/Quantification]]                                          | Quantification                                                                         | 3:10 AM - November 26, 2025 |
| [[The_World/Office_of_Public_Diplomacy]]                  | Office_of_Public_Diplomacy                                                             | 3:10 AM - November 26, 2025 |
| [[The_World/Occupied_Namibia]]                                      | Occupied Namibia                                                                       | 3:10 AM - November 26, 2025 |
| [[The_World/Palestine]]                                                    | Palestine                                                                              | 3:10 AM - November 26, 2025 |
| [[The_World/Lesotho]]                                                        | Lesotho                                                                                | 3:10 AM - November 26, 2025 |
| [[The_World/Liberia]]                                                        | Liberia                                                                                | 3:10 AM - November 26, 2025 |
| [[The_World/Namibia]]                                                        | Occupied Namibia                                                                       | 3:10 AM - November 26, 2025 |
| [[The_World/July_Revolution]]                                        | July Revolution                                                                        | 3:10 AM - November 26, 2025 |
| [[The_World/Lenin]]                                                            | Lenin                                                                                  | 3:10 AM - November 26, 2025 |
| [[The_World/Lao_Peoples_Democratic_Republic]]        | Lao People's Democratic Republic                                                       | 3:10 AM - November 26, 2025 |
| [[The_World/July_Monarchy]]                                            | July Monarchy                                                                          | 3:10 AM - November 26, 2025 |
| [[The_World/Italy]]                                                            | Italy                                                                                  | 3:10 AM - November 26, 2025 |
| [[The_World/Italian]]                                                        | Italian                                                                                | 3:10 AM - November 26, 2025 |
| [[The_World/Greg_Grandin]]                                              | Greg_Grandin                                                                           | 3:10 AM - November 26, 2025 |
| [[The_World/Ian_Smith]]                                                    | Ian Smith                                                                              | 3:10 AM - November 26, 2025 |
| [[The_World/Ingushetia]]                                                  | Ingushetia                                                                             | 3:10 AM - November 26, 2025 |
| [[The_World/Ghana]]                                                            | Ghana                                                                                  | 3:10 AM - November 26, 2025 |
| [[The_World/Germany]]                                                        | Germany                                                                                | 3:10 AM - November 26, 2025 |
| [[The_World/Fidel_Castro]]                                              | Fidel Castro                                                                           | 3:10 AM - November 26, 2025 |
| [[The_World/First_Chechen_War]]                                    | First Chechen War                                                                      | 3:10 AM - November 26, 2025 |
| [[The_World/Ethiopia]]                                                      | Ethiopia                                                                               | 3:10 AM - November 26, 2025 |
| [[The_World/French_Revolution]]                                    | French Revolution                                                                      | 3:10 AM - November 26, 2025 |
| [[The_World/France]]                                                          | France                                                                                 | 3:10 AM - November 26, 2025 |
| [[The_World/Cuba]]                                                              | Cuba                                                                                   | 3:10 AM - November 26, 2025 |
| [[The_World/Eswatini]]                                                      | Eswatini                                                                               | 3:10 AM - November 26, 2025 |
| [[The_World/Decolonization]]                                          | Decolonization                                                                         | 3:10 AM - November 26, 2025 |
| [[The_World/Caribbean]]                                                    | Caribbean                                                                              | 3:10 AM - November 26, 2025 |
| [[The_World/Cote d'Ivoire]]                                            | Cote d'Ivoire                                                                          | 3:10 AM - November 26, 2025 |
| [[The_World/Cold_War]]                                                      | Cold War                                                                               | 3:10 AM - November 26, 2025 |
| [[The_World/Chechnya]]                                                      | Chechnya                                                                               | 3:10 AM - November 26, 2025 |
| [[The_World/Anti-Apartheid_Struggle]]                        | Anti-Apartheid Struggle                                                                | 3:10 AM - November 26, 2025 |
| [[The_World/Apartheid_South_Africa]]                          | Apartheid South Africa                                                                 | 3:10 AM - November 26, 2025 |
| [[The_World/Angola]]                                                          | Angola                                                                                 | 3:10 AM - November 26, 2025 |
| [[The_World/Apartheid_Rhodesia]]                                  | Apartheid Rhodesia                                                                     | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@wood_chechnya_2007]]                               | Chechnya: The Case for Independence                                                    | 3:10 AM - November 26, 2025 |
| [[The_World/African National Congress]]                    | African National Congress                                                              | 3:10 AM - November 26, 2025 |
| [[The_World/Amharic]]                                                        | Amharic                                                                                | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@sartre_existentialism_2007]]               | Existentialism is a Humanism                                                           | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@runciman_treatise_1983]]                       | A Treatise on Social Theory, Volume 1: The Methodology of Social Theory                | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@wedeen_ambiguities_2015]]                     | Ambiguities of Domination                                                              | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@horne_white_2019]]                                   | White Supremacy Confronted                                                             | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@louis_imperialism_1977]]                       | Imperialism at Bay, 1941-1945                                                          | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@runciman_social_1969]]                           | Social Science and Political Theory                                                    | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@may_southern_1973]]                                 | The Southern Dream of a Caribbean Empire                                               | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@grandin_empires_2006]]                           | Empire's Workshop                                                                      | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@hacking_representing_1983]]                 | Representing and Intervening: Introductory Topics in the Philosophy of Natural Science | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@branford_lula_2005]]                               | Lula and the Workers Party in Brazil                                                   | 3:10 AM - November 26, 2025 |
| [[Text_Notes/@fisher_capitalist_2009]]                       | Capitalist Realism                                                                     | 3:10 AM - November 26, 2025 |
| [[Math/Set]]                                                                     | Set                                                                                    | 3:10 AM - November 26, 2025 |
| [[Misc/Triple_quotes]]                                                 | Triple Quotes                                                                          | 3:10 AM - November 26, 2025 |
| [[Math/Group]]                                                                 | Group                                                                                  | 3:10 AM - November 26, 2025 |
| [[Math/Gödel's_Incompleteness_Theorem]]               | Gödel's Incompleteness Theorem                                                         | 3:10 AM - November 26, 2025 |
| [[Math/Insolubility_of_the_Quintic]]                     | Insolubility of the Quintic                                                            | 3:10 AM - November 26, 2025 |
| [[Math/Object-Oriented_Programming]]                     | Object-Oriented Programming                                                            | 3:10 AM - November 26, 2025 |
| [[Math/Principia_Mathematica]]                                 | Principia Mathematica                                                                  | 3:10 AM - November 26, 2025 |
| [[Math/Alfred_North_Whitehead]]                               | Alfred North Whitehead                                                                 | 3:10 AM - November 26, 2025 |
| [[Math/Bertrand_Russell]]                                           | Bertrand Russell                                                                       | 3:10 AM - November 26, 2025 |
| [[Math/Evariste_Galois]]                                             | Evariste Galois                                                                        | 3:10 AM - November 26, 2025 |
| [[Math/Galois_Theory]]                                                 | Galois Theory                                                                          | 3:10 AM - November 26, 2025 |
| [[Art_Things/Songs/NENE-アツい]]                                               | NENE-アツい                                                                               | 3:10 AM - November 26, 2025 |
| [[Growth/Self-Help Summer 2024]]                               | Self-Help Summer 2024                                                                  | 3:10 AM - November 26, 2025 |
| [[Growth/101 Coping Skills]]                                       | 101 Coping Skills                                                                      | 7:23 PM - July 05, 2025     |
| [[Math/tf-idf]]                                                               | tf-idf                                                                                 | 4:42 AM - May 06, 2025      |
| [[The_World/Flags/What Do All The Flags Mean?]]          | What Do All The Flags Mean?                                                            | 9:58 PM - January 04, 2025  |
| [[The_World/El_Salvador]]                                                | El_Salvador                                                                            | 4:57 AM - December 23, 2024 |

<!-- SerializedQuery END -->

