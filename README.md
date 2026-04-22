# 📖 Story Codex

Chào mừng đến với Bách khoa toàn thư cốt truyện (Story Codex).
Repository này đóng vai trò là "bộ não dài hạn" cho câu chuyện. AI (Gemini) sẽ đọc repository này để duy trì tính nhất quán tuyệt đối về nhân vật, thế giới và văn phong.

## 🗂️ Cấu Trúc Thư Mục

- 📜 **/01_Rules/**: Chứa các quy tắc viết (Writing Mechanics), cách xây dựng xung đột và giới hạn nội dung (NSFW/Violence).
- 🌍 **/02_World_Building/**: Quy tắc thế giới, bối cảnh xã hội, địa điểm.
- 🎭 **/03_Characters/**: Thẻ nhân vật (Character Cards). **Mỗi nhân vật là một file riêng biệt**. AI phải tham chiếu thư mục này để bắt chước chính xác giọng điệu và nắm bắt vết thương tâm lý của nhân vật.
- 💾 **/04_Story_Logs/**: Nơi lưu trữ các Checkpoint/Tóm tắt theo từng chương để AI không quên những sự kiện đã diễn ra.

---

## 🤖 Hướng dẫn dành cho AI (AI Instructions)

When processing this repository to generate story continuations:
1. **Character Priority:** Always cross-reference the files in `/03_Characters/` for the characters active in the current scene. Match their "Voice Sample" and honor their "Wound" and "Mask".
2. **Context Anchor:** Read the latest files in `/04_Story_Logs/` to understand the immediate emotional context and recent events before writing.
3. **World Consistency:** Adhere to the societal and environmental rules defined in `/02_World_Building/`.
4. **Tone & Conflict:** Apply the Three-Beat conflict engine and maturity guidelines from `/01_Rules/`.
