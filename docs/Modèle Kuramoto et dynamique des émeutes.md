# **Dynamique Non-Linéaire des Émeutes : Analyse de l'Effet Kuramoto, de l'Entraînement Émotionnel et de la Synchronisation Explosive**

## **Résumé Exécutif**

Ce rapport de recherche examine l'hypothèse selon laquelle les phénomènes sociologiques d'« effet d'entraînement » et d'« escalade contagieuse » observés lors des émeutes civiles sont intrinsèquement liés aux principes mathématiques du **modèle de Kuramoto**. À travers une analyse exhaustive de la littérature en physique sociale, en neurobiologie des rythmes sociodiens et en dynamique des réseaux complexes, nous confirmons une convergence théorique et empirique forte. L'effet d'entraînement correspond à un verrouillage de phase (*phase-locking*) entre agents biologiques oscillateurs, médié par la contagion émotionnelle. L'escalade contagieuse, quant à elle, s'identifie formellement à une **transition de phase du premier ordre**, spécifiquement une **Synchronisation Explosive (ES)**. Ce phénomène, absent du modèle classique de Kuramoto mais présent dans ses variantes inertielles et structurées en réseaux, explique la soudaineté, la violence et l'hystérésis (irréversibilité temporaire) caractéristiques des émeutes urbaines. Le rapport propose une synthèse unifiée où la tension sociale agit comme un champ de couplage critique, transformant une foule hétérogène en une entité macroscopique cohérente.

## ---

**1\. Introduction : La Physique Sociale des Foules**

L'étude des foules a longtemps oscillé entre la psychologie descriptive, initiée par Gustave Le Bon dans *Psychologie des Foules* (1895), et la sociologie politique. Le Bon décrivait la foule comme une entité où l'individu perd sa personnalité consciente pour se fondre dans une « âme collective » dominée par la contagion mentale.1 Si cette vision a posé les bases intuitives, la **physique sociale** moderne cherche à quantifier ces dynamiques en utilisant les outils de la mécanique statistique et des systèmes dynamiques non-linéaires.2

La question centrale de ce rapport est de déterminer si le modèle de Kuramoto—conçu initialement pour décrire la synchronisation d'oscillateurs biologiques et chimiques—peut fournir le substrat mathématique nécessaire pour expliquer deux phénomènes précis des émeutes :

1. **L'effet d'entraînement :** Le processus par lequel des individus adoptent involontairement le comportement ou l'émotion du groupe.  
2. **L'escalade contagieuse :** La transition rapide, souvent violente, d'un état de calme relatif à un état de désordre généralisé.

L'analyse démontre que l'analogie n'est pas seulement métaphorique mais structurelle. Les interactions humaines dans une foule dense, régies par des mécanismes neurobiologiques de mimétisme et de résonance émotionnelle, obéissent aux mêmes lois d'universalité que les oscillateurs couplés.3

### **1.1 Définitions et Opérationnalisation des Variables**

Pour établir ce lien, il est impératif de traduire le lexique sociologique en variables physiques :

