# Segmentation-des-l-sions-tumorales
e suis fier(e) de présenter notre projet primé intitulé «segmentation de lésions tumorales à partir des images IRM », qui a remporté le premier prix « Hannibal » pour le meilleur projet lors du challenge Intelligence Artificielle en médecine organisé lors de la conférence TAIMA2022. Notre équipe, composée de Fatma Jeddi, Amal Araoud, Sirine Haraketi, Arwa Habachi et Imen Smaati, a suivi deux formations, en IA en médecine et en Machine-Learning, et a été encadrée par M. Richard Noel et Nodin Mathieu de l'université de Poitiers, France.

Notre projet vise à automatiser la segmentation des tumeurs cérébrales, une anomalie des tissus cérébraux qui peut causer des dommages graves au système nerveux et, dans des cas extrêmes, entraîner la mort. Le diagnostic et la planification du traitement de cette anomalie sont coûteux, prennent du temps et peuvent être inexacts en raison d'erreurs humaines. Nous avons donc proposé une méthode automatisée de segmentation des tumeurs cérébrales à l'aide de réseaux de neurones à convolution profonde, en utilisant l'ensemble de données BRATS 2021, qui contient 2000 cas.

Notre méthode a suivi la structure du réseau U-net avec un encodeur-décodeur, et les données d'entrée étaient des images multimodales prétraitées, telles que l'IRM pondérée en T1 (T1), l'IRM pondérée en T1 avec amélioration du contraste (T1c), etc., contenant plus d'informations sur les tumeurs de forme irrégulière, difficiles à localiser avec une seule modalité. Nous avons utilisé un encodeur asymétriquement grand pour extraire les caractéristiques profondes de l'image, et la partie décodeur a reconstruit des masques de segmentation denses pour reconstruire les images d'entrée. Les résultats de segmentation et de prédiction des classes d'une tumeur ont été évalués en se basant sur quatre mesures : la perte (avec le coefficient de similarité de Dice (DSC)), la précision, la sensibilité et la spécificité.

Notre projet a permis de disposer d'une solution représentée par deux tâches : la première est la segmentation de la tumeur entière, et la deuxième tâche est la segmentation de cette lésion en sous-parties (œdème, nécrose, partie active). Nous sommes convaincus que notre méthode contribuera à améliorer le diagnostic et la planification du traitement de cette anomalie, en offrant une solution rapide, précise et moins coûteuse.





