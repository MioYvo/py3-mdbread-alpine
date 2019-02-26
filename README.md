# GW与设备通信

# 发送数据
```
{
    "agent_name": "123",
    "device_type": "ersa",
    "content": {
        "data": "MjNzc...",      // base64编码过的**binary**文件内容
        "base_path": "E :\test_data_path",
        "file_name": "data.txt",
        "data_source_type": "trend"
    }
}
```