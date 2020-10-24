
<a name="module_Digiposaja"></a>
## Digiposaja

* [Digiposaja](#module_Digiposaja)
    * _@_
        * [.@](#module_Digiposaja.@)
    * _AuthService_
        * [./user/auth/v2](#module_Digiposaja./user/auth/v2)
        * [./auth/otp](#module_Digiposaja./auth/otp)
    * _DetailOrderService_
        * [./recharge/v2](#module_Digiposaja./recharge/v2)
        * [./package-activation/v5](#module_Digiposaja./package-activation/v5)
    * _DigistarService_
        * [./redeem/detail](#module_Digiposaja./redeem/detail)
        * [./redeem/id](#module_Digiposaja./redeem/id)
    * _KonfirmasiPinService_
        * [./recharge/confirm](#module_Digiposaja./recharge/confirm)
        * [./package-activation/confirm/v2](#module_Digiposaja./package-activation/confirm/v2)
        * [./voucher-fisik/v2](#module_Digiposaja./voucher-fisik/v2)
    * _PulsaElektronikService_
        * [./recharge/denom](#module_Digiposaja./recharge/denom)
    * _TransactionService_
        * [./transactions/detail](#module_Digiposaja./transactions/detail)
        * [./transactions/history](#module_Digiposaja./transactions/history)
    * _UserService_
        * [./balance/v2/ngrs](#module_Digiposaja./balance/v2/ngrs)
        * [./outlet/linkaja](#module_Digiposaja./outlet/linkaja)
        * [./outlet/linkaja/list](#module_Digiposaja./outlet/linkaja/list)
        * [./linkaja/account](#module_Digiposaja./linkaja/account)
        * [./user/payment](#module_Digiposaja./user/payment)
        * [./product/v3](#module_Digiposaja./product/v3)
        * [./balance/v2/linkaja](#module_Digiposaja./balance/v2/linkaja)
        * [./reward/summary](#module_Digiposaja./reward/summary)
        * [./user/profile](#module_Digiposaja./user/profile)
    * _ZDingklikService_
        * [./recharge](#module_Digiposaja./recharge)
        * [./package-activation](#module_Digiposaja./package-activation)
        * [./voucher-fisik](#module_Digiposaja./voucher-fisik)



<a name="module_Digiposaja.@"></a>
### Digiposaja.@
**Akses lebih dari 1 Akun**



<a name="module_Digiposaja./user/auth/v2"></a>
### Digiposaja./user/auth/v2
**Request**


| Param | Type | Description |
| --- | --- | --- |
| username | <code>String</code> | di `query`, dibutuhkan `true` |
| password | <code>String</code> | di `query`, dibutuhkan `true` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./auth/otp"></a>
### Digiposaja./auth/otp
**Request**


| Param | Type | Description |
| --- | --- | --- |
| otp | <code>String</code> | di `query`, dibutuhkan `true` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./recharge/v2"></a>
### Digiposaja./recharge/v2
**Request**


| Param | Type | Description |
| --- | --- | --- |
| denomRecharge | <code>String</code> | di `query`, dibutuhkan `true` |
| price | <code>String</code> | di `query`, dibutuhkan `true` |
| rechargeType | <code>String</code> | di `query`, dibutuhkan `true`, nilai `BULK`/`FIX` |
| msisdn | <code>String</code> | di `query`, dibutuhkan `true` |
| paymentMethod | <code>String</code> | di `query`, dibutuhkan `true`, nilai `NGRS`/`LINKAJA` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./package-activation/v5"></a>
### Digiposaja./package-activation/v5
**Request**


| Param | Type | Description |
| --- | --- | --- |
| packageId | <code>String</code> | di `query`, dibutuhkan `true` |
| price | <code>String</code> | di `query`, dibutuhkan `true` |
| msisdn | <code>String</code> | di `query`, dibutuhkan `true` |
| trxType | <code>String</code> | di `query`, dibutuhkan `true`, nilai `HVC`/`DATA`/`DIGITAL`/`ROAMING`/`VOICE_SMS`/`VF` |
| paymentMethod | <code>String</code> | di `query`, dibutuhkan `true`, nilai `NGRS`/`LINKAJA` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./redeem/detail"></a>
### Digiposaja./redeem/detail
**Request**


| Param | Type | Description |
| --- | --- | --- |
| redeemId | <code>String</code> | di `query`, dibutuhkan `true` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./redeem/id"></a>
### Digiposaja./redeem/id
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./recharge/confirm"></a>
### Digiposaja./recharge/confirm
**Request**


| Param | Type | Description |
| --- | --- | --- |
| pin | <code>String</code> | di `query`, dibutuhkan `true` |
| token | <code>String</code> | di `query`, dibutuhkan `true` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./package-activation/confirm/v2"></a>
### Digiposaja./package-activation/confirm/v2
**Request**


| Param | Type | Description |
| --- | --- | --- |
| pin | <code>String</code> | di `query`, dibutuhkan `true` |
| token | <code>String</code> | di `query`, dibutuhkan `true` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./voucher-fisik/v2"></a>
### Digiposaja./voucher-fisik/v2
**Request**


| Param | Type | Description |
| --- | --- | --- |
| serialNumber | <code>String</code> | di `query`, dibutuhkan `true`, equal `msisdn` |
| pin | <code>String</code> | di `query`, dibutuhkan `true` |
| productId | <code>String</code> | di `query`, dibutuhkan `true` |
| price | <code>String</code> | di `query`, dibutuhkan `true` |
| paymentMethod | <code>String</code> | di `query`, dibutuhkan `true`, nilai `NGRS`/`LINKAJA` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./recharge/denom"></a>
### Digiposaja./recharge/denom
**Request**


| Param | Type | Description |
| --- | --- | --- |
| msisdn | <code>String</code> | di `query`, dibutuhkan `true` |
| paymentMethod | <code>String</code> | di `query`, dibutuhkan `true`, nilai `NGRS`/`LINKAJA` |
| categoryCode | <code>String</code> | di `query`, nilai `NSB` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./transactions/detail"></a>
### Digiposaja./transactions/detail
**Request**


| Param | Type | Default | Description |
| --- | --- | --- | --- |
| id | <code>String</code> |  | di `query`, dibutuhkan `true` |
| trxType | <code>String</code> | <code>RECHARGE</code> | di `query`, dibutuhkan `true`, nilai `RECHARGE` |
| _id | <code>String</code> |  | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./transactions/history"></a>
### Digiposaja./transactions/history
**Request**


| Param | Type | Default | Description |
| --- | --- | --- | --- |
| startDate | <code>String</code> | <code>CURRENT_DATE</code> | di `query`, dibutuhkan `true`, format `YYYYMMDD` example `20201201` |
| endDate | <code>String</code> | <code>CURRENT_DATE</code> | di `query`, dibutuhkan `true`, format `YYYYMMDD` example `20201201` |
| page | <code>String</code> | <code>0</code> | di `query`, dibutuhkan `true` |
| pageSize | <code>String</code> | <code>20</code> | di `query`, dibutuhkan `true` |
| trxType | <code>String</code> |  | di `query` |
| status | <code>String</code> |  | di `query` |
| _id | <code>String</code> |  | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./balance/v2/ngrs"></a>
### Digiposaja./balance/v2/ngrs
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./outlet/linkaja"></a>
### Digiposaja./outlet/linkaja
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./outlet/linkaja/list"></a>
### Digiposaja./outlet/linkaja/list
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./linkaja/account"></a>
### Digiposaja./linkaja/account
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./user/payment"></a>
### Digiposaja./user/payment
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./product/v3"></a>
### Digiposaja./product/v3
**Request**


| Param | Type | Description |
| --- | --- | --- |
| categoryCode | <code>String</code> | di `query`, dibutuhkan `true`, nilai `HVC`/`DATA`/`DIGITAL`/`ROAMING`/`VOICE_SMS`/`VF` |
| msisdn | <code>String</code> | di `query` |
| paymentMethod | <code>String</code> | di `query`, dibutuhkan `true`, nilai `NGRS`/`LINKAJA` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./balance/v2/linkaja"></a>
### Digiposaja./balance/v2/linkaja
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./reward/summary"></a>
### Digiposaja./reward/summary
**Request**


| Param | Type | Description |
| --- | --- | --- |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./user/profile"></a>
### Digiposaja./user/profile
**Request**


| Param | Type | Description |
| --- | --- | --- |
| code | <code>String</code> | di `query`, dibutuhkan `true` |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./recharge"></a>
### Digiposaja./recharge
**Request**


| Param | Type | Description |
| --- | --- | --- |
| transactionId | <code>String</code> | di `query` |
| jumlah | <code>String</code> | di `query`, dibutuhkan `true`, nominal yang akan dibeli |
| keuntungan | <code>String</code> | di `query`, dibutuhkan `true`, penambahan pada harga modal |
| batas | <code>String</code> | di `query`, dibutuhkan `true`, batas harga penjualan |
| msisdn | <code>String</code> | di `query`, dibutuhkan `true`, nomer hp yang akan di isi |
| paymentMethod | <code>String</code> | di `query`, dibutuhkan `true`, nilai `LINKAJA`/`NGRS` |
| rechargeType | <code>String</code> | di `query`, dibutuhkan `true`, nilai `BULK`/`FIX` |
| pin | <code>String</code> | di `query`, dibutuhkan `true`, dibutuhkan untuk melanjutkan transaksi, dikosongkan untuk cek ketersediaan produk |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./package-activation"></a>
### Digiposaja./package-activation
**Request**


| Param | Type | Description |
| --- | --- | --- |
| transactionId | <code>String</code> | di `query` |
| keuntungan | <code>String</code> | di `query`, dibutuhkan `true`, penambahan pada harga modal |
| batas | <code>String</code> | di `query`, dibutuhkan `true`, batas harga penjualan |
| categoryCode | <code>String</code> | di `query`, dibutuhkan `true`, nilai `HVC`/`DATA`/`DIGITAL`/`ROAMING`/`VOICE_SMS` |
| msisdn | <code>String</code> | di `query`, dibutuhkan `true`, nomer hp yang akan di isi |
| paymentMethod | <code>String</code> | di `query`, dibutuhkan `true`, nilai `LINKAJA`/`NGRS` |
| packageId | <code>String</code> | di `query`, dibutuhkan `true` |
| pin | <code>String</code> | di `query`, dibutuhkan `true`, dibutuhkan untuk melanjutkan transaksi, dikosongkan untuk cek ketersediaan produk |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash


<a name="module_Digiposaja./voucher-fisik"></a>
### Digiposaja./voucher-fisik
**Request**


| Param | Type | Description |
| --- | --- | --- |
| transactionId | <code>String</code> | di `query` |
| keuntungan | <code>String</code> | di `query`, dibutuhkan `true`, penambahan pada harga modal |
| batas | <code>String</code> | di `query`, dibutuhkan `true`, batas harga penjualan |
| categoryCode | <code>String</code> | di `query`, dibutuhkan `true`, nilai `VF` |
| msisdn | <code>String</code> | di `query`, dibutuhkan `true`, nomer hp yang akan di isi |
| paymentMethod | <code>String</code> | di `query`, dibutuhkan `true`, nilai `LINKAJA`/`NGRS` |
| productId | <code>String</code> | di `query`, dibutuhkan `true` |
| pin | <code>String</code> | di `query`, dibutuhkan `true`, dibutuhkan untuk melanjutkan transaksi, dikosongkan untuk cek ketersediaan produk |
| _id | <code>String</code> | di `query`, dibutuhkan `true`, awalan `digiposaja-`, digunakan untuk akses lebih dari 1 akun |

**Example**  
```bash
