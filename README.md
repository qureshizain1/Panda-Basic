# Panda-Basic
Basic Pandas Code
<br>
Author Zain ul Abideen
<br>
Bais code to upload any excel file
<br>
 ->   import pandas as pd
 <br>
 ->  data = pd.read_excel("HotelData.xlsx")
 <br>
 ->   print(data)
 <br>
To add new row and column using dataframe
<br>
 ->   import pandas as pd
 <br>
 ->    Data = {"name":["hassan", "Zain"],
               "age":[22,24],
               "city":["RWP","ISB"]}
               <br>
 ->   df =pd.DataFrame(Data)
 <br>
 ->   print(df)
 <br>
Checking duplicate in the data
<br>
->   import pandas as pd
<br>
 ->  data = pd.read_excel("HotelData.xlsx")
 <br>
 ->  print(df.isnull().sum())
 <br>
 ->  print("checking for diplicates=",df.duplicated().sum())
 <br>
Having information of the data that what kind of datatypes we have
 -> print(df.info())

 For checking small amount of data like the upper head and lower head
 -> import panda as pd
 -> data = pd.read_excel("HotelData.xlsx")
 -> print(data.head(10))// to see the starting ones.
 -> print(data.tail(10)) // to see from the ending notes.
