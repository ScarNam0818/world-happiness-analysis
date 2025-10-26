# 🌍 World Happiness Data Analysis (2019)

**概要**  
Kaggle の World Happiness Report (2019) を用いて、各国の幸福度（Score）に影響する要因を探索しました。  
主に `GDP per capita`、`Social support`、`Healthy life expectancy` の関連性を可視化・回帰分析しています。

## 🔎 目次
- データ: world-happiness-report-2019.csv  
- ノートブック: `happiness_analysis.ipynb`  
- 主要結論: 社会福祉と健康寿命が幸福度に強い影響を示す傾向が確認されました。

## 実行環境
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn
- Google Colab 推奨（そのまま実行できます）

## 使い方
1. リポジトリをクローンまたはダウンロード  
2. `happiness_analysis.ipynb` を Colab にアップロードして実行（すべてのセルが上から実行可能）  
3. 主要図は `fig1.png`, `fig2.png` に保存済み

## ファイル構成
- `happiness_analysis.ipynb` — 分析ノートブック
- `data/` — 元データ（READMEではデータ置き場を明示）
- `fig1.png` — GDP vs Happiness（サンプル画像）

## 主要結果の要約
- GDP per capita、Social support、Healthy life expectancy が幸福度と高相関  
- Generosity や Corruption perception は相関が弱い  
- 線形回帰モデルの R² = 0.68（説明変数：GDP, Social support, Healthy life expectancy）

---

## 連絡先
- GitHub: https://github.com/あなたのユーザ名
- Email: your.email@example.com

