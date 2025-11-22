# Lab 2.2 - 時空偵探社：碎片之城

## 遊戲簡介
《碎片之城》是一款懸疑推理文字冒險遊戲。  
玩家扮演時空偵探社偵探，進入每天會重置的城市，在 5 天內找出造成時間破碎的元凶。

## Lab 2.2對應
- 多個LLM任務：  
  1) 世界生成 
  2) 敘事
  3) NPC對話
  4) 狀態更新（digest LLM 自己輸出）  
  5) 結局回顧  
- 每局世界與案件不同  
- LLM digest自己的敘事與對話輸出來更新state
- 結束時自動產生本次冒險回顧

## 安裝與執行
pip install openai tiktoken

python main.py

## 指令範例
- 調查 地點
- 前往 地點
- 詢問 NPC名 關於 問題
- 推理
- 指控 NPC名
- help
- exit

## 輸出
- state/save_x.json：存檔
- output/summary_x.txt：本局遊戲回顧



