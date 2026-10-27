# ⚡ BẢNG TRA CỨU CẤP TỐC ÔN THI AWS CERTIFIED AI PRACTITIONER (AIF-C01)
### *Bảng So Sánh Toàn Bộ Dịch Vụ, Cặp Thuật Ngữ Dễ Nhầm Lẫn & Bộ Từ Khóa Vàng 3 Giây*

---

## 🎯 1. BẢNG TỪ KHÓA VÀNG "3 GIÂY" CHỌN ĐÁP ÁN ĐÚNG

Khi đọc đề bài thi scenario-based, nếu thấy xuất hiện các từ khóa (Keywords) này, 99% đáp án đúng sẽ rơi vào dịch vụ/khái niệm tương ứng:

| Từ khóa xuất hiện trong đề bài (Keywords) | Dịch vụ / Khái niệm chính xác cần chọn |
| :--- | :--- |
| *"No-code GenAI application builder without an AWS account"* | **PartyRock** |
| *"Unified serverless API to access multi-vendor foundation models"* | **Amazon Bedrock** |
| *"Deploy pre-trained models on user-managed EC2 instances/endpoints"* | **Amazon SageMaker JumpStart** |
| *"AI assistant for enterprise employees integrating with SharePoint, Jira"* | **Amazon Q Business** |
| *"AI assistant for software developers, code generation, Java upgrade"* | **Amazon Q Developer** |
| *"No-code visual ML tool for business analysts"* | **Amazon SageMaker Canvas** |
| *"Automated ML exploring algorithms and hyperparameters with code export"* | **Amazon SageMaker Autopilot** |
| *"Human-in-the-loop data labeling for ML training datasets"* | **Amazon SageMaker Ground Truth** |
| *"Visual data preparation, cleaning, and feature engineering"* | **Amazon SageMaker Data Wrangler** |
| *"Detect bias and explain model predictions with SHAP values"* | **Amazon SageMaker Clarify** |
| *"Automated monitoring for data drift, concept drift, and bias drift"* | **Amazon SageMaker Model Monitor** |
| *"Low confidence predictions automatically routed to human reviewers"* | **Amazon Augmented AI (Amazon A2I)** |
| *"Crowdsourcing global workforce for human intelligence tasks"* | **Amazon Mechanical Turk (MTurk)** |
| *"Extract text, tables, and form key-value pairs from scanned PDFs"* | **Amazon Textract** |
| *"Face analysis, object detection, and visual content moderation"* | **Amazon Rekognition** |
| *"NLP service for sentiment analysis, entity recognition, PII redaction"* | **Amazon Comprehend** |
| *"Speech-to-text with speaker identification and custom vocabulary"* | **Amazon Transcribe** |
| *"Text-to-speech with natural voices, SSML, and lexicons"* | **Amazon Polly** |
| *"Conversational AI chatbot using Alexa technology (intents, slots)"* | **Amazon Lex** |
| *"Intelligent enterprise search with natural language and direct answers"* | **Amazon Kendra** |
| *"Personalized user recommendations using Amazon.com algorithms"* | **Amazon Personalize** |
| *"Online fraud risk score between 0 and 1,000"* | **Amazon Fraud Detector** |
| *"Time-series forecasting with weather and holidays integration"* | **Amazon Forecast** |
| *"Ground FM responses with enterprise data without modifying model weights"* | **RAG (Bedrock Knowledge Bases)** |
| *"Automate multi-step tasks by executing APIs via AWS Lambda"* | **Amazon Bedrock Agents (Action Groups)** |
| *"Deterministic, predictable, factual answers"* | **Low Temperature (0.0 - 0.2)** |
| *"Creative, diverse, imaginative storytelling"* | **High Temperature (0.8 - 1.0)** |
| *"Evaluate machine translation quality"* | **BLEU Score** |
| *"Evaluate text summarization quality focusing on recall"* | **ROUGE Score** |
| *"Semantic similarity between generated and reference text via embeddings"* | **BERTScore** |
| *"Measures how surprised the model is (Lower is better!)"* | **Perplexity** |
| *"Cost of False Positive is high (avoid false alarms like Spam filter)"* | **Precision** |
| *"Cost of False Negative is catastrophic (do not miss cancer or fraud)"* | **Recall (Sensitivity)** |
| *"High training accuracy but poor test accuracy (overfitting)"* | **High Variance** |
| *"Poor accuracy on both training and test data (underfitting)"* | **High Bias** |
| *"Understand HOW a model works internally"* | **Interpretability** |
| *"Understand WHY a model made a specific prediction"* | **Explainability** |
| *"Transparency documentation from AWS for managed AI services"* | **AWS AI Service Cards** |
| *"Single source of truth documenting custom models in SageMaker for audits"* | **Amazon SageMaker Model Cards** |
| *"Energy-efficient custom chips for deep learning training"* | **AWS Trainium** |
| *"Energy-efficient custom chips for deep learning inference"* | **AWS Inferentia** |
| *"Connect VPC to Bedrock/S3 privately without internet access"* | **AWS PrivateLink (VPC Endpoints)** |
| *"Add controlled mathematical noise to dataset to preserve privacy"* | **Differential Privacy** |
| *"Replace sensitive data with non-sensitive random surrogate"* | **Tokenization** |
| *"Track original source and origin of data"* | **Data Provenance** |
| *"Track end-to-end journey and transformations of data"* | **Data Lineage** |
| *"Audit resource configuration changes over time against rules"* | **AWS Config** |
| *"Automated vulnerability scanning for CVEs in EC2 and ECR containers"* | **Amazon Inspector** |
| *"Automate evidence collection for compliance audits (SOC, HIPAA)"* | **AWS Audit Manager** |
| *"Download official AWS compliance reports and sign agreements"* | **AWS Artifact** |
| *"Immutable audit trail of all API calls in AWS account"* | **AWS CloudTrail** |
| *"Distribute image labeling tasks to workforce and review quality"* | **Amazon SageMaker Ground Truth** |
| *"Batch size vs Learning rate: what controls step size during optimization?"* | **Learning Rate** (controls step size); **Batch Size** (controls number of examples per iteration) |
| *"Feature Creation, Feature Transformation, Feature Extraction, Feature Selection"* | **Feature Engineering** (tất cả 4 dạng đều thuộc Feature Engineering) |
| *"Data Cleaning or Data Partitioning in ML pipeline"* | **KHÔNG phải Feature Engineering** (thuộc Data Preparation / Model Development) |
| *"Scope 1-5 in GenAI Security: Consumer → Provider"* | **Generative AI Security Scoping Matrix** |
| *"Consistent performance across varying inputs, including data differing from training"* | **Robustness** (KHÔNG phải Generalizability) |
| *"Perform well on unseen tasks or new domains (transfer knowledge)"* | **Generalizability** |
| *"Understand HOW a model works internally"* | **Interpretability** |
| *"Understand WHY a model made a specific prediction"* | **Explainability (SHAP / SageMaker Clarify)** |
| *"PRIMARY purpose that distinguishes GenAI from traditional ML"* | **To create new content similar to its training data** |
| *"Reduce fine-tuning cost, prevent catastrophic forgetting"* | **PEFT / LoRA / Layer Freezing** |
| *"Teach model domain-specific jargon using massive unlabeled text"* | **Continued Pre-training (Domain Adaptation)** |
| *"Teach model specific tone, style, output format using labeled pairs"* | **Fine-tuning (Instruction Tuning)** |

