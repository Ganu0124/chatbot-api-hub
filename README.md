🤖 ChatBot API Hub

<p align="center">
  <img src="assets/chatbot-api-hub.gif" alt="Animated ChatBot API Hub banner" width="100%">
</p>

<p align="center">
  <strong>A visual, developer-first directory of 240+ free and free-tier APIs for chatbots, AI agents, RAG, automation, voice apps, and modern web projects.</strong>
</p>

<p align="center">
  <a href="#-api-directory">API Directory</a> ·
  <a href="#-quick-key-access">Quick Key Access</a> ·
  <a href="#-chatbot-architecture">Architecture</a> ·
  <a href="#-contribute">Contribute</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/APIs-240%2B-00E5FF?style=for-the-badge">
  <img src="https://img.shields.io/badge/Categories-31%2B-8B5CF6?style=for-the-badge">
  <img src="https://img.shields.io/badge/No--Key-74-34D399?style=for-the-badge">
  <img src="https://img.shields.io/badge/Key%20%2F%20Token-166-FF4FD8?style=for-the-badge">
</p>

✨ What is this?

This repository collects APIs you can plug into a chatbot or AI agent.

It follows the directory idea used by the Public APIs project, but organizes the collection around chatbot tools, RAG, agents, voice, data, automation, and application backends. The Public APIs project uses fields such as API, Description, Auth, HTTPS, and CORS, and it is community-curated.

Use the links to open the provider, create your own credential when required, read the documentation, and connect the API to your application.

🔐 This repository never publishes private API keys. It provides public signup/access links for creating your own credentials.

🎯 Why this exists

SEARCH FOR API
      ↓
CHECK AUTH
      ↓
OPEN KEY / ACCESS PAGE
      ↓
READ DOCS
      ↓
TEST ENDPOINT
      ↓
CONNECT AS A CHATBOT TOOL
      ↓
SHIP

📊 Directory snapshot

Metric

Current

API entries

240+

Categories

31+

No-key / public access

74

Key / token / OAuth APIs

166

Chatbot-ready focus APIs

25

Animated GitHub header

Yes

Direct access links

Yes

Documentation links

Yes

🧠 Chatbot architecture

                         ┌─────────────────────┐
                         │       USER          │
                         │  Text / Voice / UI  │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │   CHATBOT / AGENT   │
                         │  LLM + memory +     │
                         │  tool routing       │
                         └──────────┬──────────┘
                                    │
         ┌──────────────────────────┼──────────────────────────┐
         ▼                          ▼                          ▼
  ┌─────────────┐           ┌─────────────┐            ┌─────────────┐
  │     LLM     │           │   KNOWLEDGE │            │    TOOLS    │
  │ Groq        │           │ Tavily      │            │ Weather     │
  │ Mistral     │           │ arXiv       │            │ Maps        │
  │ HuggingFace │           │ OpenAlex    │            │ News        │
  │ OpenRouter  │           │ Wikipedia   │            │ Finance     │
  └──────┬──────┘           └──────┬──────┘            │ Email       │
         │                         │                    │ Messaging   │
         └──────────────┬──────────┘                    │ Payments    │
                        ▼                               └──────┬──────┘
                ┌───────────────┐                             │
                │ RAG / MEMORY  │                             │
                │ Vector DB     │                             │
                │ Documents     │                             │
                └──────┬────────┘                             │
                       └──────────────────┬────────────────────┘
                                          ▼
                                ┌──────────────────┐
                                │ YOUR APPLICATION │
                                │ React / Next.js  │
                                │ FastAPI / Node   │
                                │ Supabase / DB    │
                                └──────────────────┘

🔥 Quick Key Access

These are common starting points for an AI chatbot stack:

#

API

Purpose

Auth

Get Access

Docs

1

Groq

Fast LLM inference

API Key

Open

Docs

2

Hugging Face

Open-source models and inference

Token

Open

Docs

3

OpenRouter

Access multiple LLM providers

API Key

Open

Docs

4

Mistral AI

LLM and embeddings

API Key

Open

Docs

5

Cohere

Chat, embeddings and RAG

API Key

Open

Docs

6

Tavily

AI web search

API Key

Open

Docs

7

Brave Search

Web search

API Key

Open

Docs

8

Serper

Google search data

API Key

