# Project-Professional-Programming-Practices
## Giới thiệu đồ án
Trong đồ án này thực hiện xây dựng một ứng dụng Android có tên là Learning English vừa học vừa chơi giúp người học có hứng thú để phát triển khả năng tiếng Anh. Đồ án này được thực hiện theo nhóm gồm có bốn thành viên. Ứng dụng Learning English bao gồm hai tính năng chính như sau:
- Chức năng English Quiz: chức năng trắc nghiệm tiếng Anh, có cả câu hỏi chữ và câu hỏi hình. Mỗi câu hỏi có 4 đáp án, trong đó có 1 đáp án đúng. Các câu hỏi xuất hiện ngẫu nhiên và không lặp lại. Cho phép người chơi chọn số lượng câu hỏi mỗi lần chơi tối thiểu là 5 và tối đa là 10. Mỗi câu hỏi trả lời đúng được tính 1 điểm, trả lời sai hoặc không trả lời hoặc hết thời gian thì tính 0 điểm. Mỗi câu hỏi có thời gian 20 giây, sử dụng đồng hồ đếm ngược nếu hết thời gian thì tự động sang câu kế tiếp. Kết thúc quiz hiển thị số điểm người chơi đạt được và lưu vào danh sách điểm cao nếu lọt vào top 5.
- Chức năng Correct word: chức năng này hiện lên 1 từ tiếng Anh có các chữ cái sắp xếp lộn xộn, người chơi suy đoán và gõ lại thành 1 chữ tiếng Anh đúng. Mỗi từ có thời gian 30 giây để người chơi trả lời, sử dụng đồng hồ đếm ngược nếu hết thời gian thì tự động sang từ kế tiếp. Thứ tự xuất hiện các từ được quy định như sau:
  - Đầu tiên xuất hiện 1 từ ở mức trung bình, nếu người chơi trả lời đúng sẽ xuất hiện từ khó hơn, nếu người chơi tiếp tục trả lời đúng thì lại xuất hiện từ khó hơn nữa và cứ tiếp tục như thế. Nếu người chơi trả lời đúng liên tiếp 3 từ thì được nhận 1 ngôi sao.
  - Khi người chơi trả lời sai thì xuất hiện từ kế tiếp dễ hơn, nếu trả lời sai 3 lần liên tiếp thì sẽ mất 1 ngôi sao nếu trước đó đã có ngôi sao. Nếu người chơi không có ngôi sao nào mà trả lời sai 3 lần liên tiếp sẽ tự động kết thúc và thông báo với người chơi “Bạn cần phải học tiếng anh từ đầu”.
  - Kết thúc trò chơi hiển thị số ngôi sao người chơi đạt được, lưu vào danh sách điểm cao nếu lọt vào top 5.
## Công nghệ sử dụng
- Android Studio (Java, XML)
- Database (SQLite)
## Vai trò trong đồ án
- Thực hiện xây dựng cơ sở dữ liệu, tổ chức các bảng và nhập dữ liệu vào các bảng trong cơ sở dữ liệu.
- Thực hiện kết nối đến database để đọc và ghi dữ liệu vào các bảng.
- Thực hiện xây dựng các hàm xử lý nghiệp vụ cho tính năng Correct Word.
- Thực hiện xây dựng tính năng hiện thị top 5 người đạt điểm cao và ghi mới người dùng nếu lọt vào top 5.
