//Dòng     || Nguyên Lý || Hậu Quả 
//28–117   ||   SRP	    ||"God class" ôm quản lý CLB + thành viên + sự kiện + log + thông báo + báo cáo
//52–63	   ||   OCP	    || Chuỗi if/else theo email domain — thêm kênh mới phải sửa method
//48, 79,  ||   DIP     ||
//94, 111  ||   DIP	    || Gọi File.AppendAllText() trực tiếp — không mock được khi test
//103–113  || SRP + OCP	|| Báo cáo chỉ ra Console, muốn xuất CSV phải
//88–98	   || SRP + OCP	||CreateEvent tự gửi email cho từng thành viên — gắn chặt logic thông báo