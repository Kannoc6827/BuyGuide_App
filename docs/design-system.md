# BuyGuide — Design System & Brand Colors

## 1. Định hướng thị giác

Theo bảng màu tham chiếu do chủ dự án cung cấp, BuyGuide sử dụng phong cách **natural, calm, minimal và premium**. Cảm giác tổng thể cần sạch, thân thiện, tinh tế và gợi liên tưởng đến thành phần thiên nhiên/chăm sóc da.

Không sử dụng hồng pastel làm màu chủ đạo như định hướng ban đầu. Bộ màu chính thức của dự án là năm màu dưới đây.

## 2. Bảng màu thương hiệu

| Token | Tên tham chiếu | HEX | Vai trò |
|---|---|---|---|
| `denim-blue` | Denim Blue | `#202C60` | Màu nhận diện đậm, header/footer, tiêu đề quan trọng, vùng điều hướng |
| `carolina-blue` | Carolina Blue | `#8FACCA` | Màu phụ, liên kết, vùng thông tin và điểm nhấn nhẹ |
| `beige` | Beige | `#F5F3DC` | Nền chính/phụ, khoảng nghỉ thị giác, thẻ nội dung nhẹ |
| `pistachio` | Pistachio | `#B6CF7B` | Điểm nhấn tích cực, tag, trạng thái hoặc CTA phụ |
| `fern-green` | Fern Green | `#4C7026` | Màu nhấn xanh lá, nút hành động chính, trạng thái thành công và chi tiết thương hiệu |

## 3. Vai trò màu trong giao diện

- **Nền tổng thể:** trắng ngà hoặc Beige `#F5F3DC` ở các khu vực cần tạo cảm giác ấm; dùng nền trắng cho vùng danh sách sản phẩm để hình ảnh rõ ràng.
- **Header và footer:** Denim Blue `#202C60`, chữ sáng.
- **Nút hành động chính:** Fern Green `#4C7026`, chữ trắng.
- **Nút phụ / vùng nhấn:** Pistachio `#B6CF7B`, chữ tối.
- **Liên kết và thông tin phụ:** Carolina Blue `#8FACCA`; đảm bảo độ tương phản đủ khi đặt chữ lên nền.
- **Chữ nội dung:** xanh navy đậm hoặc màu trung tính rất tối; không dùng xanh nhạt làm màu chữ nhỏ trên nền sáng.

## 4. Nguyên tắc sử dụng

1. Dùng Denim Blue và Fern Green làm hai màu nhận diện mạnh; không dùng cả hai với cường độ cao ở mọi khu vực.
2. Beige và trắng tạo không gian thoáng, tránh phủ xanh toàn bộ giao diện.
3. Pistachio dùng có tiết chế cho điểm nhấn, nhãn hoặc trạng thái; không dùng làm nền dài cho đoạn văn.
4. Carolina Blue phù hợp với nền phụ và các thành phần thông tin; kiểm tra contrast trước khi dùng cho chữ nhỏ.
5. Duy trì nhất quán màu sắc giữa website khách hàng và Admin Dashboard; Admin có thể dùng nền trung tính nhiều hơn.
6. Trạng thái lỗi/cảnh báo có thể dùng màu semantic riêng (đỏ/cam) khi cần thiết, không ép toàn bộ trạng thái vào bảng màu thương hiệu.

## 5. CSS variables tham khảo

```css
:root {
  --color-denim-blue: #202C60;
  --color-carolina-blue: #8FACCA;
  --color-beige: #F5F3DC;
  --color-pistachio: #B6CF7B;
  --color-fern-green: #4C7026;

  --color-text: #202C60;
  --color-surface: #FFFFFF;
  --color-surface-soft: #F5F3DC;
  --color-primary: #4C7026;
  --color-primary-foreground: #FFFFFF;
  --color-secondary: #8FACCA;
  --color-accent: #B6CF7B;
}
```

## 6. Responsive và accessibility

- Giữ độ tương phản chữ/nền phù hợp, đặc biệt với chữ nhỏ.
- Không chỉ dùng màu để biểu thị trạng thái; kết hợp nhãn hoặc biểu tượng.
- Nút bấm cần có hover, focus-visible, disabled và loading states.
- Màu sắc không được làm giảm khả năng đọc trên màn hình điện thoại.

## 7. Trạng thái

Bảng màu này được chốt làm **brand color direction** cho các giai đoạn UI tiếp theo. Trước khi triển khai giao diện, có thể điều chỉnh cách phân bổ màu nhưng không tự ý đổi mã màu gốc nếu chưa được chủ dự án đồng ý.
