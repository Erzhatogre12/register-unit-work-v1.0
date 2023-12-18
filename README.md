# register-unit-work v1.0

## Informasi API

| **Judul** | **register-unit-work-v1.0** |
| ----- | --------------------- |
| Version | v1.0 |
| URL Sandbox | http://gateway.local.gd:8080/InteroperabilitasSemantikDataRepositoryPemasyarakatan/register-unit-work/1.0 |

### Deskripsi API

#### Gambaran API <br />
API ini untuk melihat unit rutan yang ada di semua wilayah dan juga jenis pekerjaan yang ada di dalam rutan-rutan tersebut

### Endpoint <br />

#### API Statement

#### General Information <br />
Endpoint ini digunakan untuk mengakses data yang ada di dalam API register-unit-work

| HTTP Method | Path | Tipe Format |
| --- | --------------------- | --- |
| GET | http://gateway.local.gd:8080/InteroperabilitasSemantikDataRepositoryPemasyarakatan/register-unit-work/1.0 | JSON |

#### Header Structure  <br />

| Key | Value |
| --- | --- |
| Host | 192.168.100.33:8000 |
| Date | currentDateTime |
| Connection |  |
| X-Powered-By |  |
| Cache-Control |  |
| Content-Type | application/json |
| X-RateLimit-Limit |  |
| Access-Control-Allow-Origin | * |

#### Query Param Structure

**GET** `http://gateway.local.gd:8080/InteroperabilitasSemantikDataRepositoryPemasyarakatan/register-unit-work/1.0`

#### Response Structure

| Field | Data Type	 | Mandatory | Length | Deskripsi | Contoh |
| --- | --- | --- | --- | ------------ | --- |
| Jenis WBP | String | M |  | Merupakan penjelasan dari jenis kelamin  |  |
| Narapidana | integer | M |  | Jumlah Narapidana yang terdapat pada unit tersebut | 20 |
| Tahanan | integer | M |  | Merupakan jumlah dari tahanan laki-laki | 18 |
| Column7 | integer | M |  | Merupakan jumlah dari tahanan perempuan | 2 |
| Column2 | String | M |  | Merupakan Unit kerja dari suatu rutan | A I |
| Column1 | String | M |  | Merupakan Jenis registrasi dari suatu rutan | Cabang Rutan KPK |
| Totals | Integer | M |  | Total keseluruhan Tahanan yang berada di dalam unit | 20 |

