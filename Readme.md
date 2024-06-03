## Welcome To 
# MY Swift Market Project


The Society for Worldwide Interbank Financial Telecommunications (SWIFT) system powers most international money and security transfers. SWIFT is a vast messaging network used by financial institutions to quickly, accurately, and securely send and receive information, such as money transfer instructions.
---
Financial institutions use SWIFT to securely transmit information and instructions through a standardized code system. Although SWIFT is crucial to global financial infrastructure, it's not a financial institution. SWIFT does not hold or transfer assets but facilitates secure, efficient communication between member institutions.
---
This Data was collected from [kaggle](https://www.kaggle.com/datasets/monikahussain/swiftmarket-dataset)
---
``` python
def showTables():
    query='''SHOW TABLES;'''
    cursor.execute(query)
    rows = cursor.fetchall()
    df = pd.DataFrame(data=rows,columns=cursor.column_names)
    return df
```
|NAME|DESIGNATION|
|----|-----------|
|PALLAVI|DEVELOPER|
|JYOTI|CTO|
