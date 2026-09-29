<div align="center">

# Awesome Kling 4.0 Prompts — Hướng dẫn tiếng Việt

52 prompt video nguyên bản, sẵn sàng cho quy trình sản xuất phim, quảng cáo, UGC, hội thoại, VFX, hoạt hình, ẩm thực, du lịch, giáo dục và mạng xã hội.

[English](README.md) · **Tiếng Việt** · [Đủ 15 ngôn ngữ](docs/LANGUAGES.md)

[Danh mục](prompts/README.md) · [Phương pháp đầy đủ](docs/PROMPT-GUIDE.md) · [Âm thanh đa ngôn ngữ](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **Trạng thái mô hình — 29-09-2026:** Kling 4.0 Flash đã mở quyền truy cập sớm từ ngày 28 tháng 9 cho người đăng ký Ultra theo năm. Theo [thông báo chính thức của Kling AI](https://sg.linkedin.com/company/kling-ai-api), Kling 4.0 bản đầy đủ và quyền truy cập API dự kiến ra mắt trong tháng 10 năm 2026, chưa có ngày cụ thể. Khả năng tạo một lượt video dài tối đa **30 giây** được công bố cho bản đầy đủ; chưa xác nhận đó là giới hạn hiện có của Flash. Các prompt hiện tại dài 5–15 giây.

## Tính năng mới và tình trạng Kling 4.0

Theo [thông báo chính thức của Kling AI trên X](https://x.com/Kling_ai/status/2104596718067257458), Flash đã mở quyền truy cập sớm cho người đăng ký Ultra theo năm; bản 4.0 đầy đủ và API dự kiến ra mắt trong tháng 10 năm 2026. Bản đầy đủ được công bố hỗ trợ tối đa 30 giây cho mỗi lần tạo, 10 khung hình khóa, 15 tham chiếu đa phương thức, đầu ra đến 4K/10-bit HDR, âm thanh stereo và nhiều ngôn ngữ, giọng địa phương hơn. **Đây không phải giới hạn đã xác minh cho Flash hiện tại.** 52 prompt sẵn có dùng mốc thời gian 5–15 giây. Các trang FLAQ.AI cho 4.0 [văn bản thành video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) và [ảnh thành video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) vẫn ghi “Coming Soon”, chưa phải API 4.0 đang hoạt động.

## Video và prompt được chia sẻ trên X

**Kiểm tra ngày 29-09-2026.** [Video giới thiệu chính thức](https://x.com/Kling_ai/status/2104596718067257458) là bản dựng quảng bá cho dòng 4.0; tổng thời lượng không chứng minh Flash tạo được video dài tương ứng trong một lần. Các ví dụ sau là thử nghiệm do chính người sáng tạo mô tả, không phải benchmark chính thức hay kết quả được dự án này tái kiểm độc lập. Hãy xem video và prompt đầy đủ tại bài gốc; chúng tôi không sao chép chúng.

| Bài gốc | Cách viết prompt đáng thử |
|---|---|
| [Umesh: đuổi theo mèo ban đêm, 20 giây](https://x.com/umesh_ai/status/2104595267794460949) · [prompt gốc](https://x.com/umesh_ai/status/2104595270671724936) | Giữ một nhân vật chính, tuyến đường liên tục và một sự kiện vật lý ở mỗi địa điểm; camera theo sát không cắt cảnh. |
| [OscarAI: buổi diễn anime, 20 giây, kèm prompt](https://x.com/Artedeingenio/status/2104829034299351079) | Tác giả cho biết ở thử nghiệm đầu, chỉ dẫn ngắn và trực tiếp cho kết quả tốt hơn nhưng không được tuân thủ hoàn toàn. Thử chủ thể → thay đổi → camera → kết thúc. |
| [とすくん: thời tiết thay đổi, 15 giây](https://x.com/tokyo_Valentine/status/2104810060811833710) · [prompt gốc](https://x.com/tokyo_Valentine/status/2104810064750239987) | Chỉ dùng bảng nhân vật để khóa ngoại hình và trang phục; định thời điểm đổi thời tiết, ánh sáng và diễn xuất riêng. |
| [Alexandra Dekimpe: thử nghiệm quy trình sản xuất](https://x.com/HadesDesign/status/2104878440889417957) | Viết các vi cử chỉ có thể nhìn thấy thay vì cảm xúc trừu tượng; dùng “chỉ sau khi” để khóa nhân quả; nêu lời thoại chính xác hoặc yêu cầu im lặng. Đây là quan sát cá nhân. |
| [Aswin Aji Raj: UGC tiếng Hindi, 20 giây](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | Prompt đầy đủ chưa được công bố. Xác định người nói và câu thoại chính xác; kiểm tra phát âm, khẩu hình và tuyên bố về sản phẩm. |
| [@plasm0: so sánh 3.0/Flash cùng prompt](https://x.com/plasm0/status/2104597949485629557) | Giữ nguyên prompt và tham chiếu khi thử A/B, ghi lại thiết lập. Một cặp video không phải benchmark chính thức. |

**Bài tập dọc 15 giây mới viết cho dự án, chưa được thử nghiệm** (không tính vào 52 công thức; không sao chép văn bản trên X):

~~~text
[CHỦ THỂ/THAM CHIẾU] Một đèn xe đạp sạc được, không thương hiệu, vỏ màu than chì mờ và chỉ một công tắc màu hổ phách. Nếu có ảnh, chỉ dùng để khóa hình dáng đèn. Cả video chỉ có một đèn.
[CẢNH/CAMERA] Tiệm sửa xe đạp yên tĩnh lúc chạng vạng. Một cú máy cận liên tục từ hai tay thợ sửa đến đèn rồi ghi-đông. Ánh sáng tự nhiên từ cửa sổ; không cắt hoặc dịch chuyển tức thì.
[0–4 giây] Đặt đèn chưa bật cạnh ghi-đông; cho thấy cả hai tay và giá gắn.
[4–8 giây] Gài đèn vào giá. Chỉ sau tiếng “cạch” xác nhận đã gắn chắc, ngón cái mới bấm công tắc màu hổ phách.
[8–12 giây] Đèn bật đúng một lần, chiếu sáng bánh trước và một vùng sàn nhỏ. Camera trượt nhẹ sang bên để thấy luồng sáng.
[12–15 giây] Người thợ buông ghi-đông; đèn vẫn cố định. Giữ khung hình cuối ổn định.
[ÂM THANH/RÀNG BUỘC] Âm nền tiệm, một tiếng gài và một tiếng bấm; không lời thoại hay nhạc. Giữ hình dạng, số bàn tay, vị trí gắn và hướng sáng. Không chữ thương hiệu, đèn phụ hoặc cắt cảnh vô cớ.
~~~

Hãy thử cả chỉ dẫn ngắn lẫn bản dài có cấu trúc rõ ràng. Ghi lại chế độ, thời lượng, tham chiếu và kết quả trước khi gắn nhãn “đã thử nghiệm”. Mời đóng góp nội dung gốc qua [hướng dẫn đóng góp](CONTRIBUTING.md).

## Cấu trúc nhanh

```text
[ĐẦU RA] thời lượng, tỷ lệ, một cảnh/nhiều cảnh, phong cách hình ảnh
[LIÊN TỤC] đặc điểm cố định của nhân vật, trang phục, sản phẩm và đạo cụ
[KHÔNG GIAN] địa điểm, thời gian, ánh sáng và vị trí ban đầu
[CẢNH THEO THỜI GIAN] một hành động chính + một mục tiêu máy quay mỗi đoạn
[DIỄN XUẤT VÀ VẬT LÝ] ánh mắt, hơi thở, tiếp xúc, trọng lượng và quán tính
[ÂM THANH] người nói, ngôn ngữ, giọng, môi trường, foley và nhạc
[RÀNG BUỘC] danh tính, hướng, ánh sáng, chữ, logo và biến dạng
```

Tiếng Việt là ngôn ngữ tài liệu của dự án nhưng không nằm trong danh sách hội thoại gốc đã xác minh của Kling 3.0. Hãy thử giọng nói trên mô hình đang hoạt động hoặc thêm lồng tiếng đã kiểm duyệt trong hậu kỳ.

## Gợi ý

- [Cuộc hội ngộ đa ngôn ngữ](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [Quảng cáo đồ uống thảo mộc](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [Cuộc rượt đuổi khoa học viễn tưởng](prompts/action-and-vfx.md#1-the-glass-manta-pursuit)
- [Vòng lặp hài với ô](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

## Về FLAQ.AI

> Tính đến 29-09-2026, các trang FLAQ.AI cho 4.0 [văn bản thành video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) và [ảnh thành video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) vẫn ghi “Coming Soon”. Flash được truy cập sớm trên Kling không có nghĩa API 4.0 của FLAQ.AI đã hoạt động.

[FLAQ.AI](https://flaq.ai/) là nền tảng web và lớp API hợp nhất cho mô hình hình ảnh, video và ngôn ngữ. Hiện có các trang [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) và [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/). Dự án không tuyên bố Kling 4.0 đã có sẵn. Hãy kiểm tra thiết lập, giá và tài liệu API trực tiếp trước khi sản xuất.
