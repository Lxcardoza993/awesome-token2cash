<a id="awesome-token2cash"></a>
# 📈 Awesome Token2Cash

**Languages:** [English](README.md) • [简体中文](README.zh-CN.md) • [Español](README.es.md) • [日本語](README.ja.md) • [한국어](README.ko.md) • [Français](README.fr.md) • **Русский**

> Тщательно отобранная коллекция **мультиагентных платформ и больших языковых моделей (LLM) для анализа акций, торговли и финансового обучения**.
> Систематический обзор области — стоя на плечах гигантов, чтобы учиться, сравнивать и создавать, не изобретая велосипед.
>
> Каждая запись сопровождается ⭐, основным языком и лицензией, чтобы вы могли быстро оценить, что стоит изучать.

<a id="acknowledgments"></a>
## 🙏 Благодарности
- [AlanJiang98/Awesome-LLM-Trading](https://github.com/AlanJiang98/Awesome-LLM-Trading) — чья предыдущая систематизация послужила основой.
- [DataArcTech/Awesome-FinLLMs](https://github.com/DataArcTech/Awesome-FinLLMs) — чья предыдущая систематизация послужила основой.
- [Eleanorkong/Awesome-Financial-LLM-Bias-Mitigation](https://github.com/Eleanorkong/Awesome-Financial-LLM-Bias-Mitigation) — чья предыдущая систематизация послужила основой.
- [georgezouq/awesome-ai-in-finance](https://github.com/georgezouq/awesome-ai-in-finance) — чья предыдущая систематизация послужила основой.
- [wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) — чья предыдущая систематизация послужила основой.
- [leoncuhk/awesome-quant-ai](https://github.com/leoncuhk/awesome-quant-ai) — чья предыдущая систематизация послужила основой.
- [Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers](https://github.com/Tom-roujiang/Awesome-LLM-Quantitative-Trading-Papers) — чья предыдущая систематизация послужила основой.
- [kennethleungty/Finance-LLMs](https://github.com/kennethleungty/Finance-LLMs) — чья предыдущая систематизация послужила основой.
- [AI4Finance-Foundation/Awesome_AI4Finance](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance) — чья предыдущая систематизация послужила основой.
- [hananedupouy/LLMs-in-Finance](https://github.com/hananedupouy/LLMs-in-Finance) — чья предыдущая систематизация послужила основой.
- [anusky95/FinAI](https://github.com/anusky95/FinAI) — чья предыдущая систематизация послужила основой.
- [Open-Finance-Lab/FinLLM-Leaderboard](https://github.com/Open-Finance-Lab/FinLLM-Leaderboard) — чья предыдущая систематизация послужила основой.
- [AI4Finance-Foundation/Awesome_FinRL](https://github.com/AI4Finance-Foundation/Awesome_FinRL) — чья предыдущая систематизация послужила основой.
- [thuquant/awesome-quant](https://github.com/thuquant/awesome-quant) — чья предыдущая систематизация послужила основой.
- [grananqvist/Awesome-Quant-Machine-Learning-Trading](https://github.com/grananqvist/Awesome-Quant-Machine-Learning-Trading) — чья предыдущая систематизация послужила основой.
- [czyssrs/LLM_X_papers](https://github.com/czyssrs/LLM_X_papers) — чья предыдущая систематизация послужила основой.
- [masamasa59/ai-agent-papers](https://github.com/masamasa59/ai-agent-papers) — чья предыдущая систематизация послужила основой.
- **[Telegram OpenClaw 中文社区](https://t.me/OpenClaw_Group)** — китаязычное сообщество OpenClaw в Telegram — благодарим за поддержку и обсуждения.
- **[Linux.do](https://linux.do)** — китаязычное сообщество разработчиков и технических специалистов (Discourse) — благодарим за обратную связь и охват.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg) ![Tools](https://img.shields.io/badge/tools-93+-blue) ![Focus: Multi-Agent + LLM Stocks](https://img.shields.io/badge/focus-Multi--Agent%20%2B%20LLM%20stocks-purple) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

---

## Содержание
- [1. 🏛️ Базовые финансовые LLM](#foundation-llms)
- [2. 🤖 Мультиагентные фреймворки для торговли и анализа](#multi-agent)
- [3. 📈 LLM для анализа акций, прогнозирования и исследовательских отчётов](#stock-analysis)
- [4. 📰 Финансовый сентимент и NLP для новостей/соцсетей](#sentiment-nlp)
- [5. 💹 LLM/агентные торговые боты и бэктестинг](#trading-bots)
- [6. 🎓 Образовательные платформы](#learning)
- [7. 📊 Датасеты и бенчмарки](#datasets)
- [8. 🧪 Исследовательские статьи с кодом](#papers)
- [9. 🧩 Шпаргалка по применимым идеям](#absorb)
- [🙋 Внесение вклада](#contributing) · [🙏 Благодарности](#acknowledgments) · [📜 Лицензия](#license)

---

## Легенда
| Обозначение | Значение |
|------|------|
| ⭐ | Количество звёзд на GitHub (на момент исследования, приблизительно) |
| `Language` | Основной язык кода |
| `License` | Открытая лицензия |

<a id="foundation-llms"></a>
## 1. 🏛️ Базовые финансовые LLM

- [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) ⭐ `20.8k` `Jupyter Notebook` `MIT` — Открытый финансовый LLM-фреймворк с данными, дообучением, RL и торговыми приложениями.
- [XuanYuan](https://github.com/Duxiaoman-DI/XuanYuan) ⭐ `1.3k` `Python` `—` — Китайская большая языковая модель для финансового диалога от Duxiaoman.
- [DISC-FinLLM](https://github.com/FudanDISC/DISC-FinLLM) ⭐ `888` `Python` `Apache-2.0` — Китайская финансовая LLM для профессионального финансового консультирования.
- [PIXIU](https://github.com/The-FinAI/PIXIU) ⭐ `872` `Jupyter Notebook` `MIT` — Финансовые LLM, данные для инструкционной настройки и комплексные бенчмарки.
- [InvestLM](https://github.com/AbaciNLP/InvestLM) ⭐ `153` `Python` `—` — Большая языковая модель, ориентированная на финансы и инвестиции.
- [CFGPT](https://github.com/TongjiFinLab/CFGPT) ⭐ `91` `Python` `Apache-2.0` — Китайский финансовый ассистент на основе большой языковой модели.
- [BloombergGPT_zh](https://github.com/sunshineyg2018/BloombergGPT_zh) ⭐ `58` `—` `—` — Китайская реализация/воспроизведение BloombergGPT.
- [FinRAG](https://github.com/AI4Finance-Foundation/FinRAG) ⭐ `53` `Python` `Apache-2.0` — Система генерации с извлечением для финансовых доменов.

<a id="multi-agent"></a>
## 2. 🤖 Мультиагентные фреймворки для торговли и анализа

- [TradingAgents](https://github.com/TauricResearch/TradingAgents) ⭐ `90.3k` `Python` `Apache-2.0` — Мультиагентный LLM-фреймворк для торговли, имитирующий специализированные роли в торговой фирме.
- [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) ⭐ `7.4k` `Jupyter Notebook` `Apache-2.0` — Открытая платформа ИИ-агентов для финансового анализа на основе LLM.
- [TradingAgents-astock](https://github.com/simonlin1212/TradingAgents-astock) ⭐ `1.6k` `Python` `Apache-2.0` — Мультиагентный исследовательский фреймворк для акций A-shares на базе TradingAgents.
- [AgenticTrading](https://github.com/Open-Finance-Lab/AgenticTrading) ⭐ `260` `Python` `NOASSERTION` — Открытая платформа для торговых агентов на базе LLM и бэктестинга.
- [AlpacaTradingAgent](https://github.com/huygiatrng/AlpacaTradingAgent) ⭐ `238` `Python` `Apache-2.0` — Мультиагентный LLM-фреймворк для торговли, интегрированный с Alpaca для реальных сделок.
- [MarketAgents](https://github.com/marketagents-ai/MarketAgents) ⭐ `116` `Python` `—` — Фреймворк оркестрации экономических ИИ-агентов и рыночных симуляций.
- [LLM-Economist](https://github.com/sethkarten/LLM-Economist) ⭐ `114` `Python` `MIT` — Мультиагентная симуляция с большим числом LLM для механизмов и налоговой политики.
- [ai-economist](https://github.com/salesforce/ai-economist) ⭐ `110` `Python` `BSD-3-Clause` — Мультиагентный RL-фреймворк для социально-экономического поведения и проектирования политики.
- [orallexa-ai-trading-agent](https://github.com/alex-jb/orallexa-ai-trading-agent) ⭐ `52` `Python` `MIT` — Самонастраиваемая мультиагентная торговая система с дебатами бык/медведь/судья.

<a id="stock-analysis"></a>
## 3. 📈 LLM для анализа акций, прогнозирования и исследовательских отчётов

- [deep-research-machine](https://github.com/druce/deep-research-machine) ⭐ `11` `Python` `—` — Асинхронный пайплайн исследования акций с использованием LLM.
- [AI-Stock-Analyst-Agent-Langchain-Deepseek](https://github.com/Bisma-Shafiq/AI-Stock-Analyst-Agent-Langchain-Deepseek) ⭐ `7` `Python` `—` — Агент на LangChain/DeepSeek для анализа акций.
- [openbb-rag-financial-research-agent](https://github.com/sandole/openbb-rag-financial-research-agent) ⭐ `7` `Python` `—` — RAG-агент для SEC-документов и финансовых исследований.
- [stock_research_agent](https://github.com/druce/stock_research_agent) ⭐ `3` `Python` `—` — Генерация исследовательского отчёта по акциям через Claude agent SDK.
- [multi-horizon-financial-agent](https://github.com/srx7703/multi-horizon-financial-agent) ⭐ `2` `Python` `MIT` — Агент с использованием инструментов, синтезирующий SEC- и рыночные брифы.
- [stockgpt](https://github.com/ESJavadex/stockgpt) ⭐ `2` `Python` `MIT` — Анализ акций и генерация инвестиционных отчётов с помощью GPT-4.
- [StockerLens](https://github.com/Aswin-Cheerngodan/StockerLens) ⭐ `1` `Jupyter Notebook` `—` — Мультимодальное прогнозирование цен акций с сентимент-анализом и анализом графиков.
- [stock_signal_analyzer](https://github.com/mmovsesyan/stock_signal_analyzer) ⭐ `1` `Python` `—` — Самообучающаяся система для акций с сентимент-анализом новостей через LLM и планированием.
- [daily_stock_analysis](https://github.com/chief0714/daily_stock_analysis) ⭐ `1` `Python` `MIT` — Ежедневный мульти-рынковый анализ акций на базе LLM.

<a id="sentiment-nlp"></a>
## 4. 📰 Финансовый сентимент и NLP для новостей/соцсетей

- [finBERT](https://github.com/ProsusAI/finBERT) ⭐ `2.2k` `Jupyter Notebook` `Apache-2.0` — BERT-классификатор финансового сентимента для новостей и документов.
- [FinNLP](https://github.com/AI4Finance-Foundation/FinNLP) ⭐ `1.5k` `Jupyter Notebook` `MIT` — Библиотека финансового NLP для масштабных рыночных текстов.
- [FinBERT](https://github.com/valuesimplex/FinBERT) ⭐ `925` `Python` `MIT` — Реализация FinBERT для классификации финансовых текстов.
- [FinBERT](https://github.com/yya518/FinBERT) ⭐ `657` `Jupyter Notebook` `Apache-2.0` — Предобученный BERT для сентимента финансовых коммуникаций.
- [StockEmotions](https://github.com/adlnlp/StockEmotions) ⭐ `95` `Jupyter Notebook` `—` — Датасет и код для эмоций инвесторов и финансового сентимента.
- [finnlp-sentiment](https://github.com/nlp-chula/finnlp-sentiment) ⭐ `26` `Python` `—` — Тайские инструменты и модели для финансового сентимент-анализа.
- [twitter-alpha-sentiment-tracker-v2](https://github.com/Rezzecup/twitter-alpha-sentiment-tracker-v2) ⭐ `21` `Python` `—` — Трекер сентимента smart-money в X/Twitter в реальном времени.
- [Aspect-based-Financial-Sentiment-Analysis](https://github.com/ashishsalunkhe/Aspect-based-Financial-Sentiment-Analysis) ⭐ `11` `Jupyter Notebook` `—` — Aspect-based решение для финансового сентимента в рамках FiQA.
- [FinChina-SA](https://github.com/YerayL/FinChina-SA) ⭐ `7` `Python` `Apache-2.0` — Китайский датасет с детальным финансовым сентиментом и код.
- [earnings-edge](https://github.com/suhaas/earnings-edge) ⭐ `6` `Python` `—` — Мультиагентное приложение на LangGraph для аналитических брифов по транскриптам прибыли.

<a id="trading-bots"></a>
## 5. 💹 LLM/агентные торговые боты и бэктестинг

- [ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) ⭐ `60.7k` `Python` `MIT` — Мультиагентный LLM-фонд, моделирующий инвесторские персоны для принятия решений об акциях.
- [AI-Trader](https://github.com/HKUDS/AI-Trader) ⭐ `20.3k` `Python` `—` — Полностью автоматизированная торговая платформа для ИИ-агентов.
- [Qbot](https://github.com/UFund-Me/Qbot) ⭐ `17.9k` `Jupyter Notebook` `MIT` — Платформа для квантовых инвестиций и автоторговли на базе ИИ.
- [FinRL](https://github.com/AI4Finance-Foundation/FinRL) ⭐ `15.6k` `Jupyter Notebook` `MIT` — Библиотека финансового обучения с подкреплением и экосистема торговых агентов.
- [FinRL-Trading](https://github.com/AI4Finance-Foundation/FinRL-Trading) ⭐ `3.4k` `Python` `Apache-2.0` — ИИ-нативная модульная инфраструктура квантовой торговли с бэктестингом.
- [FinMem-LLM-StockTrading](https://github.com/pipiku915/FinMem-LLM-StockTrading) ⭐ `918` `Python` `MIT` — LLM-агент для торговли акциями с иерархической памятью и продуманным характером.
- [Stockagent](https://github.com/MingyuJ666/Stockagent) ⭐ `680` `Python` `—` — Торговля акциями на основе LLM в симулированных реальных рыночных условиях.
- [llm-agent-trader](https://github.com/jason8745/llm-agent-trader) ⭐ `375` `Python` `MIT` — Система бэктестинга торговли акциями с LLM-анализом решений.
- [FinRL_DeepSeek](https://github.com/benstaf/FinRL_DeepSeek) ⭐ `329` `Jupyter Notebook` `MIT` — Обучение с подкреплением с учётом риска и интеграцией LLM для торговых агентов.
- [LLM-TradeBot](https://github.com/EthanAlgoX/LLM-TradeBot) ⭐ `296` `Python` `MIT` — Мультиагентная ИИ-торговая система, использующая LLM для адаптации в реальном времени.
- [TwinMarket](https://github.com/FreedomIntelligence/TwinMarket) ⭐ `195` `Python` `MIT` — Мультиагентный LLM-фреймворк для социально-экономического моделирования рынка.
- [robinhood-ai-trading-bot](https://github.com/siropkin/robinhood-ai-trading-bot) ⭐ `118` `Python` `MIT` — Торговый бот на базе ИИ, интегрированный с Robinhood.
- [FinAgent](https://github.com/DVampire/FinAgent) ⭐ `75` `Python` `MIT` — Мультимодальный базовый агент для финансовой торговли с LLM, расширенной инструментами.
- [AutoTrader-AgentEdge](https://github.com/iAmGiG/AutoTrader-AgentEdge) ⭐ `18` `Python` `AGPL-3.0` — Продакшн-мультиагентная торговая платформа с прямой валидацией (walk-forward).
- [Auto-Trader](https://github.com/Itachi-Uchiha581/Auto-Trader) ⭐ `14` `Python` `MIT` — Торговый бот на базе LLM, автоматически исполняющий сделки.
- [trade-agent](https://github.com/mocasus/trade-agent) ⭐ `8` `Python` `MIT` — Модульный ИИ-торговый агент, использующий LLM для рынка, новостей и индикаторов.
- [ai-hedge-fund](https://github.com/zhound420/ai-hedge-fund) ⭐ `0` `Python` `—` — Мультиагентный хедж-фонд с бумажной торговлей Alpaca и LLM-аналитиками.

<a id="learning"></a>
## 6. 🎓 Образовательные платформы

- [finllm-apps](https://github.com/tinztwins/finllm-apps) ⭐ `152` `Python` `MIT` — Коллекция открытых FinLLM-приложений и демо.
- [Finance-LLMs](https://github.com/kennethleungty/Finance-LLMs) ⭐ `129` `—` `MIT` — Подборка реальных внедрений LLM в финансовых сервисах.
- [finLLM](https://github.com/ArchishmanSengupta/finLLM) ⭐ `7` `Python` `—` — Конверсационная FinLLM-демо на основе финансовой энциклопедии.
- [AI-Stock-Market-Chatbot](https://github.com/AbeTavarez/AI-Stock-Market-Chatbot) ⭐ `6` `TypeScript` `—` — ИИ-чатбот для фондового рынка на Next.js и OpenAI.
- [finLLM](https://github.com/Entropov/finLLM) ⭐ `1` `Python` `—` — Экспериментальный FinLLM-преподаватель для Q&A по финансам.
- [FinancialLiteracyChatbot](https://github.com/24prathamesh2004/FinancialLiteracyChatbot) ⭐ `2` `HTML` `—` — Конверсационный чатбот для финансовой грамотности: личные финансы и основы инвестирования.
- [FinWise](https://github.com/aadithya2007/FinWise) ⭐ `1` `JavaScript` `—` — Конверсационный ассистент для обучения финансовой грамотности и основам инвестирования.
- [financial-literacy-chatbot](https://github.com/sparsh-j01/financial-literacy-chatbot) ⭐ `1` `HTML` `—` — Двуязычный чатбот финансовой грамотности на Google Gemini.
- [ArthSakhi](https://github.com/SmritiD2004/ArthSakhi) ⭐ `1` `Python` `—` — Чатбот финансовой грамотности для женщин в Индии.
- [AI_FinancialTutor](https://github.com/NaniSkinner/AI_FinancialTutor) ⭐ `0` `TypeScript` `—` — ИИ-репетитор для интерактивного обучения инвестициям и финансам.
- [FinancialLiteracyChatbot](https://github.com/premnath228004/FinancialLiteracyChatbot) ⭐ `0` `Python` `—` — Двуязычный чатбот финансовой грамотности с CLI и доступом через WhatsApp.
- [financial-literacy-bot](https://github.com/Collin17Muse/financial-literacy-bot) ⭐ `0` `HTML` `—` — Интерактивный чатбот финансовой грамотности с обучением, тестами и отслеживанием прогресса.
- [Multilingual_financial_Chatbot](https://github.com/Indhumathi-RA/Multilingual_financial_Chatbot) ⭐ `0` `Jupyter Notebook` `—` — Мультиязычный RAG-чатбот для гонконгских финансовых концепций.
- [syf-finlit-agent](https://github.com/SidharthAnand04/syf-finlit-agent) ⭐ `0` `TypeScript` `—` — ИИ-агент для объяснения кредитных продуктов и повышения финансовой грамотности.

<a id="datasets"></a>
## 7. 📊 Датасеты и бенчмарки

- [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) ⭐ `1.9k` `Python` `MIT` — Динамические датасеты и рыночные среды для финансового RL.
- [FNSPID_Financial_News_Dataset](https://github.com/Zdong104/FNSPID_Financial_News_Dataset) ⭐ `432` `Python` `NOASSERTION` — Крупный датасет финансовых новостей и цен акций S&P 500 для временных рядов.
- [FinLLMs](https://github.com/adlnlp/FinLLMs) ⭐ `380` `—` `—` — Бенчмарки и датасеты для статьи Large Language Models in Finance.
- [financebench](https://github.com/patronus-ai/financebench) ⭐ `332` `Jupyter Notebook` `—` — Бенчмарк с открытым источником для финансового QA с LLM.
- [FinEval](https://github.com/SUFE-AIFLM-Lab/FinEval) ⭐ `278` `Python` `Apache-2.0` — Китайский финансовый бенчмарк с 26 000+ вопросов для оценки LLM.
- [live-trade-bench](https://github.com/ulab-uiuc/live-trade-bench) ⭐ `160` `Python` `NOASSERTION` — Бенчмарк для оценки торговых агентов в реальном времени.
- [BizFinBench](https://github.com/HiThink-Research/BizFinBench) ⭐ `167` `Python` `—` — Бизнес-ориентированный реальный финансовый бенчмарк для LLM.
- [cflue](https://github.com/aliyun/cflue) ⭐ `91` `Python` `—` — Китайский бенчмарк понимания финансового языка для LLM.
- [FinLoRA](https://github.com/Open-Finance-Lab/FinLoRA) ⭐ `66` `Python` `NOASSERTION` — Бенчмаркинг LoRA для дообучения LLM на финансовых данных.
- [FLANG](https://github.com/SALT-NLP/FLANG) ⭐ `57` `Python` `Apache-2.0` — Предобученная модель для финансового домена и набор бенчмарков FLUE.
- [CFBenchmark](https://github.com/TongjiFinLab/CFBenchmark) ⭐ `55` `Python` `Apache-2.0` — Китайский бенчмарк финансового ассистента для больших языковых моделей.
- [FinMTEB](https://github.com/yixuantt/FinMTEB) ⭐ `54` `Python` `—` — Финансовый масштабный бенчмарк текстовых эмбеддингов на 64 датасетах.
- [FinLLM-Leaderboard](https://github.com/Open-Finance-Lab/FinLLM-Leaderboard) ⭐ `26` `Jupyter Notebook` `MIT` — Лидерборд для оценки финансовых LLM и агентов.
- [CNFinBench](https://github.com/open-compass/CNFinBench) ⭐ `16` `Python` `—` — Комплексный высокорисковый китайский финансовый бенчмарк с цепочками агентов.
- [FinBen](https://github.com/The-FinAI/FinBen) ⭐ `15` `Python` `—` — Комплексный набор бенчмарков для оценки LLM на финансовых задачах.
- [FinanceQA](https://github.com/AfterQuery/FinanceQA) ⭐ `8` `—` `—` — Бенчмарк для оценки возможностей LLM в финансовом анализе.

<a id="papers"></a>
## 8. 🧪 Исследовательские статьи с кодом

В этой категории собраны репозитории, в которых в первую очередь публикуется официальный код к академическим статьям по LLM/агентным финансам. Если вы знаете подходящий репозиторий с кодом к статье, пожалуйста, откройте PR.

<a id="absorb"></a>
## 9. 🧩 Шпаргалка по применимым идеям

- **Мультиагентные дебаты / ролевая специализация** — Разделение анализа на специализированные персоны (бык, медведь, риск-менеджер, портфельный менеджер) и разрешение разногласий через структурированные дебаты. (exemplified by: TradingAgents, orallexa-ai-trading-agent, ai-hedge-fund)
- **Инструментально-усиленное извлечение по документам / RAG для финансов** — Привязка выводов LLM к SEC-документам, транскриптам прибылей и рыночным данным через retrieval augmentation. (exemplified by: FinRAG, openbb-rag-financial-research-agent, multi-horizon-financial-agent)
- **Сентимент-сигнал пайплайн на основе LLM** — Превращение сентимента новостей, соцсетей или звонков по прибылям в количественные торговые сигналы. (exemplified by: twitter-alpha-sentiment-tracker-v2, FinNLP, ProsusAI/finBERT)
- **Рецепт дообучения LoRA/PEFT на финансовом корпусе** — Адаптация общих LLM к финансам через лёгкое дообучение на транскриптах прибылей, новостях и отчётах. (exemplified by: FinGPT, FinLoRA, PIXIU)
- **Торговый агент с памятью** — Многоуровневая краткосрочная и долгосрочная память агента для сохранения контекста портфеля и адаптации поведения. (exemplified by: FinMem-LLM-StockTrading)
- **ReAct + инструменты для генерации исследовательских отчётов** — Использование LLM в циклах рассуждения и действий для сбора данных и написания инвестиционных отчётов. (exemplified by: deep-research-machine, stock_research_agent)
- **Бэктестинг + песочница бумажной торговли** — Валидация стратегий агентов через воспроизведение исторических рыночных данных и бумажные счета брокера перед запуском в реальную торговлю. (exemplified by: FinRL, Qbot, AlpacaTradingAgent)
- **Риск-контроль / вето человека в цепочке** — Введение ограничителей или точек одобрения человеком между генерацией сигнала и исполнением сделки. (exemplified by: AutoTrader-AgentEdge, ai-hedge-fund, LLM-TradeBot)
- **Мультимодальное понимание рынка** — Совместный анализ ценовых графиков, альтернативных данных и текста для улучшения анализа акций. (exemplified by: StockerLens, FinAgent)
- **Рыночная симуляция с генеративными агентами** — Симуляция экономических и торговых сообществ агентами LLM для изучения возникающих динамик рынка. (exemplified by: TwinMarket, LLM-Economist, ai-economist)
- **Разработка на основе финансовых бенчмарков** — Использование финансовых бенчмарков QA, эмбеддингов и торговли для оценки возможностей LLM/агентов. (exemplified by: FinEval, financebench, BizFinBench)

<a id="contributing"></a>
## 🙋 Внесение вклада

Вклады приветствуются! Пожалуйста, ознакомьтесь с [CONTRIBUTING.md](CONTRIBUTING.md), где описаны правила добавления записей, форматирования и переводов.

<a id="license"></a>
## 📜 Лицензия

Этот список распространяется под лицензией [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/). Каждый связанный проект сохраняет свою собственную лицензию — пожалуйста, соблюдайте условия каждого репозитория.

<a id="star-history"></a>
## ⭐ Star History

<sub>Если этот список оказался полезен, пожалуйста, поставьте ⭐ — это поможет другим найти его.</sub>

<a href="https://star-history.com/#Lxcardoza993/awesome-token2cash&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Lxcardoza993/awesome-token2cash&type=Date" />
  </picture>
</a>

[⬆ Наверх](#awesome-token2cash)
