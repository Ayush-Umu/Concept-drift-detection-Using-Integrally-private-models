# Concept Drift Detection using Ensemble of Integrally Private Models

Repository for the paper "Concept Drift Detection using Ensemble of Integrally Private Models" awaiting proceedings in MLCS co-located with ECML-PKDD 2023. DOI: 

Datasets used 
<img width="800" alt="Screenshot 2024-06-07 at 14 00 05" src="https://github.com/Ayush-Umu/Concept-drift-detection-Using-Integrally-private-models/assets/96262717/7e9237d1-2ef0-451d-9298-2c97a9e49885">

Flowchart of the proposed approach:
<img width="800" alt="Screenshot 2024-06-07 at 14 02 33" src="https://github.com/Ayush-Umu/Concept-drift-detection-Using-Integrally-private-models/assets/96262717/edec1fe5-2bb6-46dd-80d8-967b878cc8a8">

Our approach detects drifts from an ensemble of private models. Our approach does not need true labels to detect drifts. We consider uncertainty in prediction as a proxy for concept drift detection. 

We show that our approach returns superior results to its differentially private counter part:
<img width="900" alt="Screenshot 2024-06-07 at 14 01 51" src="https://github.com/Ayush-Umu/Concept-drift-detection-Using-Integrally-private-models/assets/96262717/a8657594-27c6-4c1b-8f60-2b3a5a970050">

With the addition of noise in DP models, the models may struggle to detect drifts.

<img width="300" alt="Screenshot 2024-06-07 at 14 00 53" src="https://github.com/Ayush-Umu/Concept-drift-detection-Using-Integrally-private-models/assets/96262717/4cae8720-f086-4fbc-bbe3-4305c33a2ec3">


Files:

Generate Synthetic Sine classification: generates synthetic sine data.
Insects files: artificial drifts introduced in the Insect dataset.

The rest of the files show the result for their respective datasets. In case of any queries please contact: ayushkv@cs.umu.se
