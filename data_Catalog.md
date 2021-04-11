## Google Data Catalog
---
### Scalable metadata management service

### Centralized search and discovery.

+ Help consumer to know where the data is.
+ Understanding data. 
  + dataset relate to another
  + who is using data and who is the onwer?
+ Making data useful
  + let consumers easy to access data

### **Centralized data catalog allows organizations to :**
+ 訂定統一個方式，降低搜尋資料的麻煩
+ _透過 technical and business metadata 來豐富資料加速洞察時間_
+ 改善數據管理提高效率
+ onwership over data 讓資料更有保障

---
### Interact ways:
1. 根據權限取得能搜索的資料<br>
IAM Terminology
根據 Roles 給予不同的權限




2. 為 metadata 加上 tag
#### Google Data Loss Prevention (DLP) 可以幫忙自動辨認敏感數據
---
### Technical and business metadata

#### Technical metadata : 描述如何訪問其原始本機數據存儲中的數據的信息。

example : 
+ ZIPCode :
  + String with 9 chars
  + Using SQL Query Language
  + Located in the Address Table
  

#### Business metadata :附加信息，不直接與數據的物理存儲有關。
example : 
+ ZIPCode :
  + First 5 chars for ZIP code, 4 for other property
---
 
 ### Search and discovery
 #### Data Catalog indexes the metadata that describes an asset (user-generated tags).

 ---
 ### Tags 怎麼規範?
 > Data Catalog tag templates help you create and manage common metadata about data assets in a single location.

 Data catalog 用 tags 為組織的提供創造 搜尋 管理 metadata
 
 Tag 可以看到 個人身分訊息 (PII), 數據保留政策 data quality score. 

 ### Tag templates
 1. data governance tag: 
    1. data governor
    2. retention date
    3. PII
    4. data classification
 2. data quality tag:
    1. quality issues
    2. update frequency
    3. SLO info
 3. data usage tag:
    1. top users
    2. top queries
    3. average daily users

---
### Data Catalog Identity and Access Management (IAM)

---
### VPC Service Controls
>減輕數據洩漏的風險，可以保護指定的資源或是數據。