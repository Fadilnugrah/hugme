---
title: "Membuat key secret"
date: 2021-10-21T03:42:09Z
tags: ['python','linux','key-secret']
draft: false
---

# key secret

Hallo gais apa kabar kalian semua, semoga sehat wa afiat aamiin dan di jauhkan
dari wabah yang melanda ini kali ini saya ingin membagi tutorial / membahas cara
membuat key secret menggunakan python wahhh.</br>

Apa saja yang harus di pahami?, cukup memanipulasi string dan digit saja
sebenarnya dan juga bantuan random.choice wkwk, emang si konten ini ga terlalu
penting, tapi apa salahnya berbagi sedikit ilmu ? hehe</br>

```
import string
import random

class generate:
   def __init__(self,value):
      self.value = value  #panjangnya key

    def key(self):
      return ''.join(random.choice(string.ascii_letters+string.digits)for _ in range(self.value))

print (generate(20).key())

```
