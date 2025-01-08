# bt1kiemthu

Bài tập: Kiểm thử lớp Calculator
Yêu cầu:

Tạo lớp Calculator với các phương thức sau:

add(int a, int b): Trả về tổng của hai số.
subtract(int a, int b): Trả về hiệu của hai số.
multiply(int a, int b): Trả về tích của hai số.
divide(int a, int b): Trả về thương của hai số (nếu b = 0, ném ra ngoại lệ IllegalArgumentException).
Viết các bài kiểm thử đơn vị cho các phương thức trên sử dụng JUnit 5.

chạy kiểm thử:
Thêm thư viện JUnit 5 vào dự án:

Nếu sử dụng Maven, thêm vào file pom.xml:
xml
Sao chép mã
<dependency>
    <groupId>org.junit.jupiter</groupId>
    <artifactId>junit-jupiter</artifactId>
    <version>5.9.3</version>
    <scope>test</scope>
</dependency>
Chạy kiểm thử:

Trong IDE như IntelliJ IDEA hoặc Eclipse, nhấp chuột phải vào file CalculatorTest.java và chọn Run Tests.
Nếu sử dụng Maven, chạy lệnh:
bash
Sao chép mã
mvn test

Kết quả: ![Screenshot 2025-01-08 090904](https://github.com/user-attachments/assets/2c559b0d-5b42-4162-953a-62d653d4f391)

