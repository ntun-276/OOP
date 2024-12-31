# OOP (Object-Oriented Programming)

### 1. Lớp (Class) & Đối tượng (Object)
Một mô tả chung cho các đối tượng cùng loại gọi là lớp. Lớp là mô tả tổng quát của đối tượng, đối tượng là một thể hiện cụ thể (instance) của lớp.

Cú pháp khai báo class:
```
access_modifier class ClassName {
    data_type attributeName;

    ClassName(parameters) {
        // Khởi tạo giá trị cho thuộc tính
    }

    return_type methodName(parameters) {
        // Thực hiện hành động
    }
}
```

Đối tượng (object) = Dữ liệu (data) + Phương thức (method)
- Dữ liệu: mô tả đối tượng.
- Phương thức: các hàm xưt lý của đối tượng.

Cú pháp xây dựng object:
```
<className> <objectName> = new <className>();
```

## So sánh Lớp & Đối tượng trong Java
| **Tiêu chí**         | **Lớp (Class)**                                                    | **Đối tượng (Object)**                                                      |
|----------------------|--------------------------------------------------------------------|-----------------------------------------------------------------------------|
| **Khái niệm**        | Là một khuôn mẫu (blueprint) để tạo ra các đối tượng.              | Là một thực thể cụ thể được tạo ra từ lớp.                                  |
| **Mục đích**         | Định nghĩa các thuộc tính và hành vi chung cho một nhóm đối tượng. | Lưu trữ trạng thái cụ thể và thực hiện các hành động của đối tượng.         |
| **Cú pháp**          | Được khai báo bằng từ khóa `class`.                                | Được tạo ra bằng từ khóa `new`.                                             |
| **Thời điểm tồn tại**| Tồn tại trong mã nguồn (compile-time).                             | Tồn tại trong bộ nhớ khi chương trình chạy (runtime).                       |
| **Bản chất**         | Là một ý niệm trừu tượng, không chiếm bộ nhớ.                      | Là một thực thể cụ thể, chiếm bộ nhớ trong quá trình thực thi chương trình. |
| **Ví dụ**            | Human                                                              | Man, Woman                                                                  |

