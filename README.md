# Assignment-5

# 1 Problem statement 
# Write a function to compute 5/0 and use try/except to catch the exceptions.

try:
    x = 5 / 0
except:
    print("Error dividing by zero")
    
    
# Implement a Python program to generate all sentences where subject is in ["Americans",
# "Indians"] and verb is in ["Play", "watch"] and the object is in ["Baseball","cricket"].

subjects=["Americans ","Indians"]
verbs=["play","watch"]
objects=["Baseball","Cricket"]
sentence_list = [(sub+" "+ vb + " " + ob) for sub in subjects for vb in verbs for ob in objects]
for sentence in sentence_list:
    print (sentence)
