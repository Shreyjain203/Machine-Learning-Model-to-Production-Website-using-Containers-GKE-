# End-to-End ML Model Deployment on Google Cloud Platform (GCP)
This project demonstrates a complete workflow for deploying a machine learning model on Google Cloud Platform. It covers the following steps:
<ol>
<li><b>Model Development:</b> Train and build your machine learning model using any framework (e.g., TensorFlow, PyTorch), I used Google Cloud Shell, a free browser-based command-line environment on GCP.<br/>
<li><b>Dockerization: </b>Create a Dockerfile and containerize your model, including its dependencies and environment. This ensures consistent and portable deployment across different environments.<br/>
<li><b>Artifact Registry(AR): </b>Push the built Docker image to Google Artifact Registry, a secure and managed repository for storing container images(Docker Images).<br/>
<li><b>Kubernetes Engine (GKE) Deployment:</b> Deploy the containerized model as a service on Google Kubernetes Engine, a managed container orchestration platform. This allows for scalable and automated deployments.<br/>
<li><b>Frontend Integration:</b> Create a basic frontend application (e.g., using Flask or Streamlit) to interact with the exposed endpoint of your deployed model.<br/>
</ol>
This project provides a starting point for learning how to deploy machine learning models on GCP using industry-standard tools and practices. It showcases the benefits of:<br/><br/>
<ul>
<li><b>Containerization:</b> Enables consistent and portable deployments.<br/>
<li><b>Artifact Registry: </b>Provides a secure and centralized location for storing container images.<br/>
<li><b>Kubernetes Engine:</b> Offers an automated, scalable, and flexible platform for container orchestration.<br/></ul>
