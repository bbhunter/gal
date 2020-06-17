# Get All Links - [gal]

Get all the links for target websites using href / src / url / etc. 

### Dependencies
```
curl
linux system
```

### Installation
```
git clone https://github.com/YashGoti/gal.git
cd gal
chmod +x gal.sh
```

### Usage
```
./gal.sh -u https://target.com #single target URL
./gal.sh -ul ./targets.txt #mulltiple target URLs
```

### Options
|Options|Description|
|-------|-----------|
|-u|Find links from single URL/Website|
|-ul|Find links from list of URLs/Websites|
|Note|Please use URL/website with slash at the end Ex. http(s)://target.com|

### Note
```
Please use target URL without slash at the end of URL / URLs
```

### Special Thanks to
```
- Gwendal Le Coguic [gwen001] - [https://github.com/gwen001] - for CURL Request
- Kathan Patel [KathanP19] - [https://github.com/KathanP19] - for Suggestion
```