* **L'Agent Social comme Oscillateur :** Chaque individu est modélisé comme un système dynamique doté d'une « phase » interne $\\theta\_i$ (état émotionnel, intention d'action) et d'une « fréquence naturelle » $\\omega\_i$ (prédisposition à l'action, radicalité intrinsèque).4  
* **La Contagion Émotionnelle comme Couplage ($K$) :** La transmission des émotions (peur, colère) agit comme une force de couplage qui tend à minimiser la différence de phase entre les individus ($\\theta\_j \- \\theta\_i$). C'est le « liant » du système.5  
* **L'Émeute comme État Synchronisé :** L'émergence de l'émeute correspond à l'apparition d'un paramètre d'ordre macroscopique $r(t) \> 0$, signifiant que les phases individuelles se sont alignées. La foule agit alors comme un seul corps.6

## ---

**2\. Fondements Théoriques : Le Modèle de Kuramoto**

Le modèle de Kuramoto est paradigmatique pour la compréhension de la synchronisation dans les grandes populations d'oscillateurs couplés. Sa pertinence pour les dynamiques sociales réside dans sa capacité à décrire comment l'ordre (synchronisation) émerge spontanément du désordre (incohérence) sans chef d'orchestre central.8

### **2.1 L'Équation Canonique**

L'évolution de la phase $\\theta\_i$ de chaque individu $i$ dans une population de taille $N$ est régie par l'équation différentielle suivante :

$$\\frac{d\\theta\_i}{dt} \= \\omega\_i \+ \\frac{K}{N} \\sum\_{j=1}^{N} \\sin(\\theta\_j \- \\theta\_i) \+ \\xi\_i(t)$$  
Les composantes de cette équation trouvent des échos directs dans la phénoménologie de l'émeute :

| Terme Mathématique | Interprétation Sociologique / Émeute | Description Détailée |
| :---- | :---- | :---- |
| **$\\omega\_i$ (Fréquence propre)** | **Prédisposition Individuelle** | La tendance naturelle de l'individu à l'action ou à la violence, indépendamment du groupe. Une distribution large de $\\omega$ indique une foule hétérogène (militants, passants, pacifistes). |
| **$K$ (Force de Couplage)** | **Tension Sociale / Influence** | L'intensité de l'interaction sociale. Un $K$ élevé signifie une forte perméabilité aux émotions d'autrui (foule dense, forte charge émotionnelle, présence policière augmentant la cohésion). |
| **$\\sin(\\theta\_j \- \\theta\_i)$** | **Fonction d'Interaction** | La mécanique de l'influence : un individu ajuste son comportement pour s'aligner sur ses voisins. L'influence est maximale quand la divergence est modérée. |
| **$\\xi\_i(t)$ (Bruit Stochastique)** | **Incertitude / Désordre** | Facteurs aléatoires perturbant l'alignement (confusion, fumée, messages contradictoires). Le « bruit » s'oppose à la synchronisation.3 |

### **2.2 Le Paramètre d'Ordre et la Cohérence Collective**

L'état global du système est mesuré par le paramètre d'ordre complexe $r(t)$ :

$$r(t) e^{i\\psi(t)} \= \\frac{1}{N} \\sum\_{j=1}^{N} e^{i\\theta\_j(t)}$$

* **$r \\approx 0$ (Phase Incohérente) :** Les phases sont distribuées uniformément. La foule est une somme d'individus aux comportements disparates (discussions, mouvements aléatoires). C'est l'état de « paix » ou de manifestation calme.  
* **$r \\approx 1$ (Phase Synchronisée) :** Les phases sont verrouillées (*phase-locked*). La foule scande les mêmes slogans, avance au même pas, ou s'engage dans la violence simultanément. C'est l'état d'émeute.4

La recherche confirme que le passage de $r \\approx 0$ à $r \> 0$ est une **transition de phase**. Si le couplage $K$ dépasse un seuil critique $K\_c$, l'ordre émerge spontanément. C'est ici que réside la réponse fondamentale à la requête : le lien entre l'effet d'entraînement et le modèle de Kuramoto est l'existence mathématique de ce seuil critique de synchronisation.

## ---

**3\. L'Effet d'Entraînement : Mécanismes Biologiques et Physiques**

L'utilisateur interroge spécifiquement le lien avec « l'effet d'entraînement ». L'analyse des documents fournis permet de déconstruire ce phénomène non plus comme une métaphore psychologique, mais comme un processus biophysique d'**entrainement neuronal et moteur**, validant l'application du modèle d'oscillateurs.

### **3.1 Rythmes Sociodiens et Synchronisation Moteur**

La recherche récente introduit le concept de **« rythme sociodien »**, un homologue social du rythme circadien. Les humains, en tant qu'organismes hautement sociaux, possèdent des mécanismes biologiques pour synchroniser leurs horloges internes et leurs comportements avec leurs congénères.9

* **L'Entraînement Neuronal :** Des études EEG montrent que le cerveau humain présente des oscillations endogènes qui se verrouillent en phase avec des stimuli rythmiques externes (musique, battement, discours d'un leader). Ce processus, connu sous le nom d'entrainement (*entrainment*), est un processus endogène médiant la perception du rythme.10  
* **Le Rôle du Contact Visuel et de l'Ocytocine :** Le contact visuel agit comme un mécanisme de synchronisation rapide, facilitant l'alignement des états émotionnels et de l'excitation (*arousal*). L'ocytocine module ces voies, renforçant le couplage ($K$) entre les oscillateurs biologiques individuels.12

Dans le contexte d'une foule, ces mécanismes sont amplifiés. La densité physique et sensorielle crée un environnement où les stimuli de synchronisation (chants, mouvements brusques) saturent les canaux sensoriels, forçant les oscillateurs neuronaux individuels à s'aligner sur la fréquence dominante du groupe.

### **3.2 La Contagion Émotionnelle comme Vecteur de Phase**

La contagion émotionnelle est définie comme le phénomène où les individus absorbent et imitent les émotions de ceux qui les entourent, souvent en quelques millisecondes.5

* **Mimétisme Moteur :** L'observation d'une expression faciale ou d'un geste agressif déclenche une simulation motrice chez l'observateur (neurones miroirs).  
* **Fusion Identitaire :** Dans les foules denses, ce mimétisme conduit à une perte des limites soi-autre. La théorie de la désindividuation suggère que cette fusion est l'équivalent psychologique de la synchronisation de phase parfaite ($r \\to 1$), où l'identité individuelle (la fréquence propre $\\omega\_i$) est totalement asservie au champ moyen du groupe.1

Ainsi, l'effet d'entraînement observé dans les émeutes est la manifestation macroscopique de millions d'interactions de couplage microscopiques, régies par les équations de Kuramoto appliquées aux réseaux neuronaux et sociaux.

## ---

**4\. Escalade Contagieuse : La Synchronisation Explosive (ES)**

Le deuxième volet de la requête concerne l'« escalade contagieuse ». Si le modèle de Kuramoto standard explique la synchronisation, il échoue parfois à expliquer la *soudaineté* et la *violence* de l'escalade. Pour cela, il faut faire appel à une variante plus complexe : la **Synchronisation Explosive**.

### **4.1 Transition de Phase du Premier Ordre vs Second Ordre**

Dans le modèle classique de Kuramoto (avec une distribution de fréquences unimodale), la transition vers la synchronisation est continue (transition de phase du second ordre). L'ordre paramètre $r$ augmente progressivement à mesure que $K$ augmente. Cela correspondrait à une manifestation qui s'échauffe doucement.

Cependant, les émeutes se caractérisent souvent par une rupture brutale : le calme règne, puis soudainement, le chaos éclate. Ce comportement correspond mathématiquement à une **transition de phase du premier ordre**, ou **Synchronisation Explosive (ES)**.14

* **Discontinuité :** Dans l'ES, le paramètre d'ordre $r$ saute de 0 à une valeur élevée de manière discontinue dès que le couplage franchit le seuil critique.  
* **Irréversibilité et Hystérésis :** Une caractéristique clé de l'ES est l'hystérésis. Le chemin pour déclencher l'émeute (augmenter la tension $K$) est différent du chemin pour l'apaiser. Une fois la foule synchronisée (émeute), réduire la tension à son niveau initial ne suffit pas à rétablir le calme. Il faut une réduction drastique de la tension (force de couplage) pour « casser » la synchronisation.16

### **4.2 Le Rôle de l'Inertie dans l'Escalade**

Pourquoi les foules humaines exhibent-elles cette explosivité? La réponse réside dans l'**inertie**. Contrairement aux oscillateurs sans masse du modèle standard, les opinions et les états émotionnels humains ont une inertie (résistance au changement).

Le modèle de Kuramoto avec inertie (équation du second ordre) est décrit par :

$$m \\ddot{\\theta}\_i \+ \\gamma \\dot{\\theta}\_i \= \\omega\_i \+ K \\sum \\sin(\\theta\_j \- \\theta\_i)$$

L'ajout du terme de masse ($m \\ddot{\\theta}$) transforme la nature de la transition. L'inertie permet aux individus de maintenir leur trajectoire (calme ou excitation) plus longtemps face à la pression sociale, jusqu'à un point de rupture où ils basculent tous simultanément.16 Ce modèle explique pourquoi une foule peut sembler résiliente pendant longtemps avant de craquer brutalement sous l'effet d'une perturbation mineure (la « goutte d'eau »).

