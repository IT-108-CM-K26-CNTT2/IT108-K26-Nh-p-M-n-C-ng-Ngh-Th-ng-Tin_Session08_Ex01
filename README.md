## **3. Hiện trường giả**

Nam lập luận: "Dùng Word tốt hơn vì có thanh công cụ chọn font chữ, màu sắc trực quan. Markdown chỉ là văn bản thô, không thể tạo được tài liệu chuyên nghiệp".

## **4. Ràng buộc & Bẫy dữ liệu**

- **Bẫy**: Nếu tệp Word của Nam bị lỗi mạng khi tải làm mất chỉ 1 byte dữ liệu, file sẽ hỏng hoàn toàn. Hãy đối chiếu với đặc tính của Markdown trong tình huống này.

## **5. Yêu cầu đầu ra**

### **Phần 1. Phân tích:**

Chỉ ra 2 sai lầm trong tư duy của Nam về việc dùng file Word cho lưu trữ mã nguồn. Giải thích tại sao Markdown lại an toàn và nhẹ hơn.

**Sai lầm trong tư duy của Nam về việc dùng file Word : **
  
+Nghĩ Word là văn bản thuần. Word tự đổi nháy thẳng " thành nháy cong “ ”, -- thành –, tự viết hoa, đổi thụt lề, nên mã chép vào dễ hỏng, không chạy được.
+Bỏ qua quản lý phiên bản và an toàn. .docx không diff/merge được trong Git, lại có thể chứa macro và metadata ẩn.

Vì Nhẹ: văn bản thuần, chỉ vài KB.
An toàn: không macro, không đối tượng nhúng, không metadata ẩn.
Giữ nguyên mã trong khối ```, và Git diff/merge từng dòng dễ dàng.

### **Phần 2. Hoàn thiện:**

Sử dụng StackEdit để chuyển đổi một đoạn giới thiệu ngắn từ Word sang Markdown, đảm bảo file có định dạng .md.
# Welcome to my porforlio!

Hi! I'm Nguyen Thanh Phat I'm a student in PTIT-RIKKEI

# Porforlio

I have many project in github.You can get  **my git hub!** in this link [enter link description here](https://github.com/thanhphat365)
