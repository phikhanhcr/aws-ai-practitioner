# 🚀 BỘ TÀI LIỆU ÔN THI CHỨNG CHỈ AWS CERTIFIED AI PRACTITIONER (AIF-C01)
### *Toàn bộ 16 Chương Chi Tiết + Bản Đồ Tư Duy (Mindmaps) + Mẹo Thi & Câu Hỏi Mô Phỏng Chuẩn Format*

---

## 📌 GIỚI THIỆU TỔNG QUAN VỀ KỲ THI AWS AIF-C01
Chứng chỉ **AWS Certified AI Practitioner (Mã đề: AIF-C01)** là chứng chỉ nền tảng chính thức của Amazon Web Services (AWS) nhằm đánh giá sự hiểu biết toàn diện về các khái niệm Trí tuệ nhân tạo (AI), Học máy (Machine Learning - ML), và Trí tuệ nhân tạo tạo sinh (**Generative AI**), cùng với các dịch vụ, kiến trúc bảo mật và nguyên tắc đạo đức AI trên nền tảng đám mây AWS.

### 📊 Cấu trúc đề thi chính thức:
- **Số lượng câu hỏi:** 65 câu hỏi (Trắc nghiệm 1 đáp án đúng hoặc chọn nhiều đáp án đúng).
- **Thời gian làm bài:** 85 phút.
- **Thang điểm:** 100 - 1000 điểm. **Điểm đỗ (Passing score): 700 / 1000**.
- **Ngôn ngữ thi:** Tiếng Anh (hoặc bản dịch tiếng Việt có đối chiếu thuật ngữ gốc).

### 🏛️ Trọng số 5 Domain của kỳ thi AIF-C01:
| Domain | Tên Lĩnh Vực (Exam Domain) | Trọng số đề thi (%) | Các Chương Tương Ứng Trong Bộ Tài Liệu |
| :---: | :--- | :---: | :--- |
| **Domain 1** | **Fundamentals of AI and ML** (Nền tảng AI & ML) | **20%** | Chương 1, Chương 2, Chương 3, Chương 4 |
| **Domain 2** | **Fundamentals of Generative AI** (Nền tảng GenAI) | **24%** | Chương 5, Chương 6, Chương 7 |
| **Domain 3** | **Applications of Foundation Models** (Ứng dụng FMs) | **28%** | Chương 8, Chương 9, Chương 10, Chương 11 |
| **Domain 4** | **Guidelines for Responsible AI** (AI có trách nhiệm) | **14%** | Chương 12, Chương 13 |
| **Domain 5** | **Security, Compliance, and Governance** (Bảo mật & Quản trị) | **14%** | Chương 14, Chương 15, Chương 16 |
| **TỔNG** | **Toàn bộ chương trình AIF-C01** | **100%** | **Trọn bộ 16 Chương** |

---

## 🗺️ MASTER MINDMAP - BẢN ĐỒ TƯ DUY TOÀN BỘ 16 CHƯƠNG