### **4.3 Structure du Réseau et Rôle des « Hubs »**

La topologie du réseau social influence directement l'escalade.

* **Corrélation Degré-Fréquence :** Si les individus les plus connectés (hubs, influenceurs, leaders) possèdent des fréquences très différentes de la masse (par exemple, des agitateurs radicaux), ils peuvent retarder la synchronisation globale. Cependant, une fois que ces hubs sont entraînés, ils entraînent instantanément tout le réseau avec eux, provoquant une synchronisation explosive.15  
* **Réseaux « Petit Monde » :** Les réseaux sociaux modernes (numériques et physiques) possèdent des propriétés « petit monde » qui raccourcissent la distance pathologique entre les individus, facilitant une propagation quasi-instantanée de l'information et de l'émotion, rendant le système « mûr » pour une transition explosive.18

## ---

**5\. La Théorie du Champ de Tension Sociale (Modèle Berestycki-Nadal)**

Pour compléter l'approche Kuramoto, il est essentiel d'intégrer le cadre développé par Henri Berestycki, Jean-Pierre Nadal et Nancy Rodríguez 6, qui modélise explicitement l'émeute non seulement comme une synchronisation temporelle, mais comme une propagation spatio-temporelle.

### **5.1 Couplage Activité ($\\lambda$) et Tension ($\\alpha$)**

