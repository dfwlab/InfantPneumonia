# Assessing Severe Pneumonia Risk in Children via Clinical Prognostic Model Based on Laboratory Markers

### Background
Pneumonia remains the leading cause of death in children, and identification and managing high-risk patients are necessary to reduce mortality in children with severe pneumonia. Existing laboratory markers for clinical decision support in childhood pneumonia cannot reliably assess disease severity and lack reliable risk grading models.

### Methods
Demographic information and laboratory parameters of 749 children aged under 3 years with severe pneumonia were extracted from the Paediatric Intensive Care database at the Children’s Hospital of Zhejiang University. The relationship between laboratory parameters and prognostic outcomes was assessed using univariate and multivariate Cox proportional hazards regression. By leveraging laboratory markers, the XGBoost classifier was used to build the pneumonia prognosis prediction model, which was then validated in the hold-out test cohort. Model performance was evaluated by the area under the receiver operating characteristic curve (AUC).

### Results
Among the 87 features, we identified five laboratory markers (i.e., oxygen saturation, hemoglobin, lipase, urea, and uric acid) associated with childhood severe pneumonia outcomes. We developed a risk model based on the five laboratory markers, which was able to effectively distinguish between dead and cured patients (AUC = 0.943), and high- and low-risk children for pneumonia death (hazard ratio [HR] = 4202, 95% confidence interval [CI]: 1431-12337, P < 0.001). The robust performance of this model was further validated in a test cohort (AUC = 0.871; HR = 130.4, 95% CI: 17.35-979.9, P < 0.001). 

### Conclusion
We developed a novel machine learning model to predict the individualized mortality risk in children with severe pneumonia by using five clinical laboratory markers. The model provides personalized risk assessments of pneumonia prognosis to assist clinical decision-making, might aid in improving the overall survival and prognosis of childhood severe pneumonia.

![图片](https://user-images.githubusercontent.com/15136517/217182352-83e1f3bc-946a-434b-a20b-cde436f9686e.png)
