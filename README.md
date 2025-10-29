# SQL-Barcode
Using SQL to generate scannable barcode


## barcode_UPC_A.SQL to generate barcode following UPC-A standard

**Set the message at the beginning in the code**
<br>
`select upc = '05100001251' into #upc`

## barcode_code_128.SQL to geneate barcode following code 128 standard.

**Set the message at the beginning in the code**
<br>
`select txt = 'HAPPY 2025!' into #txt`
