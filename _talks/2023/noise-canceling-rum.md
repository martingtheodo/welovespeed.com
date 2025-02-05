---
display-order: 1
locale: en_US
length: 45
pub_date: "2023-03-15"
speakers:
  - tim_vereecke
fr_FR:
  title: "Réduire le bruit du RUM"
  subtitle: ~
  excerpt: >-
    Les données RUM peuvent être bruyants. Les Navigations Humaines Visibles (HVN) sont un nouveau concept qui s'attaque à ce risque !
  description: >-
    Le bruit parasite du Real User Monitoring (RUM) peut gâcher votre journée !

    Nous introduisons un nouveau concept appelé "Navigations Humaines Visibles" (NVH) pour faire face à ce risque ; nous nous concentrons sur les expériences qui vous intéressent réellement lorsque vous parlez de la vitesse de nos sites :

    - Navigations : Nous ne tenons pas compte des navigations avant-arrière très rapides, qui offrent généralement peu de possibilités d'optimisation.

    - Humaines : nous excluons le bruit provenant des robots et des mesures synthétiques.

    - Visibles : Nous supprimons toute expérience partielle ou totalement cachée. Celles-ci ont tendance à être très lentes, mais les utilisateurs ne perçoivent pas cette lenteur.


    L'adoption de navigations visibles par des personnes vous offre les avantages suivants :

    - moins de changements qui restent sous le radar ;

    - moins de fluctuations de données ;

    - moins d'angles morts lors de l'identification des goulets d'étranglement ;

    - une meilleure corrélation avec les KPIs métier.


    Cette approche est étayée par de nombreux exemples concrets provenant du plus grand site de modélisation au monde (6 millions de visites par mois), combinés à des données agrégées provenant du tout nouveau site rumarchive.com. 

    > Jusqu'à 22 % des données de RUM peuvent être considérées comme du bruit.


    > Des données erronées provenant d'un scraper ont entraîné le rollback d'une livraison à tort.


    > Avec NHV, le taux de rebond réel a diminué de 4 points.


    > Le bruit fausse de 14 % mon vrai TTFB.
  slides: ~
  video: ~
en_US:
  title: "Noise Canceling RUM"
  subtitle: ~
  excerpt: >-
    RUM data can be noisy. Human Visible Navigations (HVN) is a new concept to tackle this risk!
  description: >-
    Noisy Real User Monitoring (RUM) data can ruin your day!

    We introduce a fresh concept called "Human Visible Navigations" (HVN) to tackle this risk; we focus on the experiences you actually care about when talking about the speed of our sites:

    - Human: We exclude noise coming from bots and synthetic measurements.

    - Visible: We remove any partial or fully hidden experiences. These tend to be very slow but users don’t see this slowness.

    - Navigations: We ignore lightning fast back-forward navigations which usually have few optimisation opportunities.


    Adopting Human Visible Navigations provides you with these key benefits:

    - Fewer changes staying below the radar

    - Fewer data fluctuations

    - Fewer blindspots when finding bottlenecks

    - Better correlation with business metrics


    This is supported by plenty of real world examples coming from the world's largest scale modeling site (6M Monthly visits) in combination with aggregated data from the brand new rumarchive.com 

    > Up to 22% of RUM data can be considered noise.


    > Bad data from a scraper caused a release to be wrongfully rolled back.


    > With HVN, Real Bounce Rate decreased by 4 percentage points.


    > Noise skews my actual Time To First Byte by 14%.
  slides: ~
  video: ~
---