---

## ⚖️ 2. MA TRẬN SO SÁNH CÁC CẶP KHÁI NIỆM & DỊCH VỤ DỄ GÂY LÚ

### Cặp 1: Amazon Bedrock vs Amazon SageMaker JumpStart
| Đặc điểm | Amazon Bedrock | Amazon SageMaker JumpStart |
| :--- | :--- | :--- |
| **Kiến trúc hạ tầng** | **Serverless hoàn toàn**, không cần chọn máy chủ | Người dùng **tự chọn loại Instance** (EC2) |
| **Mức độ kiểm soát** | Thấp (AWS trừu tượng hóa toàn bộ qua API) | **Rất cao** (Toàn quyền cấu hình VPC, GPU, OS, Docker) |
| **Tính phí** | Trả theo Token vào/ra (On-demand) | Trả theo **giờ chạy của Instance** |
| **Mục đích** | Ít tốn công vận hành nhất (**Least effort**) | Cần toàn quyền tinh chỉnh hoặc chạy custom Docker |

### Cặp 2: AWS AI Service Cards vs SageMaker Model Cards
| Đặc điểm | AWS AI Service Cards | Amazon SageMaker Model Cards |
| :--- | :--- | :--- |
| **Bên tạo lập** | Do **chính AWS** biên soạn và công khai | Do **doanh nghiệp / bạn** tự lập cho mô hình của mình |
| **Phạm vi** | Các **dịch vụ đóng gói sẵn của AWS** (Rekognition, Comprehend) | Từng **mô hình tùy biến** huấn luyện trên SageMaker |
| **Mục đích** | Hướng dẫn sử dụng đúng mục đích và nêu giới hạn kỹ thuật | Làm nguồn chân lý duy nhất (Single source of truth) phục vụ kiểm toán |

