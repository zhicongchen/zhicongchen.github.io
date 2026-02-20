---
layout: page
title: Online Safety in Digital Media Platforms
description: Studying the Tor network, dark web forums, cryptomarkets, and decentralized ecosystems to understand how anonymity, fringe platforms, and information flows shape online safety.
img: https://images.unsplash.com/photo-1451187580459-43490279c0fa
importance: 1
related_publications: true
---

Every society has spaces where the normal rules do not apply — where identity can be shed, authority evaded, and things said that cannot be said elsewhere. The internet has always had such spaces, and they have always been contested: sites of refuge for dissidents and journalists, playgrounds for the curious, and havens for the harmful. This project takes those spaces seriously, not as curiosities to be explained away or threats to be policed, but as revealing laboratories for some of the deepest questions in communication: What does community look like without accountability? How does dangerous content spread from the margins to the centre? And who, ultimately, pays the price when the architecture of the internet allows harm to travel freely?

{% include figure.liquid loading="eager" path="https://images.pexels.com/photos/5380664/pexels-photo-5380664.jpeg?auto=compress&cs=tinysrgb&w=1600" title="Network visualisation" class="img-fluid rounded z-depth-1" %}
<div class="caption">
  The architecture of anonymous networks — where routing, encryption, and community norms intersect to create spaces unlike anything that came before.
</div>

## Who Seeks Anonymity, and Why?