```mermaid
mindmap
  root((AWS AI Practitioner AIF-C01))
    Domain 1: Fundamentals of AI & ML (20%)
      Chương 1: Tổng quan AI - ML - DL
        Phân cấp hình phễu AI > ML > DL > GenAI
        Hạ tầng AWS: Regions, AZs, Edge Locations, EC2, S3
        Kiến trúc mạng nơ-ron: CNN (Ảnh), RNN (Tuần tự), Transformer (LLM)
        Computer Vision vs Natural Language Processing (NLP)
      Chương 2: Khái niệm cốt lõi AI & ML
        Quy trình ML: Data -> Algorithm -> Model
        SageMaker Studio, Ground Truth, Data Wrangler, Autopilot, Canvas
        Dữ liệu: Labeled vs Unlabeled, Structured vs Unstructured
        Phương pháp học: Supervised, Unsupervised, RL & RLHF, Semi-Supervised
        Chế độ suy luận: Real-time, Batch Transform, Serverless, Asynchronous
        Khi nào KHÔNG NÊN dùng AI
      Chương 3: AWS Managed AI Services
        Vision: Amazon Rekognition & Custom Labels
        Document: Amazon Textract, Comprehend, Translate
        Speech: Amazon Transcribe, Polly (SSML, Lexicons)
        Conversational: Amazon Lex (Intents, Utterances, Slots)
        Enterprise Search: Amazon Kendra
        Business: Personalize, Fraud Detector, Forecast
        Human-in-the-loop: Amazon A2I, Mechanical Turk
      Chương 4: SageMaker & ML Lifecycle
        Vòng đời ML 7 giai đoạn: Business Goal -> Framing -> Data -> Model -> Deploy -> Monitor -> Retrain
        Parameters vs Hyperparameters (Learning Rate, Batch Size, Epochs)
        ML Lifecycle vs SageMaker Pipelines (CI/CD)
        4 Cấp độ chọn Model: Pre-trained JumpStart -> Built-in -> Pre-configured -> Custom Container
        Chỉ số kỹ thuật: Accuracy, Precision, Recall, F1, AUC-ROC | MAE, MSE, RMSE, R2
        Data Drift vs Concept Drift (SageMaker Model Monitor)
    Domain 2: Fundamentals of Generative AI (24%)
      Chương 5: Cốt lõi Generative AI & Vòng đời FMs
        Bản chất Foundation Models & LLMs
        Tokens, Embeddings, Không gian Vector & Semantic Search
        Kỹ thuật cắt đoạn Chunking with Overlap
        Mô hình Đa thức Multimodal vs Đơn thức Unimodal
        Diffusion Models: Forward (thêm nhiễu) vs Reverse (khử nhiễu vẽ ảnh)
        7 Giai đoạn vòng đời FM: Pre-training (Self-supervised) -> Fine-tuning -> Evaluation
      Chương 6: Ứng dụng kinh doanh, Rủi ro & Đánh giá
        7 Thách thức lớn: Hallucination, Toxicity, Privacy, Bias, Nondeterminism
        Biện pháp giảm thiểu: RAG, Guardrails, Temperature=0, Clarify
        Lợi thế GenAI: Adaptability, Creativity, Personalization, Scalability
        Chỉ số kinh doanh: User Satisfaction (CSAT, NPS), ROI, ARPU, CLV
      Chương 7: GenAI Toolkit trên AWS
        Amazon Bedrock: Serverless Unified API đa nhà cung cấp, On-demand vs Provisioned
        PartyRock: Nền tảng No-code KHÔNG CẦN tài khoản AWS
        SageMaker JumpStart: 350+ model nguồn mở trên EC2 Instances/Endpoints riêng
        Amazon Q: Q Business (Jira, SharePoint, QuickSight) vs Q Developer (Code, Java Upgrade)
        Tháp dịch vụ 3 tầng: Frameworks -> Managed Services -> GenAI Layer
    Domain 3: Applications of Foundation Models (28%)
      Chương 8: Thiết kế ứng dụng FMs, RAG & Agents
        Tham số suy luận: Temperature, Top P (Nucleus), Top K, Context Window
        Kiến trúc RAG: Ingest -> Retrieve -> Augment -> Generate (Không đổi weights)
        Amazon Bedrock Knowledge Bases & Vector DBs (OpenSearch, Aurora pgvector, Neptune)
        Thang 5 cấp độ tùy biến: In-context -> RAG -> Fine-tuning -> Continued Pre-train -> Pre-train
        Amazon Bedrock Agents: Tự động hóa đa bước qua Action Groups (Lambda)
      Chương 9: Prompt Engineering & Lỗ hổng bảo mật AI
        4 Thành phần Prompt: Instructions, Context, Input Data, Output Indicator
        Negative Prompting: Loại trừ những thứ không mong muốn
        Kỹ thuật: Zero-shot, Few-shot, Chain-of-Thought (CoT - Think step by step)
        5 Lỗ hổng AI: Prompt Injection, Jailbreaking, Data Poisoning, Data Exposure, Model Hijacking
      Chương 10: Fine-Tuning mô hình nền tảng
        Bản chất Fine-Tuning: Thay đổi trọng số Model Weights
        Phương pháp: Instruction Tuning, RLHF, PEFT / Layer Freezing (chống quên lãng)
        Quy trình chuẩn bị dữ liệu: S3, Athena, Data Wrangler, Ground Truth, Lake Formation
        Quy tắc Bedrock: BẮT BUỘC dùng Provisioned Throughput cho Custom Model
      Chương 11: Đánh giá mô hình FMs & Bộ chỉ số
        Phương pháp: Human Evaluation vs Benchmark Datasets (GLUE, SuperGLUE, SQuAD, CodeXGLUE)
        5 Chỉ số cốt lõi: Perplexity (Càng thấp càng tốt), BLEU (Dịch máy), ROUGE (Tóm tắt), BERTScore (Ngữ nghĩa), Accuracy/F1
        Amazon Bedrock Model Evaluation
    Domain 4: Guidelines for Responsible AI (14%)
      Chương 12: Nguyên tắc phát triển AI có trách nhiệm
        8 Trụ cột: Fairness, Transparency, Privacy, Veracity, Robustness, Governance, Safety, Controllability
        Interpretability (Hiểu CÁCH làm) vs Explainability (Hiểu TẠI SAO dự đoán)
        Đánh đổi: Performance vs Transparency (Cây quyết định vs Deep Learning)
        Bền vững môi trường: Chip tiết kiệm điện AWS Trainium (Train), AWS Inferentia (Inference)
        Bias - Variance: Underfitting (High Bias) vs Overfitting (High Variance)
      Chương 13: Minh bạch, Quản trị & Human-Centered Design
        AWS AI Service Cards (Dịch vụ quản lý AWS) vs SageMaker Model Cards (Model tùy biến công ty)
        Amazon SageMaker Clarify: Phát hiện Bias trước/sau huấn luyện, SHAP Values
        3 Nguyên tắc Human-Centered: Amplified Decision-Making, Unbiased, Mutual Learning
    Domain 5: Security, Compliance & Governance (14%)
      Chương 14: Bảo mật cốt lõi trên AWS
        Shared Responsibility: Security OF the Cloud (AWS) vs Security IN the Cloud (Khách hàng)
        AWS IAM: Users, Groups (không lồng nhau), Policies (JSON), Roles (tạm thời)
        Thực hành tốt nhất: Least Privilege, Bật MFA, CẤM dùng Root User hàng ngày
        AWS PrivateLink: Kết nối VPC tới SageMaker/S3/Bedrock KHÔNG QUA Internet
      Chương 15: Bảo mật dữ liệu, Provenance & Lineage
        Kỹ thuật bảo mật: Data Masking, Obfuscation, Differential Privacy, Tokenization, KMS
        Data Provenance (Nguồn gốc xuất xứ) vs Data Lineage (Hành trình biến đổi ETL)
        AWS Glue Data Catalog, Lake Formation, CloudTrail Audit Trails
        Chiến lược quản trị: Data Lifecycles, Data Logging, Data Residency, Data Monitoring
      Chương 16: Tuân thủ pháp lý & Dịch vụ quản trị AWS
        Tiêu chuẩn: ISO/IEC 27002, SOC 1/2/3 Reports, NIST 800-53, Đạo luật EU AI Act 4 tầng rủi ro
        6 Dịch vụ quản trị: AWS Config, Amazon Inspector, Audit Manager, Artifact, CloudTrail, Trusted Advisor
        Generative AI Security Scoping Matrix: Đánh giá 5 chiều kích an toàn
```

