**Example 1: 列出指定环境属性**



Input: 

```
tccli tdmq DescribeEnvironmentAttributes --cli-unfold-argument  \
    --EnvironmentId test1
```

Output: 
```
{
    "Response": {
        "MsgTTL": 2000,
        "RateInByte": 0,
        "RateInSize": 0,
        "Replicas": 2,
        "RetentionHours": 0,
        "RetentionSize": 0,
        "EnvironmentId": "test1",
        "Remark": "备注",
        "RequestId": "dec113a8-599a-4e70-b143-14425d48ffc4"
    }
}
```

