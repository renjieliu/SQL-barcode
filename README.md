# SQL-Barcode
Using SQL to generate scannable barcode

## barcode_code_128.SQL to geneate barcode following code 128 standard.

**Set the message at the beginning in the code**
<br>
`select txt = 'HAPPY 2025!' into #txt`

Below barcode will be generated

<img width="385" height="88" alt="image" src="https://github.com/user-attachments/assets/f5f969f0-96be-4e98-b950-a4316752ea55" />


## barcode_UPC_A.SQL to generate barcode following UPC-A standard

Example
**Set the message at the beginning in the code**
<br>
`select upc = '05100001251' into #upc`

Below barcode will be generated

<img width="318" height="144" alt="image" src="https://github.com/user-attachments/assets/3aa4dbd6-1bd3-4695-8d66-c63d6c0fe43f" />




