---
layout: page
title: Cultural Analytics of Historical Texts
description: Using large-scale computational text analysis to trace long-term cultural and ideological shifts in East Asian societies, drawing on decades of digitised newspapers, books, and archival sources.
img: https://images.unsplash.com/photo-1770910328132-a4de62954292?auto=format&fit=crop&fm=jpg&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&ixlib=rb-4.1.0&q=60&w=3000
importance: 3
related_publications: true
---

Words are more than communication. They are evidence — of what a society fears and desires, what it finds natural or strange, how it imagines the self and the collective, the neighbour and the enemy. When those words accumulate across decades and millions of pages, they become something more: a record of culture in motion, of values shifting under the pressures of history. This project reads that record computationally, using large digitised corpora of East Asian texts to ask whether we can detect cultural change in the words people actually use — and what those changes tell us about the forces shaping modern China and Japan.

{% include figure.liquid loading="eager" path="https://images.unsplash.com/photo-1512820790803-83ca734da794" title="Historical archive" class="img-fluid rounded z-depth-1" %}
<div class="caption">
  Digitised archives make the long history of human thought computationally legible — transforming centuries of print culture into a landscape that can be mapped, measured, and interpreted.
</div>

## Did China Become More Individualistic?

The question has been debated for decades in cultural psychology, sociology, and China studies. On one side: the evidence of everyday life — the rise of lifestyle consumption, self-expression culture, and personal aspiration in Chinese cities after the 1980s reforms. On the other: a persistent scepticism about whether surface behaviours reflect genuine value change, or merely a cosmetic adaptation to market incentives that leaves deeper collectivist orientations intact. We approached this debate with a different kind of evidence: not surveys of attitudes, but the actual words Chinese authors used across fifty years of published books.

