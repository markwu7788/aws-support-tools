# WAF_Replication - WAF WebACL Cross Region Copy

This Python script will read all IP Sets and regex sets from your source Region WAF and create identical resources in the destination region, and finally copy all WebACLs to the destination Region.

Use example:
```
$ python3 wafv2_clone_v5.py ap-northeast-1 REGIONAL ap-southeast-1 REGIONAL
```

Note:
This Python script is purpose for POC and reference to know how to copy WebACL cross region.
Please test it in your test environment before use it at production. 

