# Trang chúc mừng sinh nhật tuổi 23

Trang dành cho một bạn nam 23 tuổi, tông xanh navy và vàng. Có bánh kem với nến số 23, thao tác thổi nến, pháo giấy, phong bì lời chúc, nhạc sinh nhật và phần cá nhân hóa.

Mã HTML, CSS và JavaScript chạy trực tiếp. Không cần cài phần mềm, không cần npm hay máy chủ riêng.

## Đưa lên GitHub Pages miễn phí

1. Giải nén `sinh-nhat23-github.zip`.
2. Đăng nhập GitHub và tạo repository tên `sinh-nhat23`. Chọn **Public**. Có thể đánh dấu **Add a README file** để có sẵn nhánh `main`.
3. Trong repository, chọn **Add file → Upload files**. Nếu repository đang trống, chọn liên kết **uploading an existing file**.
4. Kéo các tệp vừa giải nén và thư mục `assets` vào phần tải lên. `index.html` phải nằm ngay ở ngoài cùng của repository, cùng cấp với thư mục `assets`. Không tải nguyên tệp ZIP lên và không đặt tất cả trong một thư mục con.
5. Bấm **Commit changes** để lưu.
6. Mở **Settings → Pages**. Ở **Source**, chọn **Deploy from a branch**.
7. Chọn nhánh **main**, thư mục **/(root)** rồi bấm **Save**.
8. Khi triển khai xong, trở lại **Settings → Pages** và bấm **Visit site** để mở đường dẫn thực tế.

Địa chỉ mặc định có dạng `https://TEN_TAI_KHOAN.github.io/sinh-nhat23/`. Thay `TEN_TAI_KHOAN` bằng tên tài khoản GitHub thật. Địa chỉ này là tên miền phụ miễn phí do GitHub cấp và không có `chatgpt.site`.

Nếu nhánh chính của repository có tên khác `main`, chọn đúng nhánh chứa các tệp vừa tải lên. GitHub có thể cần tới 10 phút để xuất bản thay đổi.

## Đổi tên và lời chúc

Mở trang web và bấm **Sửa thiệp**. Điền tên người nhận, tuổi, người gửi và lời chúc. Bấm **Sao chép liên kết** để lấy đường dẫn có nội dung đã cá nhân hóa. Bấm **Lưu lời chúc** chỉ lưu bản tùy chỉnh trên thiết bị đang dùng; khi gửi cho người khác, hãy gửi liên kết đã sao chép.

Muốn đổi nội dung mặc định cho tất cả người xem, sửa các giá trị `DEFAULT_MESSAGE`, `DEFAULT_SENDER` và nội dung HTML trong `index.html`, sau đó lưu lên GitHub.

Các nội dung cá nhân hóa trong liên kết nằm trong phần truy vấn URL. Dùng lời chúc phù hợp để chia sẻ công khai.

## Mở thử và thao tác

- Có thể mở trực tiếp `index.html` để xem. Giữ thư mục `assets` cạnh tệp này để phông chữ tải đúng.
- Bấm **Bật nhạc** để bắt đầu nhạc; nhạc cần thao tác của người dùng.
- Bấm **Ước một điều & thổi nến**, rồi xác nhận thổi nến trong hộp thoại.
- Bấm **Mở lời chúc** để đọc thư.
- Chỉ chia sẻ đường dẫn sau khi đã đăng lên GitHub Pages. Đường dẫn tệp trên máy tính không mở được trên máy người khác.

## Các tệp chính

| Tệp | Chức năng |
| --- | --- |
| `index.html` | Toàn bộ giao diện và tương tác |
| `assets/serif.woff` | Phông tiêu đề |
| `assets/sans.woff` | Phông nội dung |
| `assets/FONT-LICENSE.txt` | Giấy phép phông DejaVu |
| `README.md` | Hướng dẫn sử dụng và xuất bản |

Phông chữ DejaVu được đóng gói kèm giấy phép. Giữ tệp giấy phép khi chia sẻ mã nguồn.

## Tài liệu GitHub chính thức

- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
