# Cách đăng ký mới một tên miền trên AWS

Cách đi đến [Trang quản lý domain Route 53](./)

[Link đến trang quản lý domain](https://console.aws.amazon.com/route53/v2/home#Dashboard)

Tại form **Register domain** nhập domain mà bạn muốn đăng ký vào input và bấm vào nút **Check**

![Register domain](https://imgur.com/cMNrjeS.jpg)

Bạn sẽ được chuyển đến trang kiểm tra lại tên miền, tại đây bạn cũng sẽ thấy số tiền mà bạn phải thanh toán cho tên miền đó.

Tên miền mà bạn đã nhập trước đó cũng sẽ được thêm vào hàng đợi của giỏ hàng bên phải. Sau khi kiểm tra đã đúng tên miền bạn muốn chọn, click vào nút **Continue**.

![Register domain](https://imgur.com/bHzoMuu.jpg)

Ở bước tiếp theo, bạn cần phải nhập thông tin chủ thể của tên miền. Mặc định AWS sẽ chọn sẵn đăng ký cho bạn 1 năm sử dụng tên miền mà bạn đã chọn, bạn cũng có thể tăng thêm số năm mà bạn muốn sử dụng ở giỏ hàng bên phải. Sau đó xuống cuối trang click vào nút **Continue**.

![Register domain](https://imgur.com/bZcUx6k.jpg)

Cuối cùng, bạn được chuyển đến trang xác nhận lại thông tin chủ thể của tên miền, ở bước này bạn vẫn có thể thay đổi số năm sử dụng tên miền. AWS sẽ hỏi bạn có muốn tự động gia hạn tên miền hay không. Nếu bạn muốn tự động gia hạn tên miền bạn chọn **Enable** ở phần *Do you want to automatically renew your domain?*

Trong phần **Terms and Conditions**, bạn phải check vào *I have read and agree to the AWS Domain Name Registration Agreement* mới có thể hoàn thành đăng ký.

Sau khi check đồng ý **Terms and Conditions**, click vào nút **Complete Order** để hoàn thành.

![Register domain](https://imgur.com/nCyCodX.jpg)

Sau khi click vào nút **Complete Order**, tên miền mà bạn đăng ký được đưa vào mục **Domain > Pending requests** trên menu bên trái để đợi được xử lý đăng ký. Có thể mất đến 10 phút quá trình đăng ký mới hoàn thành hoặc cũng có thể lâu hơn. 

Tuy nhiên, việc thanh toán cho tên miền phụ thuộc vào thông tin thanh toán của bạn ở phần **Billing** có được thực hiện thành công hay không. 

Nếu thanh toán không thành công có thể là do số tiền trong tài khoản của bạn không đủ để thanh toán. Bạn trở về trang [Route 53 > Dashboard](https://console.aws.amazon.com/route53/v2/home#Dashboard) sẽ thấy có một thông báo thanh toán không thành công ở đó.

![Register domain payment failed](https://imgur.com/BZQlITj.jpg)

Sau khi thanh toán thành công bạn mới có thể sử dụng tên miền đã đăng ký. Để xem lại danh sách tên miền đã đăng ký, truy cập vào [Domain > Registered domains](https://console.aws.amazon.com/route53/home#DomainListing:)