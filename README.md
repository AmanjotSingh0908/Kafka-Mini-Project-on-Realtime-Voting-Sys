# Real-time Voting Engineering Project using Kafka & Docker

## Project Overview

The Real-time Voting Engineering project is designed to process and analyze real-time voting data for random Indian candidates and voters. The goal is to build a scalable and distributed system that can handle high volumes of data, ensuring reliability and accuracy in vote counting and data integrity. The system integrates multiple technologies to efficiently stream, process, and store data while ensuring low latency and fault tolerance.

### Key Features:
- Real-time vote streaming using Apache Kafka.
- High-speed data processing with Apache Spark.
- Integration with PostgreSQL for storing and querying vote data.
- Docker-based containerization for easy deployment.
- Streamlit-based web application for monitoring real-time results.
  
## Technologies Used

### 1. **Programming Languages**:
   - **Python**: Used for core application development, data processing, and integration with Apache Kafka and Spark.
   
### 2. **Big Data Frameworks**:
   - **Apache Kafka**: Used for streaming vote data in real-time between different components of the system.
   - **Apache Spark**: Spark Streaming is employed for real-time data processing and aggregation of votes.

### 3. **Database**:
   - **PostgreSQL**: A relational database used for storing and querying voting data, ensuring persistence and fault tolerance.

### 4. **Containerization**:
   - **Docker**: Used to containerize the application for seamless deployment across different environments. The setup includes a `docker-compose.yml` file to manage multiple services easily.

### 5. **Web Interface**:
   - **Streamlit**: A lightweight framework used to create a real-time web interface for monitoring voting results and system performance.

### 6. **Miscellaneous**:
   - **Virtual Environment**: The project uses Python's `virtualenv` to manage dependencies.
   - **JDBC Driver**: PostgreSQL JDBC driver is included for database connectivity.
     
![streaming data into kafka topic](https://github.com/user-attachments/assets/064c09e6-359d-4c24-9500-efe971d72732)
![Kaka voters topic](https://github.com/user-attachments/assets/a5bed4e2-869d-463f-ba25-1abc7f8679db)
![DockerContainers](https://github.com/user-attachments/assets/8ba041bc-b018-4adc-9097-3c18c998fb79)
![Dashboard3](https://github.com/user-attachments/assets/37b84b42-676a-487c-a3dd-e6c52b05cab6)
![Dashboard2](https://github.com/user-attachments/assets/391baa5e-f369-49cb-955c-91377df67dc1)


For any queries, feel free to contact me @Twitter - " https://x.com/AmanjotSaini_ "

Reference Video :- https://www.youtube.com/watch?v=X-JnC9daQxE


