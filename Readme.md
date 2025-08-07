# Caro AI - Minimax + Pygame

Đây là dự án trò chơi Caro (Gomoku) được phát triển bằng Python sử dụng thư viện **Pygame** cho giao diện và **thuật toán Minimax kết hợp Alpha-Beta Pruning** cho trí tuệ nhân tạo (AI).

---

## 🚀 Tính năng

- Người chơi vs Người chơi
- Người chơi vs Máy (AI)
- Bàn cờ tùy chỉnh (mặc định 15x15)
- Giao diện đơn giản, dễ sử dụng bằng Pygame
- AI sử dụng Minimax + Cắt tỉa Alpha-Beta để tìm nước đi tối ưu

---

## 🧠 Thuật toán AI

AI sử dụng thuật toán **Minimax**, một thuật toán tìm kiếm trong cây trò chơi, được tối ưu bằng **Alpha-Beta Pruning** để cắt bỏ các nhánh không cần thiết. Trạng thái bàn cờ được đánh giá dựa trên số lượng quân liên tiếp và khả năng tạo thế thắng.

---

## 🖥️ Hướng dẫn chạy

### 1. Cài đặt thư viện cần thiết:
```bash
pip install -r requirements.txt
d