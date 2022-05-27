# Prosper's Blog (A Static Travel Blog Website)
## (Deploy Static Website to AWS)

#### In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

#### The files included are: 

#### index.html - The Index document for the website.
#### /img - The background image file for the website.
#### /vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
#### /css - CSS files for the website.
##

## 1. Create an AWS S3 Bucket and allow public access

![Bucket1](https://user-images.githubusercontent.com/97234029/170700330-d472d03d-1d23-4ae3-ac3c-4b0f26aa1a2b.jpg)

## 2. Click on "Add files" to upload files and "Add folder" to upload folder.

![upload_files2](https://user-images.githubusercontent.com/97234029/170701007-3a61b069-2f43-4d91-a594-ec52adecea94.jpg)
#### If you have your project files/folders inside a folder on your computer, don't upload that folder. Instead, upload it's content one by one.
##

## 3. After a successful upload you will see your files and folders with the name of your S3 Bucket at the top.

![uploaded3](https://user-images.githubusercontent.com/97234029/170701813-9e385928-edde-4252-9608-6ca8b82cfce3.jpg)

## 4. Secure your S3 bucket via IAM. 
#### Click on the "Permissions" tab on your S3 bucket and scroll down to the "Bucket Policy" section and enter the following policy replacing "myblogproject" with the name of your project.
