# Filter sale 1K gần bạn

## Tại sao lại có cái này?

Đôi khi bạn sẽ nhận được (hoặc săn được) voucher freeship đơn 0đ của shopee (10k hoặc 25k), và phí ship chỉ rẻ nhất khi bạn mua những sản phẩm trong <ins>**cùng tỉnh thành**</ins> hoặc <ins>**từ nước ngoài**</ins>, vậy nên script này ra đời để lọc ra các sản phẩm đó để lựa cho nhanh, đỡ mất thời gian lướt rồi coi phí ship 😂

## Không cần đăng nhập!

## Hướng dẫn sử dụng

1. Truy cập trang Flash sale: https://shopee.vn/flash_sale
2. Click chọn khung giờ và chọn mục "Đồng giá 1k" (Hoặc bất kỳ mục nào bạn muốn lọc 😂 nó chỉ khác nhau cái `categoryId` và `promotionId` thui)
3. Nhìn trên thanh địa chỉ sẽ có dạng `https://shopee.vn/flash_sale?categoryId=12&promotionId=2039645794`, hãy copy `categoryId` và `promotionId`
4. Tìm tên tỉnh thành của bạn theo danh sách bên dưới cùng, copy đúng kể cả dấu chấm phẩy nhé! Đây sẽ là `filterLocation`
5. Quay lại trang web shopee bấm F12 và mở Console
6. Copy và Paste script vào Console, khoan Enter vội, hãy thay lại `categoryId`, `promotionId` và `filterLocation`
7. Chờ tầm 3-5s để nó load
8. Paste dòng này trực tiếp vào Console: `copy(itemInfo.join("\n\n"))`
9. Mở notepad lên và Paste thành quả
10. Nếu paste bước 9 không ra gì thì chắc không có sale nào rồi, bạn thử lại với khung giờ khác xem sao nhé 😂

## Danh sách tỉnh thành

- **TỪ NƯỚC NGOÀI**: để trống `filterLocation = '';`
- An Giang
- Bà Rịa - Vũng Tàu
- Bình Dương
- Bình Phước
- Bình Thuận
- Bình Định
- Bạc Liêu
- Bắc Giang
- Bắc Kạn
- Bắc Ninh
- Bến Tre
- Cao Bằng
- Cà Mau
- Cần Thơ
- Gia Lai
- Hà Giang
- Hà Nam
- Hà Nội
- Hà Tĩnh
- Hòa Bình
- Hưng Yên
- Hải Dương
- Hải Phòng
- Hậu Giang
- Khánh Hòa
- Kiên Giang
- Kon Tum
- Lai Châu
- Long An
- Lào Cai
- Lâm Đồng
- Lạng Sơn
- Nam Định
- Nghệ An
- Ninh Bình
- Ninh Thuận
- Phú Thọ
- Phú Yên
- Quảng Bình
- Quảng Nam
- Quảng Ngãi
- Quảng Ninh
- Quảng Trị
- Sóc Trăng
- Sơn La
- TP. Hồ Chí Minh
- Thanh Hóa
- Thái Bình
- Thái Nguyên
- Thừa Thiên Huế
- Tiền Giang
- Trà Vinh
- Tuyên Quang
- Tây Ninh
- Vĩnh Long
- Vĩnh Phúc
- Yên Bái
- Điện Biên
- Đà Nẵng
- Đắk Lắk
- Đắk Nông
- Đồng Nai
- Đồng Tháp
