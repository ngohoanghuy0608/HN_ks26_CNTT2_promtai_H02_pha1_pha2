# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 05
- **Họ tên:Ngô Hoàng Huy**
- **Lớp:CNTT2**
- **Link repository Pha2:https://github.com/ngohoanghuy0608/HN_ks26_CNTT2_promtai_H02_pha1_pha2/blob/main/bai_lam_pha_2.md**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):ChatGPT**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé xem phim ra JSON

**KET QUA AI**

```text
[
  {
    "loai_ve": "P2D",
    "ngay_chieu": "2026-12-24",
    "ve_nguoi_lon": 2,
    "ve_tre_em": 1,
    "loai_ghe": "thuong",
    "ghi_chu": null
  },
  {
    "loai_ve": "P3D",
    "ngay_chieu": "2027-01-01",
    "ve_nguoi_lon": 3,
    "ve_tre_em": 0,
    "loai_ghe": null,
    "ghi_chu": "1 người hay chóng mặt, cần ngồi gần lối ra"
  },
  {
    "loai_ve": "GOLD",
    "ngay_chieu": "2026-12-25",
    "ve_nguoi_lon": 4,
    "ve_tre_em": 0,
    "loai_ghe": "doi",
    "ghi_chu": "1 bạn đi xe lăn"
  }
]
```

**Link trò chuyện:https://chatgpt.com/share/6b079da6-5cc8-83ec-8f14-bbdda120ac80**

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
1. Tiền người lớn

5 × 130.000 = 650.000 đồng

2. Tiền trẻ em
- Trẻ dưới 1 m (1 bé): Miễn phí = 0 đồng.
- Trẻ từ 1 m đến 1,3 m (2 bé):
2 × (130.000 × 70%) = 2 × 91.000 = 182.000 đồng.

3. Tiền nhóm từ 5 người trở lên

Tiền vé trước giảm:

650.000 + 182.000 = 832.000 đồng.

Tiền vé sau giảm 10%:

832.000 × 90% = 748.800 đồng.

4. Tiền combo bắp nước

3 × 75.000 = 225.000 đồng.

Tổng tiền:

748.800 + 225.000 = 973.800 đồng.

[RESULT: 973.800 đồng]
```

**Link trò chuyện:https://chatgpt.com/share/6b079e44-6004-83ec-9e4a-768db52cafd4**

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
Dưới đây là kết quả thực hiện bài tập theo đúng 3 phần:
a) Kết quả JSON của Trạm 1

{
  "loai_su_co": "loi_ky_thuat",
  "so_khach": 4,
  "so_suat_bi_loi": 2,
  "tom_tat": "Gia đình 4 người xem 2 suất phim tại phòng 3, cả hai suất đều bị mất tiếng hơn 15 phút."
}



b) Kiểm tra JSON đầu ra
1. Kiểm tra đủ 4 trường dữ liệu:
- loai_su_co: Có.
- so_khach: Có.
- so_suat_bi_loi: Có.
- tom_tat: Có.
2. Kiểm tra tính chính xác:
- Loại sự cố: loi_ky_thuat vì phim bị mất tiếng.
- Số khách: 4 người.
- Số suất bị lỗi: 2 suất.
- Tóm tắt: Đúng nội dung email, không quá 20 từ.
Tính mức đền bù:
- 80.000 × 4 khách × 2 suất = 640.000 đồng.
- Vì tổng tiền trên 500.000 đồng nên phải được Quản lý rạp duyệt trước khi gửi khách.
c) Email phản hồi khách hàng (Trạm 2)
Chúng tôi xin hoàn lại quý khách khoản tiền 640.000 đồng (Sáu trăm bốn mươi nghìn đồng) cho 4 khách hàng trong 2 suất chiếu bị lỗi âm thanh.

Rạp rất xin lỗi gia đình vì sự cố mất tiếng đã làm ảnh hưởng đến trải nghiệm xem phim. Chúng tôi sẽ kiểm tra lại hệ thống âm thanh tại phòng chiếu số 3 để tránh tình trạng tương tự xảy ra.

Khoản đền bù trên cần được Quản lý rạp phê duyệt trước khi thực hiện. Sau khi có kết quả, chúng tôi sẽ liên hệ và thông báo đến quý khách.

Cảm ơn quý khách đã phản hồi và thông cảm cho rạp. Rất mong tiếp tục nhận được sự ủng hộ của gia đình trong thời gian tới.

Trân trọng,

Bộ phận Chăm sóc khách hàng – Rạp phim Ánh Dương




Lưu ý: Email trên chưa được gửi cho khách hàng; cần chờ Quản lý rạp phê duyệt khoản đền bù 640.000 đồng.
```

**Link trò chuyện:https://chatgpt.com/share/6b079f92-69a4-83ec-b25f-bafaf41efabb**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Tiêu chí	Điểm	Minh chứng	Đề xuất sửa
Đúng thông tin (50%)	0/5	Báo giá vé 2D là 80.000 đồng, sai so với giá chuẩn 90.000 đồng. Chính sách hoàn 50% khi huỷ trước 2 tiếng cũng sai vì dưới 3 giờ không được hoàn tiền.	Thông báo chính xác giá vé 90.000 đồng/vé và chính sách huỷ dưới 3 giờ không được hoàn tiền.
Đầy đủ (30%)	1/3	Đã trả lời cả hai câu hỏi nhưng chưa mời khách cung cấp ngày chiếu, suất chiếu và số lượng vé để đặt chỗ.	Bổ sung lời mời khách cung cấp ngày chiếu, suất chiếu và số vé.
Giọng điệu (20%)	0,5/2	Sử dụng từ ngữ suồng sã như “rẻ xỉu”, “nha anh”, chưa thể hiện sự chuyên nghiệp.	Sử dụng cách xưng hô lịch sự, thân thiện và chuyên nghiệp hơn.
Tổng điểm	1,5/10	Nhân viên cung cấp sai thông tin giá vé và chính sách hoàn tiền.	Cần kiểm tra thông tin trước khi tư vấn và cải thiện cách giao tiếp với khách hàng.
```

**Link trò chuyện:https://chatgpt.com/share/6b079fc8-feb8-83ec-84d2-599b928b3102**
