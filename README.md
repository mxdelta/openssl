# openssl

openssl pkcs12 -info -in cert.pfx -noout

Команда openssl pkcs12 -info -in cert.pfx -noout используется для просмотра информации о сертификате в формате PKCS12 и проверки его структуры без вывода дополнительных данных.

----Взлом пароя сертификата 
      https://github.com/crackpkcs12/crackpkcs12.git
      ./configure 
      
---------перевод  pfx в pem

openssl pkcs12 -in cert.pfx -out cert.pem -nokeys
