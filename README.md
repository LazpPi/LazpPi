# Hi there, I'm LazpPi 👋

情報系大学院生 / 趣味は絵を描くことで、好きなものは珈琲です。
大学院で情報科学・データ分析・認知科学などを幅広く学びながら、Pythonを中心に実践的なWebシステムやAI活用の開発に取り組んでいます。
学内では大学公式イベントの賞金を元手に、完全セルフサービスの「ゼミカフェ」を立ち上げ、空間を快適にするための無人化・スマート化システムの開発と運用を行っております。

---

## 🎯 Career Vision

**Web（Front/Back）× モバイル（iOS/Android）に対応できるフルスタックエンジニア**

> **Why?**  
> 幅広い技術スタックを持つことは、**AI駆動開発時代における開発力・プロンプティング力の向上**に直結し、将来的にチームや周りのエンジニアを柔軟にサポートできる力になると考えているためです。

---

## 🛠️ Skills & Knowledge

### Programming Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-288253?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![R](https://img.shields.io/badge/R-4F4F4F?style=for-the-badge&logo=r&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Computer Science & Data Analysis
- **データ分析:** R / Python / Excel を用いたデータ分析
- **機械学習:** 深層学習（Deep Learning）の基礎理論および実装
- **行動心理:** 授業にて行動経済学やゲーミフィケーションの知見を用いた、既存システムの分析経験

---

## 🚀 Featured Projects

### 💳 [smart_payment_system](https://github.com/LazpPi/smart_payment_system)
**ゼミカフェのスマート化：スマート決済システム**
- **概要**: ゼミ内カフェのアナログな利用管理（紙の手書き）と売上データのブラックボックス化を解決する自動決済・売上管理Webシステム。NFC学生証や硬貨の識別からクラウド連携・ダッシュボード表示までを無人レジとして自動化しました。
- **使用技術**: `Python`, `C++`, `Raspberry Pi`, `M5StickC Plus2`, `PaSoRi (NFC/FeliCa)`, `HTML/CSS (Tailwind)`, `JavaScript`, `Firebase Firestore (NoSQL)`
- **アピールポイント**: 
  - **エッジとクラウドの分離**: コインセレクターのミリ秒単位のパルス検知をリアルタイム処理が得意なマイコンに委譲。メイン処理との役割分担によりシステムの堅牢性を担保しました。
  - **高可用性（無人運用）設計**: Firebase `onSnapshot` によるリアルタイムWebダッシュボードと、Linux `systemd` による完全自動起動＆自己修復プロセスを構築し、耐障害性の高いシステムを設計しました。

### 📢 [auto_ad_system](https://github.com/LazpPi/auto_ad_system)
**ゼミカフェのスマート化：自動広告システム**
- **概要**: 人が近づいた時のみプロジェクターを起動して解説動画等を流すことで、従来の紙チラシやQRコード案内の手間を解消し、ユーザが手ぶらでの情報提供を実現しました。
- **使用技術**: `Python`, `Raspberry Pi 400`, `mpv`, `M5Stack PIR/IRセンサー`, `プロジェクター`
- **アピールポイント**: 
  - **現場運用に配慮した状態管理とハード選定**: 機器の過熱を防ぐ強制クールダウンや、夜間スリープ機能を実装。また、他のゼミ生が簡単に一時停止（Ctrl+C）できるようキーボード一体型ラズパイを採用するなど、実際の利用環境（寝泊まりする学生など）に配慮した設計を行いました。

### 🎨 [ai-drawing-game](https://github.com/LazpPi/ai-drawing-game)
**AIとお絵かき伝言ゲーム**
- **概要**: MediaPipeを用いた手の骨格推定による「空中お絵描き」と、PyTorchで構築した自作CNNモデルによる「リアルタイム画像判定」を組み合わせた体験型システム。オープンキャンパスにて高校生向けに展示しました。
- **使用技術**: `Python`, `PyTorch`, `OpenCV`, `MediaPipe Hands`
- **アピールポイント**: 
  - **UI/UX最適化**: 立ち位置や体格差を補正する「4点キャリブレーション機能」や、外部モニター投影時の画面比率崩れを防ぐ「自動パディング処理」を実装。
  - **データ駆動型の改善**: 推定正誤をCSVへ自動記録する仕組みを構築し、事後アンケートと組み合わせた定量的なデータ分析（PDCA）を可能にしました。

### 👁️ 机上面視点推定システム
**研究**
- **概要**: 高価な専用機器や複雑な設定を必要とせず、一般的なWebカメラとプロジェクター投影を用いてデスク作業時の注視点を追跡・分析するシステムを研究中。作業者の「視線データ」の解析を可能にし、現場改善や技能継承における動作研究のコスト削減に貢献します。
- **使用技術**: `Python`, `MediaPipe`, `OpenCV`, `NumPy`, `Pandas`, `scikit-learn`, `SciPy`

---

## 📊 GitHub Stats

![LazpPi's GitHub stats](https://github-readme-stats.vercel.app/api?username=LazpPi&show_icons=true&theme=radial)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LazpPi&layout=compact&theme=radial)
