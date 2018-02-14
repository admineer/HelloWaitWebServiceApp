# HelloWaitWebServiceApp
Sample Webservice application with desired response times. (Works on Oracle WebLogic 11g/12c)

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

<iframe width="560" height="315" src="https://www.youtube.com/embed/lD8QkCNiDsE?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
