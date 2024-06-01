# DataWareHouse_HospitalBill

Giới thiệu
Dự án này xây dựng một Data Warehouse (Kho dữ liệu) toàn diện cho dữ liệu hóa đơn bệnh viện sử dụng Microsoft SQL Server, SQL Server Integration Services (SSIS), SQL Server Analysis Services (SSAS) và Power BI. Mục tiêu là tạo điều kiện lưu trữ, chuyển đổi, phân tích và trực quan hóa dữ liệu hiệu quả để hỗ trợ quản lý bệnh viện trong việc đưa ra các quyết định thông minh.

Các Thành Phần Dự Án
1. SQL Server
SQL Server được sử dụng làm hệ quản trị cơ sở dữ liệu quan hệ (RDBMS) để lưu trữ dữ liệu thô và dữ liệu đã được chuyển đổi. Sơ đồ kho dữ liệu bao gồm các bảng fact và bảng dimension được thiết kế để hỗ trợ các truy vấn phức tạp và báo cáo.

2. SSIS (SQL Server Integration Services)
SSIS được sử dụng cho các quy trình trích xuất, chuyển đổi và tải (ETL). Các luồng công việc ETL được thiết kế để:

Trích xuất dữ liệu từ các hệ thống nguồn khác nhau như cơ sở dữ liệu vận hành của bệnh viện và các tệp bên ngoài.
Chuyển đổi dữ liệu để đáp ứng các yêu cầu của sơ đồ kho dữ liệu, bao gồm làm sạch dữ liệu, loại bỏ trùng lặp và chuẩn hóa.
Tải dữ liệu đã chuyển đổi vào kho dữ liệu.
3. SSAS (SQL Server Analysis Services)
SSAS được sử dụng để tạo các khối OLAP và các mô hình đa chiều hỗ trợ các truy vấn phân tích nâng cao. Các khối này được thiết kế để cung cấp các chỉ số hiệu suất chính (KPI) như tổng số tiền hóa đơn, thông tin nhân khẩu học của bệnh nhân và mức độ sử dụng dịch vụ.

4. Power BI
Power BI được sử dụng để trực quan hóa và báo cáo dữ liệu. Các bảng điều khiển và báo cáo tương tác được tạo ra để cung cấp cho các bên liên quan cái nhìn sâu sắc theo thời gian thực về dữ liệu hóa đơn bệnh viện, xu hướng và mô hình.
