# AI Projects for Government Pharmaceutical Organization (GPO)

This project showcases two AI-driven solutions developed for the Government Pharmaceutical Organization (GPO) of Thailand, using KNIME Analytics Platform. The solutions aim to improve customer understanding and reverse formulation prediction from pharmaceutical sales and production data.

🔍 1. Customer Segmentation from Drug Sales Data

Objective:
To segment customers based on historical drug sales data in order to support targeted marketing, inventory planning, and distribution strategies.

Approach:

	• Utilized KNIME for data preprocessing, clustering, and visualization.
	• Applied unsupervised learning techniques like K-mean clustering.
  	• Use RFM model to extract feature from data.
	• Generated customer profiles based on purchasing patterns, volume, frequency, and product types.

🔁 2. Reverse Engineering Formulas from Output to Inputs

Objective:
To predict the required input raw material combinations (X1, X2, …, Xn) based on desired output product characteristics (Y1, Y2, …, Yn).

Approach:

	•	Built a KNIME workflow to model the reverse mapping from output to input.
	•	Applied regression and optimization techniques to solve the inverse problem.
	•	Enabled more efficient formulation design and reduced trial-and-error cycles in R&D.

🛠️ Tools & Technologies

	•	KNIME Analytics Platform
	•	Clustering Algorithms (e.g., K-Means, DBSCAN)
	•	Regression Models (e.g., Linear Regression, Decision Trees)
	•	Data visualization and workflow automation in KNIME