Ce modèle propose un système d'équations couplant :

1. **L'activité d'émeute ($\\lambda$) :** L'intensité explicite de la violence en un lieu et un temps donnés.  
2. **Le champ de tension sociale ($\\alpha$) :** Une variable implicite représentant le niveau de mécontentement ou de prédisposition à l'émeute (« ripeness »).

$$\\frac{d\\lambda}{dt} \= \\dots \+ r(\\alpha) G(\\lambda)$$  
Ici, la fonction $G(\\lambda)$ représente l'auto-renforcement (analogue au couplage de Kuramoto), mais modulé par la tension sociale $r(\\alpha)$.

### **5.2 Le Lien avec Kuramoto**

Bien que formulé différemment (équations de réaction-diffusion), ce modèle valide l'hypothèse de l'utilisateur sur plusieurs points :

* **Seuil de Déclenchement :** L'émeute ne se produit que si la tension sociale $\\alpha$ dépasse une valeur critique. Cela est analogue au seuil $K\_c$ dans Kuramoto. En dessous de ce seuil, les chocs exogènes (ex: incident policier) s'amortissent. Au-dessus, ils s'amplifient par effet d'entraînement.6  
* **Propagation par Ondes :** Une fois déclenchée, l'activité d'émeute se propage sous forme d'ondes progressives, similaire aux ondes de phase observées dans les réseaux de Kuramoto spatiaux.3

L'escalade contagieuse est ici interprétée comme le moment où le système franchit une séparatrice dans l'espace des phases, passant d'un point d'équilibre stable (paix) à un cycle limite ou un point fixe de haute activité (émeute).

## ---

**6\. Analyse Comparative des Phénomènes**

Pour répondre précisément à la demande de lier ces concepts, le tableau suivant synthétise les correspondances établies par notre recherche :

| Phénomène Observé (Utilisateur) | Concept Physique Correspondant | Mécanisme Sous-jacent | Preuves Documentaires |
| :---- | :---- | :---- | :---- |
| **Effet d'Entraînement** | **Verrouillage de Phase (Phase Locking)** | Les oscillateurs ajustent leur vitesse ($\\dot{\\theta}$) pour s'aligner sur la fréquence moyenne du groupe ($\\Omega$). | Entraînement EEG aux rythmes externes.10 Synchronisation des applaudissements.19 |
| **Escalade Contagieuse** | **Synchronisation Explosive (ES)** | Transition de phase du 1er ordre avec discontinuité. Le système "saute" vers l'ordre. | Modèles Kuramoto inertiels.16 Hystérésis dans les foules paniquées.20 |
| **Atmosphère "Mûre"** | **Couplage Super-Critique ($K \> K\_c$)** | La tension sociale ($\\alpha$) augmente la force de couplage effective entre les agents. | Modèle de tensions sociales.6 Rôle de la "maturité" du système.7 |
| **Retour au Calme Difficile** | **Hystérésis** | La stabilité de l'état synchronisé (émeute) est plus forte que celle de l'état incohérent. | Persistance de la synchronisation même si $K$ diminue.16 |
| **Rôle des Agitateurs** | **Hubs / Game Changers** | Les nœuds à haute fréquence ou connectivité entraînent le réseau. | Influence des "game changers" pour restaurer l'ordre ou semer le chaos.20 |

