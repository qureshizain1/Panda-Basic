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
<br>
 -> print(df.info())
<br>
 For checking small amount of data like the upper head and lower head
 <br>
 -> import panda as pd
 <br>
 -> data = pd.read_excel("HotelData.xlsx")
 <br>
 -> print(data.head(10))// to see the starting ones.
 <br>
 -> print(data.tail(10)) // to see from the ending notes.
 <br>
