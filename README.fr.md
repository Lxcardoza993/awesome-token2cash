<a id="awesome-token2cash"></a>
# 📈 Awesome Token2Cash

**Languages:** [English](README.md) • [简体中文](README.zh-CN.md) • [Español](README.es.md) • [日本語](README.ja.md) • [한국어](README.ko.md) • **Français** • [Русский](README.ru.md)

> Une liste curatée de **plateformes multi-agents et de grands modèles de langage (LLM) pour l'analyse boursière, le trading et l'apprentissage financier**.
> Cartographie systématique du domaine — debout sur les épaules des géants, pour vous permettre d'apprendre, de comparer et de construire sans réinventer la roue.
>
> Chaque entrée est annotée du nombre de ⭐ étoiles, de la langue principale et de la licence, afin que vous puissiez rapidement juger ce qui mérite d'être étudié.

<a id="acknowledgments"></a>
## 🙏 Remerciements

Nous nous appuyons sur le catalogage antérieur de ces listes :

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
- **[Telegram OpenClaw 中文社区](https://t.me/OpenClaw_Group)** — la communauté OpenClaw en chinois sur Telegram — merci pour le soutien et les discussions.
- **[Linux.do](https://linux.do)** — une communauté de développeurs et de technophiles chinois (Discourse) — merci pour les retours et la visibilité.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg) ![Tools](https://img.shields.io/badge/tools-83-blue) ![Focus: Multi-Agent + LLM Stocks](https://img.shields.io/badge/focus-Multi--Agent%20%2B%20LLM%20stocks-purple) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen) [![Telegram](https://img.shields.io/badge/Telegram-OpenClaw-2AABEE?style=flat&logo=telegram&logoColor=white)](https://t.me/OpenClaw_Group)

---

## Table des matières
- [1. 🏛️ LLM financiers fondation](#foundation-llms)
- [2. 🤖 Frameworks multi-agents de trading et d'analyse](#multi-agent)
- [3. 📈 Analyse boursière par LLM, prédiction et rapports de recherche](#stock-analysis)
- [4. 📰 Sentiment financier et NLP actualités/réseaux sociaux](#sentiment-nlp)
- [5. 💹 Bots de trading/backtesting LLM/Agent](#trading-bots)
- [6. 🎓 Plateformes d'apprentissage / éducation](#learning)
- [7. 📊 Jeux de données et benchmarks](#datasets)
- [8. 🧪 Articles de recherche avec code](#papers)
- [9. 🧩 Aide-mémoire des idées absorbables](#absorb)
- [🙋 Contribuer](#contributing) · [🙏 Remerciements](#acknowledgments) · [📜 Licence](#license)

---

## Légende
| Marqueur | Signification |
|------|------|
| ⭐ | Nombre d'étoiles GitHub (au moment de la recherche, approximatif) |
| `Language` | Langue principale |
| `License` | Licence |

<a id="foundation-llms"></a>
## 1. 🏛️ LLM financiers fondation

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | Framework open-source de LLM financier avec données, fine-tuning, RL et applications de trading. | 20.8k | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinGPT) |
| [XuanYuan](https://github.com/Duxiaoman-DI/XuanYuan) | Grand modèle de dialogue financier chinois par Duxiaoman. | 1.3k | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Duxiaoman-DI/XuanYuan) |
| [DISC-FinLLM](https://github.com/FudanDISC/DISC-FinLLM) | LLM financier chinois pour conseil financier professionnel. | 888 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/FudanDISC/DISC-FinLLM) |
| [PIXIU](https://github.com/The-FinAI/PIXIU) | LLM financiers, données d'instruction-tuning et benchmarks d'évaluation holistique. | 872 | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/The-FinAI/PIXIU) |
| [InvestLM](https://github.com/AbaciNLP/InvestLM) | Grand modèle de langage axé sur la finance et l'investissement. | 153 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AbaciNLP/InvestLM) |
| [CFGPT](https://github.com/TongjiFinLab/CFGPT) | Assistant financier chinois construit sur un grand modèle de langage. | 91 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/TongjiFinLab/CFGPT) |
| [BloombergGPT_zh](https://github.com/sunshineyg2018/BloombergGPT_zh) | Reproduction/implémentation chinoise de BloombergGPT. | 58 | `—` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/sunshineyg2018/BloombergGPT_zh) |
| [FinRAG](https://github.com/AI4Finance-Foundation/FinRAG) | Système de génération augmentée par récupération pour les domaines financiers. | 53 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRAG) |

<a id="multi-agent"></a>
## 2. 🤖 Frameworks multi-agents de trading et d'analyse

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [TradingAgents](https://github.com/TauricResearch/TradingAgents) | Framework multi-agents LLM de trading simulant des rôles spécialisés d'une firme de trading. | 90.3k | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/TauricResearch/TradingAgents) |
| [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | Plateforme d'agents IA open-source pour l'analyse financière utilisant les LLM. | 7.4k | `Jupyter Notebook` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRobot) |
| [TradingAgents-astock](https://github.com/simonlin1212/TradingAgents-astock) | Framework de recherche d'investissement multi-agents pour actions A basé sur TradingAgents. | 1.6k | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/simonlin1212/TradingAgents-astock) |
| [AgenticTrading](https://github.com/Open-Finance-Lab/AgenticTrading) | Plateforme open-source pour agents de trading pilotés par LLM et backtesting. | 260 | `Python` | `NOASSERTION` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Open-Finance-Lab/AgenticTrading) |
| [AlpacaTradingAgent](https://github.com/huygiatrng/AlpacaTradingAgent) | Framework multi-agents LLM de trading intégré à Alpaca pour les trades en direct. | 238 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/huygiatrng/AlpacaTradingAgent) |
| [MarketAgents](https://github.com/marketagents-ai/MarketAgents) | Framework d'orchestration pour agents économiques IA et simulations de marché. | 116 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/marketagents-ai/MarketAgents) |
| [LLM-Economist](https://github.com/sethkarten/LLM-Economist) | Simulation multi-agents à grande population de LLM pour les mécanismes et la politique fiscale. | 114 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/sethkarten/LLM-Economist) |
| [ai-economist](https://github.com/salesforce/ai-economist) | Framework multi-agents RL pour le comportement socio-économique et la conception de politiques. | 110 | `Python` | `BSD-3-Clause` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/salesforce/ai-economist) |
| [orallexa-ai-trading-agent](https://github.com/alex-jb/orallexa-ai-trading-agent) | Système de trading multi-agents auto-ajustable avec débat haussier/baissier/juge. | 52 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/alex-jb/orallexa-ai-trading-agent) |

<a id="stock-analysis"></a>
## 3. 📈 Analyse boursière par LLM, prédiction et rapports de recherche

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [deep-research-machine](https://github.com/druce/deep-research-machine) | Pipeline de recherche d'actions asynchrone utilisant les LLM. | 11 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/druce/deep-research-machine) |
| [AI-Stock-Analyst-Agent-Langchain-Deepseek](https://github.com/Bisma-Shafiq/AI-Stock-Analyst-Agent-Langchain-Deepseek) | Agent LangChain/DeepSeek pour l'analyse boursière. | 7 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Bisma-Shafiq/AI-Stock-Analyst-Agent-Langchain-Deepseek) |
| [openbb-rag-financial-research-agent](https://github.com/sandole/openbb-rag-financial-research-agent) | Agent RAG pour les déclarations SEC et la recherche financière. | 7 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/sandole/openbb-rag-financial-research-agent) |
| [stock_research_agent](https://github.com/druce/stock_research_agent) | Générer un rapport de recherche d'actions via l'agent SDK Claude. | 3 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/druce/stock_research_agent) |
| [multi-horizon-financial-agent](https://github.com/srx7703/multi-horizon-financial-agent) | Agent utilisant des outils synthétisant des synthèses SEC et de marché. | 2 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/srx7703/multi-horizon-financial-agent) |
| [stockgpt](https://github.com/ESJavadex/stockgpt) | Analyser des actions et générer des rapports d'investissement GPT-4. | 2 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ESJavadex/stockgpt) |
| [StockerLens](https://github.com/Aswin-Cheerngodan/StockerLens) | Prédiction multimodale des prix boursiers avec sentiment et analyse de graphiques. | 1 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Aswin-Cheerngodan/StockerLens) |
| [stock_signal_analyzer](https://github.com/mmovsesyan/stock_signal_analyzer) | Système de bourse auto-apprenant avec sentiment d'actualités LLM et plans. | 1 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/mmovsesyan/stock_signal_analyzer) |
| [daily_stock_analysis](https://github.com/chief0714/daily_stock_analysis) | Analyse boursière quotidienne multi-marchés pilotée par LLM. | 1 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/chief0714/daily_stock_analysis) |

<a id="sentiment-nlp"></a>
## 4. 📰 Sentiment financier et NLP actualités/réseaux sociaux

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [finBERT](https://github.com/ProsusAI/finBERT) | Classificateur de sentiment financier basé sur BERT pour actualités et déclarations. | 2.2k | `Jupyter Notebook` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ProsusAI/finBERT) |
| [FinNLP](https://github.com/AI4Finance-Foundation/FinNLP) | Bibliothèque de NLP financier pour textes de marché à échelle Internet. | 1.5k | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinNLP) |
| [FinBERT](https://github.com/valuesimplex/FinBERT) | Implémentation FinBERT pour la classification de textes financiers. | 925 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/valuesimplex/FinBERT) |
| [FinBERT](https://github.com/yya518/FinBERT) | BERT pré-entraîné pour le sentiment des communications financières. | 657 | `Jupyter Notebook` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/yya518/FinBERT) |
| [StockEmotions](https://github.com/adlnlp/StockEmotions) | Jeu de données et code pour l'émotion de l'investisseur et le sentiment financier. | 95 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/adlnlp/StockEmotions) |
| [finnlp-sentiment](https://github.com/nlp-chula/finnlp-sentiment) | Outils et modèles d'analyse de sentiment financier en thaï. | 26 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/nlp-chula/finnlp-sentiment) |
| [twitter-alpha-sentiment-tracker-v2](https://github.com/Rezzecup/twitter-alpha-sentiment-tracker-v2) | Tracker de sentiment smart-money en temps réel sur X/Twitter. | 21 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Rezzecup/twitter-alpha-sentiment-tracker-v2) |
| [Aspect-based-Financial-Sentiment-Analysis](https://github.com/ashishsalunkhe/Aspect-based-Financial-Sentiment-Analysis) | Solution de sentiment financier aspect-based pour FiQA. | 11 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ashishsalunkhe/Aspect-based-Financial-Sentiment-Analysis) |
| [FinChina-SA](https://github.com/YerayL/FinChina-SA) | Jeu de données et code chinois de sentiment financier finement granulaire. | 7 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/YerayL/FinChina-SA) |
| [earnings-edge](https://github.com/suhaas/earnings-edge) | Application LangGraph multi-agents pour les briefs d'analystes d'appels de résultats. | 6 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/suhaas/earnings-edge) |

<a id="trading-bots"></a>
## 5. 💹 Bots de trading/backtesting LLM/Agent

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | Équipe multi-agents LLM de fonds de couverture simulant des personas d'investisseurs pour les décisions d'actions. | 60.7k | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/virattt/ai-hedge-fund) |
| [AI-Trader](https://github.com/HKUDS/AI-Trader) | Plateforme de trading entièrement automatisée et native aux agents IA. | 20.3k | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/HKUDS/AI-Trader) |
| [Qbot](https://github.com/UFund-Me/Qbot) | Plateforme de recherche d'investissement quantitatif et de trading automatique pilotée par IA. | 17.9k | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/UFund-Me/Qbot) |
| [FinRL](https://github.com/AI4Finance-Foundation/FinRL) | Bibliothèque d'apprentissage par renforcement financier et écosystème d'agents de trading. | 15.6k | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRL) |
| [FinRL-Trading](https://github.com/AI4Finance-Foundation/FinRL-Trading) | Infrastructure de trading quantitatif modulaire native de l'IA avec backtesting. | 3.4k | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRL-Trading) |
| [FinMem-LLM-StockTrading](https://github.com/pipiku915/FinMem-LLM-StockTrading) | Agent de trading boursier LLM avec mémoire hiérarchisée et conception de personnage. | 918 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/pipiku915/FinMem-LLM-StockTrading) |
| [Stockagent](https://github.com/MingyuJ666/Stockagent) | Trading boursier piloté par LLM dans des environnements de marché simulés réalistes. | 680 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/MingyuJ666/Stockagent) |
| [llm-agent-trader](https://github.com/jason8745/llm-agent-trader) | Système de backtesting de trading boursier par IA avec analyse de décision LLM. | 375 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/jason8745/llm-agent-trader) |
| [FinRL_DeepSeek](https://github.com/benstaf/FinRL_DeepSeek) | Apprentissage par renforcement sensible au risque infusé de LLM pour agents de trading. | 329 | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/benstaf/FinRL_DeepSeek) |
| [LLM-TradeBot](https://github.com/EthanAlgoX/LLM-TradeBot) | Système de trading IA multi-agents utilisant les LLM pour l'adaptation en temps réel. | 296 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/EthanAlgoX/LLM-TradeBot) |
| [TwinMarket](https://github.com/FreedomIntelligence/TwinMarket) | Framework multi-agents LLM pour la simulation de marché socio-économique. | 195 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/FreedomIntelligence/TwinMarket) |
| [robinhood-ai-trading-bot](https://github.com/siropkin/robinhood-ai-trading-bot) | Bot de trading IA intégré à Robinhood. | 118 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/siropkin/robinhood-ai-trading-bot) |
| [FinAgent](https://github.com/DVampire/FinAgent) | Agent fondation multimodal pour le trading financier avec LLM augmenté d'outils. | 75 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/DVampire/FinAgent) |
| [AutoTrader-AgentEdge](https://github.com/iAmGiG/AutoTrader-AgentEdge) | Plateforme de trading multi-agents de production avec validation walk-forward. | 18 | `Python` | `AGPL-3.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/iAmGiG/AutoTrader-AgentEdge) |
| [Auto-Trader](https://github.com/Itachi-Uchiha581/Auto-Trader) | Bot de trading piloté par LLM qui exécute automatiquement les trades. | 14 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Itachi-Uchiha581/Auto-Trader) |
| [trade-agent](https://github.com/mocasus/trade-agent) | Agent de trading IA modulaire utilisant les LLM pour le marché, les actualités et les indicateurs. | 8 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/mocasus/trade-agent) |
| [ai-hedge-fund](https://github.com/zhound420/ai-hedge-fund) | Fonds de couverture boursier multi-agents avec trading papier Alpaca et analystes LLM. | 0 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/zhound420/ai-hedge-fund) |

<a id="learning"></a>
## 6. 🎓 Plateformes d'apprentissage / éducation

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [finllm-apps](https://github.com/tinztwins/finllm-apps) | Collection d'applications FinLLM open-source et de démos. | 152 | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/tinztwins/finllm-apps) |
| [Finance-LLMs](https://github.com/kennethleungty/Finance-LLMs) | Compilation d'implémentations réelles de LLM dans les services financiers. | 129 | `—` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/kennethleungty/Finance-LLMs) |
| [finLLM](https://github.com/ArchishmanSengupta/finLLM) | Démo de FinLLM conversationnel construit sur une encyclopédie financière. | 7 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ArchishmanSengupta/finLLM) |
| [AI-Stock-Market-Chatbot](https://github.com/AbeTavarez/AI-Stock-Market-Chatbot) | Chatbot boursier IA construit avec Next.js et OpenAI. | 6 | `TypeScript` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AbeTavarez/AI-Stock-Market-Chatbot) |
| [finLLM](https://github.com/Entropov/finLLM) | Instructeur FinLLM expérimental pour questions-réponses en finance. | 1 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Entropov/finLLM) |
| [FinancialLiteracyChatbot](https://github.com/24prathamesh2004/FinancialLiteracyChatbot) | Chatbot de littératie financière conversationnel pour apprendre les bases de la finance personnelle et de l'investissement. | 2 | `HTML` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/24prathamesh2004/FinancialLiteracyChatbot) |
| [FinWise](https://github.com/aadithya2007/FinWise) | Assistant conversationnel qui enseigne la littératie financière et les fondamentaux de l'investissement. | 1 | `JavaScript` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/aadithya2007/FinWise) |
| [financial-literacy-chatbot](https://github.com/sparsh-j01/financial-literacy-chatbot) | Chatbot bilingue de littératie financière alimenté par Google Gemini. | 1 | `HTML` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/sparsh-j01/financial-literacy-chatbot) |
| [ArthSakhi](https://github.com/SmritiD2004/ArthSakhi) | Chatbot de littératie financière destiné aux femmes en Inde. | 1 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/SmritiD2004/ArthSakhi) |
| [AI_FinancialTutor](https://github.com/NaniSkinner/AI_FinancialTutor) | Tuteur financier IA pour l'éducation interactive à l'investissement et la finance. | 0 | `TypeScript` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/NaniSkinner/AI_FinancialTutor) |
| [FinancialLiteracyChatbot](https://github.com/premnath228004/FinancialLiteracyChatbot) | Chatbot bilingue de littératie financière avec accès CLI et WhatsApp. | 0 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/premnath228004/FinancialLiteracyChatbot) |
| [financial-literacy-bot](https://github.com/Collin17Muse/financial-literacy-bot) | Bot de littératie financière interactif qui enseigne, quizze et suit la progression. | 0 | `HTML` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Collin17Muse/financial-literacy-bot) |
| [Multilingual_financial_Chatbot](https://github.com/Indhumathi-RA/Multilingual_financial_Chatbot) | Chatbot RAG multilingue pour les concepts financiers de Hong Kong. | 0 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Indhumathi-RA/Multilingual_financial_Chatbot) |
| [syf-finlit-agent](https://github.com/SidharthAnand04/syf-finlit-agent) | Agent IA pour expliquer les produits de crédit et améliorer la littératie financière. | 0 | `TypeScript` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/SidharthAnand04/syf-finlit-agent) |

<a id="datasets"></a>
## 7. 📊 Jeux de données et benchmarks

| Project | Description | ⭐ Stars | Language | License | 📖 Docs |
|---|---|---:|---|---|---|
| [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | Données de marché dynamiques et environnements pour l'apprentissage par renforcement financier. | 1.9k | `Python` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AI4Finance-Foundation/FinRL-Meta) |
| [FNSPID_Financial_News_Dataset](https://github.com/Zdong104/FNSPID_Financial_News_Dataset) | Grand jeu de données d'actualités financières et de prix boursiers pour la prédiction de séries temporelles S&P 500. | 432 | `Python` | `NOASSERTION` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Zdong104/FNSPID_Financial_News_Dataset) |
| [FinLLMs](https://github.com/adlnlp/FinLLMs) | Benchmarks et jeux de données pour l'article Large Language Models in Finance. | 380 | `—` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/adlnlp/FinLLMs) |
| [financebench](https://github.com/patronus-ai/financebench) | Benchmark de questions-réponses financières en livre ouvert pour les LLM. | 332 | `Jupyter Notebook` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/patronus-ai/financebench) |
| [FinEval](https://github.com/SUFE-AIFLM-Lab/FinEval) | Benchmark chinois du domaine financier avec plus de 26 000 questions pour l'évaluation des LLM. | 278 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/SUFE-AIFLM-Lab/FinEval) |
| [live-trade-bench](https://github.com/ulab-uiuc/live-trade-bench) | Benchmark d'évaluation en direct pour agents de trading. | 160 | `Python` | `NOASSERTION` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/ulab-uiuc/live-trade-bench) |
| [BizFinBench](https://github.com/HiThink-Research/BizFinBench) | Benchmark financier réel orienté entreprise pour les LLM. | 167 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/HiThink-Research/BizFinBench) |
| [cflue](https://github.com/aliyun/cflue) | Benchmark chinois de compréhension du langage financier pour les LLM. | 91 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/aliyun/cflue) |
| [FinLoRA](https://github.com/Open-Finance-Lab/FinLoRA) | Benchmarking de LoRA pour le fine-tuning de LLM sur des données financières. | 66 | `Python` | `NOASSERTION` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Open-Finance-Lab/FinLoRA) |
| [FLANG](https://github.com/SALT-NLP/FLANG) | Modèle pré-entraîné du domaine financier et suite de benchmarks FLUE. | 57 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/SALT-NLP/FLANG) |
| [CFBenchmark](https://github.com/TongjiFinLab/CFBenchmark) | Benchmark d'assistant financier chinois pour grands modèles de langage. | 55 | `Python` | `Apache-2.0` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/TongjiFinLab/CFBenchmark) |
| [FinMTEB](https://github.com/yixuantt/FinMTEB) | Finance Massive Text Embedding Benchmark across 64 datasets. | 54 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/yixuantt/FinMTEB) |
| [FinLLM-Leaderboard](https://github.com/Open-Finance-Lab/FinLLM-Leaderboard) | Leaderboard évaluant les LLM et agents financiers. | 26 | `Jupyter Notebook` | `MIT` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/Open-Finance-Lab/FinLLM-Leaderboard) |
| [CNFinBench](https://github.com/open-compass/CNFinBench) | Benchmark chinois financier à haut enjeu avec chaînes d'agents. | 16 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/open-compass/CNFinBench) |
| [FinBen](https://github.com/The-FinAI/FinBen) | Suite de benchmarks complète pour évaluer les LLM sur des tâches financières. | 15 | `Python` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/The-FinAI/FinBen) |
| [FinanceQA](https://github.com/AfterQuery/FinanceQA) | Benchmark pour évaluer les capacités d'analyse financière des LLM. | 8 | `—` | `—` | [![DeepWiki](https://img.shields.io/badge/docs-DeepWiki-7C3AED?style=flat&logo=readthedocs&logoColor=white)](https://deepwiki.com/AfterQuery/FinanceQA) |

<a id="papers"></a>
## 8. 🧪 Articles de recherche avec code

Cette section est destinée aux dépôts qui fournissent principalement le code officiel accompagnant des articles académiques sur les LLM/agents en finance. Si vous connaissez un dépôt de papier avec code pertinent, ouvrez une PR.

<a id="absorb"></a>
## 9. 🧩 Aide-mémoire des idées absorbables

- **Débat multi-agents / spécialisation des rôles** — Décomposer l'analyse en personas spécialisés (haussier, baissier, gestionnaire de risques, gestionnaire de portefeuille) et résoudre les désaccords par un débat structuré. (exemplifié par : TradingAgents, orallexa-ai-trading-agent, ai-hedge-fund)
- **Récupération augmentée d'outils sur les dépôts / RAG pour la finance** — Ancrer les sorties du LLM dans les déclarations à la SEC, les retranscriptions d'appels de résultats et les données de marché grâce à l'augmentation par récupération. (exemplifié par : FinRAG, openbb-rag-financial-research-agent, multi-horizon-financial-agent)
- **Pipeline sentiment-vers-signal piloté par LLM** — Transformer le sentiment des actualités, des réseaux sociaux ou des appels de résultats en signaux de trading quantitatifs. (exemplifié par : twitter-alpha-sentiment-tracker-v2, FinNLP, ProsusAI/finBERT)
- **Recette de fine-tuning LoRA/PEFT sur corpus financier** — Adapter des LLM généraux à la finance via un fine-tuning léger sur les appels de résultats, les actualités et les rapports. (exemplifié par : FinGPT, FinLoRA, PIXIU)
- **Agent de trading à mémoire augmentée** — Intégrer une mémoire à court et à long terme dans l'agent pour conserver le contexte du portefeuille et adapter son comportement. (exemplifié par : FinMem-LLM-StockTrading)
- **ReAct + utilisation d'outils pour la génération de rapports de recherche** — Utiliser un LLM avec des boucles de raisonnement et d'action pour collecter des données et rédiger des rapports d'investissement. (exemplifié par : deep-research-machine, stock_research_agent)
- **Backtesting + bac à sable de trading simulé** — Valider les stratégies d'agents avec le replay historique du marché et des comptes papier de courtiers avant le déploiement réel. (exemplifié par : FinRL, Qbot, AlpacaTradingAgent)
- **Garde-fous de risque / véto avec humain dans la boucle** — Insérer des garde-fous ou des portes d'approbation humaine entre la génération du signal et l'exécution du trade. (exemplifié par : AutoTrader-AgentEdge, ai-hedge-fund, LLM-TradeBot)
- **Compréhension multimodale du marché** — Combiner les graphiques de prix, les données alternatives et le texte pour améliorer l'analyse boursière. (exemplifié par : StockerLens, FinAgent)
- **Simulation de marché avec agents génératifs** — Simuler des populations de trading/économiques avec des agents LLM pour étudier les dynamiques de marché émergentes. (exemplifié par : TwinMarket, LLM-Economist, ai-economist)
- **Développement piloté par benchmarks financiers** — Utiliser des benchmarks financiers de questions-réponses, d'embeddings et de trading pour évaluer les capacités des LLM/agents. (exemplifié par : FinEval, financebench, BizFinBench)

<a id="contributing"></a>
## 🙋 Contribuer
Les contributions sont les bienvenues ! Consultez [CONTRIBUTING.md](CONTRIBUTING.md) pour les recommandations sur l'ajout d'entrées, le formatage et les traductions.

<a id="license"></a>
## 📜 Licence
Cette liste est publiée sous [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/). Chaque projet lié conserve sa propre licence — veuillez respecter les conditions de chaque dépôt.

<a id="star-history"></a>
## ⭐ Star History
<sub>Si cette liste vous est utile, pensez à laisser une ⭐ — cela aide les autres à la découvrir.</sub>

<a href="https://star-history.com/#Lxcardoza993/awesome-token2cash&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date" />
  </picture>
</a>

[⬆ Retour en haut](#awesome-token2cash)
