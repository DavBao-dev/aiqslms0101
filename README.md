# aiqslms0101

## Cấu trúc file đề Markdown

Trong Contest, chọn **Upload Markdown**. Mỗi câu bắt đầu bằng tiêu đề `##`; câu trắc nghiệm có bốn lựa chọn `A)` đến `D)` và đáp án đúng.

```md
# Kiểm tra chương 3

## 1. Nội dung câu hỏi trắc nghiệm
Difficulty: easy
- A) Phương án thứ nhất
- B) Phương án thứ hai
- C) Phương án thứ ba
- D) Phương án thứ tư
Answer: B

## 2. Một câu trung bình
Difficulty: medium
- A) ...
- B) ...
- C) ...
- D) ...
Answer: A

## 22. Một câu khó hơn
Difficulty: hard
- A) Phương án thứ nhất
- B) Phương án thứ hai
- C) Phương án thứ ba
- D) Phương án thứ tư
Answer: C
```

File phải có đúng 25 câu: 7 câu `easy`, 10 câu `medium` và 8 câu `hard`. Khi chấm, hệ thống so sánh lựa chọn với `Answer`.

Tên đề được lấy từ tên file `.md`.