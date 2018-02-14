# HelloWaitWebServiceApp
Sample Webservice WAR application to test with desired response times. (Works on Oracle WebLogic 11g/12c)

# How to deploy?

Download HelloWaitServiceApp.war application and deploy to Oracle WebLogic.

# How to use?

Use below WSDL address and call sayHello WebService operation.

http://localhost:7003/HelloWaitService/HelloWaitWebService1Port?WSDL

Sample WS Request XML:

```xml
<soap:Envelope xmlns:soap="http://www.w3.org/2003/05/soap-envelope" xmlns:wiz="http://wizard/">
   <soap:Header/>
   <soap:Body>
      <wiz:sayHello>
         <!--Optional:-->
         <name>Fevzi Korkutata</name>
         <!--Optional:-->
         <waitSecond>0</waitSecond>
      </wiz:sayHello>
   </soap:Body>
</soap:Envelope>
```

# Screen capture?

!()[] 

# YouTube screen cast available:

https://youtu.be/lD8QkCNiDsE
