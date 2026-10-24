# 💬 Natural Language Processing: Foundations & Implementation

Repository này lưu trữ tài liệu lý thuyết nền tảng và mã nguồn thực hành các kỹ thuật Xử lý Ngôn ngữ Tự nhiên (NLP) từ các phương pháp xử lý văn bản truyền thống đến mô hình mạng nơ-ron hồi quy xử lý chuỗi (Sequential Deep Learning).

---

## 📂 Cấu trúc Repository

- **[Code/](./Code):** Chứa toàn bộ mã nguồn cài đặt tiền xử lý văn bản, Word Embeddings và mạng nơ-ron tuần hoàn (Jupyter Notebooks).
- **[Lý thuyết/](./L%C3%BD%20thuy%E1%BA%BFt):** Chứa các ghi chép chi tiết về lý thuyết biểu diễn ngôn ngữ, cơ chế Attention và mô hình Transformer.

---

## 📌 Nội dung chi tiết các thư mục

### 1. [Lý thuyết - Cơ chế & Nền tảng](./L%C3%BD%20thuy%E1%BA%BFt)
Tài liệu tổng kết nguyên lý lý thuyết và kiến trúc mô hình ngôn ngữ:
- **Xử lý & Biểu diễn văn bản:** Bản chất của tokenization, từ điển vựng, không gian vector từ vựng và ma trận đồng xuất hiện.
- **Mạng nơ-ron xử lý chuỗi:** Lý thuyết hoạt động của RNN, cơ chế cổng của LSTM/GRU nhằm khắc phục hiện tượng triệt tiêu gradient.
- **Mô hình ngôn ngữ hiện đại:** Khái niệm Transfer Learning trong NLP, cơ chế Self-Attention và tổng quan kiến trúc Transformers.

### 2. [Code - Triển khai Thực nghiệm](./Code)
Triển khai mã nguồn thực tế:
- **Text Preprocessing (`Tokenization_Stemming_Lemmatization.ipynb`):** Kỹ thuật tách từ (Tokenization), chuẩn hóa văn bản, lọc từ dừng và đối chiếu Stemming với Lemmatization qua thư viện NLTK.
- **Vector Space Models (`Bag of Words, TF_IDF_code.ipynb`):** Triển khai mô hình túi từ (Bag of Words) và ma trận trọng số TF-IDF cho bài toán trích xuất đặc trưng văn bản.
- **Word Embeddings (`Word2Vec, GloVe, FastText_code.ipynb`):** Thực nghiệm huấn luyện và đánh giá không gian nhúng từ với Word2Vec (CBOW, Skip-gram), GloVe và kỹ thuật phân tích cụm từ n-gram của FastText.
- **Sequential Models (`rnn-lstm-gru.ipynb`):** Cài đặt và huấn luyện các kiến trúc RNN, LSTM, GRU trên PyTorch cho bài toán phân loại chuỗi và dự đoán văn bản.

---

## 🛠️ Công nghệ & Công cụ sử dụng

- **Ngôn ngữ:** Python 3
- **Thư viện NLP & Machine Learning:** NLTK, Spacy, Gensim, Scikit-learn
- **Deep Learning Framework:** PyTorch (`torch.nn.RNN`, `torch.nn.LSTM`, `torch.nn.GRU`)
- **Phân tích dữ liệu & Trực quan hóa:** NumPy, Pandas, Matplotlib
- **Môi trường thực thi:** Jupyter Notebook / Google Colab
