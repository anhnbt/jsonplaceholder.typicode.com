# Kiểm thử với mock API JSONPlaceholder

Dưới đây là 10 câu query từ cơ bản đến nâng cao mà học viên có thể thực hành trong khóa học kiểm thử với mock API JSONPlaceholder:

### Cơ bản
1. **Lấy danh sách các bài viết (posts) với phân trang**
```
GET https://jsonplaceholder.typicode.com/posts?_page=1&_limit=10
```

2. **Tìm kiếm bài viết dựa trên tiêu đề**
```
GET https://jsonplaceholder.typicode.com/posts?title_like=qui
```

3. **Lấy danh sách các bình luận (comments) của một bài viết cụ thể**
```
GET https://jsonplaceholder.typicode.com/posts/1/comments
```

4. **Lấy danh sách các bài viết của một người dùng cụ thể**
```
GET https://jsonplaceholder.typicode.com/posts?userId=1
```

5. **Lấy danh sách các to-do (todos) đã hoàn thành**
```
GET https://jsonplaceholder.typicode.com/todos?completed=true
```

### Nâng cao
6. **Lấy chi tiết bài viết với các thông tin mở rộng**
```
GET https://jsonplaceholder.typicode.com/posts/1?_embed=comments&_expand=user
```

7. **Tìm kiếm các bình luận dựa trên nội dung**
```
GET https://jsonplaceholder.typicode.com/comments?body_like=quasi
```

8. **Lấy danh sách các to-do của một người dùng cụ thể với phân trang và trạng thái hoàn thành**
```
GET https://jsonplaceholder.typicode.com/todos?userId=1&completed=true&_page=1&_limit=5
```

9. **Tìm kiếm bài viết dựa trên tiêu đề và nội dung**
```
GET https://jsonplaceholder.typicode.com/posts?title_like=qui&body_like=dolores
```

10. **Lấy danh sách các bài viết của một người dùng cụ thể và được phân trang**
```
GET https://jsonplaceholder.typicode.com/posts?userId=1&_page=1&_limit=5
```

Hy vọng những câu query này sẽ giúp học viên của bạn thực hành tốt hơn trong khóa học kiểm thử với API! 🚀💻📚
