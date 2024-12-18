2024-12-18
14:12
#easy #forensics #base64

## Description
How about some hide and seek?
Download this file [here](https://artifacts.picoctf.net/c_titan/6/unknown.zip).

## Steps Taken
1. download file 
2. run strings command on .jpg
3. one of the strings look like it base64 encoded 
4. run through a [base64 decoder](https://www.base64decode.org/)
5. Flag: **picoCTF{ME74D47A_HIDD3N_a6df8db8}**