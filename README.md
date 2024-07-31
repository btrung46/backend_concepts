# internet hoạt động như thế nào 
**Một số khái niệm cần biết:**

-Internet là gì? Internet mạng lưới một mạng lưới toàn cầu gồm các máy tính được kết nối với nhau và giao tiếp thông qua một bộ giao thức được tiêu chuẩn hóa.

-địa chỉ ip là địa chỉ của các thiết bị trên internet mỗi thiết bị sẽ có 1 địa chỉ ip.

-DNS (Domain Name System) là hệ thống phân giải tên miền nó giống như danh bạ điện thoại mỗi tên miền đại diện cho 1 dịa chỉ ip

**Thông tin được truyền như thế nào trên internet**

 Khi bạn truy cập một trang web ví dụ youtube.com thì tên miền youtube.com sẽ được gửi tới máy chủ DNS để tìm địa chỉ ip của nó. Sau khi tìm được địa chỉ ip sẽ được gửi về trình duyệt và sau đó trình duyệt đi đến địa chỉ ip đó và đi đến trung tâm dữ liệu để lấy trang web mà bạn yêu cầu. Trang web này sẽ được gửi đến bạn đưới dạng nhị phân thông qua cáp quang rồi đến router sau đó là thiết bị của bạn

# http là gì???
Http (hyper text Transfer Protocol) là giao thức chịu trách nhiệm liên lạc giữa máy chủ vào máy khách

Http là không có trạng thái nghĩa là mỗi request là hoàn toàn độc lập

Https (hyper text Transfer Protocol Secure) là phiên bản bảo mật hơn của http mọi dữ liệu gửi đều được mã hóa 

# Http methods:

-GET: lấy data từ sever

-POST: gửi data đến sever 

-PUT: cập nhật data trên sever

-DELETE: xóa data ở trên sever

# http header fields

**-General:**

+Request URL

+Request Method

+Status Code

+Remote Address

+Referrer Policy

**-Response:**

+Sever

+Set-cookie

+Content Type

+Content Length

+Date 

**-Request:**

+Cookies

+Accept-xxx

+Content Type

+Content Length

+Authorization

+User Agent

+Referrer

# Http status code

1xx: Informational

2xx: Success

3xx: Redirect

4xx: client Error

5xx: Server Error

# web hosting là gì??

Web hosting là nơi lưu trữ toàn bộ trang web của bạn, nó sẽ giúp các trang web có thể truy cập được bằng internet

**các loại web hosting**

- Shared hosting: đơn giản là website của bạn sẽ được lưu trữ cùng với rất nhiều website khác, do đó chi phí bỏ ra khá là rẻ. Tuy nhiên, tài nguyên là 1 vấn đề vì website của bạn phải chia sẻ với nhiều website khác

- VPS hosting(virual private server) là máy chủ riêng ảo nhưng chia sẻ chung phần cứng vật lý với các máy chủ ảo khác, về cơ bản khi sử dụng dịch vụ này thì bạn sẽ được cung cấp X RAM, X CPU của riêng bạn không dung chung với bất cử máy chủ riêng ảo nào khác

- Dedicated Server: là máy chủ vật lý riêng của bạn 

**phân biệt web page, website, web server, search engine**

- Web page là tài liệu đơn giản được hiển thị bằng trình duyệt. Các tài liệu này thường được viết bằng html

- Website là tập hợp các web page được liên kết có chung tên miền duy nhất

- Web server là máy lưu trữ 1 hoặc nhiều trang web khác nhau.

- Search engines là trang web đặc biệt giúp người dùng tìm kiếm những trang web khác


