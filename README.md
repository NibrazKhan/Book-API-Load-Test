# Book-API-Load-Test
### Scenario
Here Load testing  is performed using [BooksStore API](https://demoqa.com/BookStore/v1/Books) where 
the expected load is 10000 per hour. Severall tests has been performed for 60s,300s,600s and 900s load 
using Jmeter. The tests having TPS breakdown are summarized in excel spreadsheet and the images of 
tests screenshots are attached in doc file containing HTML report for the last test of 900s having 2500 users.

The excel and word file can be accessed from :
- [Excel report](https://github.com/NibrazKhan/Book-API-Load-Test/blob/main/Resources/Performance%20testing%20using%20JMETER.xlsx)
- [Word file having test screenshots](https://github.com/NibrazKhan/Book-API-Load-Test/blob/main/Resources/Test%20results%20from%20jmeter.docx)
### Overall TPS and test breakdown.
![image](https://user-images.githubusercontent.com/55280106/175831845-5faa3510-21b6-42e6-b9f8-84594d0b7e7c.png)

### Individual Test Reports
- 167 users for 60 seconds
 ![Test1](https://user-images.githubusercontent.com/55280106/175831924-5182de29-55d8-4ab6-892b-5ceb829a2f9b.png)
- 833 users for 300 seconds
![Test2](https://user-images.githubusercontent.com/55280106/175831938-d91d23a6-6dbf-48a7-b3d0-afed55162400.png)
- 1667 users for 600 seconds
![Test3](https://user-images.githubusercontent.com/55280106/175831946-22227ef9-311d-41ab-ab2f-77865822538e.png)
- 2500 users for 900 seconds
![Test4](https://user-images.githubusercontent.com/55280106/175831953-3493726f-1e45-4900-a65e-98def4f604ce.png)
### HTML summary report.
- For 2500 users of 900 seconds.
![summary_report](https://user-images.githubusercontent.com/55280106/175831979-c4411d1c-188a-4689-a6ce-fb28a1f2cf92.png)
