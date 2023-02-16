# LẬP TRÌNH PYTHON CƠ BẢN
Python là một ngôn ngữ lập trình bậc cao cho các mục đích lập trình đa năng.Python được thiết kế với ưu điểm mạnh là dễ đọc, dễ học và dễ nhớ và làm nền tảng để học lâp trình Trí tuệ nhân tạo

1.Biến:Khai báo biến bằng một câu lệnh gán có thể gán nhiều loại giá trị (số, chuỗi) cho một biến:
    
          a = 1
          b = 'Hello World'
          c = [1, 2, 3]
          d = [1.2, 'Hello', 'W', 2]
          
2.Toán tử<br />
2.1 Toán tử số học:

          + phép cộng
          - phép trừ
          * phép nhân
          / phép chia
          % phép chia lấy dư (modulo)
          
2.2 Toán tử logic và boolean<br />
Giá trị đúng và sai tương ứng là True và False<br />

          - not để đảo giá trị
          - and phép tính logic và
          - or phép tính logic hoặc
          
 Một số phép so sánh thông thường như < (bé hơn), <= (béhơn hoặc bằng), > (lớn hơn), >= (lớn hơn hoặc bằng), ==
(bằng), != (khác) để so sánh 2 giá trị.<br />
 ví du:
 
            x = 2
            1 < x < 3 # True
            10 < x < 20 # False
            3 > x <= 2 # True
            2 == x < 4 # True
            
  Ngoài ra còn toán tử kiểm tra phần tử tồn tại trong tập hợp in<br />
  3.Cấu trúc điều kiện<br />
  3.1 If...elif...else
  
            if condition1 :
                indentedStatementBlockForTrueCondition1
            elif condition2 :
                indentedStatementBlockForFirstTrueCondition2
            elif condition3 :
                indentedStatementBlockForFirstTrueCondition3
            elif condition4 :
                indentedStatementBlockForFirstTrueCondition4
            else:
                indentedStatementBlockForEachConditionFalse
                
  3.2 For...in
    
            for iterating_var in sequence:
                statements(s)
                
  ví dụ:
  
            for letter in 'Python': # First Example
                print 'Current Letter :', letter

            fruits = ['banana', 'apple', 'mango']
            for fruit in fruits: # Second Example
                print 'Current fruit :', fruit

            print "Good bye!"
   
  Kết quả hiển thị của ví dụ trên:
  
            Current Letter : P
            Current Letter : y
            Current Letter : t
            Current Letter : h
            Current Letter : o
            Current Letter : n
            Current fruit : banana
            Current fruit : apple
            Current fruit : mango
            Good bye!
            
  3.3 While
  
            while expression:
                statement(s)
                
  ví dụ:
  
            count = 0
            while (count < 9):
                print 'The count is:', count
                count = count + 1

            print "Good bye!"
            
  Kết quả hiển thị của ví dụ trên:
  
            The count is: 0
            The count is: 1
            The count is: 2
            The count is: 3
            The count is: 4
            The count is: 5
            The count is: 6
            The count is: 7
            The count is: 8
            Good bye!
  4.Hàm
  
            
   
  
  
