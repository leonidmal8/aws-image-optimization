# aws-image-optimization
Simple, performant and cost efficient solution for optimizing images using Amazon CloudFront, Amazon S3 and AWS Lambda with svg updates

git clone https://github.com/leonidmal8/aws-image-optimization.git

cd image-optimization

npm install

cdk bootstrap

npm run build

cdk deploy -c DEPLOY_SAMPLE_WEBSITE=false -c S3_IMAGE_BUCKET_NAME="your bucket" -c MAX_IMAGE_SIZE=47000000
