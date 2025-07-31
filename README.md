# Migrating MySQL to Aurora RDS using DMS

In this project, a MySQL instance hosted on EC2 was migrated to Aurora RDS for MySQL. In order to accomplish this goal, a replication instance was created to host the migration. Next, two endpoints were created. One to connect the source database, and another to connect the target database. Lastly, a migration task was created to perform the database migration. The results of the migration were verified using MySQL Workbench

## Creation of replication instance
<img width="1200" height="336" alt="image" src="https://github.com/user-attachments/assets/ac86fae5-61f0-4e8c-9173-d0b287e36d6c" />

## Source and Target endpoints
<img width="1431" height="386" alt="image" src="https://github.com/user-attachments/assets/ee16fe9a-56fa-42b8-a9d1-aa4367114b1f" />

## Migration task complete
<img width="1416" height="362" alt="image" src="https://github.com/user-attachments/assets/6c25fd8c-a552-4ceb-90b4-1257d1daa6ff" />

## Source Database
<img width="500" height="480" alt="image" src="https://github.com/user-attachments/assets/d72bd9cb-5a8a-4b10-8484-8da91227c572" />

## Target Database after migration
<img width="500" height="480" alt="image" src="https://github.com/user-attachments/assets/eb000845-e4b9-42c3-a493-2c08e4f85330" />