---

## 📂 DANH MỤC TRỌNG TÂM 16 CHƯƠNG CHI TIẾT

Nhấn vào từng liên kết bên dưới để xem tài liệu chi tiết, sơ đồ tư duy riêng biệt và bộ câu hỏi trắc nghiệm của từng chương:

1. [**Chương 01: Tổng quan về AI, Machine Learning và Deep Learning**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_01_Tong_Quan_AI_ML_Deep_Learning.md)
   - *Khái niệm AI/ML/DL, Hạ tầng toàn cầu AWS, CNN, RNN, Transformer, Computer Vision vs NLP.*
2. [**Chương 02: Nắm vững các khái niệm cốt lõi về AI và Machine Learning**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_02_Khai_Niem_Cot_Loi_AI_va_ML.md)
   - *Hệ sinh thái SageMaker (Studio, Canvas, Autopilot, Clarify), Các dạng học (Supervised, Unsupervised, RLHF), 4 chế độ Inference, Khi nào KHÔNG dùng AI.*
3. [**Chương 03: Chi tiết các dịch vụ AWS AI Managed Services**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_03_Dich_Vu_AI_Managed_Services_AWS.md)
   - *Deep dive 13 dịch vụ: Rekognition, Textract, Comprehend, Translate, Transcribe, Polly, Lex, Kendra, Personalize, Fraud Detector, Forecast, MTurk, A2I.*
