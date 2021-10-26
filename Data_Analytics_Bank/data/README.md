### DỮ LIỆU KHÁCH HÀNG CỦA NGÂN HÀNG:
1. **age**: tuổi của khách hàng - numeric
1. **job**: Công việc của khách hàng - Categorical
1. **marital**: tình trạng hôn nhân - Categorical
1. **education**: trình độ học vấn - Categorical
1. **default**: cho biết có các bất kỳ các khoản tín dụng nào chưa thanh toán nào hay không - Categorical
1. **housing**: cho biết có bất kỳ khoản vay nhà ở nào hay không - Categorical
1. **loan**: cho biết có bất kỳ khoản vay cá nhân nào hay không - Categorical

### LIÊN QUAN ĐẾN LẦN LIÊN HỆ TRƯỚC ĐÓ CỦA CHIẾN DỊCH HIỆN TẠI
1. **contact**: kiểu liên lạc - Categorical
1. **month**: tháng liên hệ - Categorical
1. **day_of_week**: ngày trong tuần liên hệ - Categorical
1. **duration**: thời lượng liên hệ (tính bằng giây - s) - numeric

### CÁC THUỘC TÍNH KHÁC
1. **campaign**: số lượng địa chỉ liên hệ được trong chiến dịch và cho khách hàng này - numeric
1. **pdays**: số ngày trôi qua khi được liên hệ lần cuối kể từ chiến dịch trước đó - numeric
1. **previous**: số lượng địa chỉ liên hệ đuợc thực hiện trước chiến dịch này và cho khách hàng này - numeric
1. **poutcome**: kết quả của chiến dịch marketing trước đó - Categorical

### THUỘC TÍNH BỐI CẢNH CỦA KINH TẾ/XÃ HỘI THỜI ĐIỂM ĐÓ
1. **emp.var.rate**: tỷ lệ thay đổi việc làm (chỉ số hàng quý) - numeric
1. **cons.price.idx**: chỉ số giá tiêu dùng (chỉ số hàng tháng) - numeric
1. **cons.conf.idx**: chỉ số niềm tin của người tiêu dùng (chỉ số hàng tháng) - numeric
1. **euribor3m**: lãi suất euribor 3 tháng - chỉ báo hàng ngày - numeric
1. **nr.employed**: số lượng nhân viên (chỉ số hàng quý) - numeric

### BIẾN ĐẦU RA (KẾT QUẢ)
1. **y**: khách hành đăng ký tiền gửi chưa (yes/no) - Categorical
