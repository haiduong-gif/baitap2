<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Đăng ký</title>
<style>
    body {font-family: Arial;}
    .box {
        width: 420px;
        margin: 30px auto;
        border: 1px solid #ccc;
        padding: 15px;
    }
    h3 {text-align: center;}
    .row {
        display: flex;
        margin: 8px 0;
        align-items: center;
    }
    .row label {
        width: 140px;
    }
    input, select, textarea {
        flex: 1;
        padding: 5px;
    }
    .btn {
        text-align: center;
        margin-top: 10px;
    }
</style>
</head>

<body>

<div class="box">
<h3>ĐĂNG KÝ THÔNG TIN CÁ NHÂN</h3>

<div class="row">
<label>Tài khoản</label>
<input type="text">
</div>

<div class="row">
<label>Mật khẩu</label>
<input type="password">
</div>

<div class="row">
<label>Nhập lại</label>
<input type="password">
</div>

<div class="row">
<label>Email</label>
<input type="text">
</div>

<div class="row">
<label>Họ tên</label>
<input type="text">
</div>

<div class="row">
<label>Giới tính</label>
<input type="radio" name="gt"> Nam
<input type="radio" name="gt"> Nữ
</div>

<div class="row">
<label>Quê quán</label>
<select>
<option>Cần Thơ</option>
<option>Hà Nội</option>
<option>TP.HCM</option>
</select>
</div>

<div class="row">
<label>Sở thích</label>
<input type="checkbox"> Điện ảnh
<input type="checkbox"> Âm nhạc
<input type="checkbox"> Thể thao
</div>

<div class="row">
<label>Ghi chú</label>
<textarea></textarea>
</div>

<div class="btn">
<button>Lưu</button>
<button type="reset">Nhập lại</button>
</div>

</div>

</body>
</html>
