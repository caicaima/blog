# 认证与授权

## HTTP 身份认证与授权

HTTP提供了一个通用的访问控制和身份认证框架。最通用的一种方案为 "Basic" 认证。本文介绍并讨论常见的几种认证机制。

---
- **Basic** (见 RFC 7617,基于base64编码的证书),
- **Bearer** (见 RFC 6750,bearer tokens to access OAuth 2.0-protected resources),
- **Digest** (见 RFC 7616 在Firefox 中仅md5哈希支持)
- **HOBA** (见 RFC 7486(draft), **H**TTP **O**rigin-**B**ound **A**uthentication,基于数字签名)
- **Mutual** (见 draft-ietf-httpauth-mutual)
- **AWS4-HMAC-SHA256** (见 AWS文档)
 