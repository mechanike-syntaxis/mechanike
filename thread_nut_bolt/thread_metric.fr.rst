Filetage métrique ISO
=====================

Présentation
------------

C'est le profil le plus couramment utilisé pour les pièces filetées. La désignation se fait avec la lettre **M** suivi par le diamètre *d* et du pas *P* séparés par un signe de mutlipcation. Si la tolérance est différante de **6H** pour le taraudage et de **6g** pour la vis, il est nécessaire de la préciser en fin de désignation.

Exemple pour une vis: **M10 x 1,5 - 6g**

Exemple pour un taraudage: **M10 x 1,5 - 6H**


Plan
----

.. image:: /thread_nut_bolt/image/thread_metric.png

Définition:

- *D*, *D1*, *D2* : diamètres de l'écrou 
- *d*, *d1*, *d2*, *d3* : diamètres de la vis
- *D*, *d* : diamètre nominal
- *P* : pas du profil

Calculs:

- *R1* = 0,1443 × *P*
- *R2* ≤ 0,0721 × *P*
- *H* = 0,866 × *P*
- *D1* = *d1* = *d* - 1,0825 × *P*
- *D2* = *d2* = *d* - 0,6495 × *P*
- *d3* = *d* - 1,2268 × *P*

Filetage couramments utilisé 
----------------------------

Tableau des dimensions de filetages couramments utilisés avec une tolérance 6H/6g. Il est conseillé d'utiliser les filetages listés dans ce tableau.

.. include:: /thread_nut_bolt/table/thread_metric.rst.inc

Totalité des filetages
----------------------

Tableau complet avec un tolérance 6H/6g

.. include:: /thread_nut_bolt/table/full_thread_metric.rst.inc

