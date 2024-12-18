Rainfall detection in environmental recordings has become a critical preprocessing step for eco-acoustic analyses. Acoustic interference caused by rainfall often biases acoustic indices, leading researchers to exclude rain-contaminated recordings. This exclusion can significantly limit the data available for biodiversity assessments (Metcalf et al., 2020). Furthermore, rainfall impacts species behavior, and analyzing rainfall patterns in bioacoustic data can provide valuable insights into ecological dynamics (Brown et al., 2018).

Currently, automated tools like hardRain (Metcalf et al., 2020) offer threshold-based methods for rain detection in ecoacoustic datasets. However, these methods may lack robustness under diverse acoustic conditions and require manual tuning of thresholds using separate training and test datasets. To address these limitations, this project proposes a novel supervised deep learning (DL) approach for rainfall detection. Our method aims to:
Provide accurate classification of rain in environmental audio recordings.
Extract specific segments of recordings containing rainfall.
Classify recordings into no-rain, light-rain, and heavy-rain categories.

The downstream implications of automated rainfall detection extend to multiple areas, including:
Enhanced Biodiversity Monitoring (Napier et al., 2024)
Improved Landscape Health Assessment (Nieto-Mora et al., 2023)
Data for Climate and Environmental Change (Pijanowski et al., 2011)
Applications in Conservation Strategies: e.g., predicting species breeding patterns or assessing habitat quality.
Our contribution lies in leveraging advanced DL methods to improve rainfall detection accuracy, enabling domain experts to process environmental datasets more efficiently.

The code is inspired by https://github.com/charanya78/fall_detection_audios/tree/main
Other code is available in Google Colab
amplititude: https://colab.research.google.com/drive/1XDaQyPSsUriSf82rm0R68BHCWapXy31W#scrollTo=plxGTPsRvl_l 
