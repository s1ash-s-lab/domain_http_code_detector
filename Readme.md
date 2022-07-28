# domain http code detector
一個為了ais3而生ㄉhttp code偵測器
## intro
讀取數個txt檔中的domain，並且分析其每個domain對應的server是否有內容，如果有東西的話則記錄到`output.txt`
## init
設定main.py中的46行的`txt_path`，把所需的檔案都寫到`[]` list內，若是通過的domain會依序輸入`output.txt`內
## usage
`python3 main.py --timeout [time]`
[time] 就是 設定curl timeout的時間，且以秒為單位，實測建議2s
##### example:
`python3 main.py --timeout [time]`
