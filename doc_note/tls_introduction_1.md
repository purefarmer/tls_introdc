SSL/TLS 简述

---------

## 简述

SSL/TLS 过程概览:

1. 协商使用哪种加密协议
2. server选择加密算法
3. 相互交换数字证书认证
4. 使用非对称加密产生公钥，分发密钥.SSL/TLS通过对称加密通信.

## SSL/TLS协商过程

![tls_uml](http://www.plantuml.com/plantuml/png/VLBDReGW4Bxp5CIJ7FRG_tRJRFO1UlEwIKDna4aHB61RtxxiKbQDqPF9V3z-tp177xWBVQj95xyeiECcqAfwUnSQmOJ5s8Fx1aV8IDaT3YEmBszOaUPKWTQs8CO6e0uR5QYL4-kzS4CNREDufr1GDDAwbWUqXen-k-IU9UKjAn8mSzSWitdE4IEhoF8z1ZYPAca4n38I1J_FbXNoJ-vO9ACSg5_8rdlVi__Qdp1G-1MAcmRMotimTVGN3f9YKlzaIZ2NvK1DVp2edAFhFpIACvsjvtXW5-k4JQENAAc3hnuTr6osufd-CPVVTjX8y7Iz08a6lOAws7ZHv_oYCtR6N-VXNbZUB6t1Uzw09yTODnxm7m00)<br>[tls 握手示意图](http://www.plantuml.com/plantuml/uml/VLBDReGW4Bxp5CIJ7FRG_tRJRFO1UlEwIKDna4aHB61RtxxiKbQDqPF9V3z-tp177xWBVQj95xyeiECcqAfwUnSQmOJ5s8Fx1aV8IDaT3YEmBszOaUPKWTQs8CO6e0uR5QYL4-kzS4CNREDufr1GDDAwbWUqXen-k-IU9UKjAn8mSzSWitdE4IEhoF8z1ZYPAca4n38I1J_FbXNoJ-vO9ACSg5_8rdlVi__Qdp1G-1MAcmRMotimTVGN3f9YKlzaIZ2NvK1DVp2edAFhFpIACvsjvtXW5-k4JQENAAc3hnuTr6osufd-CPVVTjX8y7Iz08a6lOAws7ZHv_oYCtR6N-VXNbZUB6t1Uzw09yTODnxm7m00)



### 参考

[SSL/TLS算法流程解析](<https://www.cnblogs.com/littleatp/p/6219630.html>)

[SSL/TLS 双向认证(一) -- SSL/TLS工作原理](<https://blog.csdn.net/ustccw/article/details/76691248>)

[IBM An overview of the SSL or TLS handshake](<https://www.ibm.com/support/knowledgecenter/SSFKSJ_7.1.0/com.ibm.mq.doc/sy10660_.htm>)

[rfc5246](<https://www.rfc-editor.org/pdfrfc/rfc5246.txt.pdf>)











