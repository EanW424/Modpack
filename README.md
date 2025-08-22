# Tide Mod - Mod Thủy Triều cho Minecraft

Mod này thêm hiện tượng thủy triều lên và thủy triều rút vào Minecraft Java Edition với Fabric Loader.

## Tính năng

- **Thủy triều tự nhiên**: Mô phỏng hiện tượng thủy triều với chu kỳ 20 phút
- **Thay đổi mực nước**: Nước biển sẽ lên xuống theo chu kỳ thủy triều
- **Chỉ hoạt động ở Overworld**: Không ảnh hưởng đến các thế giới khác
- **Command tiện ích**: Kiểm tra thông tin thủy triều bằng lệnh `/tide`

## Cài đặt

1. Cài đặt Fabric Loader cho Minecraft 1.21.1
2. Cài đặt Fabric API
3. Tải mod này và đặt vào thư mục `mods`
4. Khởi động Minecraft

## Sử dụng

### Commands

- `/tide` - Hiển thị thông tin thủy triều hiện tại
- `/tide info` - Hiển thị thông tin chi tiết về mod
- `/tide set <level>` - Đặt mực nước thủy triều (chỉ dành cho OP)

### Thông tin thủy triều

- **Chu kỳ**: 20 phút (24000 ticks)
- **Độ cao tối đa**: +3 blocks so với mực nước biển
- **Độ cao tối thiểu**: -2 blocks so với mực nước biển
- **Các giai đoạn**: Thấp → Lên → Cao → Rút

## Cấu hình

Mod này hoạt động tự động và không cần cấu hình thêm. Thủy triều sẽ bắt đầu ngay khi bạn vào thế giới.

## Xây dựng từ mã nguồn

1. Clone repository này
2. Chạy `./gradlew build`
3. File JAR sẽ được tạo trong `build/libs/`

## Yêu cầu

- Minecraft 1.21.1
- Fabric Loader 0.15.0+
- Fabric API
- Java 17+

## Giấy phép

MIT License - Xem file LICENSE để biết thêm chi tiết.

## Đóng góp

Mọi đóng góp đều được chào đón! Hãy tạo issue hoặc pull request nếu bạn muốn cải thiện mod này.
