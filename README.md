# HashCrackers

hash crackers & hash generator

# crypt hashes capabilities added #

- all crypt hashes are supported in (CryptHash.py) utility

- examples of crypt hashes:
```
md5crypt: $1$8jUqZFui$IoratnUIS46gSGOfrb1Fe/
sha-256crypt: $5$8jUqZFuinvUd.1uN$y7wPemqm7DrpRjFfYH0GTutsYJGeYWcDkuIvbA1.jKC
sha-512crypt: $6$8jUqZFuinvUd.1uN$JXWt3HIsOaJWkxxubL3GHCZYY.wV9ng9fc0wCESEYOv1oHYMMF5.lap/iAMxwuy5qVT/05K5Pe4HZ0tYyoXCz1
```

- the crypt functionality is auto detect all you need to provide is only the hash 

- the crypt cracking capabilities is wrote in seperate script (CryptHash.py) because it uses multiprocessing for performance imporvments