### Cặp 3: Amazon Textract vs Amazon Rekognition
| Đặc điểm | Amazon Textract | Amazon Rekognition |
| :--- | :--- | :--- |
| **Đối tượng xử lý** | **Tài liệu, biểu mẫu, hợp đồng, hóa đơn PDF/Scan** | **Hình ảnh đời sống, video, khuôn mặt, phong cảnh** |
| **Cấu trúc trích xuất** | Đọc hiểu **Bảng biểu (Tables), Forms (Key-Value), Chữ viết tay** | Đọc chữ thô trên biển báo/biển số xe, nhận diện vật thể |

### Cặp 4: Amazon Kendra vs Amazon OpenSearch Service
| Đặc điểm | Amazon Kendra | Amazon OpenSearch Service |
| :--- | :--- | :--- |
| **Đối tượng người dùng** | Nhân viên văn phòng, người dùng cuối doanh nghiệp | Kỹ sư phần mềm, kiến trúc sư hệ thống |
| **Cơ chế tìm kiếm** | Đặt câu hỏi tự nhiên ➔ Trả về **câu trả lời trực tiếp trích dẫn** | Công cụ tìm kiếm văn bản toàn diện (Full-text) và Vector Search kỹ thuật |
| **Tích hợp** | Sẵn Connectors (SharePoint, S3, Salesforce) | Phải cấu hình index, pipeline dữ liệu tùy biến |

### Cặp 5: RAG vs Fine-Tuning
| Đặc điểm | Retrieval-Augmented Generation (RAG) | Fine-Tuning (SFT / RLHF) |
| :--- | :--- | :--- |
| **Thay đổi trọng số?** | **TUYỆT ĐỐI KHÔNG (0% Weight changes)** | **CÓ (Cập nhật các trọng số nơ-ron)** |
| **Chi phí** | Thấp (chỉ tốn chi phí lưu trữ Vector DB) | Trung bình / Cao (tốn chi phí tính toán GPU huấn luyện) |
| **Cập nhật tri thức** | **Thời gian thực** (chỉ cần thêm file vào S3) | Phải huấn luyện lại khi có dữ liệu mới |
| **Thế mạnh nhất** | Giảm ảo giác, cập nhật thông tin mới nhất có trích dẫn nguồn | Thay đổi phong cách, văn phong, tuân thủ cấu trúc output đặc thù |

---

## 📈 3. CÂY QUYẾT ĐỊNH CÁC CHẾ ĐỘ SUY LUẬN (INFERENCE SELECTION TREE)

