# Major-Airline-Data-Analysis_Big-Data-Marketing
Major airlines data analysis by comparing with LCC data 

### 1.Project Summary 
```
purpose of this project: compare the key difference of Low Cost Career(LCC) with major korean airlines
Source of SNS for analysis: Youtube, Twitter, Naver Blog 
Key Brands: Jeju airlines, Asiana Airlines, Korean Air


SNS type	: Youtube		Naver Blog		Twitter				
Language	: Python 								
Essential Module	: sys		urllib		time	pandas	re	bs4(beautifulsoup)	selenium
Final code update date	: 2019.05.07								
crawling 기간	: Youtube_2017.05.01~ 2019.05.03		Naver_2018.04.27~2019.05.04		Twitter_2018.04.03~2019.05.04				

```

<table>
  <thead>
    <tr>
      <th width = "130"></th>
      <th>Youtube</th>
      <th>Naver Blog</th>
      <th>Twitter</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align = "center">Language</td>
      <td colspan="3" align = "center">Python3</td>
    </tr>
    <tr>
      <td align = "center"> Module </td>
      <td colspan = "3" align = "center">sys, urllib, time, pandas, re, bs4, selenium</td>
    </tr>
    <tr>
      <td align = "center">Final update</td>
      <td colspan ="3" align = "center">2019.05.07</td>
    </tr>
    <tr>
      <td align = "center"> Crawling&nbsp;Target</td>
      <td align = "center"> Commentes</td>
      <td align = "center"> Blog preview text</td>
      <td align = "center"> Posts</td>
    </tr>
    <tr>
      <td> crawling 기간</td>
      <td>2017.05.01&nbsp;~&nbsp;2019.05.03</td>
      <td>2018.04.27&nbsp;~&nbsp;2019.05.04</td>
      <td>2018.04.03&nbsp;~&nbsp;2019.05.04</td>
    </tr>
  </tbody>
</table>


### 2. Crawling
```
-Filtering Code: filter spam words in crawled data
-Or: get data with word A or B 
-And: get data with word A and B (this code is to filter SNS comment which mentioned more than two brands) 


```


### 3. input/output files
<img width="396" alt="github" src="https://user-images.githubusercontent.com/48209176/59550920-87fa8580-8fac-11e9-8348-81a0bbd1143c.PNG">



### 4. Frequency Analysis
<img width="456" alt="github" src="https://user-images.githubusercontent.com/48209176/59550944-e58ed200-8fac-11e9-99cc-57ba462a7cb1.PNG">


### 5. Conclusion
<img width="919" alt="github" src="https://user-images.githubusercontent.com/48209176/59550970-4918ff80-8fad-11e9-96c9-1552a935ff06.PNG">
