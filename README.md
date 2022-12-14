#Project 02: Xây dựng giao diện sử dụng Bootstrap

Các công việc thực hiện:
- Sử dụng các class có sẵn của Bootstrap cũng như tự viết thêm các class để thiết kế trang web yêu cầu responsive.
- Tìm hiểu và sử dụng thư viện Chart JS để thiết kế biều đồ đường và biểu đồ cột.
- Fake dữ liệu:
    - Đối với các ngày khác, chỉ fake dữ liệu tổng số ca.
    - Đối với ngày hiện tại:
        - Fake dữ liệu số ca CT và DX đã duyệt của từng bác sĩ.
        - Fake dữ liệu số ca chưa được đọc và đang được đọc.
- Đối với biểu đồ đường: 
    - Hiển thị tổng số ca trong từng ngày trong tuần hoặc từng tháng dựa trên khoảng thời gian đã chọn.
    - Xác thực các ngày được chọn (đúng định dạng và ngày bắt đầu không được lơn hơn ngày kết thúc).
    - Khi vừa truy cập trang web, cả 2 ngày bắt đầu và ngày kết thúc đều được đặt là ngày hiện tại.
- Trong khối hiển thị thống kê của ngày hiện tại:
    - Đã duyệt = Tổng số ca đã duyệt của các bác sĩ.
    - Tổng số = Đã duyệt + Đang đọc + Chưa đọc.
- Đối với biểu đồ cột: hiển thị tổng số ca CT và tổng số ca DX trong ngày.
- Đối với bảng "Số ca/Bác sĩ"
    - Gồm 4 cột:
        - Tên bác sĩ
        - Số ca CT
        - Số ca DX
        - Tổng số = CT + DX
    - Cho phép thiết lập số lượng bác sĩ hiển thị trong một lượt.
    - Cho phép bảng cuộn hoặc không, nếu bảng không cuộn thì sau 1 khoảng thời gian nhất định sẽ hiển thị các bác sĩ tiếp theo.
- Tạo modal cho phép thiết lập số lượng bác sĩ hiển thị mỗi lượt trong bảng "Số ca/Bác sĩ".