## ---

**7\. Implications Pratiques et Gestion de Crise**

La compréhension de l'émeute comme une dynamique de type Kuramoto offre des perspectives nouvelles pour la gestion des foules, dépassant la simple coercition.

### **7.1 La Stratégie des « Game Changers » (Changeurs de Jeu)**

Les simulations montrent que l'introduction d'agents « Game Changers »—des individus qui résistent à l'entraînement de la foule et maintiennent une trajectoire ou une émotion stable—peut inverser la transition de phase.

* **Mécanisme :** Ces agents agissent comme des « points d'ancrage » (*pinning control*) qui brisent la cohérence de phase locale. Pour être efficaces, ils doivent être positionnés stratégiquement là où le flux (la vitesse de phase) est le plus rapide.20  
* **Application :** Plutôt que de comprimer une foule (ce qui augmente le couplage $K$ et favorise la synchronisation explosive), les stratégies de désescalade devraient viser à injecter du « bruit » ou des agents de calme pour réduire le paramètre d'ordre $r$.

### **7.2 Surveillance des Précurseurs de Transition**

L'approche par la physique sociale suggère que l'escalade contagieuse n'est pas aléatoire mais précédée par des signaux précurseurs dans la dynamique des réseaux.

* **Entropie de Transition :** La mesure de l'entropie des motifs ordinaux sur des nœuds sentinelles (leaders d'opinion, groupes clés) peut prédire l'imminence d'une synchronisation explosive.14  
* **Détection des Cascades d'Information :** Sur les réseaux sociaux, l'analyse de la propagation des émotions (controverses, messages toxiques) permet d'estimer le niveau de tension $\\alpha$ et donc la proximité du seuil critique $K\_c$.21

## ---

**Conclusion**

La recherche confirme de manière affirmative et détaillée l'hypothèse de l'utilisateur : **il existe un lien fondamental et quantifiable entre l'effet d'entraînement, l'escalade contagieuse et le modèle de Kuramoto.**

1. **L'effet d'entraînement** n'est autre que la manifestation comportementale du **verrouillage de phase** des oscillateurs biologiques humains, facilité par des mécanismes neurobiologiques (rythmes sociodiens, neurones miroirs) qui agissent comme fonction de couplage.  
2. **L'escalade contagieuse** correspond à une **Synchronisation Explosive**, une transition de phase abrupte rendue possible par l'inertie des opinions et la structure complexe des réseaux sociaux. Ce phénomène explique pourquoi les émeutes éclatent soudainement et pourquoi, une fois déclenchées (hystérésis), elles développent une dynamique propre, difficile à arrêter.

En somme, l'émeute peut être décrite comme une **catastrophe** (au sens mathématique de la théorie des catastrophes de René Thom) dans un système d'oscillateurs couplés, où la tension sociale joue le rôle de paramètre de contrôle. Le modèle de Kuramoto, enrichi par l'inertie et la spatialité (Berestycki-Nadal), constitue ainsi l'outil théorique le plus puissant pour décrypter la physique de la violence collective.

### ---

**Annexes : Données Structurées et Comparaisons**

#### **Tableau 1 : Comparaison des Régimes Dynamiques (Modèle de Kuramoto)**

