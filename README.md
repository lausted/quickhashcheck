# Quickhashcheck

For use with hashfiles generated by hashdeep.

Example:

```
$ hashdeep ./folder > hash.txt
$ quickhashcheck [OPTIONS] hash.txt
  -h     Help & information"
  -p     Percent of files to check MD5 hashes (default 0)
  -a     Algorithm 'md5' (default) or 'sha256'
```
