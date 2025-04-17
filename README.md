# Hybrid_GPU-Accelerated_Huffman_Encoding

This project demonstrates a hybrid implementation of **Huffman Encoding**, combining **GPU-accelerated frequency analysis using CuPy** with traditional CPU-based Huffman tree construction and encoding. It runs smoothly on **Google Colab with GPU support**.
**[RUN_IN_COLAB](https://colab.research.google.com/drive/1xR_gPCnK5FuTSfRaqT-2-Bg1MYMp4ZJJ?usp=sharing)**
---

## 📌 Features

- ✅ Frequency counting on **GPU** using CuPy for high-speed analysis
- ✅ Huffman tree construction on **CPU**
- ✅ Compression of large strings with customizable input
- ✅ Fully executable on **Google Colab** (no local GPU required)

---

## 🔗 Run in Google Colab

👉 **[Click here to open in Colab](https://colab.research.google.com/drive/1xR_gPCnK5FuTSfRaqT-2-Bg1MYMp4ZJJ?usp=sharing)**  

---

## 📦 Dependencies

- Python 3.x
- CuPy (compatible with CUDA 12.x on Colab)

Install CuPy in your Colab notebook with:

```bash
!pip install cupy-cuda12x
```

## 🧠 How It Works

1.	Input a large text/string to be compressed. 
2. GPU acceleration is used for counting symbol frequencies. 
3. Huffman tree is built on the CPU from the frequency table. 
4. Data is encoded into a compressed bitstring using the generated Huffman codes.

## 📁 File Structure

```
.
├── LICENSE
├── README.md
├── file_structure
├── main.py
└── main_notebook.ipynb

1 directory, 5 files
```

## 📜 License

This project is licensed under the MIT License.