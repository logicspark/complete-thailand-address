<a id="readme-top"></a>
<div align="center">
	<h1> Complete Thailand Address </h1>
การรวบรวมข้อมูลทางภูมิศาสตร์ของประเทศไทย จังหวัด อำเภอ ตำบล และรหัสไปรษณีย์ ในรูปแบบ XLSX, JSON เพื่อให้ง่ายในการเข้าถึงข้อมูลที่ถูกต้อง พัฒนาโดยทีม Logic Spark.
	

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/logicspark/thailand-address-picker-core/blob/main/LICENSE)


</div>



## :rocket: Getting Started
เริ่มต้นใช้งานเกี่ยวกับข้อมูลทางภูมิศาสตร์ของประเทศไทย จังหวัด อำเภอ ตำบล และรหัสไปรษณีย์

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :memo: JSON Key
ทำความเข้าใจเกี่ยวกับ ตัวอย่างข้อมูล JSON

| Key | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `provinceCode`      | `string` | Province code (2-digit number) |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :test_tube: Demo

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :card_file_box:  Sample Data
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
https://github.com/logicspark/thailand-address-picker-core/issues


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :recycle: Changelog
สำหรับข้อมูลที่มีการเปลี่ยนแปลงในแต่ละเวอร์ชัน สามารถตรวจสอบได้ที่ [`CHANGELOG`](https://github.com/logicspark/thailand-address-picker-core/blob/main/CHANGELOG.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