The question sounds simple, but the answer turns out to be politically significant. [Tor](https://www.torproject.org/) — The Onion Router — is the most widely used anonymity tool on the internet, routing traffic through multiple encrypted relays to hide users' locations and identities. Its user base is heterogeneous in ways that defy easy characterisation: political dissidents in authoritarian states, journalists protecting sources, privacy advocates frustrated with surveillance capitalism, curious teenagers, and people who have far less benign purposes. To understand what anonymity technology *does* to a society, we first need to understand who uses it and under what pressures they reach for it.

Using longitudinal relay-level data spanning more than 140 countries from the [Tor Metrics Project](https://metrics.torproject.org/), we find that the dominant driver of Tor adoption is not technical curiosity or ideological commitment to privacy — it is **necessity**. When governments block social-media platforms, filter news sites, or impose internet shutdowns, Tor usage surges, often within days. The pattern is reactive and event-driven: each new censorship measure produces a measurable uptick in the countries affected. Adoption also spreads geographically, from early-adopting neighbours and through informal community networks, suggesting that trust and word-of-mouth matter more than formal awareness campaigns. Technical literacy shapes how quickly a population can act on the need for anonymity; it does not determine whether that need arises.

The implication is sobering: as governments around the world tighten their grip on the open internet, demand for anonymity tools grows not as a choice but as a necessity of civic participation.

## Life Inside Anonymous Communities

Knowing who uses anonymity tells us little about what anonymity actually *does* to communities. To get at that question, we needed a design that could isolate the effect of anonymity from everything else — topic, culture, history — that might explain how an online community behaves. The solution was to study **twin forums**: communities that exist simultaneously as a dark-web version (accessible only over Tor, with no identity verification) and an open-web counterpart covering identical subject matter. Same people, same conversations, two radically different identity environments.

{% include figure.liquid loading="eager" path="https://images.pexels.com/photos/5198392/pexels-photo-5198392.jpeg?auto=compress&cs=tinysrgb&w=1600" title="Dark web and surface web" class="img-fluid rounded z-depth-1" %}
<div class="caption">
  Twin forums — identical communities running in parallel across the dark web and the surface web — offer a rare natural experiment in what anonymity actually does to social life.
</div>

The differences are striking and consistent. Anonymous forums produce substantially more risk-taking content, consistent with the classical finding that reduced accountability loosens social inhibition. But they are also more fragile: users cycle through faster, the community depends disproportionately on a small core of pseudonymous regulars, and when platforms are taken offline — by law enforcement or server failures — anonymous communities fragment more severely and reconstitute less reliably than their surface counterparts. Most revealing is what fills the gap left by real-world identity: anonymous communities develop elaborate surrogate trust systems — reputation scores, vouching threads, tenure signals — that perform some of the functions of identity without actually providing it. They are social structures built on inference rather than knowledge.

A parallel study, drawn from the forums of dark-web drug marketplaces (cryptomarkets), surfaces a deeper tension at the heart of anonymous community life. Users who rotate pseudonyms frequently to maximise their anonymity sacrifice the accumulated social capital that makes them visible, credible, and effective. Those who build lasting pseudonymous identities gain influence and trust — but also become progressively more de-anonymisable as their posting history accumulates. There is no anonymity strategy that escapes this dilemma. What our analysis of over two million posts does find is that the quality of communication — linguistic diversity, conversational depth — matters more than any identity strategy for sustaining a community. People stay where the conversation is worth having.

## When Fringe Spaces Shape the Mainstream

The question that gives this research agenda its urgency is not what happens inside anonymous and fringe spaces, but what happens when content escapes them. During the COVID-19 pandemic and the 2020 US Presidential Election, both the internet and the real world were flooded with misinformation that seemed to have no clear origin — claims about vaccines, voting machines, and foreign interference that appeared, multiplied, and persisted despite repeated debunking. Where did this content come from? And how did it travel?

Tracing URL-sharing patterns, hashtag genealogies, and cross-platform diffusion across dark-web forums, fringe imageboards (4chan, 8kun), right-wing social-media platforms (Parler, Gab), and mainstream networks (Twitter, Facebook), we reconstruct the pathways through which specific claims moved. The pattern is consistent enough to constitute a model: content originates in anonymous or semi-anonymous spaces where the absence of reputational risk enables extreme claims; it then migrates to fringe surface platforms where it gains an audience; from there, it reaches mainstream networks where engagement further amplifies it; and finally, mainstream news coverage — often framed as debunking — paradoxically extends its reach further still. The entire journey, from dark-web debut to mainstream uptake, typically takes 48 to 72 hours.

Two findings complicate simple solutions. First, deplatforming does not automatically contain this process; it can displace content production and circulation toward less moderated spaces. Second, the anonymous origin of content is no impediment to virality. In some contexts, transgressive framing from low-accountability environments appears to increase sharing appeal.

Complementary work on the demand side shows that right-leaning media exposure and selective exposure dynamics are significant predictors of conspiracy-theory propagation and uptake. The mechanism is confirmation bias: users preferentially seek and amplify content aligned with prior beliefs. Related research further shows that authoritarian personality traits can intensify selective exposure to partisan media in policy-attitude formation, highlighting a broader susceptibility pathway in polarized information environments.

The picture that emerges from this body of work is one in which online safety cannot be understood at the level of individual platforms or individual pieces of content. It is a systemic property of an interconnected information environment in which the most extreme spaces set the terms for what eventually becomes thinkable, shareable, and believed.

## Research Contributions and Next Steps

This project contributes three connected claims. First, anonymity adoption is often a civic response to censorship pressure, not merely a privacy preference {% cite chen2024tor %}. Second, anonymous communities are not socially empty; they develop compensatory trust systems with distinctive retention and fragility dynamics {% cite chen2025twin chen2023darkweb %}. Third, misinformation diffusion is ecosystem-level: fringe-to-mainstream pathways can be traced and modeled across platforms {% cite chen2025darkside yu2024conspiracy %}.

The next phase extends this agenda from description to intervention. Current work focuses on early-warning indicators for cross-platform escalation, moderation strategies that reduce downstream spillover rather than only local prevalence, and communication interventions that target susceptibility mechanisms such as selective exposure in politically polarized settings {% cite jiang2025authoritarian %}. The goal is to inform platform governance and public-interest policy with evidence that matches how harm actually moves through networked media systems.

## Methods

This project draws on large-scale web scraping and archiving of dark-web content via Tor SOCKS proxies and custom crawlers, longitudinal panel analysis of Tor relay and bridge statistics, computational text analysis including topic modelling, word embeddings, and sentiment classification, survival analysis for user retention and platform migration patterns, and cross-platform diffusion tracing using URL genealogy graphs and network cascade analysis.
