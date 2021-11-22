# JwtConfiguration NetCore 5

**#JWt**
JSON Web Tokens are an open, industry standard RFC 7519 method for representing claims securely between two parties

It contains 
a)	Header
b)	Payload
c)	Very signature

#Install below Package 
Install-package Microsoft.AspNetCore.Authentication.JwtBearer

#Below namespaces needed, which are predefined  

using Microsoft.IdentityModel.Tokens;
using System.IdentityModel.Tokens.Jwt;
using System.Security.Claims;
using System.Text;
