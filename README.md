# Panda-Basic
Basic Pandas Code
<br>
Author Zain ul Abideen
<br>
Bais code to upload any excel file
 ->   import pandas as pd
 ->  data = pd.read_excel("HotelData.xlsx")
 ->   print(data)
To add new row and column using dataframe
 ->   import pandas as pd
 ->    Data = {"name":["hassan", "Zain"],
               "age":[22,24],
               "city":["RWP","ISB"]}
 ->   df =pd.DataFrame(Data)
 ->   print(df)
Checking duplicate in the data
->   import pandas as pd
 ->  data = pd.read_excel("HotelData.xlsx")
 ->  print(df.isnull().sum())
 ->  print("checking for diplicates=",df.duplicated().sum())
Having information of the data that what kind of datatypes we have
 -> print(df.info())

 For checking small amount of data like the upper head and lower head
 -> import panda as pd
 -> data = pd.read_excel("HotelData.xlsx")
 -> print(data.head(10))// to see the starting ones.
 -> print(data.tail(10)) // to see from the ending notes.
