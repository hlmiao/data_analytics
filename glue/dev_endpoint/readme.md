Each dev endpoint gets 5 DPUs by default (with a minimum of 2 DPUs), this was expensive enough to customer for midnight or weekend if you open the dev endpoint all the time. It's a way to deploy an endpoint quickly through AWS CLI.

AWS Glue Development Endpoint Creation with AWS CLI Command:
aws glue create-dev-endpoint --cli-input-json file:///tmp/example.js --region cn-north-1

Delete endpoint:
aws glue delete-dev-endpoint --endpoint-name test001
aws glue list-dev-endpoints
