---
layout: default
title: Chronology
---

<h2 class="text-4xl">Chronology (to 1453)</h2>

<ul class="list-disc list-inside">
{% for event in site.events %}
	{% if event.year < 0 %}
		{% assign year = event.year | times: -1 | append: " BCE" %}
	{% else %}
	 {% assign year = event.year | append: " CE" %}
	{% endif %}
	<li>{{ year }}: {{event.description}}</li>
{% endfor %}
</ul>

861 BC: Kingdom of Urartu founded
513 BC: Darius’ campaign against the Scythians 
480 BC: Greek colonies on Crimean and Taman peninsulas form the Bosporan Kingdom
Mid 200s BC: Apollonius of Rhodes writes the Argonautica
120-63 BC: Reign of Mithridates VI king of Pontus.
88-63BC: Mithridatic Wars between the Roman Republic and the Kingdom of Pontus.
337: Christianity becomes state religion of Iberia (Kartli)
380: Theodosius I confirms Christianity as official state religion of Byzantine Empire
527-565: Reign of Justinian I (Hagia Sophia completed in 537)
c.650: The Rise of Khazar Empire in the Black Sea Zone 
681: first Bulgarian empire
726-787; 814-842: Byzantine iconoclasm 
C. 860: Cyrillic alphabet developed by Saint Constantine the Philosopher (St Cyril)
904: Sack of Thessalonica by Abbasid Caliphate
950(ca.): Olga of Kiev, wife of the Varangian ruler Igor and the grandmother of Vladimir I, converts to Christianity and is baptized in Constantinople.
976: Official reign of Basil II begins
988: Baptism of Vladimir and conversion of Rus’ to the Christian faith
1014: Basil II destroys Bulgarian army of Samuel. Bulgaria incorporated into Empire soon after.
1025: Death of Basil II
1043: Fall of Isfahan, end of Safavid dynasty [1501-1736]
1046: Fall of Bagratid Armenia
1054: Great Schism 
1055: Fall of Baghdad to Turks, led by Seljuks
1064: Fall of Ani (the important victory of Seljuks over Christians on the eve of the Battle of Manzikert)
1071: Battle of Manzikert, Seljuk victory, gradual Turkification of Anatolia 
1204: Fourth Crusade and Sack of Constantinople
1204: Foundation of the Empire of Trebizond by Alexios Komnenos.
1237: Mongol invasion of Kievan Rus’ 
2 June 1243: Mongol army defeats Seljuks near Köse Dagh (eastern Anatolia)
1261: Reconquest of Constantinople by Greeks under Emperor Michael VIII Palaeologus
1266: Caffa established by Genoese
1346-7: Plague arrives in Caffa through biological warfare by Mongols, Genoese sailors carry it to Sicily
1350: Creation of Serbian empire under Stephan Dushan (death in 1355, empire disintegrates)
1375: Fall of Armenian Kingdom of Cilicia (Last Armenian Kingdom in Anatolia)
28 June 1389: Battle at Kosovo Polje between Serb (under Prince Lazar) and the Ottoman army (under Sultan Murad I).
1396: Victory of Bajazet I of Osmans over France, Rome and Hungary, “the last real crusade” (Itzkowitz, 19) 
1402: Battle of Ankara between the Ottoman Empire and the Timurid Empire that stopped the Ottoman expansion. 
1403 — 1413: “Interregnum,” ends with Mohammed I, son of Bajazet, taking power
1438: Murad II invades Serbia, besieges Belgrade in 1440
29 May 1453: Fall of Constantinople (invasion of Ottoman army led by Sultan Mehmet II)
1461: Fall of Trebizond, conquered by Mehmed II.
1472: Ivan III marries Sophie (Zoe) Palaeologus, the niece of the Constantine XI, the last Byzantine Emperor. As such, Ivan begins using the Byzantine seal, the eagle with two heads
1475: Slavery Trade in Caffa under the Ottoman Empire 
1478: Foundation of Ottoman supremacy over Crimean khans
1520: Suleiman the Magnificent begins his reign
1525: France defeated by Hapsburgs and begin alliance with Ottomans
1555-1561: St. Basil’s Cathedral in Moscow is commissioned and built at the behest of Ivan IV in order to commemorate the Russian conquest of Kazan and Astrakhan. 
1552: Ivan IV captures Kazan
1556: Astrakhan is conquered by Ivan IV
1566: Suleiman the Magnificent dies

