# SecurityFoscusOnline2023 之 Python程式與資安應用入門 
# 開場白與上課模式說明
## SecurityFoscusOnline2023課程宗旨:從CTF實戰學習資訊安全測試
- 讓全台灣的學生都有機會快速學到底下基本技術
  - 一點點的資安與CTF技術
  - 一點點的LINUX
  - 一點點的Python程式開發與在資安的應用

# 課程模組:
  - A1_MyFirstSecurity資安入門的第一堂課
  - A2_Linux資安技術入門
  - A3_Python程式與資安應用入門 

# 上課所使用的平台:請參看你的錄取通知書
- CTF平台解題(平常沒開放~只有上課期間才會開放):請參看你的錄取通知書
- Discord課程討論區:請參看你的錄取通知書
  - 嚴格禁止上傳答案(違背者取消證書|且不得參與後續研習活動)
- 上課簽到簿:請每日上課不要遲到
- 問卷調查:上完課後再填寫!一定要填寫,不然沒有證書 
  - 問卷調查須正確填寫CTF註冊的使用者ID 以供驗證解題數作為通過課程考核的依據

## CTF 入門:透過參與CTF搶旗大賽學習資安實務 [線上課程]
  - CTF搶旗大賽
  - 註冊與登入CTF
## 早上: Python 快速上手
- 1.開發環境與基本輸入與輸出 
  - python開發環境 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/0_python開發環境.md) [[YOUTUBE教學影片]](https://youtu.be/9Doo0hgbpow)
  - 基本輸入與輸出 格式化輸出 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/1_基本輸入與輸出.md)  
- 2.Python資料型態(data Type)及其各種運算 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/2_資料型態及其運算.md)  [[YOUTUBE教學影片]](https://youtu.be/zCfVPuJWRg8) 
- 3.python決策與選擇結構 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/3_python決策與選擇結構.md) [YOUTUBE預錄影片]() 
- 4.廻圈(loop) [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/4_廻圈loop.md) [[YOUTUBE教學影片]](https://youtu.be/12I7eNHQpgY) 
- 5.函數(function) [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/5_函數.md) [[YOUTUBE教學影片]](https://youtu.be/tRtsxZ73LVk) 

## 下午: Python 資安應用
- 1.使用Python求解編碼與解碼問題
  - 使用Python程式與內建函數進行ASCII的編碼與解碼 [[YOUTUBE教學影片]](https://youtu.be/0Tr-X0Lpi7g)
  - 使用Python標準函式庫進行BASE64的編碼與解碼 [[YOUTUBE教學影片]](https://youtu.be/z2jxjkl5X-4) 
  - 編碼102_Internetwache CTF 2016_The hidden message [解答]()
  - 編碼102:SECCON CTF 2014: Easy Cipher [解答]()
- 2.使用Python求解古典密碼破密分析問題 Crypto102
  - 【自行完成】{Crypto102::CRY11_PythonCrypto} [解答]()
  - 使用Python求解變形caesar密碼{Crypto102::CRY12_變形caesar密碼} [解答]()
  - 使用Python求解affine-cipher{Crypto102::CRY13_affine-cipher} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/3_Python%E5%8F%A4%E5%85%B8%E7%A0%B4%E5%AF%86%E6%B3%95/2_%E4%BD%BF%E7%94%A8Python%E6%B1%82%E8%A7%A3affine-cipher.md)
- 3.使用Python求解PPC(Professional Program Code)問題
  - PPC(Professional Program Code)之使用 nc 遠端連線{PPC101::PPC1_hello world} [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC(Professional%20Program%20Code)%E4%B9%8B%E4%BD%BF%E7%94%A8%20nc%20%E9%81%A0%E7%AB%AF%E9%80%A3%E7%B7%9A%7BPPC101::PPC1_hello%20world%7D.md)  [[教學影片]](https://youtu.be/zJF4LBBHHrE)
  - PPC(Professional Program Code)之pwntools快速入門與示範解題{PPC101::PPC2_3rd} [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC(Professional%20Program%20Code)%E4%B9%8Bpwntools%E5%BF%AB%E9%80%9F%E5%85%A5%E9%96%80%E8%88%87%E7%A4%BA%E7%AF%84%E8%A7%A3%E9%A1%8C.md) [[教學影片]](https://youtu.be/XVRYjrbBYw4)
  - PPC101::PPC3_beautify解答 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC3_beautify%E8%A7%A3%E7%AD%94.md)
  - 【自行完成】自行完成 PPC101::PPC4_count[線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC4_count%E8%A7%A3%E7%AD%94.md)
  - PPC101::PPC5_lambda解答 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC5_lambda%E7%AD%94%E6%A1%88.md)
  - PPC101::PPC6_money解答 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC6_money%E7%AD%94%E6%A1%88.md)
  - PPC101::PPC7_calendar解答 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC7_calendar%E8%A7%A3%E7%AD%94.md)
  - PPC101::PPC8_temperature答案 [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC101::PPC8_temperature%E7%AD%94%E6%A1%88.md)  [[教學影片]](https://youtu.be/_YGpD7wXGOo)



