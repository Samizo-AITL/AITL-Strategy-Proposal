## 🧠 **AITLとは | What is AITL?**

**AITL (All-in-Theory Logic)** は、以下の**三層アーキテクチャ**で構成されます：

- 🔍 **Logic Layer** – **AI推論・異常検出・仮説生成**（ChatGPT等と連携）  
- ⚙️ **Control Layer** – **PID**, **MPC**, **FSM統合**による意思決定制御  
- 🌍 **Physical Layer** – **センサ・アクチュエータ・実世界モデル**  
　（**EduMechaやSystemDK**による物理制約設計と連携）

This three-layer architecture bridges **AI** and **real-world physical control**,  
enabling **explainable**, **robust**, and **field-deployable** intelligent systems.  
**SystemDK provides the constraint-aware design platform enabling GAA / AMS / MRAM PoC integration.**

---

## 📌 **提案の柱 | Core Proposal Themes**

- 🏫 **教育：Edusemiを中核とした異分野融合教材**  
  **半導体技術 × 制御理論 × メカ設計 × AI** を横断する**次世代STEM教育**

- 🛠 **産業応用：中小製造業・災害対応現場へのPoC展開**  
  **AITL-H**や**EduController**により、**実装容易かつ安全なAI制御**の地域導入を推進

- 🧱 **物理制約ベース設計：SystemDKによるPoC支援基盤**  
  AITLアーキテクチャの**実世界適合性と設計実装性を担保**するために、SystemDKを用いた**GAA / AMS / MRAM設計**の統合PoCを展開。物理制約の視点から**AI制御とデバイス実装の接続**を支援。

- ⚡ **災害・エネルギー分野：Edge AIによる自律制御**  
  **センサ系＋LLM**による**判断・適応型の災害対応設計モデル**（Rekiden等と連携）

- 🧠 **AI安全性と透明性：構造制御に基づく正しさ保証**  
  **FSM・PID内包の明示的アーキテクチャ**により、**LLM制御の透明性と可視性**を担保

- 🇯🇵 **地域主導の展開：教育・設計・製造の一体型導入モデル**  
  **高専・大学・地域企業**が連携して**AITL技術**を吸収・実装できる構造を提示

---

## 📦 **関連プロジェクト | Linked Repositories**

- [📘 **Edusemi-v4x**](https://github.com/Samizo-AITL/Edusemi-v4x)  
  👉 **半導体デバイス設計・プロセス教育**の中核教材（**sky130演習**含む）

- [🎛 **EduController**](https://github.com/Samizo-AITL/EduController)  
  👉 **PID・状態空間・AI制御**までを段階的に学ぶ制御教材

- [🛠 **EduMecha**](https://github.com/Samizo-AITL/EduMecha)  
  👉 **Creoを用いた筐体設計・図面演習・量産プロセス教育**

- [🧱 **SystemDK-PoC**](https://github.com/Samizo-AITL/SystemDK-PoC)  
  👉 **GAA/AMS/MRAMの統合PoC設計**と**物理制約統合設計**の基盤（Edusemi・AITL-Hと連携）

- [🤖 **AITL-H**](https://github.com/Samizo-AITL/AITL-H)  
  👉 **FSM×PID×LLMの統合制御アーキテクチャとPoC設計群**

- [🧠 **SamizoGPT**](https://github.com/Samizo-AITL/SamizoGPT)  
  👉 **ChatGPTによるプロンプト支援・教材構築・GUI支援テンプレート**

- [📄 **提言書ドラフト v3**](./AITL_Strategy_Proposal_Draft_v3.md)  
  👉 **ChatGPTテンプレートによる統合型設計戦略**を含む**最新版提言書**
