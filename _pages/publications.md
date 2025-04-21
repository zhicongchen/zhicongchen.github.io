---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Research Overview
My research investigates the dynamic interplay between media technologies, cultural identities, and social transformations in contemporary China and beyond. Bridging the fields of communication studies and computational social science, my work critically examines how technological infrastructures—ranging from mobile devices to anonymous networks—reconfigure modes of information dissemination, cultural production, and civic mobilization. By combining quantitative inquiry with computational methods, I aim to illuminate the socio-technical undercurrents that shape public discourse, identity construction, and collective action in an increasingly mediated world.

## Research Areas
### 1. Media Ecology and the Impact of Digital Technology on Culture and Society
My research focuses on applying computational methods to communication studies, particularly in understanding how technology influences culture and society. I pursue methodological innovation by integrating computational tools into critical communication research. My projects leverage natural language processing, social network analysis, and LLM-based modeling to investigate phenomena such as online anonymity (e.g., via Tor) and discursive dynamics across digital platforms. My goal is to situate computational communication not only as a methodological extension but also as a theoretical frontier that reveals the algorithmic and infrastructural forces underpinning public discourse. For instance, my use of network analysis sheds light on the structure and dynamics of online social networks. By examining the relationships between individuals and groups, I uncover critical insights into information diffusion, community formation, and social influence (see Chen, Meng & Wang, 2023). These findings are essential for understanding how online interactions shape public opinion and influence societal behaviors. 

Moving beyond, my work emphasizes the broader impact of technology on cultural practices (see Yu et al., 2024). My research during the COVID-19 pandemic analyzed the spread of conspiracy theories and their entanglement with geopolitical narratives (see Chen et al., 2025). I have also explored the implications of anonymization technologies, such as the Tor network (see Chen et al., 2024). My research reveals that while anonymity empowers individuals to express dissent and share sensitive information, it also presents challenges, such as the spread of misinformation. These two strands of research underscore the dual nature of technology—as both a liberating force and a potential catalyst for social fragmentation. 

- Chen, Z., Yu, W., Sun, Y., Wang, C.-J.*, & Liu, X. F.* (2025). The dark side of the Internet: Fueling misinformation in the COVID-19 pandemic and the 2020 US Presidential Election. Communication and the Public [IF=2.4, Scopus ranking: 131/511  in Communication], OnlineFirst. https://doi.org/10.1177/20570473251323752
- Yu W., Chen Z.*, Meng X.*, Yan Q. (2024). Propagating COVID-19 Conspiracy Theories: The Influence of Right-Wing Sources. Sage Open [IF=2.2, Scopus ranking: 65 out of 262 in General Social Sciences | 5 out of 163 in General Arts and Humanities, Q1], 14(2). https://doi.org/10.1177/21582440241258026. 
- Chen, Z., Jardine, E., Liu, X. F.*, & Zhu, J. J. H. (2024). Seeking anonymity on the Internet: The knowledge accumulation process and global usage of the Tor network. New Media & Society [IF=6.9, Scopus ranking: 16 out of 1415 in Sociology and Political Science; 6/493 in Communication, Q1], 26(2), 1074-1095. https://doi.org/10.1177/14614448211072201
- Chen Z., Meng X., Wang C. J. * (2023). The Dark Web Privacy Dilemma: Linguistic Diversity, Talkativeness, and User Engagement on the Cryptomarket Forums. Humanities and Social Sciences Communications [IF=3.5, Scopus ranking: 4/163 in General Arts and Humanities, Q1], 10(1), 1-11. https://doi.org/10.1057/s41599-023-02424-0
- 


### 2. Cultural Shifts and Global Influences in Contemporary China

Global crises, conflicts, and technological globalization provide the backdrop for my investigation into cultural representation and transnational communication. My methodological approach integrates advanced natural language processing (NLP) algorithms with quantitative analysis to offer a nuanced understanding of communication phenomena across diverse contexts. Through the analysis of large-scale textual datasets from books, I have examined the rise of individualism in China and how cultural norms and values are being reinterpreted and renegotiated. A key contribution of my work was the application of word embedding techniques to investigate cultural shifts in China (see Hamamura et al., 2021; Hamamura et al., 2022). This project not only deepened our understanding of cultural psychology but also highlighted the potential of data visualization to inform decision-making processes across various sectors.

I have also examined how international advertising strategies shift in response to armed conflicts, illustrating how cultural orientations—individualism vs. collectivism—are reactivated or reconfigured under conditions of global uncertainty. These projects reflect a sustained interest in how media representations mediate cross-cultural perception and identity politics (see Sun et al., 2024), specifically the impact of military conflicts on the cultural orientations of multinational corporations' advertising in modern China. The research explored how geopolitical factors shape advertising strategies, analyzing shifts in messaging and cultural references as corporations navigate the complexities of a global market influenced by conflict. This study provides valuable insights into the intersection of international relations and corporate communication, shedding light on how global brands position themselves within a rapidly changing marketplace like China.

- Zhang Y., Lu G., Sun Y., Chen Z.*, Wang C. J.* (Accepted). Let us not wallow in the valley of despair: The role of emotion, panic, and sympathy discourses in promoting productive actions. International Journal of Business Communication. 
- Sun Y., Yan X. F., Zhang Y., Chen Z.*, Wang C. J.* (2024). Globalization in International Tensions: The Impact of Military Conflicts on Cultural Orientations of Multinational Corporations’ Advertising in Modern China (1932-1937). Chinese Journal of Communication [IF=3.5, Scopus ranking: 42 out of 493 in Communication, Q1], 1–19. https://doi.org/10.1080/17544750.2024.2354698 
- Hamamura, T.*, Chan, C. S., Chen, S. X., Chen, Z., Kobayashi, T., & Ng, J. C. K. (2022). Toward a better understanding of cultural change: Reply to Bao et al. (2022). American Psychologist [IF=16.4, Scopus ranking: 7/209 in General Psychology, Q1], 77(6), 789–790. https://doi.org/10.1037/amp0001032
- Hamamura, T.*, Chen, Z., Chan, C. S., Chen, S. X., & Kobayashi, T. (2021). Individualism with Chinese characteristics? Discerning cultural shifts in China using 50 years of printed texts. American Psychologist [IF=16.4, Scopus ranking: 7/209 in General Psychology, Q1], 76(6), 888–903. https://doi.org/10.1037/amp0000840

# Featured Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