4. [**Chương 04: Amazon SageMaker AI và Vòng đời phát triển Machine Learning**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_04_Amazon_SageMaker_AI_va_Vong_Doi_ML.md)
   - *7 giai đoạn ML Lifecycle, Hyperparameters vs Parameters, 4 cấp độ Container JumpStart, Bộ chỉ số phân loại (Precision, Recall, F1) & hồi quy (RMSE, R2), Data Drift.*
5. [**Chương 05: Generative AI - Các thành phần cốt lõi, Các loại mô hình và Vòng đời**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_05_Generative_AI_Thanh_Phan_Mo_Hinh_Vong_Doi.md)
   - *Foundation Models, Tokens, Embeddings, Semantic Search, Chunking with Overlap, Multimodal, Diffusion Models (Forward & Reverse), Vòng đời FM.*
6. [**Chương 06: Các ứng dụng kinh doanh của Generative AI, Rủi ro và Đánh giá giá trị**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_06_Ung_Dung_Kinh_Doanh_Cua_Generative_AI.md)
   - *7 rủi ro lớn (Ảo giác, Độc hại, Bảo mật, Tính bất định), Biện pháp giảm thiểu (RAG, Guardrails), Các chỉ số giá trị kinh doanh (CSAT, NPS, ARPU, CLV).*
7. [**Chương 07: Bộ công cụ Generative AI trên AWS - Bedrock, PartyRock, JumpStart và Amazon Q**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_07_GenAI_Toolkit_Bedrock_PartyRock_SageMaker_JumpStart.md)
   - *Amazon Bedrock (On-demand vs Provisioned), PartyRock (Không cần tài khoản AWS), SageMaker JumpStart, Amazon Q Business vs Q Developer, Tháp 3 tầng AI/ML.*
8. [**Chương 08: Thiết kế ứng dụng Foundation Models - RAG, Agents và Vector Databases**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_08_Thiet_Ke_Ung_Dung_FM_RAG_Agents_VectorDB.md)
   - *Tham số suy luận (Temperature, Top P, Top K), Kiến trúc RAG 4 bước, Bedrock Knowledge Bases, Lựa chọn Vector DB (OpenSearch, Aurora pgvector, Neptune), Bedrock Agents.*
9. [**Chương 09: Kỹ thuật Prompt Engineering và Các lỗ hổng bảo mật AI**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_09_Prompt_Engineering_va_Lo_Hong_Bao_Mat_AI.md)
   - *4 thành phần Prompt chuẩn, Negative Prompting, Zero-shot, Few-shot, Chain-of-Thought (CoT), 5 kiểu tấn công: Prompt Injection, Jailbreaking, Data Poisoning.*
10. [**Chương 10: Tinh chỉnh mô hình nền tảng (Fine-Tuning FMs Deep Dive)**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_10_Fine_Tuning_Mo_Hinh_Nen_Tang.md)
    - *Instruction Tuning, RLHF, PEFT / Layer Freezing, Chuỗi công cụ chuẩn bị dữ liệu (S3, Athena, Data Wrangler, Ground Truth), Quy tắc Provisioned Throughput.*
11. [**Chương 11: Đánh giá mô hình nền tảng - Phương pháp và Bộ chỉ số đo lường**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_11_Danh_Gia_Mo_Hinh_FM_Phuong_Phap_va_Chi_So.md)
    - *Human Evaluation vs Benchmarks (GLUE, SuperGLUE, SQuAD, CodeXGLUE), Perplexity (Càng thấp càng tốt), BLEU (Dịch), ROUGE (Tóm tắt), BERTScore (Ngữ nghĩa).*
12. [**Chương 12: Phát triển AI có trách nhiệm (Responsible AI Development)**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_12_Phat_Trien_AI_Co_Trach_Nhiem_Responsible_AI.md)
    - *8 nguyên tắc Responsible AI, Interpretability vs Explainability, Performance-Transparency Tradeoff, Phần cứng tiết kiệm điện Trainium & Inferentia, Bias vs Variance.*
