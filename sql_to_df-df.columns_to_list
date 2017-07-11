import pandas as pd
from sqlalchemy import create_engine
import sqlite3

con = sqlite3.connect(r"C:\Users\Administrator\Desktop\excel-upload-sqlite3\mins\db.sqlite3")
sql = "SELECT shiliyi.'★机构全名' FROM shiliyi"
data = pd.read_sql(sql, con)
fund_name_list = data["★机构全名"].tolist()
print(fund_name_list)
