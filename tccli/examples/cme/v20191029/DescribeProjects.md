**Example 1: 获取项目列表**



Input: 

```
tccli cme DescribeProjects --cli-unfold-argument  \
    --Platform test \
    --ProjectIds 1111
```

Output: 
```
{
    "Response": {
        "TotalCount": 1,
        "ProjectInfoSet": [
            {
                "ProjectId": "1111",
                "Name": "test",
                "AspectRatio": "16:9",
                "Category": "VIDEO_EDIT",
                "Owner": {
                    "Type": "PERSON",
                    "Id": "user_1233"
                }
            }
        ],
        "RequestId": "requestId"
    }
}
```

