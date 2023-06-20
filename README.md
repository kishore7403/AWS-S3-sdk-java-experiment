# AWS-S3-sdk-java-experiment

This repository contains the code and documentation for an AWS S3 experiment.

## Description

The experiment involved using an AWS Academy account to perform various tasks related to AWS S3. The tasks included creating an HTML file with profile information, using the AWS SDK for Java to create an S3 bucket, uploading the HTML file to the S3 bucket, enabling hosting for the bucket, changing the bucket's policy for hosting the static webpage, deleting the file from the bucket, and deleting the bucket itself.

## Getting Started

To run the experiment, follow the steps below:

1. Create an HTML file named `index.html` with the profile information, including the full name, banner number, email, and a declaration of original work.

2. Open the `Main.java` file in your preferred Java IDE or text editor.

3. Locate the `createS3Client` function. This function creates an instance of the S3Client using the AWS SDK for Java and the default credentials provider.

4. Modify the `bucketName` variable in the `main` function to specify the desired name for your S3 bucket.

5. Compile and run the program.

6. Enter the desired operation number when prompted:
    - Operation 1: Creates an S3 bucket with the specified bucket name.
    - Operation 2: Uploads the `index.html` file to the S3 bucket.
    - Operation 3: Deletes the `index.html` file from the S3 bucket.
    - Operation 4: Deletes the S3 bucket.

7. The program will execute the selected operation and display a success message.

![flowchart](https://github.com/kishore7403/AWS-S3-sdk-java-experiment/assets/48860055/d2f6cf36-a1ef-4936-934a-4eb480cb0f15)


Feel free to modify and adapt this README file to meet the specific requirements of your assignment.
