**Example 1: 拒绝黑石对等连接申请**



Input: 

```
tccli bmvpc RejectVpcPeerConnection --cli-unfold-argument  \
    --Version 2018-06-25 \
    --VpcPeerConnectionId pcx-5p7vkch8
```

Output: 
```
{
    "Response": {
        "TaskId": 1234,
        "RequestId": "09186e64-d19e-4ca1-968f-df4fc8139192"
    }
}
```

