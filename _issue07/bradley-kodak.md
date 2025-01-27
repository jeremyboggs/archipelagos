---
layout: article
section: articles
title: 
  "long": "Breaking the *Kodak*: Surveillance and Subversion in the *Monograph of
the Republic of Haiti* Map"
  "short": "Breaking the Kodak"
doi: "10.7916/archipelagos-0702"
author: 
- name: Isabel Bradley
  shortname: Bradley
  bio: >
    Isabel Bradley is a PhD candidate in Romance Studies at Duke University. Her work is broadly framed by currents of decolonial thought and their intersections with environmental studies in the Francophone Caribbean. She studies the ways in which modes of being, sensory perception, and historicity emerge from embodied engagements with ecologies such as subsistence plots, plantation monocultures, mornes, and oceans. Grounded in French-language natural historical texts, visual and cartographic materials, and Caribbean literatures, her dissertation project traces the role of the manioc root in sustaining relational, counter-plantation modes of being human from the 16th-century to the present. Isabel has held research fellowships at the John Carter Brown Library and the Library Company of Philadelphia and spent a visiting semester at the École normale supérieure in Paris. 
date: May 2023
issue: 7
order: 2
abstract: >
    This article begins from the Monograph of Haiti Map project, which presents a set of aerial photographs taken during the U.S. military occupation of Haiti by mapping them onto contemporary satellite imagery using GIS. Reflecting on the process and methods of the project, I interrogate the operations of racializing surveillance and plantation visuality at work in both the aerial photos themselves and in the photomap as a digital object. I read occupation-era archives of photos, poetry, and sound through Simone Browne’s "dark sousveillance" and other paradigms to unearth traces of counter-surveillance and to understand contested Haitian spaces as dynamic sites of resistance to forced labor and racist extractivism. I take inspiration from Caco insurgents’ tactics of "undersight" to reflect on how this rendering self out of sight and other occupation-era freedom practices against racializing "oversight" might inform digital design choices for this project and others hoping to account for Black geographic knowledge.      
abstract_fr: >
    Cet article commence par le projet Monograph of Haiti Map, qui présente un ensemble de photographies aériennes prises pendant l'occupation militaire américaine d'Haïti en les cartographiant sur des images satellites contemporaines à l'aide du SIG. Réfléchissant sur le processus et les méthodes du projet, j'interroge les opérations de racialisation de la surveillance et de la visualité des plantations à l'œuvre tant dans les photos aériennes elles-mêmes que dans la photocarte en tant qu'objet numérique. J'ai lu des archives de photos, de poésie et de sons de l'époque de l'occupation à travers la « sousveillance sombre » de Simone Browne et d'autres paradigmes pour déterrer des traces de contre-surveillance et pour comprendre les espaces haïtiens contestés comme des sites dynamiques de résistance au travail forcé et à l'extractivisme raciste. Je m'inspire des tactiques de « méconnaissance » des insurgés Caco pour réfléchir à la façon dont cette mise hors de vue et d'autres pratiques de libération de l'ère de l'occupation contre la « surveillance » racialisante pourraient éclairer les choix de conception numérique pour ce projet et d'autres espérant rendre compte de la connaissance géographique noire.
abstract_es: >
    Este artículo comienza con el proyecto *Monograph of Haiti Map*, que presenta un conjunto de fotografías aéreas tomadas durante la ocupación militar estadounidense de Haití al mapearlas en imágenes satelitales contemporáneas utilizando GIS. Reflexionando sobre el proceso y los métodos del proyecto, interrogo las operaciones de vigilancia racializadora y la visualidad de la plantación en nuestro trabajo, tanto en las fotos aéreas como en el fotomapa como objeto digital. Leo archivos de fotos, poesía y sonido de la era de la ocupación a través de la "supervigilancia oscura" de Simone Browne para desenterrar rastros de contravigilancia y comprender los espacios haitianos en disputa como sitios dinámicos de resistencia al trabajo forzado y al extractivismo racista. Me inspiro en las tácticas de "desconocimiento" de los insurgentes de Caco para reflexionar sobre cómo esta representación de uno mismo fuera de la vista y otras prácticas de libertad de la era de la ocupación contra la "supervisión" racializadora podrían informar las opciones de diseño digital para este proyecto y para otros que esperan dar cuenta de conocimiento geográfico negro.   
language: en
pdf: true
---



## I. Introduction

