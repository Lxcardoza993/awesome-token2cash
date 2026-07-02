<a id="awesome-token2cash"></a>
# 📈 Awesome Token2Cash

**Languages:** [English](README.md) • [简体中文](README.zh-CN.md) • [Español](README.es.md) • **日本語** • [한국어](README.ko.md) • [Français](README.fr.md) • [Русский](README.ru.md)

> 株価分析、トレーディング、金融学習向けの**マルチエージェント＆大規模言語モデル（LLM）プラットフォーム**の厳選リスト。
> この分野を体系的に整理し、先人の肩の上に立つことで、車輪の再発明をせずに学び、比較し、構築できるようにします。
>
> 各エントリーには⭐スター数、主要なプログラミング言語、ライセンスが付記されているため、価値あるものをすばやく判断できます。

<a id="acknowledgments"></a>
## 🙏 Acknowledgments

これらのリストの先人による整理に基づいて構築しています：

- [AlanJiang98/Awesome-LLM-Trading](https://github.com/AlanJiang98/Awesome-LLM-Trading)
- [DataArcTech/Awesome-FinLLMs](https://github.com/DataArcTech/Awesome-FinLLMs)
- [Eleanorkong/Awesome-Financial-LLM-Bias-Mitigation](https://github.com/Eleanorkong/Awesome-Financial-LLM-Bias-Mitigation)
- [georgezouq/awesome-ai-in-finance](https://github.com/georgezouq/awesome-ai-in-finance)
- [wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant)
- [leoncuhk/awesome-quant-ai](https://github.com/leoncuhk/awesome-quant-ai)
- [Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers](https://github.com/Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers)
- [kennethleungty/Finance-LLMs](https://github.com/kennethleungty/Finance-LLMs)
- [AI4Finance-Foundation/Awesome_AI4Finance](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance)
- [hananedupouy/LLMs-in-Finance](https://github.com/hananedupouy/LLMs-in-Finance)
- [anusky95/FinAI](https://github.com/anusky95/FinAI)
- [Open-Finance-Lab/FinLLM-Leaderboard](https://github.com/Open-Finance-Lab/FinLLM-Leaderboard)
- [AI4Finance-Foundation/Awesome_FinRL](https://github.com/AI4Finance-Foundation/Awesome_FinRL)
- [thuquant/awesome-quant](https://github.com/thuquant/awesome-quant)
- [grananqvist/Awesome-Quant-Machine-Learning-Trading](https://github.com/grananqvist/Awesome-Quant-Machine-Learning-Trading)
- [czyssrs/LLM_X_papers](https://github.com/czyssrs/LLM_X_papers)
- [masamasa59/ai-agent-papers](https://github.com/masamasa59/ai-agent-papers)
- **[Telegram OpenClaw 中文社区](https://t.me/OpenClaw_Group)** — Telegram上の中国語OpenClawコミュニティ — 議論とサポートに感謝します。
- **[Linux.do](https://linux.do)** — 中国語の開発者＆技術コミュニティ（Discourse） — フィードバックと拡散に感謝します。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg) ![Tools](https://img.shields.io/badge/tools-94%2B-blue) ![Focus: Multi-Agent + LLM Stocks](https://img.shields.io/badge/focus-Multi--Agent%20%2B%20LLM%20stocks-purple) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen) [![Telegram](https://img.shields.io/badge/Telegram-OpenClaw-2AABEE?style=flat&logo=telegram&logoColor=white)](https://t.me/OpenClaw_Group)

---

## Table of Contents
- [1. 🏛️ 基盤金融LLM](#foundation-llms)
- [2. 🤖 マルチエージェント トレーディング＆分析フレームワーク](#multi-agent)
- [3. 📈 LLM 株価分析・予測・調査レポート](#stock-analysis)
- [4. 📰 金融センチメント＆ニュース/ソーシャル NLP](#sentiment-nlp)
- [5. 💹 LLM/エージェント トレードボット＆バックテスト](#trading-bots)
- [6. 🎓 学習 / 教育プラットフォーム](#learning)
- [7. 📊 データセット＆ベンチマーク](#datasets)
- [8. 🧪 コード付き研究論文](#papers)
- [9. 🧩 取り入れられるアイデア チートシート](#absorb)
- [🙋 貢献](#contributing) · [🙏 Acknowledgments](#acknowledgments) · [📜 ライセンス](#license)

---

## Legend
| Marker | Meaning |
|------|------|
| ⭐ | GitHubスター数（調査時点の概算値） |
| `Language` | 主要コード言語 |
| `License` | ライセンス |

<a id="foundation-llms"></a>
## 1. 🏛️ 基盤金融LLM

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | オープンソース金融LLMフレームワーク。データ、ファインチューニング、強化学習、トレーディング応用をカバー。 | 20.8k | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinGPT) |
| [XuanYuan](https://github.com/Duxiaoman-DI/XuanYuan) | 度小満による中国語金融対話大規模言語モデル。 | 1.3k | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Duxiaoman-DI/XuanYuan) |
| [DISC-FinLLM](https://github.com/FudanDISC/DISC-FinLLM) | 専門的な金融コンサルティング向け中国語金融LLM。 | 888 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/FudanDISC/DISC-FinLLM) |
| [PIXIU](https://github.com/The-FinAI/PIXIU) | 金融LLM、指示チューニングデータ、包括的評価ベンチマーク。 | 872 | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/The-FinAI/PIXIU) |
| [InvestLM](https://github.com/AbaciNLP/InvestLM) | 金融・投資に特化した大規模言語モデル。 | 153 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AbaciNLP/InvestLM) |
| [CFGPT](https://github.com/TongjiFinLab/CFGPT) | 大規模言語モデルベースの中国語金融アシスタント。 | 91 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/TongjiFinLab/CFGPT) |
| [BloombergGPT_zh](https://github.com/sunshineyg2018/BloombergGPT_zh) | BloombergGPTの中国語再現/実装。 | 58 | `—` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/sunshineyg2018/BloombergGPT_zh) |
| [FinRAG](https://github.com/AI4Finance-Foundation/FinRAG) | 金融領域向け検索増強生成（RAG）システム。 | 53 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRAG) |

<a id="multi-agent"></a>
## 2. 🤖 マルチエージェント トレーディング＆分析フレームワーク

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [TradingAgents](https://github.com/TauricResearch/TradingAgents) | 専門的なトレーディング企業の役割をシミュレートするマルチエージェントLLMトレーディングフレームワーク。 | 90.3k | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/TauricResearch/TradingAgents) |
| [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | LLMを活用した金融分析のためのオープンソースAIエージェントプラットフォーム。 | 7.4k | `Jupyter Notebook` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRobot) |
| [TradingAgents-astock](https://github.com/simonlin1212/TradingAgents-astock) | TradingAgentsベースのA株マルチエージェント投資研究フレームワーク。 | 1.6k | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/simonlin1212/TradingAgents-astock) |
| [AgenticTrading](https://github.com/Open-Finance-Lab/AgenticTrading) | LLM駆動のトレーディングエージェントとバックテストのためのオープンソースプラットフォーム。 | 260 | `Python` | `NOASSERTION` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Open-Finance-Lab/AgenticTrading) |
| [AlpacaTradingAgent](https://github.com/huygiatrng/AlpacaTradingAgent) | Alpacaと連携して実取引も可能なマルチエージェントLLMトレーディングフレームワーク。 | 238 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/huygiatrng/AlpacaTradingAgent) |
| [MarketAgents](https://github.com/marketagents-ai/MarketAgents) | 経済AIエージェントと市場シミュレーションのためのオーケストレーションフレームワーク。 | 116 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/marketagents-ai/MarketAgents) |
| [LLM-Economist](https://github.com/sethkarten/LLM-Economist) | メカニズム設計と税制政策向けの大規模LLMマルチエージェントシミュレーション。 | 114 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/sethkarten/LLM-Economist) |
| [ai-economist](https://github.com/salesforce/ai-economist) | 社会経済行動と政策設計のためのマルチエージェントRLフレームワーク。 | 110 | `Python` | `BSD-3-Clause` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/salesforce/ai-economist) |
| [orallexa-ai-trading-agent](https://github.com/alex-jb/orallexa-ai-trading-agent) | 強気・弱気・判定エージェントによる議論を行う自己調整型マルチエージェントトレーディングシステム。 | 52 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/alex-jb/orallexa-ai-trading-agent) |

<a id="stock-analysis"></a>
## 3. 📈 LLM 株価分析・予測・調査レポート

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [deep-research-machine](https://github.com/druce/deep-research-machine) | LLMを使った非同期の株式調査パイプライン。 | 11 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/druce/deep-research-machine) |
| [AI-Stock-Analyst-Agent-Langchain-Deepseek](https://github.com/Bisma-Shafiq/AI-Stock-Analyst-Agent-Langchain-Deepseek) | 株価分析のためのLangChain/DeepSeekエージェント。 | 7 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Bisma-Shafiq/AI-Stock-Analyst-Agent-Langchain-Deepseek) |
| [openbb-rag-financial-research-agent](https://github.com/sandole/openbb-rag-financial-research-agent) | SEC提出書類と金融調査のためのRAGエージェント。 | 7 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/sandole/openbb-rag-financial-research-agent) |
| [stock_research_agent](https://github.com/druce/stock_research_agent) | Claude agent SDKで株価調査レポートを生成。 | 3 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/druce/stock_research_agent) |
| [multi-horizon-financial-agent](https://github.com/srx7703/multi-horizon-financial-agent) | SEC資料と市場調査ブリーフを統合するツール使用型エージェント。 | 2 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/srx7703/multi-horizon-financial-agent) |
| [stockgpt](https://github.com/ESJavadex/stockgpt) | GPT-4で株価を分析し投資レポートを生成。 | 2 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ESJavadex/stockgpt) |
| [StockerLens](https://github.com/Aswin-Cheerngodan/StockerLens) | センチメントとチャート分析を組み合わせたマルチモーダル株価予測。 | 1 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Aswin-Cheerngodan/StockerLens) |
| [stock_signal_analyzer](https://github.com/mmovsesyan/stock_signal_analyzer) | LLMニュースセンチメントと計画による自己学習型株価システム。 | 1 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/mmovsesyan/stock_signal_analyzer) |
| [daily_stock_analysis](https://github.com/chief0714/daily_stock_analysis) | LLM駆動の日次多国間株価分析。 | 1 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/chief0714/daily_stock_analysis) |

<a id="sentiment-nlp"></a>
## 4. 📰 金融センチメント＆ニュース/ソーシャル NLP

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [finBERT](https://github.com/ProsusAI/finBERT) | ニュースと提出書類向けのBERTベース金融センチメント分類器。 | 2.2k | `Jupyter Notebook` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ProsusAI/finBERT) |
| [FinNLP](https://github.com/AI4Finance-Foundation/FinNLP) | インターネット規模の市場テキスト向け金融NLPライブラリ。 | 1.5k | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinNLP) |
| [FinBERT](https://github.com/valuesimplex/FinBERT) | 金融テキスト分類のためのFinBERT実装。 | 925 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/valuesimplex/FinBERT) |
| [FinBERT](https://github.com/yya518/FinBERT) | 金融コミュニケーションセンチメント向け事前学習BERT。 | 657 | `Jupyter Notebook` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/yya518/FinBERT) |
| [StockEmotions](https://github.com/adlnlp/StockEmotions) | 投資家の感情と金融センチメントのデータセットとコード。 | 95 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/adlnlp/StockEmotions) |
| [finnlp-sentiment](https://github.com/nlp-chula/finnlp-sentiment) | タイ金融センチメント分析のツールとモデル。 | 26 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/nlp-chula/finnlp-sentiment) |
| [twitter-alpha-sentiment-tracker-v2](https://github.com/Rezzecup/twitter-alpha-sentiment-tracker-v2) | リアルタイムのX/Twitterスマートマネーセンチメントトラッカー。 | 21 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Rezzecup/twitter-alpha-sentiment-tracker-v2) |
| [Aspect-based-Financial-Sentiment-Analysis](https://github.com/ashishsalunkhe/Aspect-based-Financial-Sentiment-Analysis) | FiQA向けアスペクトベース金融センチメントソリューション。 | 11 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ashishsalunkhe/Aspect-based-Financial-Sentiment-Analysis) |
| [FinChina-SA](https://github.com/YerayL/FinChina-SA) | 中国語細粒度金融センチメントデータセットとコード。 | 7 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/YerayL/FinChina-SA) |
| [earnings-edge](https://github.com/suhaas/earnings-edge) | 決算説明会アナリストブリーフのためのマルチエージェントLangGraphアプリ。 | 6 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/suhaas/earnings-edge) |

<a id="trading-bots"></a>
## 5. 💹 LLM/エージェント トレードボット＆バックテスト

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | 投資家ペルソナをシミュレートするマルチエージェントLLMヘッジファンドチーム。 | 60.7k | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/virattt/ai-hedge-fund) |
| [AI-Trader](https://github.com/HKUDS/AI-Trader) | AIエージェント向け完全自動エージェントネイティブトレーディングプラットフォーム。 | 20.3k | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/HKUDS/AI-Trader) |
| [Qbot](https://github.com/UFund-Me/Qbot) | AI主導の定量的投資研究と自動トレードプラットフォーム。 | 17.9k | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/UFund-Me/Qbot) |
| [FinRL](https://github.com/AI4Finance-Foundation/FinRL) | 金融強化学習ライブラリとトレーディングエージェントエコシステム。 | 15.6k | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRL) |
| [FinRL-Trading](https://github.com/AI4Finance-Foundation/FinRL-Trading) | バックテストを備えたAIネイティブなモジュラー定量トレーディング基盤。 | 3.4k | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRL-Trading) |
| [FinMem-LLM-StockTrading](https://github.com/pipiku915/FinMem-LLM-StockTrading) | 階層化記憶とキャラクター設計を持つLLM株売買エージェント。 | 918 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/pipiku915/FinMem-LLM-StockTrading) |
| [Stockagent](https://github.com/MingyuJ666/Stockagent) | シミュレートされた実世界市場環境でのLLM駆動株売買。 | 680 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/MingyuJ666/Stockagent) |
| [llm-agent-trader](https://github.com/jason8745/llm-agent-trader) | LLMベースの判断分析を備えたAI株売買バックテストシステム。 | 375 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/jason8745/llm-agent-trader) |
| [FinRL_DeepSeek](https://github.com/benstaf/FinRL_DeepSeek) | トレーディングエージェント向けLLM注入型リスク考慮強化学習。 | 329 | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/benstaf/FinRL_DeepSeek) |
| [LLM-TradeBot](https://github.com/EthanAlgoX/LLM-TradeBot) | リアルタイム適応のためLLMを用いるマルチエージェントAIトレーディングシステム。 | 296 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/EthanAlgoX/LLM-TradeBot) |
| [TwinMarket](https://github.com/FreedomIntelligence/TwinMarket) | 社会経済市場シミュレーションのためのマルチエージェントLLMフレームワーク。 | 195 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/FreedomIntelligence/TwinMarket) |
| [robinhood-ai-trading-bot](https://github.com/siropkin/robinhood-ai-trading-bot) | Robinhoodと連携したAIトレーディングボット。 | 118 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/siropkin/robinhood-ai-trading-bot) |
| [FinAgent](https://github.com/DVampire/FinAgent) | ツール拡張LLMによる金融トレードのためのマルチモーダル基盤エージェント。 | 75 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/DVampire/FinAgent) |
| [AutoTrader-AgentEdge](https://github.com/iAmGiG/AutoTrader-AgentEdge) | ウォークフォワード検証を備えた本番用マルチエージェントトレーディングプラットフォーム。 | 18 | `Python` | `AGPL-3.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/iAmGiG/AutoTrader-AgentEdge) |
| [Auto-Trader](https://github.com/Itachi-Uchiha581/Auto-Trader) | 取引を自動実行するLLM駆動トレーディングボット。 | 14 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Itachi-Uchiha581/Auto-Trader) |
| [trade-agent](https://github.com/mocasus/trade-agent) | 市場・ニュース・指標にLLMを用いたモジュラーAIトレーディングエージェント。 | 8 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/mocasus/trade-agent) |
| [ai-hedge-fund](https://github.com/zhound420/ai-hedge-fund) | AlpacaペーパートレードとLLMアナリストによるマルチエージェント株ヘッジファンド。 | 0 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/zhound420/ai-hedge-fund) |

<a id="learning"></a>
## 6. 🎓 学習 / 教育プラットフォーム

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [finllm-apps](https://github.com/tinztwins/finllm-apps) | オープンソースFinLLMアプリとデモのコレクション。 | 152 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/tinztwins/finllm-apps) |
| [Finance-LLMs](https://github.com/kennethleungty/Finance-LLMs) | 金融サービスにおける実世界LLM実装のまとめ。 | 129 | `—` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/kennethleungty/Finance-LLMs) |
| [finLLM](https://github.com/ArchishmanSengupta/finLLM) | 金融百科事典をベースに構築された対話型FinLLMデモ。 | 7 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ArchishmanSengupta/finLLM) |
| [AI-Stock-Market-Chatbot](https://github.com/AbeTavarez/AI-Stock-Market-Chatbot) | Next.jsとOpenAIで構築されたAI株市場チャットボット。 | 6 | `TypeScript` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AbeTavarez/AI-Stock-Market-Chatbot) |
| [finLLM](https://github.com/Entropov/finLLM) | 金融Q&Aのための実験的金融LLMインストラクター。 | 1 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Entropov/finLLM) |
| [FinancialLiteracyChatbot](https://github.com/24prathamesh2004/FinancialLiteracyChatbot) | 個人金融・投資基礎を学ぶ対話型金融リテラシーチャットボット。 | 2 | `HTML` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/24prathamesh2004/FinancialLiteracyChatbot) |
| [FinWise](https://github.com/aadithya2007/FinWise) | 金融リテラシーと投資の基礎を教える対話型アシスタント。 | 1 | `JavaScript` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/aadithya2007/FinWise) |
| [financial-literacy-chatbot](https://github.com/sparsh-j01/financial-literacy-chatbot) | Google Gemini駆動のバイリンガル金融リテラシーチャットボット。 | 1 | `HTML` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/sparsh-j01/financial-literacy-chatbot) |
| [ArthSakhi](https://github.com/SmritiD2004/ArthSakhi) | インドの女性向けにカスタマイズされた金融リテラシーチャットボット。 | 1 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/SmritiD2004/ArthSakhi) |
| [AI_FinancialTutor](https://github.com/NaniSkinner/AI_FinancialTutor) | 対話的投資・金融教育のためのAI金融チューター。 | 0 | `TypeScript` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/NaniSkinner/AI_FinancialTutor) |
| [FinancialLiteracyChatbot](https://github.com/premnath228004/FinancialLiteracyChatbot) | CLIとWhatsApp対応のバイリンガル金融リテラシーチャットボット。 | 0 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/premnath228004/FinancialLiteracyChatbot) |
| [financial-literacy-bot](https://github.com/Collin17Muse/financial-literacy-bot) | 教え、クイズ、進捗管理を行う対話型金融リテラシーボット。 | 0 | `HTML` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Collin17Muse/financial-literacy-bot) |
| [Multilingual_financial_Chatbot](https://github.com/Indhumathi-RA/Multilingual_financial_Chatbot) | 香港の金融概念に関するマルチリンガルRAGチャットボット。 | 0 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Indhumathi-RA/Multilingual_financial_Chatbot) |
| [syf-finlit-agent](https://github.com/SidharthAnand04/syf-finlit-agent) | クレジット商品を説明し金融リテラシーを向上させるAIエージェント。 | 0 | `TypeScript` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/SidharthAnand04/syf-finlit-agent) |

<a id="datasets"></a>
## 7. 📊 データセット＆ベンチマーク

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | 金融強化学習向け動的データセットと市場環境。 | 1.9k | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRL-Meta) |
| [FNSPID_Financial_News_Dataset](https://github.com/Zdong104/FNSPID_Financial_News_Dataset) | S&P500時系列予測のための大規模金融ニュース・株価データセット。 | 432 | `Python` | `NOASSERTION` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Zdong104/FNSPID_Financial_News_Dataset) |
| [FinLLMs](https://github.com/adlnlp/FinLLMs) | 金融分野の大規模言語モデルに関する論文のベンチマークとデータセット。 | 380 | `—` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/adlnlp/FinLLMs) |
| [financebench](https://github.com/patronus-ai/financebench) | LLM向けオーブック型金融質問応答ベンチマーク。 | 332 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/patronus-ai/financebench) |
| [FinEval](https://github.com/SUFE-AIFLM-Lab/FinEval) | LLM評価のための26,000問以上の中国語金融領域ベンチマーク。 | 278 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/SUFE-AIFLM-Lab/FinEval) |
| [live-trade-bench](https://github.com/ulab-uiuc/live-trade-bench) | トレーディングエージェントのためのライブ評価ベンチマーク。 | 160 | `Python` | `NOASSERTION` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ulab-uiuc/live-trade-bench) |
| [BizFinBench](https://github.com/HiThink-Research/BizFinBench) | LLM向けビジネス駆動の実世界金融ベンチマーク。 | 167 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/HiThink-Research/BizFinBench) |
| [cflue](https://github.com/aliyun/cflue) | LLM向け中国語金融言語理解ベンチマーク。 | 91 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/aliyun/cflue) |
| [FinLoRA](https://github.com/Open-Finance-Lab/FinLoRA) | 金融データでのLLMファインチューニングのためのLoRAベンチマーク。 | 66 | `Python` | `NOASSERTION` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Open-Finance-Lab/FinLoRA) |
| [FLANG](https://github.com/SALT-NLP/FLANG) | 金融領域事前学習モデルとFLUEベンチマークスuite. | 57 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/SALT-NLP/FLANG) |
| [CFBenchmark](https://github.com/TongjiFinLab/CFBenchmark) | 大規模言語モデル向け中国語金融アシスタントベンチマーク。 | 55 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/TongjiFinLab/CFBenchmark) |
| [FinMTEB](https://github.com/yixuantt/FinMTEB) | 64のデータセットに跨る金融大規模テキスト埋め込みベンチマーク。 | 54 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/yixuantt/FinMTEB) |
| [FinLLM-Leaderboard](https://github.com/Open-Finance-Lab/FinLLM-Leaderboard) | 金融LLMとエージェントを評価するリーダーボード。 | 26 | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Open-Finance-Lab/FinLLM-Leaderboard) |
| [CNFinBench](https://github.com/open-compass/CNFinBench) | エージェントチェインを含む高難易度中国語金融総合ベンチマーク。 | 16 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/open-compass/CNFinBench) |
| [FinBen](https://github.com/The-FinAI/FinBen) | 金融タスクでのLLM評価のための包括的ベンチマークスweat. | 15 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/The-FinAI/FinBen) |
| [FinanceQA](https://github.com/AfterQuery/FinanceQA) | LLMの金融分析能力を評価するためのベンチマーク。 | 8 | `—` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AfterQuery/FinanceQA) |

<a id="papers"></a>
## 8. 🧪 コード付き研究論文

このセクションでは、LLM/エージェント金融に関する学術論文の公式コードを主に提供するリポジトリを掲載しています。該当する論文＋コードのリポジトリをご存じでしたら、PRをお願いします。

<a id="absorb"></a>
## 9. 🧩 取り入れられるアイデア チートシート

- **マルチエージェントの議論 / 役割特化** — 強気、弱気、リスクマネージャー、ポートフォリオマネージャーなどの専門ペルソナに分析を分割し、構造化された議論で意見を統合する。 (exemplified by: TradingAgents, orallexa-ai-trading-agent, ai-hedge-fund)
- **提出書類に対するツール拡張検索 / 金融RAG** — LLMの出力をSEC提出書類、決算説明会記録、市場データへの検索増強により根拠付ける。 (exemplified by: FinRAG, openbb-rag-financial-research-agent, multi-horizon-financial-agent)
- **LLM駆動センチメント→シグナルパイプライン** — ニュース、ソーシャルメディア、決算説明会のセンチメントを定量的トレードシグナルに変換する。 (exemplified by: twitter-alpha-sentiment-tracker-v2, FinNLP, ProsusAI/finBERT)
- **金融コーパスでのLoRA/PEFTファインチューニングレシピ** — 決算説明会、ニュース、レポートを用いて汎用LLMを金融分野に軽量ファインチューニングする。 (exemplified by: FinGPT, FinLoRA, PIXIU)
- **記憶拡張型トレーディングエージェント** — 短期記憶と長期記憶をエージェントに重ね、ポートフォリオコンテキストを維持し行動を適応させる。 (exemplified by: FinMem-LLM-StockTrading)
- **調査レポート生成のためのReAct＋ツール使用** — 推論と行動を繰り返すループでデータを収集し、投資調査レポートを作成する。 (exemplified by: deep-research-machine, stock_research_agent)
- **バックテスト＋ペーパートレードサンドボックス** — 本番運用前に過去の市場リプレイと証券業者のペーパー口座でエージェント戦略を検証する。 (exemplified by: FinRL, Qbot, AlpacaTradingAgent)
- **リスクガード / ヒューマン・イン・ザ・ループの拒否権** — シグナル生成と執行の間にガードレールや人間の承認ゲートを挿入する。 (exemplified by: AutoTrader-AgentEdge, ai-hedge-fund, LLM-TradeBot)
- **マルチモーダル市場理解** — 株価チャート、代替データ、テキストを組み合わせて株価分析を改善する。 (exemplified by: StockerLens, FinAgent)
- **生成エージェントによる市場シミュレーション** — 市場動向の創発的ダイナミクスを研究するため、LLMエージェントで経済・トレーディング集団をシミュレートする。 (exemplified by: TwinMarket, LLM-Economist, ai-economist)
- **金融ベンチマーク駆動開発** — 金融特化のQA、埋め込み、トレーディングベンチマークを使ってLLM/エージェント能力を評価する。 (exemplified by: FinEval, financebench, BizFinBench)

<a id="contributing"></a>
## 🙋 貢献
貢献を歓迎します！エントリーの追加、フォーマット、翻訳のガイドラインについては [CONTRIBUTING.md](CONTRIBUTING.md) をご覧ください。

<a id="license"></a>
## 📜 ライセンス
このリストは [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/) の下で公開されています。リンク先の各プロジェクトはそれぞれのライセンスを保持しています — 各リポジトリの利用条件を尊重してください。

<a id="star-history"></a>
## ⭐ Star History
<sub>このリストが役に立ったら、⭐ を付けていただけると他の人にも発見してもらいやすくなります。</sub>

<a href="https://star-history.com/#Lxcardoza993/awesome-token2cash&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date" />
  </picture>
</a>

[⬆ ページトップへ](#awesome-token2cash)
