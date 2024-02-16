# Storage_add

**Como adicionar um usuário ao servidor samba:**

```
adduser ane --ingroup ouvidoria
usermod --shell /bin/false ane
smbpasswd -a ane
smbpasswd -e ane
smbpasswd ane - Altera a senha do usuário
```

**Caso queira permitir o acesso ao shell novamente**
```
usermod --shell /bin/bash ane
```

**Para ver os grupos disponiveis:**
```
groups
```

