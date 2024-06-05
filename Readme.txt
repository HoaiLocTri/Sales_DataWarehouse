XÂY DỰNG KHO DỮ LIỆU VÀ PHÂN TÍCH DỮ LIỆU BÁN HÀNG

MÔ TẢ
Dự án nhằm mục đích xây dựng một hệ thống kho dữ liệu để lưu trữ thông tin về bán hàng và thực hiện phân tích dữ liệu từ các thông tin đó. Dự án giúp cho việc quản lý và phân tích dữ liệu bán hàng trở nên hiệu quả hơn, từ đó mang lại các thông tin quan trọng và đáng tin cậy để hỗ trợ quyết định kinh doanh.

CÔNG NGHỆ VÀ CÔNG CỤ
- Visual Studio 2019/2022
- Microsoft SQL Server 2019/2022
- Microsoft Power BI
- các package:
    + SQL Server Integration Services (SSIS)
    + SQL Server Analysis Services (SSAS)

CÀI ĐẶT VÀ SỬ DỤNG
	Bước 1: Trong T-SQL, thực thi 3 file .sql (SalesData.sql, SalesStage.sql, SalesDW.sql)
	Bước 2: Trong Code, chạy Nhom14_SSIS_Project.sln -> chạy 3 package theo thứ tự SalesData.dtsx > SalesStage.dtsx > SalesDW.dtsx
	Bước 3: Trong Code, chạy Nhom14_SSAS_Project.sln -> Deploy
	Bước 4: Phân tích và trực quan dữ liệu trên PowerBI

DỮ LIỆU
- Tập dữ liệu gôm 2824 dòng và có 25 cột thuột tính
- Link tập dữ liệu: https://www.kaggle.com/kyanyoga/sample-sales-data 
- Các thuộc tính: 
    + ORDERNUMBER: Mã Order của hóa đơn
    + QUANTITYORDERED: Số lượng đã order
    + PRICEEACH: Giá bán ra
    + ORDERLINENUMBER: Mã order line của hóa đơn
    + SALES: Tổng chi phí hóa đơn
    + ORDERDATE: Ngày order
    + STATUS: Trạng thái order
    + QTR_ID: Quý
    + MONTH_ID: Tháng
    + YEAR_ID: Năm
    + PRODUCTLINE: Tên sản phẩm
    + MSRP: Giá niêm yết
    + PRODUCTCODE: Mã sản phẩm
    + CUSTOMERNAME: Tên khách hàng (công ty)
    + PHONE: Số điện thoại khách hàng
    + ADDRESSLINE1: Địa chỉ 1 của khách hàng
    + ADDRESSLINE2: Địa chỉ 2 của khách hàng
    + CITY: Tên thành phố
    + STATE: Tên tiểu bang
    + POSTALCODE: Mã bưu điện
    + COUNTRY: Tên đất nước
    + TERRITORY: Tên vùng
    + CONTACTLASTNAME: Tên liên hệ cuối của khách hàng
    + CONTACTFIRSTNAME: Tên liên hệ đầu của khách hàng
    + DEALSIZE: Kích cỡ sản phẩm

