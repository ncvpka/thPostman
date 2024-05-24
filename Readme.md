# repoPosman_
<!-- Postman là gì?
Postman là một App Extensions, cho phép làm việc với các API, nhất là REST, giúp ích rất nhiều cho việc testing. Hỗ trợ tất cả các phương thức HTTP (GET, POST, PUT, DELETE, OPTIONS, HEAD ...) Postman cho phép lưu lại các lần sử dụng. Sử dụng cho cá nhân hoặc team lớn 
Cách sử dụng
Làm việc với request get

* Request GET được sử dụng để truy vấn thông tin được truyền vào từ URL. Điều này sẽ không làm thay đổi gì với endpoint. Chúng ta sẽ sử dụng URL bên dưới cho các ví dụ trong bài này:
https://jsonplaceholder.typicode.com/users
Trong workspace của postman:
    Thiết lập request HTTP của bạn là GET
    Trong trường URL yêu cầu, nhập vào link
    Kích nút Send
    Bạn sẽ nhìn thấy message là 200 ok
    Sẽ hiển thị kết quả 10 người dùng trong phần Body của bạn.

* Làm việc với request post
Request post khác với request get ở chố request post có thao tác dữ liệu. Bước 1: Kích dấu + để thêm mới một tab cho request mới:
Trong tab mới 
    Thiết lập request HTTP là POST
    Nhập vào link với url: https://jsonplaceholder.typicode.com/users
    Chuyển tới tab Body
Trong tab Body
    Click chọn raw
    Select JSON
    Dán phần 
        {
            "id": 11,
            "name": "Krishna Rungta",
            "username": "Bret",
            "email": "Sincere@april.biz",
            "address": {
                "street": "Kulas Light",
                "suite": "Apt. 556",
                "city": "Gwenborough",
                "zipcode": "92998-3874",
                "geo": {
                    "lat": "-37.3159",
                    "lng": "81.1496"
                }
            },
            "phone": "1-770-736-8031 x56442",
            "website": "hildegard.org",
            "company": {
                "name": "Romaguera-Crona",
                "catchPhrase": "Multi-layered client-server neural-net",
                "bs": "harness real-time e-markets"
            }
        }
    Lưu ý phải đúng định dạng json và đúng các tên trường 
Kích nút Send
    Status: 201 Created được hiển thị
    Dữ liệu Post được hiển thị trong tab Body


-->