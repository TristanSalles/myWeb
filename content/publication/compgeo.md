+++
abstract = "In this paper, we propose a minimal numerical model which governing equations describe the following processes: erosion, sedimentation, diffusion and flexure. The model respects conservation laws for water and sediment. The implementation is based on a finite volume approach and the explicit solution stability is ensured by a CFL-like condition. This common core of accepted physical principles governing landscape evolution is ported into a distributed memory parallel environment. Badlands (acronym for BAsin anD LANdscape DynamicS) is an open-source, flexible, TIN-based landscape evolution model, built to simulate landform development and test source-to-sink concepts at regional to continental scale over thousands to millions of years. To illustrate the model capabilities, we first present an example of delta evolution under sea-level fluctuations. The model predicts the successive progradation and transgression phases, the development of depositional and erosional patterns as well as the associated stratigraphic formation. Then, we investigate the importance of climate, and in particular the spatial pattern of precipitation, on the topographic evolution of mountain belts. The simulation and associated quantitative analyses suggest that the main drainage divide migrates and asymmetric topography develops in response to orographic precipitation. This mechanism, documented in recent analogue and numerical experiments, results in a complex reorganisation of drainage networks that our model is able to reproduce."

abstract_short = "In this paper we present a landscape evolution model able to simulate erosion, deposition, diffusion and flexure. The code is parallelised based on a sub-catchment partitioning approach. Models of delta stratigraphic evolution under sea-level fluctuations as well as mountain belts topographic evolution with climatic changes showcase the capabilities of the code. "
authors = ["T Salles", "L. Hardiman"]
date = "2016-03-17"
image_preview = "cgeo.jpg"
math = true
publication_types = ["2"]
publication = "Computers & Geosciences"
publication_short = "In Computers & Geosciences"
selected = true
title = "Badlands: An open-source, flexible and parallel framework to study landscape dynamics"
url_code = "https://github.com/badlands-model/pyBadlands"
url_dataset = "https://github.com/badlands-model/pyBadlands-Companion"
url_pdf = "http://www.sciencedirect.com/science/article/pii/S0098300416300851"
url_project = "project/deep-learning/"
url_slides = "https://prezi.com/5y1usorz8e8k/badlands-overview/?utm_campaign=share&utm_medium=copy"
url_video = "https://www.youtube.com/channel/UC3mu0qg-m0gUdbNWQxzuQnw"

[[url_custom]]
name = "RG"
url = "https://www.researchgate.net/publication/299111625_Badlands_An_open-source_flexible_and_parallel_framework_to_study_landscape_dynamics?_iepl%5BviewId%5D=FZf0fmOGk4aVY8efu9HOhncu&_iepl%5BprofilePublicationItemVariant%5D=default&_iepl%5Bcontexts%5D%5B0%5D=prfpi&_iepl%5BinteractionType%5D=publicationTitle"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/compgeo.jpg"
caption = "Badlands landscape evolution model overview."

+++
