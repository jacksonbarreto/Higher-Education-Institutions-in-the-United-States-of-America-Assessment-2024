# Higher-Education-Institutions-in-the-United-States-of-America-Assessment-2024

This repository contains a dataset of higher education institutions in the United States of America. This dataset was compiled in response to a cybersecurity research of American higher education institutions' websites [1]. The data is being made publicly available to promote open science principles [2]. The data was collected on November 3, 2024.

## Methodology

The database for this research was extracted from the following repository [3]. To analyze this data, a security scanner was used to analyze a set of parameters, namely dnssec, https, axfr and security headers, sharing the results with each institution regarding whether or not each parameter was correct. 

The data obtained was sent to a list of each school informing them of the existence or correct implementation of each checker. This data was then passed to an analyzer [4], which aggregated it to give us a dimension of the implementation of these security requirements in educational institutions in the United States by each state.

The result of this parser generated the files that are at the root of this project.

## Usage

This data is available under the Creative Commons Zero (CC0) license and can be used for any purpose, including academic research purposes. We encourage the sharing of knowledge and the advancement of research in this field by adhering to open science principles [2].

If you use this data in your research, please cite the source and include a link to this repository. To properly attribute this data, please use the following DOI:

## Contribution

If you have any updates or corrections to the data, please feel free to open a pull request or contact us directly. Let's work together to keep this data accurate and up-to-date.

## Acknowledgment

We would like to acknowledge the support of the Norte Portugal Regional Operational Programme (NORTE 2020), under the PORTUGAL 2020 Partnership Agreement, through the European Regional Development Fund (ERDF), within the project "Cybers SeC IP" (NORTE-01-0145-FEDER-000044). This study was also developed as part of the Master in Cybersecurity Program at the Instituto Politécnico de Viana do Castelo, Portugal.

## References

1. Pending.
2. S. Bezjak, A. Clyburne-Sherin, P. Conzett, P. Fernandes, E. Görögh, K. Helbig, B. Kramer, I. Labastida, K. Niemeyer, F. Psomopoulos, T. Ross-Hellauer, R. Schneider, J. Tennant, E. Verbakel, H. Brinken, and L. Heller, Open Science Training Handbook. Zenodo, Apr. 2018. [Online]. Available: [https://doi.org/10.5281/zenodo.1212496]
3. Higher-Education-Institutions-in-the-United-States-of-America-Dataset. Available: [https://github.com/jacksonbarreto/Higher-Education-Institutions-in-the-United-States-of-America-Dataset/blob/main/heis_usa.csv]
4. WebSecureScout-Analyzer. Available: [https://github.com/jacksonbarreto/WebSecureScout-Analyzer]
