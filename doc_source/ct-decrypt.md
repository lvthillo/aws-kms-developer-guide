# Decrypt<a name="ct-decrypt"></a>

The following example shows a log file generated by calling `Decrypt`\.

```
{
    "Records": [
    {
        "eventVersion": "1.02",
        "userIdentity": {
            "type": "IAMUser",
            "principalId": "EX_PRINCIPAL_ID",
            "arn": "arn:aws:iam::123456789012:user/Alice",
            "accountId": "123456789012",
            "accessKeyId": "EXAMPLE_KEY_ID",
            "userName": "Alice"
        },
        "eventTime": "2014-11-04T00:52:20Z",
        "eventSource": "kms.amazonaws.com",
        "eventName": "Decrypt",
        "awsRegion": "us-east-1",
        "sourceIPAddress": "192.0.2.0",
        "userAgent": "AWS Internal",
        "errorCode": "InvalidCiphertextException",
        "requestParameters": null,
        "responseElements": null,
        "requestID": "d5239dea-63bc-11e4-bc2b-4198b6150d5c",
        "eventID": "954983cf-7da9-4adf-aeaa-261a1292c0aa",
        "readOnly": true,
        "resources": [{
            "ARN": "arn:aws:kms:us-east-1:123456789012:key/e17cebae-e7a6-4864-b92f-0365f2feff38",
            "accountId": "123456789012"
        }],
        "eventType": "AwsApiCall",
        "recipientAccountId": "123456789012"
    }
  ]
}
```