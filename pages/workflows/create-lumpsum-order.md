## Create Lumpsum Order
----------------

#### Netbanking
|     Steps    |     Method       |    Reference    |
|--------------|------------------|-----------------|
| Fetch bank account ID | GET | [Get Investor Details](https://fintechprimitives.com/api/#get-investor-details) |
| Fetch ISIN | GET | [Get Fund Schemes](https://fintechprimitives.com/api/#get-fund-schemes) |
| Create Lumpsum Order | POST | [Create Lumpsum Order](httpshttps://fintechprimitives.com/api/#post-create-lumpsum-order-netbanking) |
| Call the netbanking API | POST | [Netbanking](https://fintechprimitives.com/api/#post-net-banking) |
| Sync payment details | POST | - |
| Simulate the reconciliation from AMC | POST | - |

#### NACH
|     Steps    |     Method       |    Reference    |
|--------------|------------------|-----------------|
| Fetch bank account ID | GET | [Get Investor Details](https://fintechprimitives.com/api/#get-investor-details) |
| Fetch ISIN | GET | [Get Fund Schemes](https://fintechprimitives.com/api/#get-fund-schemes) |
| Create a NACH order | POST | [Create Lumpsum Order NACH](https://fintechprimitives.com/api/#post-create-lumpsum-order-nach) |