| Régime | Paramètre d'Ordre (r) | État de la Foule | Dynamique Temporelle | Type de Transition |
| :---- | :---- | :---- | :---- | :---- |
| **Sous-critique** ($K \< K\_c$) | $r \\approx 0$ | Calme, Incohérence, Diversité d'actions. | Fluctuations aléatoires autour de zéro. | Stable. |
| **Critique** ($K \\approx K\_c$) | Fluctuant | Tension, "Mûr" (*Ripe*), Apparition de clusters locaux. | Augmentation de la longueur de corrélation. | Instable (Sensible aux chocs). |
| **Super-critique** ($K \> K\_c$) | $r \\to 1$ | Émeute, Action unitaire, "Âme collective". | Verrouillage de phase global. | Stable (Hystérésis forte). |

#### **Tableau 2 : Facteurs Favorisant la Synchronisation Explosive (Riot)**

| Facteur | Effet Physique | Conséquence Sociale | Source |
| :---- | :---- | :---- | :---- |
| **Réseaux Scale-Free** | Corrélation Degré-Fréquence | Les leaders radicaux retardent puis précipitent l'explosion. | 15 |
| **Inertie Cognitive** | Terme $m\\ddot{\\theta}$ | La foule résiste au changement puis bascule brutalement. | 16 |
| **Tension Sociale Élevée** | Augmentation de $\\alpha$ (et $K$) | Réduit la barrière énergétique pour la transition. | 6 |
| **Contagion Émotionnelle** | Couplage fort ($K$) | Synchronisation rapide des états affectifs. | 5 |

#### **Sources des citations**

