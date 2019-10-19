<img src="https://github.com/DeepCure-UMB-Project-f19/ML_Model/blob/master/CyanideIon.png" width="200" height="156" /> 

### <b>Toxicity Modeling</b>

A Machine Learning Model for Predicting Small Molecule Toxicity Properties in Humans.

#### Motivation

The mission of DeepCure is to apply AI and machine learning models to determine novel drug candidates from a vast search space of more than 100 billion possible small molecules. Machine learning techniques represent the possibility of dramatic reductions in the time and costs involved in drug discovery over conventional discovery methods. DeepCure&#39;s technology helps identify novel optimization steps that would escape the eyes of even the most experienced medicinal chemist.



#### Goal

The objective of this project is to develop a new machine learning software model for predicting human toxicity in small-molecule datasets. This model will be used by scientists and research personnel at DeepCure to reduce the size of the molecule search space for new drug candidates, and aid in further model development.



#### Milestones

* <b>Narrow Problem Scope</b> 

	Decide which endpoints and pathways should be considered and determine specifically what aspect of toxicity in humans the model will predict for. Given this endpoint, it will then be possible to consider expanding the scope of the model to find wider patterns in the toxicity data.


* <b>Data Acquisition and Curation</b>

	Find and research sources of data which are relevant to our definition of toxicity in humans. Research and determine which properties of molecules are relevant in the prediction of our classification of toxicity. Select optimal software packages for handling data of this type, and for interfacing them with the Python machine learning libraries we will be using. Perform preprocessing techniques to prepare data for model training.

* <b>Modality Analysis</b>

	Research various types of machine learning methods and algorithms. Considering our endpoints, determine which types show promise. Research options and aspects of candidate model(s). Compare potential options and define class of candidate model types, taking into account implementation requirements.

* <b>Feature Engineering and Data Pre-processing</b>

	Curate feature space to increase predictive power of model. This includes identifying and eliminating redundant or extraneous features, using existing data to generate new potentially relevant features, and developing strategies to optimize the features&#39; representations in the model. Preprocess training datasets based on feature engineering outcomes. Feature engineering will be continuous through iterative refinement of model.

* <b>Model Development</b>

	Research existing approaches to the model type selected. Determine how one or more of these approaches can be best be applied to a model for predicting small molecule toxicity in humans specific to our defined endpoint(s). Research options for hyperparameter optimization and model training. Construct the model in Python leveraging the selected machine learning libraries.

* <b>Training and Iterative Refinement</b>

	Develop an accurate and generalizable model by iteratively:
    * Training the model using the training set
    * Validating the model against the validation set, measuring for accuracy and generalizability
    * Comparing results against previous results and existing benchmarks
    * Considering alternative algorithms or
    * Optimizing hyperparameters and features<br> 	  



* <b>Final Testing</b>

	Once the model is finalized, test it against the final test dataset to evaluate its performance.

* <b>Conclusion</b>

	Develop a complete report and presentation on the model, its design and implementation, test, training, and potential inference datasets, and our results with respect to benchmarks. The report will document what has been learned from the project, as well as possibilities for expanding the model&#39;s scope, and future problems that can be addressed using the model.

#### Deliverables

- Prepared and curated training dataset
- Initial model/concept including feature concepts and preprocessed training data
- Report of Iterative improvements on model
- Final Model including preprocessed training dataset and test dataset
- Final Report and Presentation, including test data outcomes and current benchmarks


#### Out of Scope

- Predictions of small molecule toxicity across pathways aggregate
- Interface for automation of model deployment
- Preprocessed datasets used in iterative refinement
- Reports on research of methods that did not result in model and optimization algorithm choices used in iterative refinement
- Inference datasets
