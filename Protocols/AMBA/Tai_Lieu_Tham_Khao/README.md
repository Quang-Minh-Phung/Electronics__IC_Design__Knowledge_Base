## Tài Liệu Tham Khảo Chính Thức Từ ARM
Dưới đây là lộ trình tự học các giao thức AMBA (từ cơ bản đến nâng cao) mà Minh Ú đề xuất, giúp hiểu rõ cấu trúc và vai trò của từng loại bus trong SoC.
Các bạn có thể tham khảo thêm ở https://developer.arm.com/documentation

### 1. Bus nền tảng
APB → ASB → AHB

### 2. Bus hiệu năng cao
AXI

### 3. Bus hỗ trợ cache coherency
ACE → CHI

### 4. Bus phục vụ Debug & Trace
ATB

### 5. Bus chuyên biệt
- **LPI**: điều khiển Clock & Power states.
- **GFB**: điều khiển Embedded Flash.
- **CXS**: kết nối với PCIe / interconnect mở rộng.
- **LTI, DTI**: quản lý bộ nhớ và giao tiếp liên kết hệ thống.