13. [**Chương 13: Quản trị AI - AWS AI Service Cards, SageMaker Model Cards, Clarify và Thiết kế lấy con người làm trung tâm**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_13_AI_Governance_Service_Cards_Model_Cards_Clarify.md)
    - *AWS AI Service Cards vs SageMaker Model Cards, Tính năng toàn diện của SageMaker Clarify (SHAP values), 3 nguyên tắc Human-Centered Design.*
14. [**Chương 14: Các thực hành bảo mật cốt lõi trên AWS - Shared Responsibility, IAM và PrivateLink**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_14_Bao_Mat_AWS_Shared_Responsibility_IAM_PrivateLink.md)
    - *Mô hình Shared Responsibility (Security OF vs IN the Cloud), Quản trị danh tính IAM (Least privilege, MFA, Cấm Root), AWS PrivateLink cho AI Workloads.*
15. [**Chương 15: Bảo mật dữ liệu và Quản trị dữ liệu cho hệ thống AI (Data Governance & Lineage)**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_15_Bao_Mat_Du_Lieu_Provenance_Lineage_Governance.md)
    - *4 trụ cột Secure Data Engineering, Kỹ thuật bảo vệ quyền riêng tư (Differential Privacy, Masking, Tokenization), Data Provenance vs Data Lineage, 4 chiến lược quản trị.*
16. [**Chương 16: Bảo mật hệ thống AI, Tiêu chuẩn tuân thủ pháp lý và Các dịch vụ quản trị AWS**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/Chuong_16_Bao_Mat_AI_Tuan_Thu_Compliance_Frameworks.md)
    - *Tiêu chuẩn ISO 27002, SOC Reports, Đạo luật EU AI Act 4 tầng rủi ro, Phân biệt 6 dịch vụ quản trị: Config, Inspector, Audit Manager, Artifact, CloudTrail, Trusted Advisor.*

---

## 🏆 TÀI LIỆU ÔN THI BỔ TRỢ ĐẶC BIỆT
- [**Bảng Tra Cứu Cấp Tốc & So Sánh Toàn Bộ Dịch Vụ AI/ML (CheatSheet)**](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/AIF-C01_CheatSheet_On_Thi_Cap_Toc.md)
  *(Bao gồm bảng tổng hợp từ khóa vàng 3 giây, ma trận so sánh các cặp dịch vụ hay gây nhầm lẫn nhất và chiến lược thi phòng thi)*.

---

## 💡 CHIẾN LƯỢC ÔN THI HIỆU QUẢ TRONG 7 NGÀY
1. **Ngày 1 - 2 (Làm chủ Domain 1 - 20%):** Đọc kỹ Chương 1 đến Chương 4, hiểu sâu về phân biệt ML/DL/AI và các dịch vụ Managed AI (Rekognition, Textract, Comprehend).
2. **Ngày 3 - 4 (Chinh phục Domain 2 & Domain 3 - 52% số điểm đề thi):** Đây là phần quan trọng nhất quyết định bạn Đỗ hay Trượt. Học kỹ Chương 5 đến Chương 11, đặc biệt là kiến trúc **Amazon Bedrock, RAG, Prompt Engineering, và Bộ chỉ số BLEU/ROUGE/Perplexity**.
3. **Ngày 5 (Nắm chắc Domain 4 & Domain 5 - 28%):** Học Chương 12 đến Chương 16. Thuộc lòng sự khác nhau giữa Service Cards vs Model Cards, Shared Responsibility Model, và 6 dịch vụ quản trị AWS.
4. **Ngày 6 (Luyện tập thực chiến):** Làm lại toàn bộ câu hỏi trắc nghiệm ở cuối mỗi chương trong bộ tài liệu này, đọc kỹ phần giải thích chi tiết.
5. **Ngày 7 (Tổng kết & Đi thi):** Đọc lại file [CheatSheet Ôn Thi Cấp Tốc](file:///home/phikhanhcr/Desktop/AWS-/AIF-C01_Study_Guide/AIF-C01_CheatSheet_On_Thi_Cap_Toc.md) để củng cố các từ khóa then chốt trước khi bước vào phòng thi.

*Chúc bạn hoàn thành xuất sắc kỳ thi và sớm nhận chứng chỉ AWS Certified AI Practitioner (AIF-C01)!*