```
Bạn cần triển khai mô hình học máy trên Amazon SageMaker?
 │
 ├── Dữ liệu có sẵn theo lô lớn trên S3 và chấp nhận trễ hàng giờ?
 │    └── ➔ CHỌN: SageMaker Batch Transform (Rất tiết kiệm chi phí)
 │
 ├── Kích thước Payload cực lớn (lên tới 1 GB) và thời gian xử lý tới 1 giờ (ảnh CT, video dài)?
 │    └── ➔ CHỌN: SageMaker Asynchronous Inference (Có hàng đợi S3, tự scale về 0)
 │
 ├── Lưu lượng truy cập thất thường, nhàn rỗi nhiều, muốn tự động co giãn về 0 để tiết kiệm?
 │    └── ➔ CHỌN: SageMaker Serverless Inference (Payload <= 6MB, có cold start)
 │
 └── Ứng dụng tương tác trực tuyến 24/7 cần phản hồi ngay dưới vài mili-giây?
      └── ➔ CHỌN: SageMaker Real-Time Inference (Chạy instance cố định 24/7)
```

---

## 🛡️ 4. BẢNG QUY TRÌNH PHÒNG CHỐNG TẤN CÔNG BẢO MẬT AI

| Loại tấn công AI | Bản chất nguy hại | Biện pháp bảo vệ tối ưu nhất trên AWS |
| :--- | :--- | :--- |
| **Prompt Injection** | Kẻ xấu nhập văn bản lừa mô hình bỏ qua hướng dẫn hệ thống ban đầu. | **Guardrails for Amazon Bedrock** (Denied topics, contextual grounding check). |
| **Jailbreaking** | Vượt qua các rào chắn an toàn và bộ quy tắc đạo đức của mô hình. | Thiết lập bộ lọc nội dung nhiều lớp (Multi-layer guardrails) và kiểm duyệt kép. |
| **Data Poisoning** | Cấy các mẫu dữ liệu sai lệch vào tập huấn luyện để thao túng kết quả. | Kiểm tra **Data Provenance**, xác thực chữ ký số, theo dõi **Data Lineage**. |
| **Data Exposure** | Mô hình vô tình làm lộ số thẻ tín dụng hoặc PII trong câu trả lời. | Kích hoạt bộ lọc PII trong **Amazon Comprehend** và **Bedrock Guardrails**. |
| **Model Hijacking** | Chiếm quyền điều khiển mô hình thực hiện các tác vụ ngầm trái phép. | Chỉ sử dụng các mô hình đã được xác thực từ **Amazon SageMaker JumpStart**. |

---

## 🎯 5. NGUYÊN TẮC "VÀNG" KHI LÀM BÀI THI TRẮC NGHIỆM

1. **Luôn ưu tiên giải pháp có sẵn (Managed Services / Serverless) nếu đề bài yêu cầu "Least operational overhead"**: Nếu câu hỏi yêu cầu giải pháp tốn ít công sức nhất, hãy chọn **Amazon Bedrock** thay vì SageMaker, chọn **Amazon Textract** thay vì tự huấn luyện OCR trên EC2.
2. **Cảnh giác với các từ mang tính tuyệt đối**: Trong AI/ML, bất kỳ phương án nào khẳng định: *"Mô hình AI đảm bảo độ chính xác tuyệt đối 100% không sai số"*, hoặc *"Khách hàng chịu trách nhiệm bảo mật trung tâm dữ liệu vật lý"* đều là **PHƯƠNG ÁN SAI**.
3. **Quy tắc Perplexity**: Nhớ duy nhất Perplexity là **CÀNG THẤP CÀNG TỐT** (5 - 20 là tốt). Mọi chỉ số còn lại (BLEU, ROUGE, BERTScore, Accuracy, Precision, Recall, F1) đều là **CÀNG CAO CÀNG TỐT** (gần 1.0).
4. **Phân biệt Precision vs Recall**:
   - Nhầm người vô tội thành tội phạm (False Positive) là thảm họa ➔ Tối ưu **Precision**.
   - Thả nhầm một tên tội phạm hoặc bỏ sót ca ung thư (False Negative) là thảm họa ➔ Tối ưu **Recall**.
