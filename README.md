# ottgnn

+ Clone the repository

  ```bash
  git clone https://github.com/heap-limit-exceeded/ottgnn.git 
  ```

  and change the current working directory to ottgnn directory

  ```bash
  cd ottgnn
  ```

+ Create a python virtual environment

  ```bash
  python -m venv {virt}
  ```

  To activate the virtual environment

  On Unix like systems,

  ```bash
  source {virt}/bin/activate
  ```

  On Windows,

  ```powershell
  .\{virt}\Scripts\activate.ps1
  ```

+ Install necessary requirements

  ```bash
  pip install -r requirements.txt
  ```

+ To train on a dataset,

  ```bash
  python3 run.py --dataset {reddit/taobao/yelp}
  ```
