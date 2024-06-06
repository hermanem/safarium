---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid=obj005 %} 

{% include feature/nav-menu.html sections="About Safarium;Objectives;Methods;Pedagogy" %}

## About Safarium

Safarium is the creation of Matthew Hermane, a PhD candidate in the Department of History at Indiana University Bloomington with the support of the Institute for Digital Arts and Humanities at Indiana University [IDAH@IU] (https://idah.indiana.edu/index.html) and the Humanities, Arts, Sciences, and Technology Alliance and Collaborative [HASTAC] (https://hastac.hcommons.org/). Inspired by a dissertation project examining examples of French and Persian travel writing produced by embassies that nearly crossed paths in Siam during the winter of 1685-1686, Safarium endeavors to promote transregional historical studies that involve complementary sources written by authors of disparate cultures and geographies. By searching locations in Safarium's database, users can identify travel accounts across languages that comment on the queried locale. Users are also presented with maps reflecting the itineraries and routes in the travel accounts returned by the search results. Safarium strives to put users in touch with sources they may be unaware of due to research specialties or language limitations. Because the instances of travel writing produced by European printers alone during the early modern period number in the thousands, Safarium is a project in the fullest sense of the word. In the future, Safarium hopes to enable the contributions of volunteers employing various digital methods. Beyond research, Safarium intends to be a tool for familiarizing students and the public with both early modern history and the digital humanities.

Safarium is built with [CollectionBuilder](https://github.com/CollectionBuilder/), an open source framework for creating digital collection and exhibit websites that is developed by faculty librarians at the University of Idaho Library following the Lib-Static methodology.

## Objectives 

**Inclusive scholarship** Safarium strives to overcome western-dominated and colonial narratives by pointing researchers, teachers, and students toward complementary sources of various origins.

**Community** Safarium is a project for public use that encourages and depends on the participation of both professional and amateur scholars. All one needs to contribute is the ability to read a single language. 

**Pedagogy** Safarium endeavors to be a useful education tool. The project's sample course teaches students how to do history in the 21st century by employing digital tools and methods that are relevant across a variety of fields. 

## Methods

**Digital Approaches to early modern travel texts** In the process of extracting travel itineraries from early modern texts for database entry, route mapping, and visualization, Safarium employs a number of digital tools. Safarium aims to not only familiarize users and students with the early modern world through travel writing but also with the modern tools and methodologies that might be used to approach that world and our own. Learn more about the approaches and tools used to create Safarium below.

***Text Analysis*** Various text analysis tools can enable the efficient extraction of travel itineraries from original travel texts. Converting original texts to plain text using ABBYY FineReader enables KWIC (keyword in context) analysis using Voyant to identify words that indicate arrival at and departure from specific locations. With original text converted to plain text, it is also possible to use AI chatbots, like ChatGPT, to retrieve travel itineraries in minutes. See an example chatbot query.

***Data Management*** This project uses the CollectionBuilder-CSV template and the static website generator Jekyll to create an engaging metadata-driven interface. CollectionBuilder-CSV is a "Stand Alone" template for creating digital collection with only a CSV of collection metadata and a folder of images, PDFs, audio, or video files. With collection metadata, the template generates engaging visualizations to browse and explore your objects. The resulting static site can be hosted on any basic web server. See [CB Docs](https://collectionbuilder.github.io/cb-docs/) for detailed information.

***Mapping*** Safarium's maps have been created in QGIS from the itineraries extracted from original travel texts in the database. Right now, each travelogue's map can be viewed on the correlated item page. In the future, Google My Maps and StoryMaps will also be employed to present engaging digital exhibits, and it is hoped that itinerary maps can be overlaid, allowing users to view connections between travelogues based on where itinerary routes intersect.

## Pedagogy

**Early modern topics and the public digital humanities in the classroom** One of Safarium's primary objectives is to provide a model for making pre-modern historical studies relevant for today's students. In pursuit of this objective, an experimental course has been designed that encourages students to interrogate notions of modernity through the study of early modern travel accounts. Over the duration of the course, students examine a travel account of their choice, extract its itinerary, map the itinerary, and add it to Safarium's database. In this way, students also become familiar with digital tools and methods that have applicability beyond the humanities. See the syllabus below.

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
