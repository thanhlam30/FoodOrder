# Lập trình website đặt thức ăn sử dụng backend Java Springboot

Trang web bán hàng thực phẩm


## Công nghệ sử dụng

**Client:** HTML, CSS, JS

**Server:** Springboot, mysql

**Tool:** Docker


## Cài đặt
### Cài đặt backend
#### Yêu cầu môi trường
Môi trường yêu cầu để chạy backend:

* Java 11
* mysql:9.1

Chạy springboot

```bash
  mvn spring-boot:run
```

### Cài đặt frontend

Fontend là web tĩnh nên có thể dùng các công cụ chạy file index.html lên


        

```

#### Thư mục backend chưa code springboot


**config** Chứa các cấu hình cho springboot

**domain** Chứa các lơp dùng để định nghia các đối tượng tương ứng với các bảng trong sql

**model** Chứa các lớp dùng để trao đổi dữ liệu như DTO

**repos** Dùng định nghĩa các hàm thao tác với csdl

**rest** Định nghĩa các restAPI

**service** Định nghĩa các service

**resources** Định nghia resources

**application.properties** Chứa các thuộc tính cấu hình cho springboot

#### Thư mục frontend chứa code frontend


## Triển khai sử dụng docker-compose

Để chạy ta sử dụng lênh

```bash
  docker-compose up
```




