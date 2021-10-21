Very basic example using Go in arm64 Lambda using provided.al2 runtime

Inside `example-go1.x` directory run (replace `<parameters>` with the corresponding values)
- `sam build`
- `sam package --s3-bucket <bucket-name> --output-template-file ./new-template.yaml`
- `sam deploy --template-file ./new-template.yaml --stack-name <stack-name> --capabilities CAPABILITY_IAM`

