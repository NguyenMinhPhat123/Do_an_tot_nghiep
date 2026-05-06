# VIFOOD Chatbot: Personalized Vietnamese Cuisine Recommendation System 📌

## 📌 Giới thiệu dự án
VIFOOD là một hệ thống Chatbot thông minh được thiết kế để tư vấn ẩm thực Việt Nam dựa trên sở thích cá nhân của người dùng. Hệ thống sử dụng kỹ thuật **RAG (Retrieval-Augmented Generation)** kết hợp với các mô hình ngôn ngữ lớn (**LLMs**) để đưa ra các gợi ý món ăn phù hợp theo vùng miền, nguyên liệu, hoặc thậm chí là tâm trạng và cảm xúc của người dùng.

*Dự án này được **Fork** từ repository gốc của nhóm nhằm mục đích lưu trữ và trình bày các đóng góp chuyên sâu của tôi trong vai trò Kỹ sư AI.*

---

## 👨‍💻 Đóng góp cá nhân (My Contributions)
Trong dự án này, tôi đảm nhận hai vai trò cốt lõi trong quy trình phát triển AI[cite: 1]:

### 1. Data Engineer
* **Xây dựng Dataset**: Trích xuất và tiền xử lý dữ liệu ẩm thực từ các file Excel, chuyển đổi sang định dạng **JSON** để chuẩn hóa cấu trúc đầu vào cho mô hình[cite: 1].
* **Tối ưu hóa dữ liệu**: Thực hiện làm sạch dữ liệu và gán nhãn có cấu trúc, giúp cải thiện chất lượng dữ liệu đầu vào[cite: 1].
* **Quy trình Fine-tuning**: Thiết kế quy trình tự động chuyển đổi dữ liệu từ dạng bảng thành các cặp **Question-and-Answer (Q&A)** để phục vụ việc tinh chỉnh (fine-tuning) cho mô hình Reranker và LLM[cite: 1].

### 2. AI Engineer
* **Thiết kế hệ thống**: Xây dựng kiến trúc Chatbot dựa trên sự kết hợp giữa **RAG** và **LLM**[cite: 1].
* **Tối ưu hóa mô hình**: Trực tiếp thực hiện 3 vòng tối ưu hóa về cả dữ liệu và kiến trúc, giúp nâng cao độ chính xác **MRR (Mean Reciprocal Rank)** của danh sách thực đơn từ **0.76 lên 0.79**[cite: 1].
* **Reranking**: Áp dụng kỹ thuật fine-tuning cho mô hình Reranker để đảm bảo các kết quả trả về có độ liên quan cao nhất với yêu cầu của người dùng[cite: 1].

---

## 🛠️ Công nghệ sử dụng ⚙️
* **AI/ML**: LLMs, RAG, Fine-tuning, Cross-encoder Reranker[cite: 1].
* **Vector Database**: FAISS / ChromaDB[cite: 1].
* **Data Processing**: Python, Pandas, Numpy, JSON[cite: 1].
* **Frameworks**: FastAPI/Flask cho việc triển khai API[cite: 1].

---

## 📊 Kết quả đạt được 📈
* Hệ thống có khả năng hiểu và phản hồi ngữ cảnh tốt dựa trên sở thích người dùng[cite: 1].
* Độ chính xác của danh sách món ăn gợi ý (MRR) tăng đáng kể (**+0.03**) sau các vòng thực nghiệm và tối ưu hóa[cite: 1].

---

## 🤝 Credit 💛
* **Dự án tốt nghiệp**: Đại học FPT Quy Nhơn (Khóa 2021 - 2025)[cite: 1].
* **Original Repository**: [(https://github.com/Niel-Nguyen/Do_an_tot_nghiep)]
