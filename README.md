<a id="readme-top"></a>
<div align="center">
	<h1> Complete Thailand Address </h1>
รวบรวมและอัปเดตข้อมูลล่าสุดของตำบล, อำเภอ, จังหวัด และรหัสไปรษณีย์ของประเทศไทย ได้อย่างครบถ้วน เพื่อให้นักพัฒนานำข้อมูลไปใช้งานต่อไปได้ ในรูปแบบ XLSX และ JSON  
พัฒนาโดยทีมนักพัฒนาจาก Logic Spark Co., Ltd.
	

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/logicspark/thailand-address-picker-core/blob/main/LICENSE)


</div>



## :rocket: Getting Started
เริ่มต้นใช้งานข้อมูลตำบล, อำเภอ, จังหวัด และรหัสไปรษณีย์ของประเทศไทย

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :memo: JSON Key
อธิบายความหมายของข้อมูล เพื่อให้เกิดความเข้าใจและใช้งานได้อย่างง่ายดาย

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
สามารถแสดงความคิดเห็นหรือแจ้งปัญหาในการใช้งานได้ที่ [`FEEDBACK`](https://github.com/logicspark/thailand-address-picker-core/issues)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :recycle: Changelog
สามารถตรวจสอบข้อมูลที่มีการเปลี่ยนแปลงของแต่ละเวอร์ชันได้ที่ [`CHANGELOG`](https://github.com/logicspark/thailand-address-picker-core/blob/main/CHANGELOG.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