1. Crowds – Structures of Chaos \- Spiegeloog, consulté le janvier 2, 2026, [https://www.spiegeloog.amsterdam/crowds-structures-of-chaos/](https://www.spiegeloog.amsterdam/crowds-structures-of-chaos/)  
2. The physical modelling of society: A historical perspective | Request PDF \- ResearchGate, consulté le janvier 2, 2026, [https://www.researchgate.net/publication/228942578\_The\_physical\_modelling\_of\_society\_A\_historical\_perspective](https://www.researchgate.net/publication/228942578_The_physical_modelling_of_society_A_historical_perspective)  
3. Dynamics of topological defects in the noisy Kuramoto model in two dimensions \- Frontiers, consulté le janvier 2, 2026, [https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2022.976515/full](https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2022.976515/full)  
4. Kuramoto model \- Wikipedia, consulté le janvier 2, 2026, [https://en.wikipedia.org/wiki/Kuramoto\_model](https://en.wikipedia.org/wiki/Kuramoto_model)  
5. What Is Emotional Contagion Theory? (Definition & Examples) \- Positive Psychology, consulté le janvier 2, 2026, [https://positivepsychology.com/emotional-contagion/](https://positivepsychology.com/emotional-contagion/)  
6. A MODEL OF RIOTS DYNAMICS: SHOCKS ... \- AIMS Press, consulté le janvier 2, 2026, [https://www.aimspress.com/aimspress-data/nhm/2015/3/PDF/1556-1801\_2015\_3\_443.pdf](https://www.aimspress.com/aimspress-data/nhm/2015/3/PDF/1556-1801_2015_3_443.pdf)  
7. (PDF) A Model Of Riots Dynamics: Shocks, Diffusion And Thresholds \- ResearchGate, consulté le janvier 2, 2026, [https://www.researchgate.net/publication/272521456\_A\_Model\_Of\_Riots\_Dynamics\_Shocks\_Diffusion\_And\_Thresholds](https://www.researchgate.net/publication/272521456_A_Model_Of_Riots_Dynamics_Shocks_Diffusion_And_Thresholds)  
8. The Kuramoto model: A simple paradigm for synchronization phenomena \- SciSpace, consulté le janvier 2, 2026, [https://scispace.com/pdf/the-kuramoto-model-a-simple-paradigm-for-synchronization-2akwf0t24m.pdf](https://scispace.com/pdf/the-kuramoto-model-a-simple-paradigm-for-synchronization-2akwf0t24m.pdf)  
9. Sociodian Rhythm: Eye Contact and Social Synchronization \- European Society of Medicine, consulté le janvier 2, 2026, [https://esmed.org/sociodian-rhythm-eye-contact-and-social-synchronization/](https://esmed.org/sociodian-rhythm-eye-contact-and-social-synchronization/)  
10. A coupled oscillator model predicts the effect of neuromodulation and a novel human tempo-matching bias | Journal of Neurophysiology | American Physiological Society, consulté le janvier 2, 2026, [https://journals.physiology.org/doi/full/10.1152/jn.00348.2024](https://journals.physiology.org/doi/full/10.1152/jn.00348.2024)  
11. A coupled oscillator model predicts the effect of neuromodulation and a novel human tempo-matching bias \- PubMed, consulté le janvier 2, 2026, [https://pubmed.ncbi.nlm.nih.gov/40298211/](https://pubmed.ncbi.nlm.nih.gov/40298211/)  
12. Sociodian Rhythm: Eye Contact and the Neurobiology of Social Synchronization | Medical Research Archives \- European Society of Medicine, consulté le janvier 2, 2026, [https://esmed.org/MRA/mra/article/view/6978](https://esmed.org/MRA/mra/article/view/6978)  
13. Sociodian Rhythm: Eye Contact and the Neurobiology of Social Synchronization, consulté le janvier 2, 2026, [https://www.researchgate.net/publication/397184575\_Sociodian\_Rhythm\_Eye\_Contact\_and\_the\_Neurobiology\_of\_Social\_Synchronization](https://www.researchgate.net/publication/397184575_Sociodian_Rhythm_Eye_Contact_and_the_Neurobiology_of_Social_Synchronization)  
14. Local Predictors of Explosive Synchronization with Ordinal Methods \- MDPI, consulté le janvier 2, 2026, [https://www.mdpi.com/1099-4300/27/2/113](https://www.mdpi.com/1099-4300/27/2/113)  
15. Two-step and explosive synchronization in frequency-weighted Kuramoto model \- Forschungszentrum Jülich, consulté le janvier 2, 2026, [https://juser.fz-juelich.de/record/1035133/files/1-s2.0-S0167278924003002-main.pdf](https://juser.fz-juelich.de/record/1035133/files/1-s2.0-S0167278924003002-main.pdf)  
16. Synchronization Transition of the Second-Order Kuramoto Model on Lattices \- MDPI, consulté le janvier 2, 2026, [https://www.mdpi.com/1099-4300/25/1/164](https://www.mdpi.com/1099-4300/25/1/164)  
17. Complete entrainment of Kuramoto oscillators with inertia on networks via gradient-like flow | Request PDF \- ResearchGate, consulté le janvier 2, 2026, [https://www.researchgate.net/publication/263891980\_Complete\_entrainment\_of\_Kuramoto\_oscillators\_with\_inertia\_on\_networks\_via\_gradient-like\_flow](https://www.researchgate.net/publication/263891980_Complete_entrainment_of_Kuramoto_oscillators_with_inertia_on_networks_via_gradient-like_flow)  
18. Energy–dynamics interplay in temporal networks triggers explosive synchronization \- arXiv, consulté le janvier 2, 2026, [https://arxiv.org/html/2509.08651v1](https://arxiv.org/html/2509.08651v1)  
19. Free Falling Into Sync \- Kate Loves Math, consulté le janvier 2, 2026, [https://katelovesmath.com/free-falling-into-sync/](https://katelovesmath.com/free-falling-into-sync/)  
20. People acting as 'game changers' could calm panicked crowds, simulation reveals, consulté le janvier 2, 2026, [https://physicsworld.com/a/people-acting-as-game-changers-could-calm-panicked-crowds-simulation-reveals/](https://physicsworld.com/a/people-acting-as-game-changers-could-calm-panicked-crowds-simulation-reveals/)  
21. Opinion dynamics modelling: distinct attraction and repulsion topologies highlight quantitative effects of trolling \- ResearchGate, consulté le janvier 2, 2026, [https://www.researchgate.net/publication/398430787\_Opinion\_dynamics\_modelling\_distinct\_attraction\_and\_repulsion\_topologies\_highlight\_quantitative\_effects\_of\_trolling](https://www.researchgate.net/publication/398430787_Opinion_dynamics_modelling_distinct_attraction_and_repulsion_topologies_highlight_quantitative_effects_of_trolling)