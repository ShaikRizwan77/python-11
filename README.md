# python-11
International date and time


import pytz
from datetime import datetime
a=pytz.timezone("Asia/Kolkata")
b=datetime.now(a)
print(b)
