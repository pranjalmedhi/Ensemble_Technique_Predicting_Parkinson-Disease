# Ensemble_Technique_Predicting_Parkinson-Disease
### Data Description &amp; Context:  
 Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.  Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician  
### Objective:
 Objective behind leveraging Machine Learning Algorithm for predicting Parkinson Disease in subjects: PD patients exhibit characteristic vocal features and voice recordings are a useful and non-invasive tool for diagnosis. So this case study aims at identifying if Machine learning algorithms can be applied to a voice recording dataset to accurately diagnosis PD; if this is successful then this would be an effective screening step prior to an appointment with a clinician;  
### Domain: Medicine
### Attribute Information:
- name -ASCII subject name and recording number
- MDVP:Fo(Hz) -Average vocal fundamental frequency
- MDVP:Fhi(Hz) -Maximum vocal fundamental frequency
- MDVP:Flo(Hz) -Minimum vocal fundamental frequency
- MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP -Several measures of variation in fundamental frequency
- MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA -Several measures of variation in amplitude
- NHR,HNR -Two measures of ratio of noise to tonal components in the voice
- status -Health status of the subject (one) -Parkinson's, (zero) -healthy
- RPDE,D2 -Two nonlinear dynamical complexity measuresDFA -Signal fractal scaling exponents
- spread1,spread2,PPE -Three nonlinear measures of fundamental frequency variation 


### More about the attributes
- MDVP: Fo (Hz) Average vocal fundamental
- MDVP: Fhi (Hz) Maximum vocal fundamental frequency
- MDVP: Flo (Hz) Minimum vocal fundamental frequency
- MDVP: Jitter (%) Kay Pentax MDVP jitter as percentage
- MDVP: Jitter (Abs) Kay Pentax MDVP absolute jitter in microseconds
- MDVP: RAP Kay Pentax MDVP relative amplitude perturbation
- MDVP: PPQ Kay Pentax MDVP five-point period perturbation quotient
- Jitter: DDP Average absolute difference of differences between cycles, divided by the average period
- MDVP: Shimmer Key Pentax MDVP local shimmer
- MDVP: Shimmer (dB) Key Pentax MDVP local shimmer in decibels
- Shimmer: APQ3 3 point amplitude perturbation quotient
- Shimmer: APQ5 5 point amplitude perturbation quotient
- MDVP: APQ Kay Pentax MDVP eleven-point amplitude perturbation quotient
- Shimmer: DDA Average absolute difference between consecutive differences between the amplitude of consecutive periods
- NHR Noise to harmonic ratio
- HNR Harmonics to noise ratio
- RPDE Recurrence period density entropy
- DFA Detrended fluctuation analysis
- spread1 Nonlinear measure of fundamental frequency
- spread2 Nonlinear measure of fundamental frequency
- D2 Pitch period entropy
- PPE Pitch


### Tasks:
- Training at least 3 standard classification algorithms -Logistic Regression, Naive Bayes’, SVM, k-NN etc, and noting down their accuracies on the test data 
- Training a meta-classifier and note the accuracy on test data 
- Training at least one standard Ensemble model -Random forest, Bagging, Boosting etc, and noting down the accuracy
- Comparing all the models and picking the best one among them.
