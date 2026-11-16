# TechZone — Giao diện sản phẩm công nghệ

## Giới thiệu

TechZone là trang giao diện tĩnh minh họa khu vực danh sách sản phẩm của một
website thương mại điện tử bán thiết bị công nghệ. Thiết kế tập trung vào thẻ
sản phẩm gọn, dễ đọc giá và thuận tiện thao tác trên điện thoại.

Đây là bài tập giao diện tham khảo phong cách trình bày của CellphoneS, không
phải website chính thức hay có liên kết với CellphoneS.

## Tham khảo thiết kế

- Website: CellphoneS
- URL: <https://cellphones.com.vn/?version=2>
- Khu vực tham khảo: danh sách sản phẩm và thẻ sản phẩm.

## Tính năng giao diện

- Hiển thị bốn sản phẩm mẫu với hình ảnh, tên, giá ưu đãi, giá gốc và nhãn giảm giá.
- Trình bày khuyến mãi ngắn gọn và có nút “Thêm vào giỏ”.
- Bố cục lưới tự điều chỉnh theo kích thước màn hình: bốn cột trên desktop,
  ba cột ở màn hình trung gian và hai cột trên điện thoại.
- Có trạng thái hover và focus để hỗ trợ thao tác chuột và bàn phím.

> Đây là bản giao diện tĩnh: nút “Thêm vào giỏ” chưa thực hiện chức năng mua hàng.
> Thông tin giá và sản phẩm chỉ dùng để minh họa.

## Công nghệ

- HTML5 ngữ nghĩa
- CSS3 (CSS Grid, Flexbox, CSS Variables và media queries)
- Không dùng JavaScript, framework, backend hoặc cơ sở dữ liệu.

## Cấu trúc thư mục

```text
ecommerce-UI-improvement/
├── README.md
├── CSS/
│   └── styles.css
└── ecommerce-UI-improvement/
    └── index.html
```

`index.html` nạp stylesheet bằng đường dẫn tương đối `../CSS/styles.css`.
Vì vậy, hãy giữ nguyên cấu trúc thư mục này hoặc cập nhật đường dẫn trong HTML
nếu bạn di chuyển một trong hai tệp.

## Cách chạy

1. Mở thư mục dự án trong File Explorer hoặc VS Code.
2. Mở `ecommerce-UI-improvement/index.html` bằng trình duyệt (nhấp đúp hoặc
   chọn **Open with**).
3. Có thể mở `index.html` trực tiếp bằng trình duyệt; không cần cài đặt gói,
   chạy máy chủ hay kết nối backend.

Ảnh sản phẩm được tải từ Unsplash nên cần Internet để hiển thị. Nếu ảnh không
tải được, kiểm tra kết nối mạng hoặc thay URL ảnh trong `index.html`.

## Các cải tiến đã thực hiện

- Tách biệt thị giác giữa giá bán và giá gốc; giá gốc được gạch ngang.
- Rút gọn thông tin ưu đãi, giới hạn số dòng để thẻ sản phẩm đồng đều.
- Thêm nhãn giảm giá và nút thao tác có vùng bấm cao tối thiểu 44px.
- Dùng bố cục responsive để danh sách dễ xem trên cả máy tính và điện thoại.
- Dùng HTML có cấu trúc rõ ràng: `header`, `main`, `section`, `article` và
  `footer`; ảnh có văn bản thay thế.

## Hỗ trợ từ AI và kiểm tra

AI được dùng để đề xuất bố cục thẻ sản phẩm, tạo bản HTML/CSS ban đầu và hỗ trợ
hoàn thiện tài liệu hướng dẫn. Các yêu cầu chính là giao diện công nghệ bằng
HTML5/CSS3 thuần, tối thiểu bốn sản phẩm, responsive và hướng dẫn chạy trang.

Đã kiểm tra trang mở được bằng trình duyệt, stylesheet được liên kết đúng trong
cấu trúc thư mục hiện tại, bốn ảnh mẫu tải được, lưới hiển thị bốn cột ở
1440px và hai cột ở 390px. Hãy tự xem lại nội dung, thử trên thiết bị/trình
duyệt của bạn và điều chỉnh trước khi nộp bài.
