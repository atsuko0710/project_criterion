# 用户相关接口

## 1. 创建用户

### 1.1 接口描述

创建用户。

### 1.2 请求方法

POST /v1/users

### 1.3 输入参数

**Body 参数**

| 参数名称 | 必选 | 类型                      | 描述               |
| -------- | ---- | ------------------------- | ------------------ |

### 1.4 输出参数

| 参数名称 | 类型                      | 描述               |
| -------- | ------------------------- | ------------------ |

### 1.5 请求示例

**输入示例**

```bash
 curl -XPOST -H'Content-Type: application/json' -H'Authorization: Bearer $Token' -d'{
  "metadata": {
    "name": "foo"
  },
  "nickname": "foo",
  "password": "Foo@2020",
  "email": "foo@foxmail.com",
  "phone": "1812884xxxx"
}' http://marmotedu.io:8080/v1/users
```
**输出示例**

```json
{
    "code":200,
    "msg":"",
    "data"
}
```