On the [Monograph of Haiti
Map](https://www.arcgis.com/apps/webappviewer/index.html?id=de268c688b8142fbb689fb52826fa818),
Haiti appears as a scattering of confetti pieces in a sea of white. Its
silhouette is rendered in studded fragments, but those familiar with the
country's form will find its contours immediately and recognize the
stars of the constellation as cities. Port-au-Prince is brighter,
bigger; the outline of the Tiburon peninsula dotted with smaller sepia
photos in regular intervals: Bainet, Côtes-de-Fer, Aquin, Saint Louis du
Sud, and so on. The sprawling empty space around the cities seems to
have resisted the photographer's airborne lens. It remains opaque,
unmapped, a receptacle for imagination.

These photographs were taken during the U.S. military occupation of
Haiti and published in the 1932 [*Monograph of the Republic of
Haiti*](https://archive.org/details/MonographOfHaiti1932/mode/2up).
In keeping with 20th-century interventionist policies, the U.S.
Marines had invaded Haiti in 1915, immediately declaring martial law
under the pretext of maintaining political and economic stability in the
country. A constabulary made up of Haitian troops raised and trained by
U.S. Marines, the *Gendarmerie d'Haïti,* quickly became the key
enforcing body of the occupation. For nineteen years, until 1934, the
occupation's field activities coupled aggressive corporate expansionism
with Jim Crow-era white supremacist terrorism. Its agents perpetrated
acts of economic and physical violence at every level of civilian
society. These brutalities, including the civil conscription of peasant
labor to build infrastructure, incited a series of anti-occupation
revolts led by decentralized guerilla groups, or *Cacos*.[^1]

The photos pinned to the satellite base layer on the [Monograph of Haiti
Map](https://www.arcgis.com/apps/webappviewer/index.html?id=de268c688b8142fbb689fb52826fa818)
were originally collected as part of intelligence amassed by the
Marines. Produced by the first United States Geological Survey aerial
mapping project outside of the U.S., they illustrated the 900-page
*Monograph of the Republic of Haiti*, whose object was "to provide
operative and war plans information upon the Republic of Haiti."[^2] The
volume had been assembled to assist Marine officers in operating on the
ground, and Marine Corps bases throughout Haiti housed copies for
consultation. To convey intelligence information more clearly, the
*Monograph* effectively dissects the country of Haiti into a list of
towns in alphabetical order; each town's section contains a photograph
accompanied by scrupulous notes on population, agriculture, climate,
topography, industry, and possible resistance activity. The report was
held in the Marine Corps Archives in Quantico until 2014, when Duke's
Rubenstein Library acquired and digitized a copy.

I began digital work with the *Monograph* in the summer of 2020, in
collaboration with Laurent Dubois, historian of Haiti, and Nicolas
Scheffer, a graduate student in geography. Curious about what histories
might emerge from reconfiguring the aerial photos, and especially hoping
to piece together a diachronic environmental picture of Haiti, we
decided to extract the images from their framework in the *Monograph*
compilation and to lay them over a satellite base map. In the pages that
follow, I focus on a set of theoretical and ethical questions brought to
the surface by the mapping process.[^3] Without prescribing concrete
formal modifications to the project, I employ Simone Browne's concept of
"dark sousveillance,"[^4] which provides a way to think through
countersurveillance and the freedom practices generated against chattel
slavery in order to probe how a critical theoretical reorientation
inspired by these praxes might shape future iterations of the
*Monograph* map and initiatives like it.

The incomplete mosaic image housed on the project website reflects
strategic imperial objectives of nearly a century ago. It exists because
of the use of aerial technology in the service of violent
occupation---and because of our team's work pulling photos from the
binding of the U.S. Marines' wartime compilation. The website's base map
gallery allows users to change the map format beneath the aerial photos
to generate a picture of how road systems, urban areas, rural zones, and
coastlines have transformed over the last near-century. The zoom tool's
shift of scale reveal the aerial photograph's meticulous contours of
roads, grids of city blocks, tree cover, and coastlines as they appeared
in 1932. Waves, captured breaking onto a beach ninety years ago, are
fixed mid-movement. This photo-object came into existence in the service
of aggressive land-grabbing and corporate extractivism, fed by racist
regimes of forced labor. The digital project gives it new life as a map.

The impetus behind the mapping project was to reanimate these
images---photographs of towns with attached metadata of altitude, scale,
and place name---by liberating them from their accompanying text in the
*Monograph* and setting them against present-day satellite imagery. The
team did this through georeferencing each image, and the process
troubled and intrigued me.[^5] What did it mean to close the distance
between sets of points across time, between captured space in one
political moment and its future anchor on the earth's surface? The
practice of transforming these occupation-era snapshots into a map and
effectively bringing 1932 to meet 2021 was not benign; the act of
elevating reconnaissance photography into cartography seemed to endow
these surveillance objects with more power, greater legitimacy.

As we attributed coordinates to the photos, I was reminded of Vincent
Brown's observation that "cartography presumes the natural existence of
points on a grid much as history naturalizes the timeline, though these
are ultimately folkways for representing space and time that have more
in common with slaveholders' epistemes than with those of their
slaves."[^6] Our mapping efforts were intended to be redemptive, to
repurpose the images towards ends very different from those of
occupation-era surveillance. But we were aware of the harm that might be
done by naturalizing (and neutralizing) occupiers' representations of
Haiti's inhabited landscapes. The term "georectification" has vague
moral connotations, as if an image without coordinates on a spatial grid
is a wrong that needs to be made right. The team felt there would be
some value in making these images accessible in a digital cartographic
format, though we struggled to make sense of the epistemological and
ethical stakes involved in doing mapping work with this set of sources.
On the other hand, if done a certain way, our appropriation of this part
of the occupation's photographic legacy might open possibilities for
reassessing wider issues of representation, surveillance, geographic
knowledge, sensory perception, and the afterlives of enslavers'
epistemes.

The photos, read against the satellite images of today, tell stories of
changing landscapes and hold unmined secrets for researchers. There is
dynamism in witnessing rivers cut new courses; there is energy in
processes of erosion and urban expansion. It is sobering to visually
perceive the rise of sea levels, disappearing tree cover, and soil
runoff in *lavalas* (landslides/avalanches) over the last near
century.[^7] The project directly illustrates the discourse of
Anthropocene islands, visually endorsing arguments of engineered
ecological vulnerability in the wake of colonialism and slavery. But
there is eerie stillness and stasis in the landscapes emptied of meaning
beyond the all-seeing gaze from above, both in 1932 and in 2021. Today,
these pairs of images can be made to fit the too-easy, overdetermined
script of environmental degradation exacerbated by nonsovereignty, by
*lamizè* (misery/poverty).

How can a critical viewing experience not be tainted by frustration at
the continuities between the world of these monochrome views and the
world of today? Katherine McKittrick repeats, "*description is not
liberation."*[^8] Neither is representation. This article therefore
takes the digital map as a catalyst for further reflection and
thinking-with a set of scholars of Black geographies and surveillance,
some of whose work appears in previous issues of *archipelagos*. Drawing
on occupation-era Haitian archives, I endeavor to generate a dialogue
with experiments in thinking beyond Cartesian grids, in racializing
aerial gazes, and in the replication of these grids and gazes in digital
form. Instead of reinforcing views from above, I enter, through the
*Monograph Map* project, into explorations of nonvisual perception,
Browne's "dark sousveillance," and other strategies for evading capture
by aerial or frontal fixing gazes. By turning to Black diaspora
theorists, I attempt to make room for Haitian understandings of space as
an opening onto the urgent, wider conversation about digital equity and
ethically responsible DH work involving Haiti.

## II. "Overseeing," the aerial gaze, and plantation visuality

If photography has been employed since its inception to create and
catalog human difference, aerial photography has a distinct way of doing
so. The *Monograph*'s photos, at first glance, do not act with the
violent capture of those centering human subjects, such as the
now-infamous 19th century photos of "human zoos" in World's Fairs or
*Expositions universelles*.[^9] The only photos of human subjects in the
*Monograph* are of uniformed members of the *Gendarmerie d'Haiti*, the
corps trained by U.S. Marines and "Haitianized" by 1932, with U.S.
personnel being phased out and replaced by trained Haitian officers. The
*Monograph* reports that these men conducted themselves "excellently"
during the "Cacos Trouble," presumably in putting down peasant unrest.

{% include image.html
    img="issue07/garde-haiti.jpg"
    title="Monograph image of the Garde d'Haiti."
    caption="Monograph image of the Garde d'Haiti."
    url="https://archive.org/details/MonographOfHaiti1932/page/n1493/mode/2up"
%}

The *Monograph*'s aerial photos are not portraits cataloged by projects
of biological racism; the violence and erasure they perform are of a
different sort. Instead of a gaze that meets the camera, defiant or
opaque, an invisible gaze behind the camera animates a visual operation
that has its roots in that of the all-seeing agent of plantation
goings-on. Aerial vision, or seeing from above, has semantic and
genealogical resonances with what Nicholas Mirzoeff names as
"oversight." Oversight extends the "nomination of what was visible to
the overseer on the plantation" to address the sensory primacy of the
visual in the ordering of slavery and as a perceptual practice
underpinning western epistemes in general.[^10] Plantation visuality
operates through "a combination of violent enforcement and visualized
surveillance" meant to manage time and labor to extract the biomass of
cash crops.[^11]

Although taken by an occupying force justified by white supremacy and
racial capitalism, the sepia landscapes comprising the map are
deceptively neutralized by their juxtaposition against open-source
satellite imagery. But the *Monograph*'s aerial photos are in fact
inscribed in the long practice, in American plantation zones, of
siting/sighting relational, biodiverse ecological spaces into legible
orders of racialization and extraction. In a very direct sense, during
the U.S. occupation, companies like the Haitian American Sugar Company
(HASCO) relied on inherited colonial tactics for spatializing plantation
layouts and for managing time and labor to generate profits. As the
latest technology of modernity in 1932, the marines' airborne camera
oversaw not only one plantation but the entire western half of
Hispaniola; to extract labor and sugar from a whole country demanded a
new sca[le of hyper-visual surveillance. The *Monograph* photos
themselves embody traces left by this "plantation complex of visuality,"
whose spatial logics continue to undergird forms of racialized
surveillance.[^12] Furthermore, this visual power acts forcefully on
mountains, plains, and seascapes, reducing complex sites of
human-ecological engagements to birds' eye objects of enclosure and
possession, and exposing potential refuges.

In her reading of British colonial cartography in *The Black Shoals*,
Tiffany Lethabo King calls attention to the "White cartographic
subject," or disembodied, over-represented Cartesian subject that writes
itself into being by "spatially fixingand capturingforms of
Black fugitivity and Indigenous resistance."[^13] The *Monograph*'s
aerial surveillance photos are a 20th-century iteration of a
longstanding western imperial tradition in which mapping techniques act
as symbolic arsenals that differentiate and solidify hierarchies of
humanness through what they represent and how they represent it. From colonial
cartography to aerial photography to mapping technologies used in this
project, mobilized for racialized forms of policing and military
surveillance, the construction of a dominant subject via views from
above requires the denial of subjecthood of those observed. The
overseeing geographic subject, agent of plantation visuality, creates
itself by reifying its Others and their meaningful places as
objects. As Katherine McKittrick succinctly contends, "past colonial
encounters created material and imaginative geographies that reified
global segregations through 'damning' the spaces long occupied by Man's
human others."[^14]

While handling the 1932 images, I was struck by these photos'
resemblance to their 18th Century counterparts, the intricate maps
produced by colonial era cartographers in Saint-Domingue. Because these
cartographers also focused on towns and plantation regions, their maps
represent many of the areas depicted in the *Monograph*'s photos. On the
1785 ink-and-watercolor maps of the French marine engineer René
Phelipeau, the features of Saint-Domingue towns are rendered with
martial accuracy, reifying colonial imaginaries via colorful
representations of physical markers. Possessors of plantation properties
come into being as geographic subjects as the boundaries of their
*habitations* (plantations) are traced and marked with their family
names. At the same time, Phelipeau's maps attempt to reveal and render
legible forms of Black fugitivity, labeling sites of refuge such as
*mornes* (mountains).

{% include image.html
    img="issue07/phelipeau-tiburon.jpg"
    title="insert title here"
    caption="Phelipeau, \"Plan de la Baye et du Bourg de Tiburon dans l'Isle St Domingue,\" 1785. From the Memoire des Hommes database hosted by the Service Historique de la Défense, Paris"
    url="http://optional-url.com" %}

{% include image.html
    img="issue07/screenshot.jpg"
    title="insert title here"
    caption="Screenshot from the Monograph of Haiti Map, 1932/2022."
    url="https://dukeuniv.maps.arcgis.com/apps/webappviewer/index.html?id=de268c688b8142fbb689fb52826fa818"
%}

In the case of the *Monograph*, its photos were key to a strategic and
comprehensive compiling of information from spaces occupied by Man's
human others. They were essential in a project that sought to deploy the
discipline of geography for capitalist extraction by concurrently making
war on Haitian peasants and their sovereign land management practices,
"damning" spaces inhabited by both visible and invisible forms of life.
Recognizing aerial technology and its totalizing ambitions as
conceptually beholden to European colonial cartography brings to light
the close links between epistemic and physical dispossession. The
knowledges produced by colonial and occupation administrations worked to
negate earth-based ties to ancestors, articulated through the *lakou*
system of land ownership common in rural Haiti,[^15] and to transmute
layered, spiritually meaningful ecologies into extractable resources.
Concretely, persisting colonial geographic imaginaries had/have their
material expression in the accumulation of land and capital. The
occupation, backed by its comprehensive aerial gaze, resulted in the
emptying of the Haitian national bank, the rewriting of the Haitian
constitution in 1918 to allow foreigners to purchase land (outlawed
since independence), and the subsequent acquisition of tens of thousands
of acres by American corporations.

The *Monograph* artifact itself, presented as an exhaustive,
encyclopedic register of knowledge containing "all the information
obtainable to commence active operations" in Haiti, clearly discloses
the imbrication of racial subjugation with certain modes of geographical
legibility.[^16] The *corvée,* or shackling of rural cultivators for
unfree work in infrastructure,[^17] created roads and access to Haiti's
interior. Occupiers' strategies for rendering the landscape transparent
and accessible, such as road building and aerial photography, led to the
exposure of Caco hideouts and massacres of peasants. The planes that
took photos also dropped bombs on civilian populations; Thomazeau and
Les Cayes were attacked from the air in 1919. In the photo of the latter
town, there are visible empty spaces along the streets, conceivably left
by the bombing a few decades earlier.

{% include image.html
    img="issue07/navy-planes.jpg"
    title="insert title here"
    caption="U.S. Navy Curtiss HS-2Ls and other airplanes in Haiti circa 1919.From the Walter V. Brown Collection (COLL/4326), Marine Corps Archives & Special Collections."
    url="http://optional-url.com" 
%}

## III. Detours into dark sousveillance

During the hours spent scanning for stable points in flattened, emptied
landscapes, I wondered who had been removed, what practices and everyday
paths of living made invisible, what knowledge erased. As I inscribed a
new layer of legibility onto the photos through georeferencing, I
thought about resistant forms and configurations of life, and about the
embodied refusal of occupying forces.

The creation of the white geographic/cartographic subject in tandem with
overseeing relies upon the notion of transparency and the creation of
transparent space, where making transparent can be understood as
violating Glissant's right to opacity.[^18] In the contexts of slavery and
post-slavery, a consistent goal and method of oppressors was to capture the other
through total comprehension. Pushing up against this
violent drive towards transparency, then, many scholars identify Black
geographic knowledge and placemaking as (not exclusively, but
significantly) informed by fugitivity and furtivity; uncontainability
and excess; invisibility and fungibility.[^19]

Simone Browne locates the birth of contemporary racializing surveillance
in the practices of transatlantic slavery. She troubles a surveillance
studies preoccupied with western modernity and notions like Foucault's
panopticon with readings of the slave ship, branding, slave passes and
patrols, and lantern laws as surveillance mechanisms based on
epidermalization. Most importantly, Browne recasts "sousveillance"---
the antithesis of surveillance-as-oversight, from the French *sur-,*
"from above" and *-veillance,* "watching"--- to generate the concept of
"dark sousveillance":

> I use the term 'dark sousveillance' as a way to situate the tactics
> employed to render one's self out of sight, and strategies used in the
> flight to freedom from slavery as necessarily ones of undersight
> ...I plot dark sousveillance as an imaginative place from which
> to mobilize a critique of racializing surveillance, a critique that
> takes form in antisurveillance, countersurveillance, and other freedom
> practices.[^20]

Dark sousveillance is an active inversion of those power relations
grounded in antiblack oversight and overseeing ("*sur-veillance*,"
plantation visuality, and viewing from above) through acts of
*undersight*, or appropriating, co-opting, and challenging "tools of
social control in plantation surveillance ...in order to facilitate
survival and escape."[^21] Browne finds these attempts to render one's
self out of sight in acts of physical fugitivity but also in the spaces
of epistemic refuge generated by Black performative and spiritual acts
and creative freedom practices---spirituals, songs, and dancing. What
acts of dark sousveillance did resistance groups undertake against the
racializing surveillance epitomized in the *Monograph*'s aerial photos?
How is the existence of oppositional, countersurveillance imaginaries
betrayed by the *Monograph*'s admission that "many inhabitants took to
the hills rather than to submit to 'corvee' unjustly enforced"?[^22] How
do traces of occupation-era attempts to render self out of sight
necessarily prompt more nuanced approaches to the photomap?

Although by 1932 the U.S.-trained *gendarmerie* had suppressed most
peasant resistance to the occupation's expropriation of land and forced
labor, earlier freedom efforts by Caco rebels haunt the pages of the
*Monograph*. The anxiety provoked by these uprisings is reflected in the
attention given to "Bandit Areas" as subheadings in descriptions of
regional military departments. For example, in the Department of the
Center, rural sections of Coupe Mardi Gras and Riviere Canot
(Mirebalais) "appear to offer nests where bandits can hide" in the
Department of the West, "the whole chain to the northwest, and the
Montagnes Noires are places best suited to the free display of bandit
activities."[^23]

The *Monograph*'s language citing spaces of Caco refuge as bandit
"nests" manifestly reflects the Marines' animalization of rebel
fighters, but perhaps inadvertently echoes more sympathetic perceptions
and/or mythic understandings of the Cacos' political project. The
insurgents who held out against occupying forces in the mountainous
regions of Haiti share their name with a bird endemic to the
region---either the red-plumed Hispaniolan trogon (*Priotelus
roseigaster*), Haiti's national bird, or, according to Haitian historian
Pauleus Sannon, the "Tacco d'Hispaniola," the Hispaniolan lizard cuckoo
(*Coccyzus lognirostris*).[^24] Both are forest-dependent bird species
that forage in dense vegetation and nest in tree cavities. Sannon writes
that peasant guerillas used to hide, like their avian namesake, under
plant matter to surprise and attack their adversaries. "*Devenus par corruption Cacos, le
sobriquet de Tacos fut donné aux insurgés, parce qu'ils se cachaient,
comme l'oiseau de ce nom, sous la feuillée pour surprendre et attaquer
l'ennemi*."[^25]

Whatever species they were named for, the Cacos' sobriquet stems
directly from their identification with acts of dark sousveillance.
Their work of placemaking and defense, adapted to contest capture and
death from above, relied on a tactical use of foliage, topography, and
the mirroring of animal movements to sustain survival and escape.
Resistance fighters performed countersurveillance through camouflage and
ambush techniques drawn from mountain ecologies, including rendering
themselves out of sight under leaves and undersight-based surprise
attacks. Cacos' subversive geographic imaginaries, embodied in practices
of dark sousveillance, were inspired by the natural world and by
beyond-human ways of living. However, ultimately, the plantation
visuality made possible by aerial technology undermined the success of
these strategies:

> Te U.S. opened the year 1920 with a concerted effort to rid Haiti
> of the insurgent war that had torn it apart for nearly two years. For
> the next six months, the improved force of marines and gendarmes
> relentlessly drove the cacos back whenever they met. The marines were
> assisted by the innovation of coordinated air-ground attacks through
> the use of two airplanes, a Jenny and a De Havilland.[^26]

Yet another instance of the use of photography as a technology of
terror---and its diversion by imaginaries of dark sousveillance---can be
situated in the aftermath of the Cacos' 1919 attack on Port au Prince,
led by Charlemagne Peralte.[^27] After his betrayal and assassination,
Peralte's body was tied to a door and left to decompose on public
display in Le Cap; copies of a photo taken by a U.S. Marine photographer
were distributed in the countryside with the intent of discouraging
resistance.[^28] But this visual multiplication of hypervisible,
spectacular death---a dissemination of terror meant to surveil, control,
and curtail Black life---did not have its intended effect. Photography
as an instrument of oversight (not for traditional plantation
surveillance, but to maintain the occupation and its racist, extractive
regime of terror) was coopted, repurposed, challenged, and transformed,
as "istead the photograph became an iconic depiction of Peralte as
a martyr for liberty."[^29] The photo of Peralte's body, produced and
circulated by the occupying overseers, signified differently to the
peasant population, which turned this visual tool of social control
against itself in an act of creative dark sousveillance. Peralte's
execution, its resemblance to a crucifixion, and his martyrdom and its
subsequent iconography perhaps communicated symbolic undercurrents of
resurrection and transformation. The door signifies as a cross; the
cross suggests crossroads; the crossroads opens onto powerful, invisible
forces.

Finally, in the wake of the occupation, the plantation complex of
visuality-turned-tourist gaze meets stubborn resistance in Félix
Morisseau Leroy's 1953 poem "Touris, pa pran pòtre m."[^30] The
photographer's entitled expectation of transparency is disputed by the
subtle, hostile dignity and vocal refusal of Morisseau Leroy's speaker:
"*pa pran pòtre m*."[^31] This rendering of self out of sight manifests
through words of warning, with a threat of resistance powerful enough to
break the Kodak camera, tool of surveillance and of potential
epidermalization: "*Kodak ou a va kase.*"[^32] The American camera in
the air, which Morisseau Leroy might describe as *Kodak nan syèl la*,
saw and captured entire towns, rows of houses; it effaced their
inhabitants, froze unruly vegetation and tumbling rivers. Yet the
speaker cautions the American tourist:

> *Touris, pa pran pòtre kay la*   
> *Kay mwen, se kay pay*   
> *Pa pran pòtre joupa ajoupam*   
> *Joupa m, se kay tè*   
> *Pa pran pòtre jaden m*[^e1]

[^e1]:
    "Tourist, don't take a picture of the house    
    My house is a straw house   
    Don't take a picture of my *ajoupa* hut   
    My *ajoupa* is an earthen house   
    Don't take a picture of my garden" (my translation)


The speaker's insistent use of possessive pronouns works to repossess
home and garden spaces in all their materiality, to wrest them away from
and speak back against white visual power in an act of dark
sousveillance. The admonition in this poem, its refusal of transparency
and assertion of presence in the landscape, resounds against the emptied
aerial photos of the *Monograph* *Map*. Taking seriously a perspective
of undersight against oversight means respatializing the houses, huts,
and gardens of the surveillance photos as *belonging to* someone, as
opaque and resistant to views from above despite repeated aerial
assaults.

## IV. Openings beyond ocularcentrism

The current version of the *Monograph Map* project encourages the site's
visitors to think through the questions I have raised here. When users
arrive at the home page, they do not immediately encounter the satellite
base layers; instead, a certain disorientation is produced through the
foregrounding of the white space around the incomplete mosaic of towns.
A set of reflections and questions on the "About" page suggests further
reading and invites visitors to do speculative, imaginative work looking
for what else must have been happening in the landscape. Admittedly,
these partial efforts fall short of tackling the deeper questions raised
by framing the photographs as we currently do. In my conclusion to this
article, I attempt to make a fruitful link between the freedom practices
of Haitian dark sousveillance discussed earlier and the design
approaches and tactics we might utilize in future versions of the
project. Such countermapping would consider those who refused the U.S.
Marine occupation as authors of their own geographies and would insist
that their forms of representing and inhabiting space inform ways of
seeing Haiti in the present.

Scholars employing digital mapping practices to represent and understand
Black Atlantic history from below have long confronted the challenge of
how to approximate, via design choices, ways of perceiving that refuse
plantation visuality.[^33] Jessica Marie Johnson's notion of Black
digital practice "makes space \...for black diasporic longing,
insurgence, hauntings, and community mourning to inform how digital
tools might be used to uncover acts of resistance, insurgent politics,
and evidence of self-fashioning."[^34] The lens of Black digital
practice encourages us to see past the obscuring tendencies of archives
of structural violence and the supposed neutrality of the digital
towards the experiential and embodied possibilities generated by Black
geographic subjects. It helps us to ask how we might recognize or
appreciate acts of dark sousveillance such as those of the Cacos'
camouflage or Morisseau Leroy's speaker's refusal to be photographed.

Can projects like the *Monograph of Haiti Map* be complemented or
enriched to ethically chart praxes of living and "evidence of
self-fashioning" beyond plantation and occupation oversight? How might
we engage archives and digital methods to honor perspectives of the
resistant overseen, instead of mimicking overseers' gazes? Following
McKittrick, in what ways might we attend to the connections between
material spaces, language, and subjectivity, to explore the possibility
of representing "an interpretive alterable world, rather than a
transparent and knowable world"?[^35] Without abandoning the
*Monograph*'s photos, is there room to express "dfferential modes
of survival"---ways of perceiving, communicating, expressing, and being
in the world?[^36]

At its base, this is a question of how we envision users interacting
with these maps. Placed over contemporary satellite imagery of Haiti,
are they sufficiently transformed so that they can now be used to ends
very different than those for which they were created? Can the
photographs help us better understand how Haitians organized and lived
in their space? Or is the form itself so imbued with the intent of
surveillance that, in a sense, it can't be redeemed from that original
intent? Do we need a more prescriptive set of designs to make sure users
move towards conceptualizing the inhabited landscape along different
lines and through different terms?

A partial solution, in my opinion, is to strive for an equilibrium in
design decisions that would allow for engagement with the photographs
while recalling their part in the continuation of regimes of plantation
visuality. Taken even further, this design would acknowledge the
practices of dark sousveillance that resist the photos' very existence,
augmenting the project by interweaving or punctuating the photomap with
archival materials that open onto perspectives of undersight,
counter-visuality and opacity/counter-transparency. For this, we might
turn to sources produced by ostensibly less extractive relationships to
Haitian people and landscapes---fictions or ethnographies written during
or about the period, for instance.[^37]

Other Black Atlantic digital projects, including pioneering efforts in
visualizing rebel war strategy and the flight patterns of maroons, have
experimented with designs to exploit the possibilities of historical
contingencies, uncertainties, and nonlinear temporalities, thus
upsetting overdetermined historiographies of Black expendability and
death. Scholars like Tao Leigh Goffe have asked what emancipatory
potential lies in ways of navigating and perceiving beyond the visual
realm, in collaborative intimacy with the beyond-human.[^38] Like the
Cacos, Maroons absorbed beyond-human sensory epistemologies (in this
case, bats' echolocation), and their embodied expertise nurtured unique
geographic imaginaries.

Haiti, since its days as Saint-Domingue, has been the scene of
disrupting "ocularcentric forms of knowledge production and the written
word," a space of unmapping and countermapping through radical,
ancestrally-grounded sensory orientations in space and time.[^39]
Communal forms of inhabiting space like *lakou* and *kombit*[^40] and
their urban and diasporic transformations imbue natural features,
architectures, songs, healing plants, and subsistence agriculture with
myriad and layered ties to invisible worlds. Haiti is home to "a
decolonial poetics that reads black dispossession as a 'question
mark.'"[^41]

To escape the ocularcentric plantation gaze of the *Monograph* photomap
and its always-already assumptions of Black dispossession, I end this
reflection by evoking a counter-visual archive relatively contemporary
with the occupation. Alan Lomax's 1936-1937 recordings in Mirebalais
offer a sonic point of entry into a counter-mapping, a "sounding" of
Haitian towns through the music produced by their inhabitants. These
songs hold fragments of the stories and soundscapes of a peasantry whose
eviction, abuse, and death are cleanly erased from the *Monograph*
photos' oversight. They are key to recognizing the vernacular maps and
meanings brought into existence by people resisting/existing outside of
the geospatial laws and racial categories of occupying forces. The
orientations to space and time contained in the Lomax recordings, sung
four years after the *Monograph* was compiled, represent a rich foil to
racializing surveillance techniques but also, in their own right,
revalidate peasants as expert geographic agents and authors. Song titles
hint at spatial imaginaries in which landscape features encompass the
beyond-physical world:

> "*D'leau nan rivière yo meté wanga la-dans*"
> 
> "*Ou'a campe nans bariere, atibon, ce pou m'tende
> nouvelle-yo*"
> 
> "[*Legba seul, gardé nans mitans yo*](https://www.loc.gov/item/afc9999005.28006/)" [^42]

Atibon Legba lives at physical crossroads, and he is listening.
Quotidian Vodou practices---sounds, movements, practices of healing and
growing---weave sacred relations into geomorphic features and material
culture. The earth is not a flat surface, but a dynamic site of
ancestral and sacred presencing. In the sense that it offers refuge from
colonial logics of transparency and extractivism, Vodou is dark
sousveillance; during the occupation, its codes fed powerful forms of
place-making imperceptible to Marines' surveillance efforts.

"Back lives are necessarily geographic, but also struggle with
discourses that erase and despatialize their sense of place."[^43]
Peasant communities' senses of place in 1930s Haiti might be
re-spatialized by taking seriously---and geographically---the sacred
presences invoked in Vodou songs in conjunction with topography. Digital
design might be engaged to follow *sevitè* (practitioners) in
understanding their surroundings not as fixed backdrops for events, or
"landscapes," but as emergent and agential, brought into existence by
constantly unfolding negotiations between numerous forces.

In the case of the *Monograph of Haiti Map*, this would require, through
creative design, a disturbance of the foundational logics underlying
both the aerial images and satellite map: antiblack transparency,
violent oversight, naturalized Cartesian points. Without reproducing
them, the project would need to trouble these ways of organizing space,
to make room to re-spiritualize and reanimate the frozen landscapes
captured in sepia tones as well as the falsely neutral sprawling
satellite view of today. In opacity, the *Monograph Map* project might
take up the immense challenge of how to digitally engage with Haitian
geographic knowledge---as ecological, non-objectifying, and constituted
through active, relational processes between humans and nonhumans. We
could start to ask what it would mean to map without capture or
transparency---to mark as significant, perhaps---every crossing of roads
as a *kalfou* (crossroads)*,* as a point of traffic between visible and
invisible worlds.

---

[^1]: For more on the U.S. occupation, see Roger Gaillard's seminal
    multi-volume collection; Hans Schmidt, *The United States Occupation
    of Haiti, 1915-1934*; Mary Renda, *Taking Haiti*; Laurent Dubois,
    *Haiti: The Aftershocks of History*; Jonathan Katz, *Gangsters of
    Capitalism.*

[^2]: [*Monograph of the Republic of Haiti,* (1932),
    4](https://archive.org/details/MonographOfHaiti1932/page/n3/mode/2up).
    All further page numbers for the Monograph will reference the
    Internet Archive version <https://archive.org/details/MonographOfHaiti1932/page/n3/mode/2up>.

[^3]: In a project review of the website (in this issue) my site
    co-authors and I address issues of accessibility, design, user
    experience, and other elements of the platform itself.

[^4]: Simone Browne, *Dark Matters: On the Surveillance of Blackness*
    (Durham: Duke University Press, 2015).

[^5]: "Georeferencing means that the internal coordinate system of a
    digital map or aerial photo can be related to a ground system of
    geographic coordinates. A georeferenced digital map or image has
    been tied to a known Earth coordinate system, so users can determine
    where every point on the map or aerial photo is located on the
    Earth\'s surface."
    <https://www.usgs.gov/faqs/what-does-georeferenced-mean>

[^6]: Vincent Brown, "Mapping a Slave Revolt," *Social Text* 33, no. 4
    (2015): 134-41.

[^7]: For powerful visuals on this, see Arnold Antonin's film, *Men sa
    lanmè di* (2020; Haiti, 2020), Streaming.

[^8]: Katherine McKittrick, *Dear Science and Other Stories* (Durham:
    Duke University Press, 2020), 39.

[^9]: For analysis of occupation-era photography and wider
    20th-century visual representations of Haiti in U.S. media see
    Lindsay Twa, *Visualizing Haiti in U.S. Culture, 1910--1950* (London
    and New York: Routledge, 2014). The *National Geographic* photos
    studied by Twa in her first chapter complement the aerial images of
    the *Monograph* by offering a "street view" of some of the same
    towns.

[^10]: Nicholas Mirzoeff, *The Right to Look: A Counterhistory of
    Visuality* (Durham: Duke University Press, 2011), 50.

[^11]: Mirzoeff, *The Right to Look,* 49-50.

[^12]: See Ryan Fontanilla, "Immigration Enforcement and the Afterlife
    of the Slave Ship," *Boston Review*, February 11, 2021.
    <https://bostonreview.net/articles/ryan-fontanilla-immigration-enforcement-and-afterlife-slave-ship/>

[^13]: Tiffany Lethabo King, *The Black Shoals: Offshore Formations of
    Black and Native Studies* (Durham: Duke University Press*,* 2019),
    78.

[^14]: Katherine McKittrick, "Plantation Futures," *Small Axe* 17, no. 3
    (2013): 5.

[^15]: *Lakou* is a way of organizing space that tethers ancestral and
    sacred presences to living kin through physical yard configurations;
    its participants include humans (multiple generations of living and
    deceased), plants, and *lwa* (spirits)*.* For more on *lakou* and
    wider counter-plantation practices, see Jean Casimir, *The Haitians:
    A Decolonial History* (Chapel Hill: UNC Press, 2020)*.* For
    ecological degradation as spiritual loss in Haiti, see Rebecca
    Dirksen, "Haiti, Singing for the Land, Sea, and Sky: Cultivating
    Ecological Metaphysics and Environmental Awareness through Music,"
    *MUSICultures* 45, no. 1-2 (2018).

[^16]: [*Monograph of Haiti,*
    4.](https://archive.org/details/MonographOfHaiti1932/page/n3/mode/2up)

[^17]: See Roger Gaillard, "Memories of Corvée Labor and the Caco
    Revolt," in *The Haiti Reader,* ed. Laurent Dubois et al (Durham:
    Duke University Press 2020).

[^18]: "Opacity ...tries to overcome the risk of reducing,
    normalizing and even assimilating the singularities of cultural
    differences by comprehension. Within this framework, Glissant
    challenges the rational epistemic of Enlightenment and its
    assumption of universal truths by calling into question the
    etymological meaning of 'comprehension' (com-prendere) as an act of
    appropriation." Andrea Gremels, "Opacité/Opacity (Édouard
    Glissant)." *Keywords in Transcultural English Studies* (blog).
    <http://www.transcultural-english-studies.de/opacite-opacity-edouard-glissant/>

[^19]: See Katherine McKittrick, *Demonic Grounds* (Minneapolis:
    University of Minnesota Press, 2006).

[^20]: Browne, *Dark Matters,* 21.

[^21]: Browne, *Dark Matters,* 21.

[^22]: [*Monograph of Haiti,*
    115.](https://archive.org/details/MonographOfHaiti1932/page/n113/mode/2up)

[^23]: *Monograph of Haiti,*
    [351](https://archive.org/details/MonographOfHaiti1932/page/n349/mode/2up),
    [362](https://archive.org/details/MonographOfHaiti1932/page/n359/mode/2up).

[^24]: Horace Pauleus Sannon, *Histoire de Toussaint Louverture*
    (Port-au-Prince: A Heraux, 1938), 142.

[^25]: "Corrupted as 'Cacos,' the nickname of 'Tacos' was given to the insurgents because
they used to hide, like the bird of the same name, underneath foliage to surprise and attack the enemy." Sannon, *Histoire,* 142.

[^26]: John Tierney, Jr. "America's 'Black Vietnam': Haiti's Cacos vs.
    The Marine Corps, 1915-22," *The Institute of World Politics,*
    September 1, 1981,
    <https://www.iwp.edu/articles/1981/09/01/americas-black-vietnam-haitis-cacos-vs-the-marine-corps-1915-22/>.

[^27]: For more on the life and death of Peralte and the Cacos'
    resistance, see Yveline Alexis, *Haiti Fights Back: The Life and
    Legacy of Charlemagne Péralte* (New Brunswick: Rutgers University
    Press, 2021).

[^28]: Philomé Obin, "The Crucifiction of Charlemagne Péralte," in *The
    Haiti Reader: History, Culture, Politics,* ed. Laurent Dubois et al
    (Durham: Duke University Press, 2020), 198.

[^29]: Obin, "The Crucifiction," 198.

[^30]: Félix Morisseau Leroy, "Touris, pa pran pòtre m," in *Djakout*
    (Port-au-Prince: 1953).

[^31]: "Do not take my photo."

[^32]: "Your camera will break."

[^33]: See Roopika Risam and Kelly Baker Josephs, ed., *The Digital
    Black Atlantic* (Minneapolis: University of Minnesota Press, 2021).

[^34]: Jessica M. Johnson, "Xroads Praxis: Black Diasporic Technologies
    for Remaking the New World," *archipelagos* 3 (2019).

[^35]: McKittrick, *Demonic Grounds,* xiii.

[^36]: McKittrick, "Plantation Futures," 3.

[^37]: A non-exhaustive list might include works by René Depestre,
    Frankétienne, Marie Vieux-Chauvet, Katherine Dunham, Zora Neale
    Hurston, and Melville Herskovits.

[^38]: Tao Leigh Goffe, "Unmapping the Caribbean: Toward a Digital
    Praxis of Archipelagic Sounding" *archipelagos* 5 (2020).

[^39]: Goffe, "Unmapping the Caribbean."

[^40]: *Kombit* is a collaborative agricultural effort involving many
    intangible elements (song, dance, joke telling).

[^41]: McKittrick, "Plantation Futures," 5.

[^42]: Here, I will attempt to translate from Lomax's transcribed Kreyòl
    while acknowledging the historical role of total and unilateral
    translation in surveillance efforts that disrespect rights to
    opacity: "They put *wanga* in the water of the river"; "You will
    stand at the gate, Atibon, so I can hear the news"; "Legba alone
    protects the in betweens" If the river has *wanga* in it, its
    waters become a charm. <https://www.loc.gov/item/afc9999005.28005/>; <https://www.loc.gov/item/afc9999005.28455/>. For more on *wanga* see
    Karen McCarthy Brown, "Making Wanga: Reality Constructions and the
    Magical Manipulation of Power" in *Religion and Healing in America.*

[^43]: McKittrick, *Demonic Grounds,* xiii.
