# Kết nối với cơ sở dữ liệu(CSDL-Databases)
## Syntax(Cú-Pháp)

```python
# Import thư viện sqlite3
import sqlite3

# Tạo kết nối với cơ sở dữ liệu name_database.db
conn = sqlite3.connect("name_database.db")

# Tạo đối tượng cursor
# `cur = conn.cursor()` đang tạo một đối tượng con trỏ được liên kết với kết nối `conn`. Con trỏ
# đối tượng cho phép bạn thực thi các truy vấn SQL và tìm nạp kết quả từ cơ sở dữ liệu bằng các phương thức như
# `thực thi()`(execute) và `tìm nạp()`(fetchall).
cur = conn.cursor()
```

`conn`=`sqlite3`.`connect`("`name_database`")

Gán biến `conn` `=` `Type: connection` sử dụng thư viện `sqlite3` `connect` với DB tên : `name_database`.


