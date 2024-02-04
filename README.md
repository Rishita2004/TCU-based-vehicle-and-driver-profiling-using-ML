# Project README

## Idea / Solution

### Proposed Solution
Our portal leverages advanced AI/ML models for precise and effective driver and vehicle profiling, marking a new era in two-wheeler ICE/EV computation technology. By harnessing the power of cloud connectivity via EC2 AWS and ensuring robust security with SSL/TLS protocols, we offer an innovative solution tailored for the modern vehicular environment.

### Solution Features

- **Categorized Risk Level Assessment:** Real-time risk level categorization from very high to very low, powered by clustering algorithms.
- **Accurate Vehicle Health Profiling:** Utilizes regression and classification algorithms to provide both quantitative and qualitative insights into the vehicle's condition.
- **Effective Rider Scoring:** Scores are computed in the connected cloud, generating comprehensive reports to back the scoring system.
- **Driver Behavior Analysis:** Employs driver scores and clustering techniques (K-means and DBSCAN) to intelligently profile drivers based on historical data.
- **Faster Responsiveness through Edge Computing:** Implements risk level assessment models and urgent beeping alerts from the TCU to achieve low latency and high performance.
- **Cloud Connectivity and Scalability:** Offers a holistic view of driver behavior and long-term trends, utilizing the EC2 cloud for comprehensive insights. Data is streamed directly from the TCU via port 80-HTTP.
- **Future Work:** Plans to extend the platform to include electric vehicles (EVs).

## Technology Stack / Dependencies

- **AI/ML Frameworks:** Keras, TensorFlow, Scikit-learn
- **Networking Technology:** HTTP, MQTT Protocol
- **Cloud Hosting:** EC2 AWS
- **Database Management:** MongoDB, PostgreSQL
- **Development Tools:** React, Superbase, Flask, MERN

## Show Stopper

The integration of Panda, a device designed to connect to a bike’s OBD port, stands out as a pivotal feature. It enables the control of specific functions based on the bike's ECU, paving the way for the development of "self-driving safe bikes". This innovative approach to vehicle management and safety exemplifies the potential for transformative changes in the automotive industry.

### Conclusion

Our solution represents a significant step forward in the domain of two-wheeler ICE/EV technology, offering a suite of powerful tools for vehicle and driver analysis. With a focus on safety, efficiency, and scalability, we are poised to redefine standards and lead the way in intelligent vehicular solutions.