Drawing on billions of character tokens from the [Chinese Google Books](https://books.google.com/) n-gram dataset — covering literature, journalism, social science, and popular non-fiction published between 1970 and 2020 — we track the relative frequency of individualistic vocabulary (words associated with personal achievement, self-expression, and autonomy: 个人, 自我, 独特) against collectivistic vocabulary (group harmony, duty, and collective welfare: 集体, 奉献, 团结). The signal is clear and sustained: individualistic language rises markedly from the early 1980s, closely tracking the sequence of market liberalisation, urban migration, and social reform. This is not noise — it is the fingerprint of structural change in how an entire society wrote about itself.

{% include figure.liquid loading="eager" path="https://images.unsplash.com/photo-1622128969605-819cbd8cc23c" title="Historical books" class="img-fluid rounded z-depth-1" %}
<div class="caption">
  Millions of digitised volumes encode the shifting cultural values of Chinese society — one word at a time, across five decades of transformation.
</div>

But the details resist simple interpretation. The 1989–1992 period shows a sharp plateau — a brief halt in the individualisation trend that coincides with political crisis and retrenchment, before the trajectory resumes and steepens. And the vocabulary driving Chinese individualisation is not the same vocabulary that drives it in the United States or Western Europe. Where Western individualisation clusters around self-enhancement and personal uniqueness, Chinese individualisation clusters around self-cultivation and self-discipline (修身, 自律) — values with deep roots in Confucian moral philosophy. The data suggest that China did become more individualistic, but in a distinctively Chinese way, absorbing global trends through the filter of its own cultural heritage.

## Geopolitics, Written in Words

Cultural change within a society is one thing; the cultural consequences of relations between societies are another. The Sino-Japanese relationship — one of the most fraught bilateral relationships in modern history, swinging between war, estrangement, rapprochement, and recurring crisis — offers a remarkable opportunity to study how geopolitical events leave traces in the very language that societies use.

We constructed parallel corpora of Chinese and Japanese texts published between 1950 and 2015, spanning a sequence of landmark events: the 1972 diplomatic normalisation, the 1989 Tiananmen crackdown, the 1995–1996 Taiwan Strait crisis, the 2005 anti-Japanese protests, and the 2012 Senkaku/Diaoyu Islands dispute. Using word embeddings trained separately on each decade, we track how the semantic neighbourhood of key terms shifts — how close "Japan" is to words for threat versus cooperation in Chinese text, how "China" moves in the Japanese semantic landscape — and how these shifts correlate with the political calendar.

The findings reveal something that political scientists and historians have long suspected but rarely been able to demonstrate in linguistic data: the same event registers differently in each country's language, shaped by domestic political context and media environment. Japanese texts consistently show stronger and more lasting increases in threat vocabulary following bilateral crises; Chinese texts respond with sharper and more immediate nationalist framing. The asymmetry is not accidental — it reflects the different ways each society has institutionalised the memory of the war and processed subsequent bilateral tensions. Perhaps most intriguing is the moderating effect of economic integration: during periods of high bilateral trade, the linguistic response to geopolitical friction is measurably softer, as if material interdependence creates a buffer against the worst of rhetorical escalation.

## Commerce and Nationalism in Wartime Shanghai

The third strand of this project steps back further into history, into a moment of acute cultural and political turbulence: Shanghai between 1932 and 1937, as Japanese military aggression in China intensified and the city's cosmopolitan consumer culture flourished in the shadow of impending catastrophe. Major multinational corporations — Unilever, Standard Oil, General Motors, Nestlé — were conducting business in a society where the political ground was shifting beneath their feet, where nationalist sentiment was rising, and where the wrong advertisement could attract a boycott.

We digitised and analysed approximately 12,000 advertisements placed by these corporations in major Chinese-language newspapers (*Shenbao*, *Dagong Bao*) across these five years, applying computational content analysis to track how the cultural orientation of commercial language — the balance between cosmopolitan universalism and Chinese nationalist appeal — changed in response to military incidents. The January 28 Incident of 1932 and the Marco Polo Bridge Incident of 1937 serve as event-window markers: moments around which we can measure the direction and speed of advertising's cultural adaptation.

The pattern is striking. Following each escalation of military conflict, brands pivoted toward Chinese nationalist framing — more national imagery, more references to Chinese heritage and tradition, more appeals to patriotic consumption. Cosmopolitan and universalist appeals, which had flourished in Shanghai's international atmosphere during quieter years, retreated. Companies with deep local manufacturing and distribution networks moved fastest and furthest in this adaptation. And the adaptation had real consequences: firms that successfully localised their cultural language were significantly more likely to still be operating when full-scale war began in 1937. Commercial language, it turns out, is not merely a reflection of culture — it is a survival strategy, shaped in real time by the pressures of history.

Across these three strands, a single conviction emerges: text is not just what people say, but evidence of who they are becoming.

## Research Contributions and Next Steps

This project advances cultural analytics in three ways. It provides longitudinal evidence for distinctively Chinese trajectories of individualization {% cite hamamura2021individualism hamamura2022reply %}; it models geopolitical tension as semantic movement in parallel national corpora {% cite hamamura2025geopolitics %}; and it demonstrates how multinational commercial discourse adapts to conflict shocks in historically specific media markets {% cite sun2024globalization %}.

The next phase broadens both scope and granularity: longer temporal windows, tighter event coding around policy shocks, and multi-level linkage between macro discourse shifts and meso-level institutional actors (media, firms, state agencies). The substantive aim is to build a historically grounded, computationally rigorous account of how language mediates the relationship between culture, power, and social change.

## Methods

This project draws on large-scale corpus construction from digitised archives including Google Books, national newspaper collections, and historical newspaper databases; word frequency and n-gram time-series analysis; word embeddings (Word2Vec, GloVe) trained on decade-level subcorpora for semantic change detection; cross-cultural comparative design with matched corpora; event-window regression analysis for geopolitical shocks; and manual alongside automated content coding of historical advertisements.
