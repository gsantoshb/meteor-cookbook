SSL Certificates  
=================================
Secure Sockets Layer (SSL) is a foundational part of modern [TCP](http://en.wikipedia.org/wiki/Transport_Layer_Security)/IP based telecommunications networks, and is a necessary component for many regulatory frameworks such as HIPAA or SOX.  Installing SSL certifcates is fairly straight-forward; albeit tedious.  The details differ depending on the hosting environment; so, rather than try to document the process here, lets just go to the relevant blog articles specific to each platform. 

All of the following SSL guides are with hosting providers or services that will sign HIPAA Business Associates Agreements (BAA).  

==================================================================
#### Basic Overview  

1.  Determine what kind of SSL Cert you want.
2.  Purchase the certificate from your SSL provider.
3.  Generate a Certificate Signing Request (CSR).
    - Generate your own using OpenSSL.
    - Or request it from your hosting provider.
4.  Upload the CSR to your SSL provider.
5.  Update your DNS to reference the new SSL Endpoint URL


==================================================================
#### Green URL Security Bar    
To get the green pop-up address bar, you'll need an Extended Validation certificate.

https://www.digicert.com/code-signing/ev-code-signing.htm
https://www.namecheap.com/security/ssl-certificates/comodo/ev.aspx


==================================================================
#### Installing SSL Certificates on Modulus (Software as a Service)

http://help.modulus.io/customer/portal/articles/1701165-ssl-setup-guide  
https://www.namecheap.com/security/ssl-certificates/  

==================================================================
#### Installing SSL Certificates on Amazon Web Services (Infrastructure as a Service)

http://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_server-certs.html
http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/configuring-https.html
http://docs.aws.amazon.com/ElasticLoadBalancing/latest/DeveloperGuide/ssl-server-cert.html
http://docs.aws.amazon.com/ElasticLoadBalancing/latest/DeveloperGuide/elb-update-ssl-cert.html
http://docs.aws.amazon.com/opsworks/latest/userguide/workingsecurity-ssl.html

==================================================================
#### Installing SSL Certificates on Ubuntu with NGINX (Self Hosted)
https://www.digitalocean.com/community/tutorials/how-to-create-an-ssl-certificate-on-nginx-for-ubuntu-14-04  
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-meteor-js-application-on-ubuntu-14-04-with-nginx  
https://www.digitalocean.com/community/questions/how-do-i-open-ports-on-an-ubuntu-server  


==================================================================
#### Installing SSL Certificates on Catalyze.io (Software as a Service)

https://resources.catalyze.io/paas/getting-started/deploying-your-first-app/domain-names/

==================================================================
#### FAQ  

**Q: Do you need multiple domains?**  
- You'll need to purchase a _wildcard_ certificate.

**Q: Do you need a green bar?**  
- You'll need an _Extended Validation_ certificate.







