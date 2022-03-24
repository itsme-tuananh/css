- CSS Variable

- Vendor Prefix: Hỗ trợ sử dụng các tính năng mới và hỗ trợ các trình duyệt cũ
- Đặt thuộc tính tiêu chuẩn ở dưới các Vendor Prefix

- Support Query: CSS Statement bên trong Support Query sẽ chỉ được sử dụng khi điều kiện thỏa mãn (khi Browser hiểu được cả tên thuộc tính và giá trị của nó)
  @supports (display: grid) ... {
  .container {
  display: grid;
  ...
  }
  }

- Polyfill: JavaScript Package "mô phỏng" một số CSS Feature nhất định trong những Browser không hỗ trọ
- Cần cân nhắc vì Polyfill tác động tới Performance

- Eliminate Cross-Browser Inconsistencies: Các Browser sử dụng Default khác nhau
  => Sử dụng Reset-Library hoặc Reset Style Manually

- Chọn tên Class đúng
  - Sử dụng kebab-case
  - Đặt tên theo feature
- Block Element Modifier (BEM)

  - .BLOCK\_\_ELEMENT--MODIFIER

- "Vanilla CSS" vs CSS Framework
  - Vanilla CSS
  - Component Framework
  - Utility Framework
