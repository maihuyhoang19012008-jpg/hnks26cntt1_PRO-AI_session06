

# BÀI TẬP: TỐI ƯU PROMPT 
`( LOẠI BỎ NỘI DUNG THỪA )`

## Bước 1: Phân tích lỗi trong prompt cũ

**Prompt cũ:** Hãy giải thích ngắn gọn các nội dung của Feynman Prompt gia sư, Rubric chấm bài tự động.

**3 phần văn bản thừa thường xuất hiện trong câu trả lời AI khi dùng prompt này:**

Lời chào mở đầu: 
`Ví dụ: "Chào bạn! Dưới đây là giải thích..." 
"Chào bạn, mình xin giải thích như sau..."`
 Câu dẫn giải thích không cần thiết: 
`Ví dụ: "Để giúp bạn hiểu rõ hơn, mình trình bày..." 
"Trước hết cần hiểu rằng..."`
  Lời kết  Lời mời hỏi thêm: 
`Ví dụ: "Nếu có thắc mắc hãy hỏi nhé!" 
 "Chúc bạn học tốt!"`

Nguyên nhân: 
- Prompt chỉ nói "giải thích ngắn gọn" nhưng không cấm lời chào, dẫn kết và không quy định định dạng đầu ra. 
- AI mặc định tạo văn hội thoại thân thiện thay vì nội dung thuần thông tin.

## Bước 2: Prompt đã tối ưu

**Prompt mới:** Giải thích ngắn gọn về: Feynman Prompt gia sư và Rubric chấm bài tự động. Trả về dưới dạng danh sách gạch đầu dòng. 
***CẤM*** viết lời chào, câu dẫn mở đầu và lời kết. Chỉ đưa nội dung chính thôi.

## Kết quả phản hồi của AI

-   Feynman Prompt gia sư: Là kỹ thuật yêu cầu AI giải thích kiến thức theo phương pháp Feynman  dùng ngôn ngữ đơn giản, ví dụ dễ hiểu, như đang dạy cho người mới 
- Giúp nắm vững gốc rễ vấn đề thay vì học vẹt.
-   Rubric chấm bài tự động: Là bộ tiêu chí đánh giá được viết rõ ràng theo từng mục, mức điểm và yêu cầu cụ thể. 
- AI dựa vào đó để kiểm tra, nhận xét và cho điểm bài làm một cách nhất quán, khách quan và nhanh chóng.