Open

Docs

9

Open-Meteo

Weather forecasts

None

Open

Docs

10

OpenWeather

Weather data

API Key

Open

Docs

11

NewsAPI

News search

API Key

Open

Docs

12

Pexels

Stock image search

API Key

Open

Docs

13

Unsplash

Image search

Access Key

Open

Docs

14

Deepgram

Speech-to-text and audio AI

API Key

Open

Docs

15

ElevenLabs

Text-to-speech

API Key

Open

Docs

16

Telegram Bot API

Telegram chatbots

Bot Token

Open

Docs

17

Razorpay

Indian payments

API Key

Open

Docs

18

Stripe

Payments and billing

API Key

Open

Docs

19

Supabase

PostgreSQL, auth and storage

API Key

Open

Docs

20

Pinecone

Vector database for RAG

API Key

Open

Docs

21

Qdrant Cloud

Vector search database

API Key

Open

Docs

22

Firecrawl

Web scraping for AI agents

API Key

Open

Docs

23

Google Maps Platform

Maps, geocoding and places

API Key

Open

Docs

24

GitHub REST API

Repositories and code

Token optional

Open

Docs

25

Telegram Bot API

Telegram chatbot interface

Bot Token

Open

Docs

🧩 Recommended tool stack

BRAIN
Groq / Mistral / Hugging Face / OpenRouter
        │
        ├── WEB SEARCH
        │   Tavily / Brave / Serper / Exa
        │
        ├── RAG
        │   Pinecone / Qdrant / Weaviate / Chroma
        │
        ├── WEB EXTRACTION
        │   Firecrawl / Jina / Unstructured
        │
        ├── VOICE
        │   Deepgram / AssemblyAI / ElevenLabs
        │
        ├── VISION
        │   Roboflow / Clarifai
        │
        ├── TOOLS
        │   Weather / Maps / News / Finance
        │
        ├── COMMUNICATION
        │   Telegram / Discord / Slack
        │
        └── BACKEND
            Supabase / Firebase / Appwrite

🗂️ Categories

AI / LLM\n- Authentication\n- Communication\n- Cybersecurity\n- Database / Backend\n- Developer\n- E-commerce\n- Email\n- Email / Messaging\n- Entertainment\n- Finance\n- Healthcare\n- Images / Media\n- Maps / Location\n- News\n- OCR / Documents\n- Payments\n- Programming\n- RAG / Data\n- RAG / Research\n- Science / Space\n- Search / Web\n- Social / Bots\n- Speech / Audio\n- Sports\n- Translation / NLP\n- Travel\n- Utility\n- Vision\n- Weather\n- Weather / Environment\n

📚 API Directory

