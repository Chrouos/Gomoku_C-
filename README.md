# Gomoku － 五子棋
------

開發工具: C#  
網上參照練習版本。  
   
   
說明:   
9 * 9 方格中，純策略型棋類遊戲，雙方分別使用黑白兩色的棋子，輪流下在棋盤直線與橫線的交叉點上，先在橫線、直線或斜對角線上形成5子連線者獲勝。
   
-------
程式碼介紹:  
   
>Form1.cs：主程式控制  
  
>GameController.cs：遊戲控制，規則等  
  
>Board.cs：棋盤上的控制  
>>Piece.cs：棋子製造的類別  
>>>PieceType.cs：enum 名稱  
>>>>WhitePiece.cs：白棋　　       
>>>>BlackPiece.cs：黑棋      
