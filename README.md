<div align="center">
	<h1> Complete Thailand Address </h1>

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/logicspark/thailand-address-picker-core/blob/main/LICENSE)

<p align=center> 
	A comprehensive and up-to-date database of Thailand address in both Thai (ไทย) and English. <br>
	Data is available in JSON and XLSX format. Developed by <a href="https://logicspark.com">Logic Spark</a> team.
</p>

<a id="readme-top"></a>

</div>

<div align="center">
  <a href="#open_book-overview">Overview</a> - 
  <a href="#rocket-getting-started">Getting Started</a> - 
  <a href="#card_file_box-sample-data">Sample Data</a> -
  <a href="#recycle-changelog">Changelog</a> -
  <a href="#speech_balloon-feedback">Feeback</a> -
  <a href="#books-license">License</a>
</div>


## :open_book: Overview
Thailand address will consists of provinces and their respective districts and sub-districts. We have create a simple [website](www.ctd.logicspark.com) to review the data. Have fun exploring :sunglasses:

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## :rocket: Getting Started
เริ่มต้นใช้งานข้อมูลตำบล, อำเภอ, จังหวัด และรหัสไปรษณีย์ของประเทศไทย

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :memo: JSON Key
อธิบายความหมายของข้อมูล เพื่อให้เกิดความเข้าใจและใช้งานได้อย่างง่ายดาย

| Key | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `provinceCode`      | `string` | Province code (2-digit number) |

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## :card_file_box: Sample Data
แสดงข้อมูลตัวอย่างของ จังหวัด อำเภอ ตำบล รหัสไปรษณีย์ ในรูปแบบ JSON

Provinces.json

```bash
{
	"provinceCode": 10,
	"provinceNameEn": "Bangkok",
	"provinceNameTh": "กรุงเทพมหานคร"
}
```

Districts.json

```bash
{
	"provinceCode": 10,
	"districtCode": 1002,
	"districtNameEn": "Dusit",
	"districtNameTh": "ดุสิต",
	"postalCode": 10300
}
```

Subdistricts.json

```bash
{
	"provinceCode": 10,
	"districtCode": 1002,
	"subdistrictCode": 100201,
	"subdistrictNameEn": "Dusit",
	"subdistrictNameTh": "ดุสิต",
	"postalCode": 10300
}
```


<p align="right">(<a href="#readme-top">back to top</a>)</p>
    
## :books: License

Distributed under the MIT License. See [`LICENSE`](https://github.com/logicspark/thailand-address-picker-core/blob/main/LICENSE) for more information.
  



<p align="right">(<a href="#readme-top">back to top</a>)</p>


## :speech_balloon: Feedback
สามารถแสดงความคิดเห็นหรือแจ้งปัญหาในการใช้งานได้ที่ [`FEEDBACK`](https://github.com/logicspark/thailand-address-picker-core/issues)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :recycle: Changelog
ตรวจสอบข้อมูลที่มีการเปลี่ยนแปลงของแต่ละเวอร์ชันได้ที่ [`CHANGELOG`](https://github.com/logicspark/thailand-address-picker-core/blob/main/CHANGELOG.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

