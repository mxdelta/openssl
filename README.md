# openssl

openssl pkcs12 -info -in cert.pfx -noout


            openssl pkcs12 -info -in cert.pfx -noout -------используется для просмотра информации о сертификате в формате PKCS12 и проверки его структуры без вывода дополнительных данных.


            openssl x509 -in cert.pem -noout -text -------выводит содержимое сертификата в формате X.509, включая информацию о версии, серийном номере, алгоритме подписи, эмитенте, сроке действия и открытом ключе.

----Взлом пароя сертификата 
      https://github.com/crackpkcs12/crackpkcs12.git
      ./configure 
      
---------перевод  pfx в pem

openssl pkcs12 -in cert.pfx -out cert.pem -nokeys

#Загрузить сертификат

$cert = import-pfxCertificate -FilePath '$RLYS3KF.pfx' -Password $pass -CertStoreLocation Cert:\CurrentUser\My
