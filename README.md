# 🤖 Maze Solving with BFS & DFS

## 📌 Giới thiệu
Dự án này mô phỏng bài toán tìm đường trong mê cung (Maze Solving) bằng hai thuật toán cơ bản trong Trí tuệ nhân tạo:

- BFS (Breadth-First Search) – Tìm kiếm theo chiều rộng  
- DFS (Depth-First Search) – Tìm kiếm theo chiều sâu  

Robot sẽ tìm đường từ điểm bắt đầu `S` đến điểm đích `G` trên một bản đồ mê cung dạng ma trận 2D.

---

## 🎯 Mục tiêu
- Hiểu cách hoạt động của BFS và DFS  
- So sánh hiệu năng giữa hai thuật toán  
- Quan sát đường đi và số lượng node đã duyệt  
- Phân tích ưu/nhược điểm của từng thuật toán  

---

## 🗂️ Cấu trúc thư mục
- maps/
- maze_basic.py: Lưu bản đồ mê cung đơn giản (dạng ma trận 2D)
- maze_hard.py: Lưu bản đồ mê cung nâng cao, độ khó cao hơn

- src/
- bfs_solver.py: Triển khai thuật toán BFS (tìm đường theo chiều rộng)
- dfs_solver.py: Triển khai thuật toán DFS (tìm đường theo chiều sâu)
- core_logic.py: Các hàm tiện ích: xử lý tọa độ, hiển thị mê cung
- main.py:  Điểm bắt đầu chương trình, dùng để chạy và test
- README.md


---

## ⚙️ Cách chạy chương trình
 Mở terminal tại thư mục gốc chạy, mở Terminal và gõ lệnh:
   python src/main.py
