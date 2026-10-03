<p align="center">
	<a href="https://fb.com/groups/volamquan">
		<img width="200" height="200" margin-right="100%" src="https://github.com/jxoffline/jx1linux/raw/main/_/jxoff1.jpg?raw=true">
	</a>
</p>
<p  align="center">Tham gia thảo luận tại <a href="https://fb.com/groups/volamquan">https://fb.com/groups/volamquan</a></p>
<p align="center">
	<a href="https://fb.com/groups/volamquan">
		<img src="https://raw.githubusercontent.com/jxoffline/jx1linux/main/_/love.svg" />
	</a>
	<a href="https://github.com/jxoffline/jx1linux/releases">
 		<img src="https://img.shields.io/badge/download-latest-brightgreen.svg" alt="download">
	</a>
	<a href="https://img.shields.io/badge/platform-win32,win64-cyan">
 		<img src="https://img.shields.io/badge/platform-win32,win64-cyan" alt="platform, system_requirements">
	</a>
	<a href="https://img.shields.io/badge/license-GNU-yellow">
 		<img src="https://img.shields.io/badge/license-GNU-yellow" alt="license">
	</a>
</p>

# Võ lâm Offline

JXLinux 8.x Offline (Võ lâm 1)

Các mã nguồn scripts được chỉnh sửa và phát triển bởi cộng đồng đam mê tìm hiểu kỹ thuật phát triển game hay còn được gọi là Hội quán võ lâm. Các thành viên được lựa chọn từ các bạn đã có đóng góp tích cực trong lĩnh vực phát triển trò chơi, có thể là coder, modder hoặc designer.

Trong quá trình tìm hiểu, nhóm có tải và tham khảo các nguồn tài nguyên trên các diễn đàn, blog và mạng xã hội từ internet không tránh khỏi các sai sót các vấn đề liên quan đến bản quyền. Nếu bạn thấy có vấn đề gì, hãy liên hệ với chúng tôi để chúng tôi có thể xóa hoặc sửa chữa.

Official Github: https://github.com/jxoffline/jx1linux/

## 1. 🚀 Thông tin cơ bản

Tên mã: **JxOffline 1** (tên gọi bởi cộng đồng `JXLinux`)

Tiếng Trung: **剑侠情缘**

Tiếng Việt: **Võ lâm truyền kỳ 1 - VLTK Offline**

Phiên bản: **8.x**

### Cấu trúc thư mục

- **client**: Thư mục chứa mã nguồn scripts và các tập tin cần thiết chạy game client.
- **server**
  - **jxser**: Thư mục chứa scripts và các tập tin cần thiết chạy game server trên nền **Centos**.
- **requirements.txt**: yêu cầu cấu hình tối thiểu cho phần cứng cũng như phần mềm để vận hành hệ thống game.
- **revision.log**: ghi chú các thay đổi qua từng phiên bản.

## 2. ✨Hướng dẫn đóng góp

### 2.1 Quy ước đặt tên nhánh

Khi đặt tên nhánh cần tuân theo quy ước như sau:

- Tên nhánh và tên PR được viết thường không dấu, cách nhau bởi dấu chấm (.) và có tiếp đầu ngữ. Ví dụ: **script.them-kim-ma-lenh-khi-danh-quai-9x**. Trong đó:
  - **script**: là tiếp đầu ngữ
  - **them-kim-ma-lenh**: là tên ngắn gọn của nhánh hoặc PR phản ánh được nội dung của phần chỉnh sửa

- Tiếp đầu ngữ được quy ước cụ thể như sau:
  - **doc**: chỉnh sửa bao gồm các ghi chú, tài liệu hướng dẫn.
  - **bin**: chỉnh sửa bao gồm các công cụ hỗ trợ, các tập tin nhị phân trong client, server.
  - **script**: chỉnh sửa bao gồm các tập tin scripts và tập tin cấu hình ini, txt.
  - **feat**: (viết tắt của feature) dùng khi bạn muốn đăng lên một tính năng lớn, trong nhánh gồm nhiều thay đổi về `script`, có khi kèm cả các tài liệu `doc`.

