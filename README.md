<h1 align="center">Hadith API</h1>

<p align="center">
  <img width="460" height="300" src="https://github.com/deeneislam/hadith-api/raw/1/hadith.jpg">
</p>

[![](https://data.jsdelivr.com/v1/package/gh/deeneislam/hadith-api/badge)](https://www.jsdelivr.com/package/gh/deeneislam/hadith-api)
[![](https://data.jsdelivr.com/v1/package/gh/deeneislam/hadith-api/badge/rank)](https://www.jsdelivr.com/package/gh/deeneislam/hadith-api)


**In the name of God, who has guided me to do this work**


**Features:**
- Free & Blazing Fast response
- No Rate limits
- Multiple Languages
- Multiple Grades


**URL Structure:**

`https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@{apiVersion}/{endpoint}`

**Formats:**

The Endpoints Supports HTTP GET Method and returns the data in  two formats:

`/{endpoint}.json`

`/{endpoint}.min.json`

The above formats also work for fallback i.e if `.min.json` link fails, you can use `.json` link and vice versa

**Warning:** You should include fallback mechanism in your code, [to avoid issues](https://github.com/deeneislam/hadith-api/issues/3)

**Endpoints:**

- `/editions`<br>
> Lists all the available editions in prettified json format:<br>
 [https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions.json](https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions.json "https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions.json") <br>

> Get a minified version of it:<br>
[https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions.min.json](https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions.min.json "https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions.min.json")

- `/editions/{editionName}`<br>
> Get the whole hadith/hadith translation:<br>
[https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud.json](https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud.json "https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud.json") <br>

- `/editions/{editionName}/{HadithNo}` <br>
> Get the 1035th Hadith:<br>
[https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/1035.json](https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/1035.json "https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/1035.json")

> Get the 1035th Hadith in minified format:<br>
[https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/1035.min.json](https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/1035.min.json "https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/1035.min.json")

- `/editions/{editionName}/sections/{sectionNo}` <br>
> Get Section 7:<br>
[https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/sections/7.json](https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/sections/7.json "https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/editions/eng-abudawud/sections/7.json")


- `/info` <br>
> Get all the details about hadith book, such as hadith grades, books reference etc <br>
[https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/info.json](https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/info.json "https://cdn.jsdelivr.net/gh/deeneislam/hadith-api@1/info.json")<br>

### Contribution:
Without your contribution, this work won't survive, whenever you find any issue, please let me [Know](https://github.com/deeneislam/hadith-api/issues/new "Know"), so that I can also fix it and people can benefit from it, incase of any question, issue or problems etc<br> you can let me [Know](https://github.com/deeneislam/hadith-api/issues/new "Know")

- Please help by adding new translations to this repo, you can share me the translation [here](https://github.com/deeneislam/hadith-api/issues/new "here")

or
- Read [Contribute](https://github.com/deeneislam/hadith-api/blob/1/CONTRIBUTING.md "Contribute") to add/update the translation directly to this repo


### Download: [Here](https://github.com/deeneislam/hadith-api/blob/1/download.md)

### Any Issues: [Raise here](https://github.com/deeneislam/hadith-api/issues/new "Raise here")

### Demos:
Projects using Hadith API:
- [Hadiths](https://deeneislam.github.io/hadiths)
- [Quran Hadith Search Engine](https://deeneislam.github.io/quran-hadith-search/)

### Other Similar Projects:
- [Quran-api](https://github.com/deeneislam/quran-api)


### Share:
Please share this with your friends and Star this repo by clicking on [:star: button](#) above [:arrow_upper_right:](#)

### References:
All the open source projects and dawah/Islamic organizations

Please see [References](https://github.com/deeneislam/hadith-api/blob/1/References.md "References")


<br>
<br>
<br>

[:pencil2:*Improve this page*](https://github.com/deeneislam/hadith-api/edit/1/README.md)
