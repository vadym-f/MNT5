# MNT5 -- cool research in elliptic curves

CA certificates chain at diia.gov.ua

openssl asn1parse -inform der -in CACertificates.p7b  > CACertificates-parsed.txt

openssl pkcs7 -inform der -in CACertificates.p7b > CACertificates-p7.txt

openssl pkcs7 -inform der -in CACertificates.p7b -print > CACertificates-p7print.txt

openssl pkcs7 -inform der -in CACertificates.p7b -print_certs -text  > CACertificates-certs.txt

