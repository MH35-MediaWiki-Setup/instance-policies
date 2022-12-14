# instance-policies
EC2インスタンスにアタッチするポリシー

## 使い方

1. `aws cloudformation deploy --template-file formation.yml --stack-name [your stack name] --capabilities CAPABILITY_IAM --parameter-overrides SourceBucketName=[mediawiki source bucket]`する
2. しばらく待つ
