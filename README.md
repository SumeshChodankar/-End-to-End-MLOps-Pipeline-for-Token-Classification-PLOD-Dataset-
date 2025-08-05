# End-to-End-MLOps-Pipeline-for-Token-Classification-PLOD-Dataset-
 End-to-End MLOps Pipeline for Token Classification(PLOD Dataset)

End-to-End Deep Learning Pipeline for Scene Recognition
End-to-End Deep Learning Pipeline for Scene Recognition
University of Surrey logo
Associated with University of Surrey
Associated with University of Surrey

Description:
Designed and implemented an end-to-end MLOps pipeline for a deep learning-based NLP sequence classifier. This project focused on building a production-ready system that not only provided accurate predictions but was also rigorously tested, monitored, and set up for continuous integration and deployment.

Key Contributions:
Model Engineering: Deployed a 300MB bert-base-uncased model for token classification, leveraging Hugging Face APIs for model building and deployment.

Deployment Strategy: Chose Hugging Face Spaces as the deployment platform after a detailed comparison, prioritizing its cost-effective free tier, ease of model updating, and high coordination ease for teamwork.

Testing & Validation: Conducted comprehensive functional and performance testing. Used 
Locust to perform stretch testing, successfully simulating varying request loads and identifying the service's performance characteristics, including response time and failure rates under stress. We identified a payload limit of ~500 pages before the API failed.

Monitoring & UX: Created a Python/Flask web application with an SQLite database to log and display user interactions and model predictions, simulating a real-world monitoring system for continuous analysis and improvement.

CI/CD Implementation: Outlined a CI/CD pipeline and a Docker workflow to containerize the model and its dependencies, ensuring consistent execution and a streamlined path from development to deployment.