# maternal-fetal-health-assistant

ChatGPT-based Virtual Assistant for Maternal and Fetal Health Monitoring

## Mission

- ChatGPT can act as a virtual assistant, providing pregnant women with information about fetal development, pregnancy risks, symptoms, and what to expect during prenatal visits.
- By leveraging data from wearables or patient-reported symptoms, ChatGPT can assist in triaging symptoms like contractions, bleeding, or changes in fetal movement, and recommend when immediate medical attention is required.
- ChatGPT can automate the generation of patient summaries, reports, and clinical notes during and after patient interactions, reducing the administrative burden on healthcare providers.
- In advance, ChatGPT can be integrated into decision-support systems to assist clinicians in evaluating maternal and fetal health risks by analyzing complex datasets from clinical records, past pregnancies, or real-time monitoring systems.

## DataSet

Dataset are prepared and formatted for training and fine-tuning ChatGPT:
- Dataset of the projects was collected from UCI and Kaggle, which include information about maternal health base on IoT, and fetal health of Cardiotocograms.
- The Fetal Health Classification Dataset and UCI CTG Dataset for actual medical data that contains fetal heart rate, uterine contractions, and health indicators.
- Maternal Health Risk Data for additional inputs like blood pressure, glucose, and maternal health risk factors that may affect fetal well-being. 

Dataset List Information and Sources:
- Cardiotocography (Donated on 9/6/2010): The dataset consists of measurements of fetal heart rate (FHR) and uterine contraction (UC) features on cardiotocograms classified by expert obstetricians. Source: https://archive.ics.uci.edu/dataset/193/cardiotocography
- Maternal Health Risk (Donated on 8/14/2023): Data has been collected from different hospitals, community clinics, maternal health cares from the rural areas of Bangladesh through the IoT based risk monitoring system. Source: https://archive.ics.uci.edu/dataset/863/maternal+health+risk
- Fetal Health: Cardiotocograms (CTGs) are a simple and cost accessible option to assess fetal health, allowing healthcare professionals to take action in order to prevent child and maternal mortality. The equipment itself works by sending ultrasound pulses and reading its response, thus shedding light on fetal heart rate (FHR), fetal movements, uterine contractions and more.. Soruce: https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification