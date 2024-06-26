# Title:A primer on data on Kubernetes
#### Date: 2024-04-10
#### URL: https://youtu.be/l9o88O422EM



## SUMMARY

Akay Ram and Prashant Vina discuss the evolution of data on Kubernetes, focusing on stateful applications, AIML training and inference, and their implementations in Google Kubernetes Engine (GKE) and Pixel Cut.

## IDEAS:

- Kubernetes evolved from stateless to stateful applications, enhancing data orchestration.
- Customers demand safety features and storage integrations for data on Kubernetes.
- GKE introduced backup, HA, and upgrades aware of stateful applications.
- Data on Kubernetes community survey shows productivity doubled by using Kubernetes.
- Cloud storage is popular for AIML due to cost efficiency and Python integration.
- GCS Fuse launched to address latency issues with small file access in training.
- Parallel Store, a first-party parallel file system, introduced for high-performance storage.
- GKE's CSI driver integration with Parallel Store simplifies data transfer from GCS.
- Container preloading in GKE accelerates loading of large inference server images.
- GCS Fuse and PDSS used to speed up model weights loading for inference.
- Recommendations for model size considerations when choosing between GCS Fuse and PDSS.
- Pixel Cut improved ML deployments on Kubernetes by optimizing container sizes and dependencies.
- Secondary boot disks and image streaming significantly reduced image pull times at Pixel Cut.
- Implementing best practices in Kubernetes can materially impact business responsiveness and cost.
- The evolution of data management on Kubernetes reflects broader trends in cloud computing.

## INSIGHTS:

- Kubernetes' adaptability to stateful applications signifies its growing role in complex data orchestration.
- The intersection of Kubernetes and AIML highlights the importance of efficient data handling for innovation.
- Enhancements in GKE for stateful applications demonstrate the cloud's evolution towards more resilient data management.
- The productivity gains from Kubernetes adoption underscore the technology's impact on operational efficiency.
- The development of solutions like GCS Fuse and Parallel Store reflects the ongoing need for performance optimization in cloud storage.
- The challenges of AIML training and inference data management reveal the critical role of infrastructure in AI development.
- Pixel Cut's experience illustrates the tangible benefits of applying Kubernetes best practices to real-world problems.
- The rapid evolution of data management tools on Kubernetes points to a future where cloud-native technologies drive business agility.
- The collaboration between Google and its customers on Kubernetes solutions exemplifies a user-centric approach to technology development.
- The case studies of GKE and Pixel Cut provide valuable lessons for organizations seeking to leverage Kubernetes for data-intensive applications.

## QUOTES:

- "Kubernetes has moved from the stateless world to quite a stateful world."
- "Over 40% of leaders said we're not only running data on applications on Kubernetes but we're also being more productive."
- "Cloud storage is extremely cost efficient, scalable, and has integration with Python."
- "We launched a GCS cloud storage fuse...it's been super popular."
- "Parallel Store is a first-party parallel file system launched by Google."
- "We're introducing GKE container preloading for fast acceleration of container images."
- "GCS Fuse has been around...now with read caching, your data is cached on your local storage."
- "Our mission is to give every merchant creative superpowers."
- "We had one container which was over 19 GB...pull times could sometimes exceed 30 minutes."
- "After implementing best practices...our pull times now look like around 2 seconds."

## HABITS:

- Regularly assessing customer needs to adapt Kubernetes for data orchestration.
- Focusing on safety features and storage integrations for running stateful applications on Kubernetes.
- Leveraging community feedback to double productivity through Kubernetes adoption.
- Integrating Python with cloud storage for efficient AIML application development.
- Utilizing GCS Fuse for addressing latency issues with small file access during training.
- Adopting Parallel Store for high-performance storage needs in AIML training.
- Implementing container preloading in GKE to accelerate loading of large inference server images.
- Choosing between GCS Fuse and PDSS based on model size for inference efficiency.
- Optimizing container sizes and dependencies to improve ML deployments on Kubernetes.
- Enabling secondary boot disks and image streaming to reduce image pull times significantly.

## FACTS:

- Kubernetes has evolved to support both stateless and stateful applications effectively.
- The Data on Kubernetes community survey indicated a twofold increase in productivity among users.
- Google Cloud Storage (GCS) is a popular choice for AIML due to its cost efficiency and scalability.
- GCS Fuse was launched to improve access times for training data consisting of many small files.
- Google introduced Parallel Store, a parallel file system, for high-performance storage needs.
- GKE now supports container preloading to speed up the loading of large inference server images.
- Cloud Storage Fuse CSI with read caching was launched to enhance training data access speeds.
- Pixel Cut implemented Kubernetes best practices to significantly improve their ML deployments.
- Secondary boot disks and image streaming in GKE can reduce image pull times to around 2 seconds.
- Recommendations for model size considerations help users choose between GCS Fuse and PDSS.

## REFERENCES:

- Google Kubernetes Engine (GKE)
- Data on Kubernetes Community
- Cloud Storage Interface (CSI)
- GCS Cloud Storage Fuse
- Parallel Store
- Python SDK for Google Cloud Storage
- DLIO Benchmarking Tool
- Bert Language Model
- Nvidia Triton Inference Server
- Seldon Core ML Deployment Framework
- Hyperdisk ML Block Storage

## RECOMMENDATIONS:

- Consider adopting Kubernetes for both stateless and stateful application orchestration.
- Explore GCS Fuse for efficient AIML training with large datasets of small files.
- Evaluate Parallel Store for high-performance storage needs in cloud-native environments.
- Implement container preloading in GKE to accelerate inference server image loading times.
- Use GCS Fuse with read caching for improved training data access speeds in AIML projects.
- Optimize container sizes and offload heavy dependencies to improve ML deployment efficiency.
- Enable secondary boot disks and image streaming in GKE for faster container startup times.
- Choose between GCS Fuse and PDSS based on model size for optimal inference performance.
- Follow Pixel Cut's example of applying Kubernetes best practices for tangible business benefits.
- Stay informed about the latest developments in Kubernetes and cloud-native technologies for data management.