### 2.2 [Các bước thực hiện](./CONTRIBUTING.md)

Xem chi tiết tại [ĐÂY](./CONTRIBUTING.md)

## 3. 🕹Hướng dẫn cài đặt

### Các bước cài đặt

- **Bước 1**: Cài đặt trò chơi phiên bản gốc, sau đó mở sẵn thư mục cài đặt lên chuẩn bị cho Bước 4
  - **data**
  - **music**

- **Bước 2**: Tải máy chủ ảo VMWare **WinXP** và **CentOS** `server.7z`.
  
  Chọn một trong các nhà cung cấp dịch vụ lưu trữ bên dưới:
  - **Mediafire**: [Tải về](https://www.mediafire.com/file/3i9biis3j27urzq/server.7z/file)
  - **Mega**: [Tải về](https://mega.nz/file/BJZHjQLC#XRYZVoqiCLfNqP-eLmzeZpWClAdY0Cp7WbzA2fo4zZ4)

- **Bước 3**: Tải client và server mới nhất từ Github.
  
  GitHub sẽ nén cả client và server mới nhất vào tập tin `jx1linux-main.tar.gz`. Để tải tập tin này bấm vào link dưới đây
  
  https://github.com/jxoffline/jx1linux/archive/refs/heads/main.tar.gz
  
- **Bước 4**: Cài đặt
  - Giải nén `jx1linux-main.tar.gz` vào nơi bạn muốn lưu trữ hệ thống game
  - Giải nén các máy chủ ảo `server.7z` vào thư mục server
  - Dữ liệu gốc gồm 2 phần là `data` và `music`:
    - **data**: Copy thư mục `data` từ Bước 1 dán đè lên thư mục `data` có sẵn trong `client`
    - **music**: Copy thư mục `music` từ Bước 1 chép đè vào thư mục music có sẵn trong `client`

- **Bước 5**: Triển khai
  - Vận hành máy chủ: Mở thư mục `server` chạy lần lượt các máy ảo
    - `server\CentOS\CentOS16-EuroFun.vmx`
    - `server\Win\JXWindows-EuroFun.vmx`
  - Cập nhật jxser: Sử dụng WinSCP kết nối vào máy chủ CentOS
  - Khởi động các dịch vụ trên máy chủ CentOS

**Video hướng dẫn**: https://youtu.be/xrgB5tpAHNQ?si=XptYZwgmkFXR-q-1

**FAQ**: https://fb.com/groups/volamquan/posts/997527467623112/

## 4. ☣Công cụ hỗ trợ phát triển

### 4.1 JXStudio 2012

Công cụ đa dụng hỗ trợ biên tập Lua scripts hiển thị tiếng Việt TCVN3, chỉnh sửa nhanh tài khoản, v.v...

- **Mega**: [Tải về](https://mega.nz/file/8VZhWZ6K#COZqGMq5ayWQX-9JtB5VTR94wS6V-gcJn8z0BclmqC4)
- **Mediafire**: [Tải về](https://www.mediafire.com/file/yfhlwn0wkhkgkzt/JxStudio_2012.7z/file)

### 4.2 JXLuaEditor 1.0

Công cụ hỗ trợ biên tập Lua scripts hiển thị tiếng Việt TCVN3, không phá vỡ cấu trúc chữ gốc tiếng Trung.

- **Mega**: [Tải về](https://mega.nz/file/4RJEVIzY#LtY9XKpUJwOm7-sVmU1qtLZmT1VTmtw--hmP5-NyrlY)
- **Mediafire**: [Tải về](https://www.mediafire.com/file/6u0x9mlkk0vz9j1/JxLuaEditor-v1.0.7z/file)

### 4.3 WinSCP

Công cụ chép scripts và các tập tin khác lên game server.

- **Mega**: [Tải về](https://mega.nz/file/II5wFZYT#6XCyrcJHlRrSHQKQQ_dG12sIef6-0rA9fySFMXpsRZU)
- **Mediafire**: [Tải về](https://www.mediafire.com/file/kbyox8j2hfq2p5r/WinSCP.7z/file)

---

**Giấy phép**: GNU General Public License v3.0
