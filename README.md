# 🧬 BypassMaster

### Laboratório de shellcode e bypass de proteções para ambientes de simulação, CTFs e aprendizado ofensivo.

##  Objetivo
Executar shellcode simples via loader em C para testar proteção contra execução (DEP, ASLR, etc).

## Funcionalidades
- Shellcode NASM 32-bit Linux
- Loader em C com `mmap` + `exec`
- Makefile para build automatizado

##  Uso

```bash
make
./bypassmaster
```

Recomenda-se executar em VMs Linux 32-bit com ASLR e DEP desabilitados.

## ⚠️ Aviso

Uso exclusivo para CTFs, laboratórios controlados ou testes explícitos de segurança.
