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
In the subsequent subsections, we will display the data structure of Thailand address. The sample data will be in JSON format. Let's get started!

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## :card_file_box: Sample Data
Below, there are three sample data, namely provinces, districts and sub-districts in JSON format. Keys that contain En or Th in them mean English or Thai respectively.

### <h4>Provinces.json</h4>

```json
	{
		"provinceCode": 10,
		"provinceNameEn": "Bangkok",
		"provinceNameTh": "กรุงเทพมหานคร"
	}
```

#### JSON Key Description

| Key | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `provinceCode`      | `string` | Province code (2-digit number) |


<h4>Districts.json</h4>

```json
	{
		"provinceCode": 10,
		"districtCode": 1002,
		"districtNameEn": "Dusit",
		"districtNameTh": "ดุสิต",
		"postalCode": 10300
	}
```
#### JSON Key Description
| Key | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `districtCode`      | `string` | district code (4-digit number) |
| `postalCode`      | `string` | Postal code (5-digit number) |


<h4>Subdistricts.json</h4>

```json
	{
		"provinceCode": 10,
		"districtCode": 1002,
		"subdistrictCode": 100201,
		"subdistrictNameEn": "Dusit",
		"subdistrictNameTh": "ดุสิต",
		"postalCode": 10300
	}
```
#### JSON Key Description
| Key | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `subdistrictCode`      | `string` | Sub district code (6-digit number) |



<p align="right">(<a href="#readme-top">back to top</a>)</p>
    

## :speech_balloon: Feedback
If there is missing/incorrect data or any suggestion, please reach out to us [here](https://github.com/logicspark/complete-thailand-address/issues/new).


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## :recycle: Changelog
For change or update to address data, please check [Changelog](https://github.com/logicspark/complete-thailand-address/blob/main/CHANGELOG.md) for more details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## :books: License

Distributed under the MIT License. See [`LICENSE`](https://github.com/logicspark/complete-thailand-address/blob/main/LICENSE) for more information.
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

