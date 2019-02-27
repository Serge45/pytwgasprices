# pytwgasprices 

## Brief
A simple package to fetch the latest Taiwan gas prices

## Install
`pip install pytwgasprices`

## Usage
Example
```
from pytwgasprices import cpcgas, fpccgas

if __name__ == '__main__':
    print(cpcgas.get_cpc_gas_info())
    print(fpccgas.get_fpcc_gas_info())
```

will ouput

```
[('92無鉛', '26.3'), ('95無鉛', '27.8'), ('98無鉛', '29.8'), ('酒精汽油', '27.8'), ('超級柴油', '25.5'), ('液化石油氣', '17.4')]
[('92無鉛汽油', '26.3'), ('95+無鉛汽油', '27.7'), ('98無鉛汽油', '29.8'), ('超級柴油', '25.3')]
```