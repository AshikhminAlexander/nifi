

### Requirements
- Docker Desktop

### Environment Setup
 1. Clone the repo

 2. Create "nifi" docker network.
    ```bash
        docker network create nifi
    ```
 3. Run the NiFi container.
    
    ```bash
        docker compose up -d
    ```

 4. Use the usernames and passwords from docker-compose.yml to access NiFi, MinIO, Postgre

 5. Minio bucket contains a  .csv file, which will be automatically loaded in Postgre
 
 6. You can download and load again the same file to repeat the process

 7. NiFi is set up to the schema of that particular .csv (7 columns of text data)

