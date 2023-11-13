# Incremental-Data-load-with-Azure-Data-Factory
In this tutorial, use the Azure portal to create a data factory. then use the Copy Data tool to create a pipeline that incrementally copies new and changed files only, from Azure Blob storage to Azure Blob storage. It uses LastModifiedDate to determine which files to copy.

### In this tutorial, I complete the following tasks:

- Create a storage account.
- Create a data factory.
- Use the Copy Data tool to create a pipeline.
- Monitor the pipeline and activity runs.

### Azure blob store.
![Azure blob store](https://github.com/Nkamanyi/Incremental-Data-load-with-Azure-Data-Factory/blob/main/Azure%20blob%20store.png)

### Deployment.
![Deployment](https://github.com/Nkamanyi/Incremental-Data-load-with-Azure-Data-Factory/blob/main/Deployment.png)

### Monitor the data pipeline.
![Monitor the data pipeline](https://github.com/Nkamanyi/Incremental-Data-load-with-Azure-Data-Factory/blob/main/Monitor%20the%20data%20pipeline..png)

### Detail of activity run.
![Detail of activity run](https://github.com/Nkamanyi/Incremental-Data-load-with-Azure-Data-Factory/blob/main/Detail%20of%20activity%20run.png)

### Added file1.txt to the source folder.
![Added file1.txt to the source folder](https://github.com/Nkamanyi/Incremental-Data-load-with-Azure-Data-Factory/blob/main/Added%20file1.txt%20to%20the%20source%20folder.png)

### The pipeline automatically deploy when when it dectects new data.
![The pipeline automatically deploy when when it dectects new data](https://github.com/Nkamanyi/Incremental-Data-load-with-Azure-Data-Factory/blob/main/The%20pipeline%20automatically%20deploy%20when%20when%20it%20dectects%20new%20data..png)

### File1.txt is copied to the destination data store.
![file1.txt is copied to the destination data store](https://github.com/Nkamanyi/Incremental-Data-load-with-Azure-Data-Factory/blob/main/file1.txt%20is%20copied%20to%20the%20destination%20data%20store.png)
