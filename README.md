# AWS_GenerativeAI

在這次黑客松競賽中，我們的目標是建立一個能根據客群和產品資料進行對話的 AI 銷售員。首先，我們從東森提供的客戶資料中，篩選出可能影響購買能力和意願的關鍵變數，包括會員等級、健康意識程度、保健產品瀏覽習慣和職業等。接著，我們運用非監督式分群法（kmodes）將客戶分類。完成分群後，透過 AI 為各群體對不同產品的購買意願和能力進行評分，讓 AI 能針對不同類型的客群調整對話策略。最後，在實際對話過程中，系統會依據特定關鍵字進行評估，以提供更客製化的銷售流程和對話內容。
AWS flow:https://us-west-2.console.aws.amazon.com/bedrock/home?region=us-west-2#/flows/KY7UKXJ6BW/builder
