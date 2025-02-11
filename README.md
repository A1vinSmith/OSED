# OSED
Prepartion with HTB

```bash
msf-pattern_create -l 5000 > eip.txt

msf-pattern_offset -q 31684630
[*] Exact match at offset 4112

msf-pattern_offset -q $(echo -n "B5eB" | xxd -p)
[*] Exact match at offset 915
```
