Train dữ liệu với tập dữ liệu thu thập được

Bước 1: git clone https://github.com/nguyenhuyquang/train_yolov3_customdata.git

đổi tên train_yolov3_customdata folder thành yolo_train
Vào folder yolo_train, 
----------------------------------------------------------------
Do github không cho phép upload file trên 100Mb nên chúng em để file tại google drive:
https://drive.google.com/file/d/1ahtzbxBjQqh4ZDAieJ4TILj5k_rgIggH/view?usp=sharing
Tạo folder custom_weight trong folder  yolo_train
Sau khi tải file về đưa file vào thư mục custom_weight
Tạo thêm folder backup
----------------------------------------------------------------

Bước 2: Upload folder lên google drive

Bước 3: Đổi tên folder thành custom_data

Bước 4: Chạy google Colab và load file train_yolo.ipynb vào google colab để chạy

Bước 5: Chọn Runtime (Thời gian chạy) -> Chọn change runtime type (Thay đổi loại thời gian chạy)
        Sửa Hardware accelerator (Trình tăng tốc phần cứng) thành GPU

Bước 6: Run all (Ctrl + F9) (Cấp quyền để có thể đọc và ghi dữ liệu trên drive)

Sau khi kết thúc quá trình train (Khoảng 2h) ta thu được file yolov3_custom_final.weights
