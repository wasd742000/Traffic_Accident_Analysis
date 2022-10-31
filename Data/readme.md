# Note

- Đây là folder tổng hợp dữ liệu của các quá trình thu thập, tiền xử lý dữ liệu
- Tên file và ý nghĩa
    - Các file data từ năm 2014 đến 2019 có cấu trúc tên file là `data_201x.csv` (x từ 4 đến 9)
    - `guidance.xlsx`: File chứa thông tin (không đầy đủ) về các trường dữ liệu, được lấy từ cùng 1 nguồn với dữ liệu thô
    - `data_merge.csv`: File tổng hợp dữ liệu từ năm 2014 đến năm 2019, có được sau khi chạy file `./src/preprocess/merge_data.ipynb`
    - `afterPreprocess.csv`: File output của quá trình tiền xử lý dữ liệu, có được sau khi chạy file `./src/preprocess/preprocess.ipynb`
