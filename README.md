# 1C_HTML
Tuần 4
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>Đăng Nhập</title>
</head>
<body>
    <h1>Thông Tin Đăng Nhập</h1>
    <form action="https://www.google.com/" method="post" id="form-login">
        <div>
            <p>Mã Số Sinh Viên</p>
            <input type="text">
        </div>
        <div>
            <p>Mật Khẩu</p>
            <input type="text">
        </div>
        <div>
            <input type="submit" value="Đăng Nhập" />
        </div>
    </form>
    <p>Sử dụng thông tin đangư nhập do trường cấp, nếu quên mật khẩu thì nhấp vào <a href="Repass.html">đây</a></p>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>Lấy Lại Mật Khẩu</title>
</head>
<body>
    <h1>Lấy Lại Mật Khẩu</h1>
    <form action="https://www.google.com/" method="post" id="form-login">
        <div>
            <p>Mã Số Sinh Viên</p>
            <input type="text">
        </div>
        <div>
            <p>Mật Khẩu Cũ</p>
            <input type="text">
        </div>
        <div>
            <p>Mật Khẩu Mới</p>
            <input type="text">
        </div>
        <div>
            <p>Nhập Lại Mật Khẩu Mới</p>
            <input type="text">
        </div>
        <div>
            <input type="checkbox"> Lưu Thông Tin Đăng Nhập
        </div>
        <div>
            <input type="submit" value="Lưu Lại" />
        </div>
    </form>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title></title>
</head>
<body>
    <h1>Nhập Thông Tin Sinh Viên</h1>
    <form action="https://www.google.com/" method="post" id="form-login">
        <div>
            Họ Và Tên <input type="text">
        </div>
        <div>
            Mã Số Sinh Viên <input type="text">
        </div>
        <div>
            Ngày Sinh <input type="text">
        </div>
        <div>
            Chuyên Ngành <input type="checkbox">CNPM <input type="checkbox">HTTT <input type="checkbox">An Ninh Mạng
        </div>
        <div>
            Sở Thích
            <ul id="so-thich">
                <li><input type="checkbox">Viết Chương Trình</li>
                <li><input type="checkbox">Phân Tích Cơ Sở Dữ Liệu</li>
                <li><input type="checkbox">Xây Dựng Sơ Đồ Mạng Mạng</li>
            </ul>
        </div>
        <div>
            Màu sắc yêu thích <input type="button" id="color">
        </div>
        <div>
            Tên Đăng Nhập Web Trường <input type="text">
        </div>
        <div>
            Mật Khẩu Đăng Nhập Web Trường <input type="text">
        </div>
        <div>
            <input type="submit" value="Gửi Dữ Liệu Về Máy Chủ" />
        </div>
    </form>
</body>
</html>
