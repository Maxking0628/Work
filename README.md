## **1.系級班級**
資工1A
## **2.組別號碼**
18
## **3.成員資訊**
資工1A 曾鈺翔
資工1A 林軒承
資工   宋承哲
## **4.程式介紹**
分別輸入w、s、a、d後，程式會控制所有方塊進行上下左右的移動，並判斷是否有相同方塊可以合併，接著統計空的數量（為０的），接著在隨機１～２個空的位置上產生隨機的２或４
## **5.程式規則**
當任一方塊的值達到2048時或沒有任何方塊可以進行加總時，遊戲結束
## **6.程式玩法**
輸入WASD來控制方塊移動方向
## **7.程式如何安裝執行**
下載程式並解壓縮
## **8.程式碼執行方式**
• 先製作一個4*4的二維陣列
• 隨機位置新增兩個2的方塊
• 輸入w,a,s,d來控制方向
• 讓方塊移動
• 判斷數字移動得方向的相鄰方塊是否相同，若相同就相加
• 判斷是否有數字達到2048或是沒有地方可以移動則遊戲結束
• 若沒結束再隨機新增一至兩個2或4的方塊
• 印出結果
## **9.程式畫面截圖**
![image](https://github.com/Maxking0628/Work/assets/126648509/1561ac9a-7263-4379-a5d7-144ac7d1aee5)
## **10.分工資訊**
林軒丞：
1. 初始化 
2. 新增方塊 
3. 文字輸入接收
4. 統合

曾鈺翔：
1. 格子移動 
2. 計算格子的數值
3. 印出計算過的結果
4. 印出開始結束畫面

宋承哲(消失)