AI / LLM {#ai-llm}

#

API

Purpose

Auth

Get Access

Docs

1

Groq

Fast LLM inference

API Key

Open

Docs

2

Hugging Face

Open-source models and inference

Token

Open

Docs

3

OpenRouter

Access multiple LLM providers

API Key

Open

Docs

4

Mistral AI

LLM and embeddings

API Key

Open

Docs

5

Cohere

Chat, embeddings and RAG

API Key

Open

Docs

6

Together AI

Open-source LLM inference

API Key

Open

Docs

7

Cerebras

Fast AI inference

API Key

Open

Docs

8

Replicate

Run hosted AI models

API Token

Open

Docs

9

Ollama

Run LLMs locally

None

Open

Docs

10

LM Studio

Local LLM server

None

Open

Docs

11

Anthropic

Claude models and AI assistants

API Key

Open

Docs

12

AI21 Labs

Language models and text APIs

API Key

Open

Docs

13

Fireworks AI

Fast generative AI inference

API Key

Open

Docs

14

DeepInfra

Hosted open-source model inference

API Key

Open

Docs

15

SambaNova Cloud

Generative AI inference

API Key

Open

Docs

16

AI Horde

Community-powered image and text generation

API Key optional

Open

Docs

17

Perplexity

AI search and language models

API Key

Open

Docs

18

GroqCloud Models

Open models on Groq infrastructure

API Key

Open

Docs

19

NVIDIA Build

Generative AI model APIs

API Key

Open

Docs

20

Modal

Run serverless AI workloads

API Key

Open

Docs

Authentication {#authentication}

#

API

Purpose

Auth

Get Access

Docs

1

Clerk

Authentication and user management

API Key

Open

Docs

2

Auth0

Authentication and authorization

Domain / Client ID

Open

Docs

3

Stytch

Authentication APIs

API Keys

Open

Docs

4

Kinde

Authentication and identity

OAuth

Open

Docs

5

Supabase Auth

Authentication and sessions

Project Key

Open

Docs

Communication {#communication}

#

API

Purpose

Auth

Get Access

Docs

1

Telegram Bot API

Telegram chatbots

Bot Token

Open

Docs

2

Discord

Discord bots

Bot Token

Open

Docs

3

Slack

Workspace bots

OAuth

Open

Docs

4

Twilio

SMS and communication

API Key

Open

Docs

5

WhatsApp Cloud API

WhatsApp messaging

Token

Open

Docs

Cybersecurity {#cybersecurity}

#

API

Purpose

Auth

Get Access

Docs

1

VirusTotal

File and URL intelligence

API Key

Open

Docs

2

AbuseIPDB

IP reputation

API Key

Open

Docs

3

Shodan

Internet intelligence

API Key

Open

Docs

4

URLScan

URL analysis

API Key

Open

Docs

5

NVD

Vulnerability database

API Key optional

Open

Docs

6

CISA KEV

Known exploited vulnerabilities

None

Open

Docs

7

URLhaus

Malicious URL intelligence

None

Open

Docs

Database / Backend {#database-backend}

#

API

Purpose

Auth

Get Access

Docs

1

Supabase

PostgreSQL, auth and storage

API Key

Open

Docs

2

Firebase

Database, auth and storage

Config/API

Open

Docs

3

Appwrite

Backend services

API Key

Open

Docs

4

Convex

Backend database

Project credentials

Open

Docs

Developer {#developer}

#

API

Purpose

Auth

Get Access

Docs

1

GitHub

Repositories and developer data

Token

Open

Docs

2

GitLab

Repositories and CI/CD

Token

Open

Docs

3

npm Registry

Package metadata

None

Open

Docs

4

PyPI

Python package metadata

None

Open

Docs

5

JSONPlaceholder

Fake REST data

None

Open

Docs

6

DummyJSON

Fake REST data

None

Open

Docs

7

httpbin

HTTP testing

None

Open

Docs

8

Random User

Random user profiles

None

Open

Docs

E-commerce {#e-commerce}

#

API

Purpose

Auth

Get Access

Docs

1

Fake Store API

Fake products and carts

None

Open

Docs

2

DummyJSON Products

Mock products data

None

Open

Docs

3

Shopify Admin API

Store data and operations

OAuth

Open

Docs

4

WooCommerce REST API

Products and orders

Consumer Key/Secret

Open

Docs

5

Printful API

Print-on-demand catalog

API Key

Open

Docs

6

eBay APIs

Marketplace data

OAuth

Open

Docs

Email {#email}

#

API

Purpose

Auth

Get Access

Docs

1

Resend

Transactional email

API Key

Open

Docs

2

Brevo

Email and messaging

API Key

Open

Docs

3

SendGrid

Transactional email

API Key

Open

Docs

4

Mailgun

Email API

API Key

Open

Docs

Email / Messaging {#email-messaging}

#

API

Purpose

Auth

Get Access

Docs

1

EmailJS

Client-side email sending

Public Key

Open

Docs

2

Mailjet

Email API

API Key

Open

Docs

3

Postmark

Transactional email

Server Token

Open

Docs

4

EmailOctopus

Email marketing API

API Key

Open

Docs

5

OneSignal

Push notifications

App ID / Key

Open

Docs

Entertainment {#entertainment}

#

API

Purpose

Auth

Get Access

Docs

1

TMDB

Movies and TV

API Key

Open

Docs

2

OMDb

Movie information

API Key

Open

Docs

3

TVMaze

TV show data

None

Open

Docs

4

Spotify

Music data

OAuth

Open

Docs

5

Jikan

MyAnimeList API

None

Open

Docs

6

YouTube Data API

Video metadata and search

API Key

Open

Docs

Finance {#finance}

#

API

Purpose

Auth

Get Access

Docs

1

Alpha Vantage

Stocks and forex

API Key

Open

Docs

2

Finnhub

Market data

API Key

Open

Docs

3

CoinGecko

Crypto data

API Key

Open

Docs

4

CoinCap

Crypto market data

API Key optional

Open

Docs

5

Frankfurter

Currency exchange

None

Open

Docs

6

FRED

Economic indicators

API Key

Open

Docs

7

Twelve Data

Stocks, forex and crypto

API Key

Open

Docs

8

World Bank

Economic and development data

None

Open

Docs

9

Marketstack

Stocks and market data

API Key

Open

Docs

10

Polygon

Market data

API Key

Open

Docs

11

Tink

Financial account connectivity

API Key

Open

Docs

12

Plaid

Financial data connectivity

Client ID/Secret

Open

Docs

13

Teller

Open banking API

Application

Open

Docs

14

ExchangeRate.host

Currency conversion

None / Key

Open

Docs

Healthcare {#healthcare}

#

API

Purpose

Auth

Get Access

Docs

1

OpenFDA

FDA public data

None/API Key

Open

Docs

2

ClinicalTrials.gov

Clinical trials

None

Open

Docs

3

RxNorm

Medication terminology

None

Open

Docs

4

NLM APIs

Biomedical data

None

Open

Docs

Images / Media {#images-media}

#

API

Purpose

Auth

Get Access

Docs

1

Pexels

Stock image search

API Key

Open

Docs

2

Unsplash

Image search

Access Key

Open

Docs

3

Pixabay

Images and videos

API Key

Open

Docs

4

Giphy

GIF search

API Key

Open

Docs

5

Tenor

GIF search

API Key

Open

Docs

6

DiceBear

Avatar generation

None

Open

Docs

7

Lorem Picsum

Placeholder images

None

Open

Docs

Maps / Location {#maps-location}

#

API

Purpose

Auth

Get Access

Docs

1

OpenStreetMap

Open map data

None

Open

Docs

2

Nominatim

Geocoding

None

Open

Docs

3

Mapbox

Maps and navigation

Access Token

Open

Docs

4

OpenRouteService

Routing and directions

API Key

Open

Docs

5

Geoapify

Geocoding and places

API Key

Open

Docs

6

GeoNames

Geographic data

Username

Open

Docs

7

IPinfo

IP geolocation

Token

Open

Docs

8

IP-API

IP geolocation

None

Open

Docs

9

Google Maps Platform

Maps, geocoding and places

API Key

Open

Docs

10

HERE

Maps and location services

API Key

Open

Docs

11

Radar

Geofencing and maps

API Key

Open

Docs

12

LocationIQ

Geocoding and maps

API Key

Open

Docs

13

Bing Maps

Maps and geocoding

API Key

Open

Docs

14

GeoJS

IP geolocation

None

Open

Docs

News {#news}

#

API

Purpose

Auth

Get Access

Docs

1

NewsAPI

News search

API Key

Open

Docs

2

GNews

News search

API Key

Open

Docs

3

TheNewsAPI

News feeds

API Key

Open

Docs

4

Guardian API

News articles

API Key

Open

Docs

5

New York Times API

News and archives

API Key

Open

Docs

6

Currents API

News search

API Key

Open

Docs

7

NewsData.io

Global news

API Key

Open

Docs

8

Mediastack

News API

API Key

Open

Docs

9

NYTimes API

News and archive data

API Key

Open

Docs

10

GDELT

Global event and news data

None

Open

Docs

11

The Guardian API

News articles

API Key

Open

Docs

OCR / Documents {#ocr-documents}

#

API

Purpose

Auth

Get Access

Docs

1

OCR.Space

OCR API

API Key

Open

Docs

2

Nanonets

OCR and document processing

API Key

Open

Docs

3

Mindee

Document parsing

API Key

Open

Docs

4

Cloudmersive

Document and OCR APIs

API Key

Open

Docs

5

PDF.co

PDF processing

API Key

Open

Docs

6

ConvertAPI

Document conversion

API Key

Open

Docs

Payments {#payments}

#

API

Purpose

Auth

Get Access

Docs

1

Razorpay

Indian payments

API Key

Open

Docs

2

Stripe

Payments and billing

API Key

Open

Docs

3

Cashfree

Indian payments

API Key

Open

Docs

4

PayPal

Payments

Client ID/Secret

Open

Docs

Programming {#programming}

#

API

Purpose

Auth

Get Access

Docs

1

Judge0

Online code execution

API Key

Open

Docs

2

Piston

Code execution API

None

Open

Docs

3

GitHub REST API

Repositories and code

Token optional

Open

Docs

4

GitHub GraphQL API

Graph data for GitHub

Token

Open

Docs

5

GitLab API

Repositories and CI/CD

Token

Open

Docs

6

Codeforces API

Contest and problem data

API Key optional

Open

Docs

7

HackerRank

Coding platform integrations

API / partner

Open

Docs

RAG / Data {#rag-data}

#

API

Purpose

Auth

Get Access

Docs

1

Pinecone

Vector database for RAG

API Key

Open

Docs

2

Qdrant Cloud

Vector search database

API Key

Open

Docs

3

Weaviate Cloud

Vector database

API Key

Open

Docs

4

Milvus

Vector database

None / Token

Open

Docs

5

Chroma

Open-source vector database

None

Open

Docs

6

LanceDB

Embedded vector database

None

Open

Docs

7

Supabase Vector

Postgres vector search

Project Key

Open

Docs

8

Neo4j Aura

Graph database for knowledge graphs

Login

Open

Docs

9

Unstructured

Document processing for RAG

API Key

Open

Docs

10

Firecrawl

Web scraping for AI agents

API Key

Open

Docs

RAG / Research {#rag-research}

#

API

Purpose

Auth

Get Access

Docs

1

arXiv

Research papers

None

Open

Docs

2

OpenAlex

Academic research graph

None

Open

Docs

3

Crossref

Publication metadata

None

Open

Docs

4

Semantic Scholar

Academic search

API Key optional

Open

Docs

5

PubMed

Biomedical literature

None

Open

Docs

6

Open Library

Books and metadata

None

Open

Docs

7

Wikidata

Knowledge graph

None

Open

Docs

Science / Space {#science-space}

#

API

Purpose

Auth

Get Access

Docs

1

NASA APIs

Space and Earth data

API Key

Open

Docs

2

SpaceX API

Launch and rocket data

None

Open

Docs

3

USGS

Earthquake and Earth data

None

Open

Docs

4

GBIF

Biodiversity data

None

Open

Docs

5

NASA

Space and Earth data

API Key

Open

Docs

6

SpaceX

Launch and rocket data

None

Open

Docs

7

USGS Earthquake

Earthquake feeds

None

Open

Docs

8

OpenAQ

Air quality measurements

None

Open

Docs

9

Wikidata

Structured knowledge graph

None

Open

Docs

Search / Web {#search-web}

#

API

Purpose

Auth

Get Access

Docs

1

Tavily

AI web search

API Key

Open

Docs

2

Brave Search

Web search

API Key

Open

Docs

3

Serper

Google search data

API Key

Open

Docs

4

Wikipedia

Knowledge retrieval

None

Open

Docs

5

GDELT

Global news and events

None

Open

Docs

6

Internet Archive

Web and digital archives

None

Open

Docs

7

Hacker News

Technology stories

None

Open

Docs

8

Reddit

Community content

OAuth/API

Open

Docs

9

Exa

Semantic web search for AI agents

API Key

Open

Docs

10

Jina Reader

Web page to LLM-ready text

API Key

Open

Docs

11

Jina Search

Search API for agents

API Key

Open

Docs

12

SearXNG

Open metasearch engine

None

Open

Docs

13

DuckDuckGo Instant Answer

Search answers

None

Open

Docs

14

Google Custom Search

Programmable web search

API Key

Open

Docs

15

Common Crawl

Web crawl index

None

Open

Docs

16

Mediastack

News and media data

API Key

Open

Docs

17

SerpApi

Search engine results

API Key

Open

Docs

Social / Bots {#social-bots}

#

API

Purpose

Auth

Get Access

Docs

1

Telegram Bot API

Telegram chatbot interface

Bot Token

Open

Docs

2

Discord Developer API

Bots and applications

Bot Token

Open

Docs

3

Slack Platform

Workspace bots

OAuth

Open

Docs

4

Twitch API

Streaming and creator data

OAuth / Client ID

Open

Docs

5

Bluesky API

Social graph and posts

Session

Open

Docs

6

Mastodon API

Social platform API

OAuth

Open

Docs

Speech / Audio {#speech-audio}

#

API

Purpose

Auth

Get Access

Docs

1

Deepgram

Speech-to-text and audio AI

API Key

Open

Docs

2

AssemblyAI

Speech-to-text

API Key

Open

Docs

3

ElevenLabs

Text-to-speech

API Key

Open

Docs

4

Whisper

Speech recognition

Local/Open-source

Open

Docs

5

Piper TTS

Local text-to-speech

None

Open

Docs

6

Google Speech-to-Text

Speech recognition

API Key

Open

Docs

7

Azure Speech

Speech and voice services

API Key

Open

Docs

8

PlayHT

Text-to-speech

API Key

Open

Docs

9

Cartesia

Low-latency voice AI

API Key

Open

Docs

10

Picovoice

On-device voice AI

Access Key

Open

Docs

Sports {#sports}

#

API

Purpose

Auth

Get Access

Docs

1

TheSportsDB

Sports data

API Key optional

Open

Docs

2

API-Football

Football data

API Key

Open

Docs

3

balldontlie

Basketball data

API Key

Open

Docs

4

Jolpica F1

Formula 1 data

None

Open

Docs

Translation / NLP {#translation-nlp}

#

API

Purpose

Auth

Get Access

Docs

1

LibreTranslate

Machine translation

API Key optional

Open

Docs

2

DeepL

Translation

API Key

Open

Docs

3

LanguageTool

Grammar checking

API Key optional

Open

Docs

4

Datamuse

Word relationships

None

Open

Docs

5

Free Dictionary

Definitions

None

Open

Docs

Travel {#travel}

#

API

Purpose

Auth

Get Access

Docs

1

Amadeus

Flights and travel

API Key

Open

Docs

2

AviationStack

Flight data

API Key

Open

Docs

3

OpenSky Network

Aircraft tracking

OAuth/None

Open

Docs

4

REST Countries

Country information

None

Open

Docs

5

OpenTripMap

Tourist attractions

API Key

Open

Docs

Utility {#utility}

#

API

Purpose

Auth

Get Access

Docs

1

IPify

Public IP address

None

Open

Docs

2

QR Server

QR code generation

None

Open

Docs

3

Advice Slip

Advice text

None

Open

Docs

4

Numbers API

Number facts

None

Open

Docs

5

Agify

Age prediction

None

Open

Docs

6

Genderize

Gender prediction

None

Open

Docs

7

Nationalize

Nationality prediction

None

Open

Docs

8

Random User

Random profile data

None

Open

Docs

9

DiceBear

Avatar generation

None

Open

Docs

10

JSONPlaceholder

Fake REST API

None

Open

Docs

11

DummyJSON

Mock REST data

None

Open

Docs

12

HTTPBin

HTTP request testing

None

Open

Docs

13

Public APIs Directory API

Searchable public API catalog

None

Open

Docs

Vision {#vision}

#

API

Purpose

Auth

Get Access

Docs

1

Roboflow

Computer vision inference and datasets

API Key

Open

Docs

2

Clarifai

Vision and AI inference

API Key

Open

Docs

3

Hugging Face Inference

Computer vision and multimodal models

Token

Open

Docs

4

Google Vision

Image understanding

API Key

Open

Docs

5

Azure Computer Vision

Vision AI

API Key

Open

Docs

6

AWS Rekognition

Image and video analysis

Access Key

Open

Docs

Weather {#weather}

#

API

Purpose

Auth

Get Access

Docs

1

Open-Meteo

Weather forecasts

None

Open

Docs

2

OpenWeather

Weather data

API Key

Open

Docs

3

WeatherAPI

Weather and forecasts

API Key

Open

Docs

4

Weatherbit

Weather data

API Key

Open

Docs

5

OpenAQ

Air quality

None

Open

Docs

6

AQICN

Air quality

API Key

Open

Docs

Weather / Environment {#weather-environment}

#

API

Purpose

Auth

Get Access

Docs

1

Meteostat

Historical weather

None

Open

Docs

2

Visual Crossing

Weather data

API Key

Open

Docs

3

Tomorrow.io

Weather intelligence

API Key

Open

Docs

4

Weatherstack

Current and historical weather

API Key

Open

Docs

5

Climatiq

Carbon emissions data

API Key

Open

Docs

🔐 Authentication legend

Auth

Meaning

None

Public endpoint or no key listed

API Key

Create your own API key with the provider

Token

Create an access token

OAuth

Use the provider OAuth flow

Client ID/Secret

Create app credentials

Project Key

Key tied to a project or backend

Free-tier limits, credit amounts, authentication rules, geographic availability, and pricing change over time. Verify the provider page before deploying.

🚀 Quick Start

git clone https://github.com/YOUR_USERNAME/chatbot-api-hub.git
cd chatbot-api-hub

Create .env:

GROQ_API_KEY=your_key_here
TAVILY_API_KEY=your_key_here
SUPABASE_URL=your_project_url
SUPABASE_KEY=your_key_here

Add .env to .gitignore:

.env
.env.*
*.key
secrets/
credentials/

🧪 Minimal Python pattern

import os
from groq import Groq

client = Groq(api_key=os.environ["GROQ_API_KEY"])

response = client.chat.completions.create(
    model="YOUR_MODEL",
    messages=[
        {"role": "user", "content": "Hello"}
    ],
)

print(response.choices[0].message.content)

🛠️ Recommended repository structure

chatbot-api-hub/
├── README.md
├── assets/
│   └── chatbot-api-hub.gif
├── APIs/
│   ├── ai/
│   ├── search/
│   ├── rag/
│   ├── vision/
│   ├── speech/
│   ├── weather/
│   ├── maps/
│   ├── news/
│   ├── finance/
│   ├── cybersecurity/
│   ├── communication/
│   ├── payments/
│   └── developer/
├── examples/
│   ├── chatbot/
│   ├── rag/
│   ├── agents/
│   ├── voice/
│   └── automation/
├── templates/
│   ├── python/
│   ├── javascript/
│   └── fastapi/
├── CONTRIBUTING.md
└── LICENSE

🤖 Chatbot use cases

Build

Useful API groups

Research assistant

Search + RAG + LLM

Study assistant

Research + books + LLM

News bot

News + search + LLM

Travel assistant

Maps + flights + weather

Voice assistant

Speech + LLM + TTS

Finance assistant

Market data + currency + LLM

Cybersecurity assistant

Threat intel + search + LLM

Customer support bot

LLM + RAG + email

Shopping assistant

Products + search + payments

Telegram / Discord bot

LLM + communication

🌐 Inspired by Public APIs

The project uses the same broad discovery philosophy as the Public APIs repository. That project organizes free APIs by category and exposes fields such as authentication, HTTPS, and CORS. citeturn365816search9turn365816search2

Official reference:

https://github.com/public-apis/public-apis

Public APIs also exposes a separate catalog API with endpoints such as /entries, /random, /categories, and /health.

🤝 Contribute

Add an API only when you have enough public information to verify its official homepage and documentation.

Use this format:

API:
Category:
Purpose:
Authentication:
Free / free-tier:
Key or access URL:
Documentation:
Chatbot use case:

Do not submit private API keys.

🗺️ Roadmap

[x] Visual GitHub README
[x] Animated banner
[x] Large API directory
[x] Direct access links
[x] Authentication labels
[x] Documentation links
[x] Chatbot architecture
[ ] 250+ curated chatbot APIs
[ ] 500+ curated chatbot APIs
[ ] Searchable static website
[ ] API health checker
[ ] Free-tier change tracker
[ ] API comparison page
[ ] AI API recommender
[ ] MCP server directory
[ ] Auto-generated SDK examples

⭐ Project idea

Turn this repository into a developer tool:

"Describe what your chatbot needs"
             ↓
      API Recommender
             ↓
  ┌──────────┼──────────┐
  ↓          ↓          ↓
 Search     LLM       Database
  ↓          ↓          ↓
  Suggested APIs + Auth + Docs
             ↓
       Copy integration

⚠️ Security

Never publish real credentials.

Bad:

API_KEY = "sk-real-secret"

Good:

import os

API_KEY = os.environ["API_KEY"]

📜 License and provider terms

This repository is an API discovery directory. Each listed API belongs to its respective provider. Follow each provider's license, rate limits, authentication rules, attribution requirements, and terms.

<p align="center">
  <strong>Find an API → Get access → Connect it to your chatbot → Build.</strong>
</p>
