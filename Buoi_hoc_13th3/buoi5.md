1 Tìm hiểu về các giá trị của thuộc tính display
1.1 Thuôc tính block

- Thẻ block chiếm trọn 1 dòng bỏ qua việc nd dài bn
- Thẻ block không chiếm cùng hàng nhau được mặc cho chiều rộng
  1,2 inline
- Thẻ inline chỉ chiếm chiều rộng đúng bằng nội dung của nó.
- Thẻ inline không thể thay đổi chiều rộng, chiều cao được.
  1.3 inline-block : vừa có thể thay đổi chiều rộng chiều cao.

  1.4 flex

- Bộ công cụ cho phép developer dàn layout (giao diện), căn chỉnh vị trí của các phần tử trong html
- display: flex cho thẻ cha
- justify-content: điều khiển phần tử theo trục chính
- các giá trị của justify-content
  start: Các phần tử con sẽ nằm bên tay phải.
  end: Các phần tử con sẽ nằm về bên tay phải
- align-items: điều khiển phần tử theo trục phụ.

* baseline : cho các nội dung thẳng hàng

- flex-direction: thay đổi chiều trục chính trục phụ
- align-self phần tử con tự thay đổi vị trí không tuân theo thẻ cha.
- align-content: Căn chỉnh vị trí các thẻ theo hàng (wrap)
- flex-wrap: xuống dòng khi chiều rộng không đủ để đảm bảo chiều rộng mong muốn.
- align-content: Căn chỉnh khoảng cách các thẻ theo hàng.
- flex-basis : Xác định độ dài thẻ con theo chiều trục chính
- flew-grow: Cho phép các phần tử tăng width hoặc height để chiếm hết khoảng trống còn lại của thẻ cha( Giá trị chiếm được sẽ chia theo phần)
