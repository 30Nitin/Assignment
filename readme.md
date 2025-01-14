# AWS Lambda Function

## Add Two Numbers

event = {

    'a': enter first number ,
    'b': enter second number

}

# AWS Lambda Function to store File in S3 Bucket

## Enter the Bucket Name

bucket_name = 'your-s3-bucket-name' # Replace with your S3 bucket name

## Enter File Name

event = {

    'body': {
        'file_content': base64.b64encode(b'This is a test file content').decode('utf-8'),
        'file_name': 'test_document.pdf' # Replace with your file_name
    }
}
   
