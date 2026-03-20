# Japanese Grape Price Analysis
## From Intuition to Data — Explaining Japanese Grape Prices Through Variety Systems and Appearance
## 直感からデータへ：品種構造と外観から読み解く日本の葡萄価格

## Project Overview

In premium fruit markets, grape pricing is influenced by multiple factors such as variety, size, and visual appearance.

This project investigates how grape prices are formed through a structured analysis pipeline, including:

- Variety-based feature analysis  
- Price distribution analysis  
- Modeling with feature interactions  

The goal is to understand how different factors jointly influence pricing, rather than relying on a single explanation.

## 🇯🇵 プロジェクト概要

高級果実市場において、ぶどうの価格は品種・サイズ・外観など複数の要因に影響される。

本プロジェクトでは、以下の分析プロセスを通じて価格形成を検証する：

- 品種グループ別の特徴量分析  
- 価格分布の分析  
- 交互作用を含むモデリング  

単一要因ではなく、複数要素の組み合わせによる価格形成を理解することを目的とする。

## Analysis Structure

This project is organized into four main notebooks:

1. **01_data_collection.ipynb**  
   → Data structure and preprocessing workflow  

2. **02_feature_analysis_by_variety_group.ipynb**  
   → Comparison of physical characteristics across variety groups  

3. **03_price_analysis.ipynb**  
   → Price distribution and relationship with key features  

4. **04_modeling.ipynb**  
   → Regression and machine learning models with feature interactions  


## 🇯🇵 分析構成

本プロジェクトは以下の4つのNotebookで構成されています：

1. **01_data_collection.ipynb**  
   → データ構造および前処理  

2. **02_feature_analysis_by_variety_group.ipynb**  
   → 品種グループ別の外観特徴の比較  

3. **03_price_analysis.ipynb**  
   → 価格分布および特徴量との関係分析  

4. **04_modeling.ipynb**  
   → 回帰分析および交互作用を含むモデリング

## Key Findings

- Some differences were observed between grape variety groups (e.g., Shine Muscat vs Kyoho) in both price levels and physical characteristics  

- However, these differences are not substantial, and there is considerable overlap, suggesting that variety alone does not determine price  

- Price distributions are right-skewed, with a small number of high-priced products influencing overall trends  

- Physical features such as grain size and bunch structure contribute to pricing, especially when considered in combination  

- Interaction features improved model performance (R²: 0.35 → 0.49), indicating that visual balance plays an important role  

- Overall, grape pricing is best explained by a combination of variety, appearance, and their interactions  

## 🇯🇵 主な知見

- 品種グループ間で価格水準および外観特徴に一定の違いが見られた  

- ただしその差は大きくなく、分布にも重なりがあるため、品種のみで価格が決まるわけではない  

- 価格分布は右に歪んでおり、一部の高価格商品が全体に影響を与えている  

- 粒径や房構造などの外観特徴は価格に寄与するが、組み合わせによってより強く影響する  

- 交互作用特徴量の導入によりモデル性能が向上（R²: 0.35 → 0.49）  

- ブドウ価格は、品種・外観・その組み合わせによって説明される

##  Limitations

- Small dataset (~200 samples)  
- Manual measurement introduces noise  
- Sampling bias due to limited store selection  
- Missing variables (e.g., sugar content, branding)  
- Some shape categories not analyzed due to limited data  

## 🇯🇵 制約

- サンプル数が少ない（約200件）  
- 手動測定による誤差  
- 特定店舗に偏ったデータ収集（サンプリングバイアス）  
- 糖度・ブランドなどの変数が未考慮  
- 一部形状はサンプル不足のため未分析

## Why This Matters for Agriculture

This project highlights how pricing in agricultural markets is influenced by multiple interacting factors rather than a single attribute.

The findings suggest potential applications in:

- Quality evaluation based on measurable features  
- Data-driven pricing strategies  
- Aligning production with market expectations  

## 🇯🇵 農業への意義

本分析は、農産物価格が単一要因ではなく複数要素の組み合わせによって決まることを示した。

これにより以下の応用が期待される：

- 客観的な品質評価  
- データに基づく価格戦略  
- 生産と市場ニーズの適合

## Conclusion

This project demonstrates how intuitive perceptions of grape quality can be translated into measurable and explainable factors.

The results indicate that pricing is shaped by the interaction between variety and visual characteristics, rather than by a single dominant factor.

Despite data limitations, this study provides a structured approach to understanding agricultural pricing through data analysis.

## 🇯🇵 まとめ

本プロジェクトは、「見た目が良い＝高そう」という直感をデータで説明可能な形にする試みである。

分析の結果、価格は単一の要因ではなく、品種と外観の相互作用によって形成されることが示唆された。

データの制約はあるものの、農産物価格をデータで理解するための枠組みを提示した。
