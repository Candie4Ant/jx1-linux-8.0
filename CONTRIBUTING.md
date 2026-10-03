<p align="center">
	<a href="https://fb.com/groups/volamquan">
		<img width="200" height="200" margin-right="100%" src="https://github.com/jxoffline/jx1linux/raw/main/_/jxoff1.jpg?raw=true">
	</a>
</p>
<p  align="center">Tham gia thảo luận tại <a href="https://fb.com/groups/volamquan">https://fb.com/groups/volamquan</a></p>

[🏡 Trở về trang chính](./README.md) > Hướng dẫn đóng góp

## Hướng dẫn đóng góp

### 1. Tạo bản sao đề án với Fork

Thao tác này bạn chỉ thực hiện một lần duy nhất khi bắt đầu đóng góp.

**Bước 1**: Truy cập trang Github của Hội quán https://github.com/Candie4Ant/jx1-linux-8.0

**Bước 2**: Thực hiện fork toàn bộ đề án

Tại trang chính, bấm vào mũi tên sổ xuống bên cạnh mục Fork và chọn mục **Create a new fork**

**Bước 3**: Ở màn hình tiếp theo, bấm **Create fork**.

**Bước 4**: Chờ một chút đến khi quá trình sao chép hoàn tất.

### 2. Tạo nhánh trên bản sao fork

- **Bước 1**: Tải đề án về máy qua git clone

**Windows**
```bash
cd d:\jx
git clone <địa-chỉ-fork-git>
```

**Mac/Unix**
```bash
cd ~/jx
git clone <địa-chỉ-fork-git>
```

Trong đó, `địa-chỉ-fork-git` được lấy từ trang Github bản sao của bạn. Ví dụ:
```bash
git clone git@github.com:vodanh-x/jx1linux.git
```

Sau khi hoàn tất, bạn sẽ tìm thấy một thư mục mới tên **jx1-linux-8.0** xuất hiện trong thư mục **jx** của mình. Gõ lệnh sau để truy cập thư mục:
```bash
cd jx1-linux-8.0
```

- **Bước 2**: Tạo nhánh trên máy tính cá nhân với lệnh:
```bash
git checkout -b <tên-nhánh>
```

Xem cách đặt tên nhánh ở [README.md](./README.md#21-quy-ước-đặt-tên-nhánh). Ví dụ:
```bash
git checkout -b doc.cap-nhat-huong-dan-dong-gop
```

- **Bước 3**: Chỉnh sửa, viết script thoải mái trên máy cá nhân.

- **Bước 4**: Commit và push toàn bộ nội dung chỉnh sửa lên git server
```bash
git add .
git commit -m "ghi chú commit"
git push --set-upstream origin <tên-nhánh>
```

Commit cần phản ánh nội dung các tập tin đã chỉnh sửa. Ví dụ: `git commit -m "chore: Cập nhật hướng dẫn đóng góp"`

- **Bước 5**: Từ giao diện web Github, mở tab Pull Request (kế tab Code)

Trong màn hình hiện ra, ở góc phải sẽ có nút **Compare & pull request** màu xanh lá. Bấm vào nút này để bắt đầu tạo Pull Request.

Nút **Compare & pull request** sẽ tự động điền cho bạn nhánh làm việc.

Bên dưới ghi chú vào tóm tắt nội dung các thay đổi và bấm **Create pull request** để hoàn tất.

- **Bước 6**: Nếu có thêm thay đổi chỉnh sửa gì trên nhánh/PR này, mọi thao tác sẽ thực hiện trên nhánh đấy trong máy cá nhân theo hướng dẫn ở Bước 3-4.

---

**Cảm ơn bạn đã đóng góp!**
