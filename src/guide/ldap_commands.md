# 🆕 AÑADIR UN USUARIO NUEVO
```shell
ldapadd -x -D cn=admin,dc=doncom,dc=com -W -f file.ldif
```

## 📄 REVISAR EL LISTADO DE ARCHIVOS LDIF SUBIDOS
```shell
ldapsearch -x -LLL -H ldap://localhost -D "cn=admin,dc=doncom,dc=com" -W -b "dc=doncom,dc=com"
```
```shell
ldapsearch -x -LLL -H ldap://localhost -D "cn=admin,dc=doncom,dc=com" -w davidtomas -b "dc=doncom,dc=com" "(objectClass=*)"
```
---

# 🆕 ADD A NEW USER
```shell
ldapadd -x -D cn=admin,dc=doncom,dc=com -W -f file.ldif
```

## 📄 REVIEW THE LIST OF UPLOADED LDIF FILES
```shell
ldapsearch -x -LLL -H ldap://localhost -D "cn=admin,dc=doncom,dc=com" -W -b "dc=doncom,dc=com"
```