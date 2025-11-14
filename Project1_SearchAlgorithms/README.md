# Thiết lập đồ án

Đồ án này sử dụng các thư viện Python: NumPy, Pandas, Matplotlib và Seaborn.

## 1. Sử dụng Conda

1. Đảm bảo rằng Anaconda hoặc Miniconda đã được cài đặt.

2. Tạo môi trường bằng file `environment.yml` đã cung cấp:
``` bash
conda env create -f environment.yml
```

3. Kích hoạt môi trường:
``` bash
conda activate myenv
```

## 2. Sử dụng pip

1. Tạo môi trường ảo:
``` bash
python -m venv project_env
```

2. Kích hoạt môi trường:

Windows:
``` bash
project_env\Scripts\activate
```

Linux hoặc macOS:
``` bash
source project_env/bin/activate
```

3. Cài đặt các gói cần thiết:
``` bash
pip install -r requirements.txt
```

## 3. Chạy Notebook

Để chạy notebook của đồ án, chọn một trong hai cách sau:

Mở file `23122024_23122025_23122032_23122045.ipynb`.

### Cách 1. Chạy toàn bộ notebook
1. Chọn Run -> Run All.
2. Chờ tất cả các ô chạy xong. Quá trình có thể mất nhiều thời gian với thiết lập hiện tại.

### Cách 2. Chạy từng phần theo thứ tự
Nếu bạn muốn kiểm soát từng bước, chạy các phần theo thứ tự sau:

1. Phần import
2. Phần algorithms
3. Phần problem
4. Một trong các phần sau:
   - Travelling Salesman Problem
   - Continuous Problem
   - Thử nghiệm với TSPLIB

---
---

# Project Setup

This project uses these Python libraries: NumPy, Pandas, Matplotlib, and Seaborn.

## 1. Using Conda

1. Make sure Anaconda or Miniconda is installed.

2. Create the environment using the provided `environment.yml` file:
``` bash
conda env create -f environment.yml
```

3. Activate the environment:
``` bash
conda activate myenv
```

## 2. Using pip

If you prefer pip, use the `requirements.txt` file.

1. Create a virtual environment:
``` bash
python -m venv project_env
```

2. Activate it:

Windows:
``` bash
project_env\Scripts\activate
```

Linux or macOS:
``` bash
source project_env/bin/activate
```

3. Install the required packages:
``` bash
pip install -r requirements.txt
```

## 3. Running the Notebook

To run the project notebook, follow one of the options below:

Open the file `23122024_23122025_23122032_23122045.ipynb`.

### Option 1. Run the entire notebook
1. Select Run -> Run All.
2. Wait until all cells finish running. The execution may take a long time with the current settings.

### Option 2. Run the notebook step by step
If you prefer to control each part manually, run the notebook in this order:

1. Import section
2. Algorithms section
3. Problem section
4. One of the following:
   - Travelling Salesman Problem
   - Continuous Problem
   - Experiment with TSPLIB