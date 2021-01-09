# -*- coding: utf-8 -*-
"""
Created on Tue Jan  5 18:19:25 2021

@author: Purwantoro
"""

from nltk.stem import PorterStemmer
ps = PorterStemmer()
kata = ["program","programs","programer","programing","programers"]
for k in kata:
    print(k, " : " , ps.stem(k))
    
    
from nltk.stem import LancasterStemmer
lst = LancasterStemmer()
stm = ["giving","given","given","gave"]
for word in stm:
    print(word, ":", lst.stem(word))