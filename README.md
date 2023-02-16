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
  4.Hàm<br />
  Khai báo hàm theo cú pháp:
  
            def functionname(param, param2,..):
                statements(s)
                
  Hàm nếu không trả dữ liệu thì mặc định sẽ trả về giá trị None<br />
  Ví dụ khai báo hàm tính và trả về giá trị tổng của 2 tham số đầu vào:
  
            def sum(a, b):
                return (a+b)
  
  Cách gọi hàm:
  
            sum(1, 2)
                (trả về giá trị là 3)
                
  5.Xử lí chuỗi<br />
  Một chuỗi có thể khai báo bằng dấu nháy đôi " hoặc đơn'. Ví dụ các chuỗi sau:
  
            str1 = "Hello"
            str2 = 'world'
            
  Có thể truy xuất từng ký tự trong một chuỗi theo hình thứcindex, ví dụ: str1[0] , str1[1] ...<br />
  Có thể sử dụng 3 dấu nháy (đôi hoặc đơn) để khai báo chuỗi trên nhiều dòng. Ví dụ:
  
            paragraph = """This is line 1
            This is line 2
            This is line 3"""
            
  - Nối chuỗi : Có thể tạo một chuỗi dài từ việc nối các chuỗi lại theo cú pháp:

            str = str1 + " " + str2
  
  - Truy cập chuỗi con<br />
  Có thể tạo các chuỗi con thông qua toán tử lấy khoảng [start:end] (range). Mặc định start là từ vị trí đầu chuỗi<br />
( 0 ) và end là đến vị trí cuối chuỗi. Ví dụ:

            str = 'Hello world'

            print str[0:4]
            (Hiển thị "Hell")

            print str[:4]
            (Hiển thị "Hell")

            print str[-3:]
            (Hiển thị "rld")

            print str[6:-3]
            (Hiển thị "wo")
    
   - Lấy độ dài chuỗi: Sử dụng hàm len(...) để trả về độ dài của chuỗi. Ví dụ:

            count = len("Hello world")
            (count có giá trị 11)   

   - Tìm và thay thế nội dung:Có thể tìm và thay thế trong chuỗi bằng cách gọi phương<br />
    thức replace(search, replace[, max]) của một chuỗi.
    
            str = 'Hello world'
            newstr = str.replace('Hello', 'Bye')
            print newstr
            (Sẽ hiển thị chuỗi "Bye world" trên màn hình)
            
   - Tìm vị trí chuỗi con:Có thể tìm vị trí của một chuỗi con trong chuỗi lớn bằng cách 
   gọi phương thức find(str, beg=0 end=len(string)). Bắt đầu là vị trí 0 , nếu không tìm ra thì trả về -1
    
            str = 'Hello world'
            print str.find('world')
            (hiển thị 6)

            print str.find('Bye');
            (hiển thị -1)
            
   Hàm find() sẽ tìm theo thứ tự từ trái qua phải của chuỗi,Có thể dùng hàm rfind()để tìm theo vị trí từ cuối chuỗi về phía trước.<br />
   - Tách chuỗi : tách chuỗi dựa theo một chuỗi delimeter bằng cách gọi phương thức split(str="", num=string.count(str))
    
            str = 'Hello world'
            print str.split(' ')
            (Trả về một mảng có 2 phần tử là 2 chuỗi "Hello" và "world")
           
   6.List<br />
   List trong Python là cấu trúc mảng và các phần tử có index có thứ tự.Ví dụ:
     
            numbers = [1, 2, 3, 4, 5]
            names = ['Marry', 'Peter']
            
   Có thể truy xuất từng phần tử của mảng bằng index,phần tử đầu tiên có thứ tự là 0
    
            print numbers[0]
            (Hiển thị 1)

            print numbers[-3]
            (Hiển thị 3)

            print names[1]
            (Hiển thị 'Peter')
            
   Để biết được số lượng phần tử của 1 List, có thể sử dụng hàm len(array) để lấy số lượng phần tử của mảng tham số truyền vào.<br />
   - Trích xuất mảng con:<br />
   Tương tự như chuỗi, có thể tạo các mảng con thông qua toán tử lấy khoản [start:end] (range). Mặc định start là từ vị trí đầu 
   chuỗi ( 0 ) và end là đến vị trí cuối chuỗi. Ví dụ:
     
            numbers = ['a', 'b', 'c', 'd']
            print numbers[:2]
            (Hiển thị ['a', 'b'])

            print numbers[-2:]
            (Hiển thị ['c', 'd'])
            
   - Xóa phần tử của mảng <br />
   Có thể xóa một phần tử thông qua toán tử del . Thứ tự của các phần tử sẽ dịch chuyển tùy vào vị trí của phần tử bị xóa. Ví dụ:
   
            numbers = [1, 2, 3, 4, 5]
            del numbers[0]
            print numbers
            (Hiển thị [2, 3, 4, 5])
            
   Có thể xóa một khoảng dựa vào toán tử lấy khoản [start:end] . Ví dụ:
   
            numbers = [1, 2, 3, 4, 5, 6, 7]
            del numbers[2:4]
            print numbers
            (Hiển thị [1, 2, 5, 6, 7])
   
   - Nối 2 mảng
   - Thêm phần tử vào mảng
   - Lấy phần tử cuối mảng
