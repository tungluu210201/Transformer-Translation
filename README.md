<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">TRƯỜNG ĐẠI HỌC KHOA HỌC TỰ NHIÊN - ĐẠI HỌC QUỐC GIA THÀNH PHỐ HỒ CHÍ MINH</h3>

  <p align="center">
    ĐỒ ÁN TRANSLATION - HỌC THỐNG KÊ
    <br />
   <strong>Nhóm gồm 2 thành viên: </strong>
    <br />
    <ol  style="text-align:left">
    <li>
     MSSV: 20120616. Họ và tên: LƯU QUÝ TÙNG (Nhóm trưởng)
    </li>
    <li>
     MSSV: 20120598. Họ và tên: DƯƠNG TẤN TỒN 
    </li>
    </ol>
  </p>
</div>


## GIỚI THIỆU ĐỒ ÁN
- Đồ án "Neural Machine Translation with Transformer" là một dự án trong lĩnh vực dịch máy sử dụng mô hình Transformer. Mục tiêu chính của dự án là xây dựng một hệ thống dịch máy tự động hiệu quả sử dụng các mô hình học sâu.

- Trong quá khứ, các mô hình dịch máy truyền thống sử dụng phương pháp cơ sở trên các mô hình ngôn ngữ và xác suất. Tuy nhiên, với sự phát triển của deep learning, các mô hình dịch máy sử dụng mạng nơ-ron đã đạt được hiệu suất tốt hơn.

- Trong dự án này, mô hình Transformer được sử dụng làm cơ sở cho việc dịch máy. Mô hình Transformer được giới thiệu bởi Vaswani et al. vào năm 2017 và đã trở thành một trong những công cụ quan trọng trong dịch máy hiện đại.

- Mô hình Transformer dựa trên cơ chế Attention, cho phép mô hình tập trung vào các phần quan trọng của câu nguồn và tạo ra dự đoán chính xác hơn. Nó sử dụng một kiến trúc encoder-decoder với nhiều lớp mã hóa và giải mã, cùng với cơ chế Attention để trích xuất thông tin từ câu nguồn và sinh ra câu dịch.


Trình bày sơ lược đồ án.
-	Mục tiêu: dịch từ tiếng anh sang tiếng việt 

Đồ án môn học Thống kê với đề tài Transformer là kết quả của quá trình cố gắng không ngừng nghỉ của cả nhóm và nhận được sự hướng dẫn tận tình của thầy cô  cùng các bạn học. Qua đây, chúng em xin gửi lời cảm ơn chân thành tới những người đã giúp đỡ chúng  em hoàn thành được đồ án này!

## Công ghệ sử dụng 
Ngôn ngữ: Python

Thư viện, framework: Flask, flask, Flask-SQLAlchemy, transformers, torchvision, sentencepiece, sacremoses


## Môi trường thực thi và phát triễn 
1. Python
2. Visual studio code
 
## Cài đặt
1. Clone the repo
  ```sh
  git clone https://github.com/tungluu210201/Transformer-Translation 
  ```
2. Mở terminal ngay thư mục app

  **Lúc khởi tạo (khi chưa có folder venv)

  B1 : 
  ```sh
  py -m venv venv
  ```
  B2 : 
  ```sh
  venv\Scripts\activate
  ```
  B3 : 
  ```sh
  pip install -r requirements.txt
  ```
  B4 : 
  ```sh
  flask --app flaskr run --debugger --reload --host=0.0.0.0 --port=4201 // chạy với port 4200 (puplic), nếu muốn public ra ngoài phải config lại router
  ```

  **Lúc khởi tạo (khi có folder venv)// mở terminal ngay thư mục app
  
  B2 : 
  ```sh
  venv\Scripts\activate
  ```
  B2 :
  ```sh
  flask --app flaskr run --debugger --reload --host=0.0.0.0 --port=4201 // chạy với port 4200 (puplic), nếu muốn public ra ngoài phải config lại router
  ```

3. Sau khi chạy có thể truy cập vào đường link: http://localhost:4201/

4. Hoàn thành.

### KẾT THÚC.
Chúng em xin tỏ lòng kính trọng và biết ơn sâu sắc đến thầy cô giáo là người trực tiếp hướng dẫn đồ án. Thầy cô đã cung cấp cho chúng em những tài liệu cần thiết cho đồ án của chúng em. 
Em xin chân thành cảm ơn! 

<br/>

