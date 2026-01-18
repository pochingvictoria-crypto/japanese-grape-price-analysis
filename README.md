# Japanese Grape Price Analysis
## From Intuition to Data — Explaining Japanese Grape Prices Through Variety Systems and Appearance
### Overview

This project explores how grape prices in the Japanese market are formed, focusing on the relationship between grape variety systems and physical appearance.
While high prices are often intuitively attributed to specific premium varieties (such as Shine Muscat), this analysis examines whether observable physical characteristics better explain price differences.

本プロジェクトは、日本市場におけるぶどう価格の形成要因を分析し、
品種系統（香印系・巨峰系）と外観特性の関係に着目しています。
高価格は特定の高級品種によるものと直感的に考えられがちですが、
本分析では、実際に価格を左右している要因が何であるかをデータから検証します。
### Data

Due to data usage considerations, the raw dataset is not publicly shared.
The data structure, variable definitions, and preparation workflow are documented in 01_data_collection.ipynb.

データ利用上の理由により、本プロジェクトでは元データの公開は行っていません。
データ構造、変数定義、および前処理の流れについては
01_data_collection.ipynb に記載しています。
### Methods

The analysis workflow is documented in the following notebooks:

01_data_collection.ipynb: data structure and preparation

02_eda.ipynb: exploratory data analysis

03_modeling.ipynb: regression and machine learning models

本分析は以下の Notebook によって構成されています。

01_data_collection.ipynb：データ構造および前処理

02_eda.ipynb：探索的データ分析（EDA）

03_modeling.ipynb：回帰分析および機械学習モデル
### Key Findings

Grape prices exhibit a right-skewed distribution, with a small number of high-priced products.

Average prices vary across grape varieties, with Shine Muscat-type varieties generally positioned at higher price levels.

A clear positive relationship is observed between grain diameter and price, suggesting that visual appearance plays a major role in price formation.

Regression and machine learning models indicate that physical characteristics explain price variation more consistently than variety labels alone.

ぶどう価格は右に裾の長い分布を示し、一部の高価格商品が平均値を押し上げています。

品種ごとに平均価格には差があり、香印系品種は全体的に高価格帯に位置しています。

粒径と価格の間には明確な正の関係が見られ、外観要素が価格形成に大きく関与していることが示唆されます。

回帰分析および機械学習モデルの結果から、品種名そのものよりも、外観特性の方が価格変動を安定して説明する傾向が確認されました。
### Limitations

The dataset is based on manually collected samples and is relatively small in size.

Measurements were taken manually, introducing potential measurement error.

Grape shape varies across samples, and some shape categories could not be separately analyzed due to limited sample size.

Results should therefore be interpreted as exploratory rather than definitive.

本データは手作業による収集であり、サンプル数は限定的です。

寸法測定は手動で行われているため、一定の測定誤差が含まれる可能性があります。

ぶどうの形状には個体差があり、一部の形状タイプはサンプル不足のため個別分析を行っていません。

そのため、本結果は探索的な知見として解釈されるべきものです。
### Conclusion

With the increasing diversity of grape varieties in the Japanese market, consumers often face difficulty understanding what differentiates one grape from another.
This project demonstrates how data analysis can be used to translate intuitive impressions—such as “this grape looks premium”—into measurable and explainable factors.
Despite limitations in data scale, the process of validating intuition through data provided valuable insights into market pricing mechanisms.

近年、日本のぶどう市場では品種の多様化が進み、消費者にとって違いを理解することが難しくなっています。
本プロジェクトでは、「見た目が良い＝高そう」といった直感を、データを用いて説明可能な要素へと分解する試みを行いました。
データの制約はあるものの、感覚をデータで検証するプロセスそのものが、市場理解において有意義な経験となりました。
