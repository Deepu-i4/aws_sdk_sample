# aws_sdk_sample


Postman collection
:-
{
"info": {
"_postman_id": "594ac7ed-d2dd-4fe8-b7ba-907bf332e500",
"name": "AWS S3",
"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
"_exporter_id": "6569817",
"_collection_link": "https://blue-escape-405356.postman.co/workspace/MyPersonalWorkspace~1bd086fd-f0a8-4e0c-a7ad-4944bc057e0f/collection/6569817-594ac7ed-d2dd-4fe8-b7ba-907bf332e500?action=share&source=collection_link&creator=6569817"
},
"item": [
{
"name": "S3 bucket creation",
"request": {
"method": "GET",
"header": [],
"url": {
"raw": "localhost:8080/s3bucket/add/pushp",
"host": [
"localhost"
],
"port": "8080",
"path": [
"s3bucket",
"add",
"pushp"
]
}
},
"response": []
},
{
"name": "Upload s3 file",
"request": {
"method": "POST",
"header": [],
"body": {
"mode": "formdata",
"formdata": [
{
"key": "file",
"type": "file",
"src": "/C:/Users/USER/OneDrive/Desktop/Bike Insurance.pdf"
}
]
},
"url": {
"raw": "localhost:8080/s3bucket/upload/file/pushp",
"host": [
"localhost"
],
"port": "8080",
"path": [
"s3bucket",
"upload",
"file",
"pushp"
]
}
},
"response": []
},
{
"name": "Delete s3 file",
"request": {
"method": "DELETE",
"header": [],
"body": {
"mode": "formdata",
"formdata": [
{
"key": "file",
"type": "file",
"src": "/C:/Users/USER/OneDrive/Desktop/Bike Insurance.pdf"
}
]
},
"url": {
"raw": "localhost:8080/s3bucket/delete/file/s3bucket/pushp",
"host": [
"localhost"
],
"port": "8080",
"path": [
"s3bucket",
"delete",
"file",
"s3bucket",
"pushp"
]
}
},
"response": []
},
{
"name": "Delete s3",
"request": {
"method": "DELETE",
"header": [],
"body": {
"mode": "formdata",
"formdata": [
{
"key": "file",
"type": "file",
"src": "/C:/Users/USER/OneDrive/Desktop/Bike Insurance.pdf"
}
]
},
"url": {
"raw": "localhost:8080/s3bucket/delete/bucket/s3bucket",
"host": [
"localhost"
],
"port": "8080",
"path": [
"s3bucket",
"delete",
"bucket",
"s3bucket"
]
}
},
"response": []
}
]
}
