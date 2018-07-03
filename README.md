# Self practice git - Version control

##### Mục lục
1. Quản lý phiên bản là gì?

### 1. Quản lý phiên bản (Version control) là gì?
Quản lý phiên bản là một hệ thống lưu trữ, quản lý các thay đổi của một tệp tin hay tập hợp các tệp tin theo thời gian. Nhờ đó bạn có thể dễ dàng quay lại một phiên bản xác định nào đó su này.
VD: git, rcs,...
### 2. Sơ lược về git.
Được phát triển bởi cộng đồng linux dựa trên các đặc tính của [BitKeeper](https://www.bitkeeper.org/) với các đặc tính mới sau:

* Nhanh
* Thiết kế đơn giản
* Phân tán toàn diện
* Hô trợ tốt cho phát triển phi tuyến
* Hỗ trợ tốt cho các hệ thống phần mềm lớn như linux

### 3. Căn bản về git.
* Phần lớn thao tác của git diễn ra cục bộ
* Git mang tính toàn vẹn
* Git chỉ thêm mới dữ liệu
* Ba trạng thái của git (Commited, Modified, Staged)
Commited: Có nghĩa là bạn đã commit và dữ liệu của bạn đã được lưu trữ an toàn trong hệ thống cơ sở dữ liệu của git.
Modified: Có nghĩa là tệp tin của bạn đã thay đổi nhưng chưa được commit vào cơ sở dữ liệu.
Stagged: Bạn đã đánh dấu sẽ commit phiên bản hiện tại của tệp tin đã thay đổi trong lần commit sắp tới.
