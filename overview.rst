.. _overview:

Aperçu
======

Fonctionnement général
----------------------

L'application Keyclic est librement ouverte aux inscriptions. Une fois inscrit, tout utilisateur peut créer des observations. Une observation est toujours liée à une position géographique et comporte éventuellement une ou plusieurs photos.

Certains utilisateurs peuvent également être regroupés au sein d'organisations. Une organisation est donc un groupe d'utilisateurs membres de la même entreprise, association, corporation, école, etc. Tout utilisateur est libre de créer sa propre organisation et d'inviter d'autres utilisateurs à en devenir membres.

Les administrateurs d'organisation définissent des zones de responsabilité sur lesquelles leur organisation peut intervenir, et des catégories d'intervention (exemples : voirie, animal perdu, propreté, etc...) Ainsi, quand un utilisateur crée une observation, la position géographique de cette observation permet de lui proposer les catégories et organisations qui sont en mesure de traiter son signalement et de le laisser choisir celle qui lui semble la plus adaptée.

Quand un utilisateur crée une observation, celle-ci doit tout d'abord être validée par un administrateur de l'application, sauf dans certains cas où la validation est automatique (voir : :ref:`feedbacks-lifecyle`). Une fois validée, cette observation est visible par la communauté : ainsi, les autres utilisateurs peuvent la commenter et/ou la soutenir. De plus, au moment où l'observation est validée, un rapport est généré et transmis à l'organisation concernée. 

Un administrateur d'organisation a donc accès à l'ensemble des rapports concernant son organisation, chaque rapport correspondant à une observation. Pour chaque rapport, il peut créer une ou plusieurs opérations, et affecter ces opérations aux utilisateurs membres de son organisation. Une fois que toutes les opérations ont été accomplies, il pourra considérer que le traitement est terminé et clôturer le rapport. Une autre possibilité est de déléguer ce rapport à une organisation partenaire.

Vocabulaire
-----------

Observation
~~~~~~~~~~~

Remarque effectuée sur le terrain par un utilisateur, pouvant porter sur un dysfonctionnement, un problème technique, une nuisance, etc. Toute observation est forcément faite en une position géographique donnée. Elle peut éventuellement comporter des photos, et être commentée et/ou soutenue par les autres utilisateurs.

Terme technique : feedback.

Voir la page :ref:`feedbacks`.

Rapport
~~~~~~~

Toute observation, une fois validée par un administrateur de l'application, entraîne la génération d'un rapport. Un rapport reprend donc toutes les informations de l'observation dont il est issu, et n'est visible et manipulable que par l'organisation concernée. Le rapport peut donc être vu comme le pendant « professionnel » de l'observation. C'est sur ce rapport que l'organisation travaille : création d'opérations, suivi, délégation, etc.

Terme technique : report.

Voir la page :ref:`reports`

Organisation
~~~~~~~~~~~~

Groupe d'utilisateurs pouvant être une entreprise, une école, une association, etc.

Terme technique : organization.

Voir la page :ref:`organizations`.

Zone de responsabilité
~~~~~~~~~~~~~~~~~~~~~~

Aire géographique sur laquelle une organisation peut intervenir.

Terme technique : place.

Voir la section :ref:`organizations-places`.

Catégorie
~~~~~~~~~

Secteur d'activité d'une organisation.

Terme technique : category.

Voir la section :ref:`organizations-categories`.

Application
~~~~~~~~~~~

Un client de l'API travaille toujours sur une application particulière de Keyclic, correspondant à un domaine applicatif. Chaque application possède ses propres administrateurs, dont la principale mission est de modérer les observations avant que celles-ci ne soient transmises sous forme de rapport aux organisations concernées.

Soutien
~~~~~~~

Une observation peut être soutenue par les utilisateurs de la communauté, afin de leur donner plus de poids.

Terme technique : contribution.

Voir la section :ref:`feedbacks-contributions`.

Opération
~~~~~~~~~

Une opération est une tâche créée par un administrateur d'organisation sur un rapport donné. Cette tâche est assignée à un membre de l'organisation. Un rapport ne peut être clôturé que si toutes les opérations qui lui sont liées ont été accomplies.

Terme technique : operation.

Voir la section :ref:`reports-operations`.

Partenaires
~~~~~~~~~~~

Un administrateur d'organisation peut définir des organisations partenaires, qui sont d'autres organisations auxquelles il pourra déléguer des rapports.

Terme technique : relationship.

Voir la section :ref:`organizations-relationships`.

