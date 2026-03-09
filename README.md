# 🎬 AI Video Generator API – Sora 2 | Veo 3 | Kling AI | Runway | Hailuo | Text-to-Video | Image-to-Video

[English](#english) | [中文](#中文)

> **One API key, all top AI video models.** Access **Sora 2**, **Veo 3**, **Kling AI**, **Runway**, **Hailuo AI** and more through a single, affordable API. The cheapest AI video generation API — cheaper than Fal.ai, Replicate, and direct provider APIs.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![API Status](https://img.shields.io/badge/API-Online-green.svg)](https://shanhaiapi.com/zh/)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Node.js 16+](https://img.shields.io/badge/Node.js-16+-339933.svg)](https://nodejs.org/)
[![Sora Docs](https://img.shields.io/badge/Docs-Sora_API-blue.svg)](https://docs.mountsea.ai/api-reference/sora/introduction)
[![Veo Docs](https://img.shields.io/badge/Docs-Veo_API-blue.svg)](https://docs.mountsea.ai/api-reference/veo/introduction)

---

<a name="english"></a>

## 📑 Table of Contents

- [What is AI Video Generator API?](#-what-is-ai-video-generator-api)
- [What's New](#-whats-new)
- [Supported Models](#-supported-models)
- [How It Works](#-how-it-works)
- [Features](#-features)
- [Model Comparison](#-model-comparison--which-ai-video-generator-should-you-choose)
- [Quick Start](#-quick-start)
- [API Endpoints](#-api-endpoints)
- [Use Cases](#-use-cases)
- [Why Mountsea AI?](#-why-mountsea-ai-vs-other-providers)
- [FAQ](#-faq)
- [Pricing](#-pricing)
- [Documentation](#-documentation)
- [Related Projects](#-related-projects)
- [Contributing](#-contributing)
- [中文文档](#中文)

---

## 🤔 What is AI Video Generator API?

This is a **unified AI video generation API** that gives you access to **ALL top AI video generators** through a single API key from [Mountsea AI](https://shanhaiapi.com/zh/).

Stop juggling multiple API keys and billing systems. **One integration, all models.**

Whether you need **text-to-video**, **image-to-video**, or **AI video editing**, this API covers it all — Sora 2 video generation, Veo 3 video generation, Kling AI video, Runway Gen-3, and Hailuo AI.

---

## 🆕 What's New

| Date | Update |
|------|--------|
| 2026-03 | **Veo 3.1** now available — next-gen video generation from Google DeepMind |
| 2026-02 | 🔥 **Veo 3 & Veo 3 Fast** — 50% OFF promotion |
| 2026-01 | **Hailuo AI** model added |
| 2025-12 | **Runway Gen-3 Alpha** integration |
| 2025-11 | Python & Node.js SDKs released |

---

## 🎯 Supported Models

| Model | Provider | Also Known As | Type | Status |
|-------|----------|--------------|------|--------|
| **Sora 2** | OpenAI | Sora2, Sora-2, Sora Pro, OpenAI Sora | Text-to-Video, Image-to-Video | ✅ Available |
| **Veo 3** | Google DeepMind | Veo3, Veo-3, Google Veo 3 | Text-to-Video, Image-to-Video | ✅ Available (50% OFF!) |
| **Veo 3 Fast** | Google DeepMind | Veo3-Fast, Veo-3-Fast | Fast Video Generation | ✅ Available |
| **Veo 3.1** | Google DeepMind | Veo3.1 | Next-gen Video Generation | ✅ Available |
| **Kling AI** | Kuaishou | Kling, Kling-AI, Kling 1.6 | Text-to-Video, Image-to-Video | ✅ Available |
| **Runway Gen-3** | Runway | Runway-ML, RunwayML, Gen-3 Alpha | Creative Video Generation | ✅ Available |
| **Hailuo AI** | MiniMax | Hailuo, MiniMax Video, Hailuo AI Video | AI Video Generation | ✅ Available |

---

## 🔧 How It Works

```
┌─────────────────┐       ┌──────────────────────┐       ┌─────────────────────┐
│   Your App      │       │   Mountsea AI API    │       │   AI Video Models   │
│                 │ ───►  │                      │ ───►  │                     │
│  Single API Key │ POST  │  Unified Gateway     │       │  Sora 2  │ Veo 3   │
│  One SDK        │ ◄───  │  Load Balancing      │ ◄───  │  Kling   │ Runway  │
│                 │ JSON  │  Credit System       │       │  Hailuo  │ ...     │
└─────────────────┘       └──────────────────────┘       └─────────────────────┘

Flow:
  1. Send prompt + model choice ──► Mountsea AI
  2. Receive taskId             ◄── Mountsea AI
  3. Poll task status           ──► Mountsea AI
  4. Get video URL              ◄── Mountsea AI
```

---

## ✨ Features

- 🎥 **Text-to-Video** – Describe it, watch it come to life
- 🖼️ **Image-to-Video** – Animate any static image with AI
- 🎬 **7+ AI Video Models** – Sora 2, Veo 3, Kling, Runway, Hailuo and more
- ⚡ **Fast Video Generation** – Veo 3 Fast for rapid prototyping
- 💰 **Cheapest AI Video API** – Cheaper than Fal.ai, Replicate, and direct APIs
- 🔄 **Unified Video Generation API** – One API key, one integration, all models
- 🐍 **Python Video SDK** – `pip install mountsea-sora` / `pip install mountsea-veo`
- 📦 **Node.js Video SDK** – `npm install mountsea-sora` / `npm install mountsea-veo`
- 🔒 **Production Ready** – Reliable uptime, rate limiting, and error handling
- 📊 **Usage Dashboard** – Track credits, monitor generation history

---

## 🆚 Model Comparison – Which AI Video Generator Should You Choose?

| Feature | Sora 2 | Veo 3 | Veo 3 Fast | Kling AI | Runway Gen-3 | Hailuo AI |
|---------|--------|-------|------------|----------|--------------|-----------|
| **Quality** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| **Speed** | Medium | Medium | ⚡ Fast | Medium | Medium | Fast |
| **Max Duration** | 10s | 8s | 5s | 10s | 10s | 6s |
| **Text-to-Video** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Image-to-Video** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Resolution** | 1080p | 1080p | 720p | 1080p | 1080p | 720p |
| **Best For** | Creative motion | Realism | Quick drafts | Chinese scenes | Artistic | General |
| **Discount** | — | 🔥 50% OFF | 🔥 50% OFF | — | — | — |

### Choosing the Right Model

- **Best overall quality**: Sora 2 or Veo 3
- **Fastest generation**: Veo 3 Fast
- **Best value**: Veo 3 (50% OFF)
- **Artistic / abstract styles**: Runway Gen-3
- **Chinese language prompts**: Kling AI
- **General purpose**: Hailuo AI

---

## 🚀 Quick Start

### Get Your API Key

1. Visit [Mountsea AI Platform](https://shanhaiapi.com/zh/)
2. Sign up and get your API key
3. Choose your model and start generating!

### Install SDK

```bash
# Python - Sora SDK
pip install mountsea-sora

# Python - Veo SDK
pip install mountsea-veo

# Node.js - Sora SDK
npm install mountsea-sora

# Node.js - Veo SDK
npm install mountsea-veo
```

### Python – Sora 2 Video Generation

```python
import requests
import time

API_KEY = "your-api-key"
BASE_URL = "https://api.mountsea.ai"
headers = {"Authorization": f"Bearer {API_KEY}", "Content-Type": "application/json"}

# Generate with Sora 2
response = requests.post(f"{BASE_URL}/sora/generate",
    headers=headers,
    json={
        "prompt": "A drone shot flying over a tropical island with crystal clear water, cinematic 4K",
        "duration": 5,
        "resolution": "1080p"
    })

task = response.json()
task_id = task['taskId']
print(f"Task ID: {task_id}")

# Poll for results
while True:
    status = requests.get(f"{BASE_URL}/sora/task",
        headers=headers, params={"taskId": task_id}).json()
    if status['status'] == 'completed':
        print(f"Video URL: {status['videoUrl']}")
        break
    elif status['status'] == 'failed':
        print(f"Error: {status['error']}")
        break
    print(f"Status: {status['status']}...")
    time.sleep(10)
```

### Python – Veo 3 Video Generation (50% OFF!)

```python
# Generate with Veo 3
response = requests.post(f"{BASE_URL}/veo/generate",
    headers=headers,
    json={
        "prompt": "A futuristic city with flying cars and neon lights, cyberpunk aesthetic",
        "model": "veo-3",
        "duration": 5,
        "resolution": "1080p"
    })

task = response.json()
print(f"Veo Task ID: {task['taskId']}")

# Use Veo 3 Fast for quick generation
response_fast = requests.post(f"{BASE_URL}/veo/generate",
    headers=headers,
    json={
        "prompt": "A puppy running on the beach, sunny day",
        "model": "veo-3-fast",
        "duration": 3
    })
```

### Python – Image-to-Video

```python
# Animate any image with Sora 2
response = requests.post(f"{BASE_URL}/sora/generate",
    headers=headers,
    json={
        "prompt": "The flowers gently sway in the breeze with petals falling",
        "imageUrl": "https://example.com/flowers.jpg",
        "duration": 5
    })

# Or animate with Veo 3
response = requests.post(f"{BASE_URL}/veo/generate",
    headers=headers,
    json={
        "prompt": "The landscape slowly pans with clouds moving across the sky",
        "imageUrl": "https://example.com/landscape.jpg",
        "model": "veo-3",
        "duration": 5
    })
```

### JavaScript / Node.js

```javascript
const axios = require('axios');

const API_KEY = process.env.MOUNTSEA_API_KEY || 'your-api-key';
const BASE_URL = 'https://api.mountsea.ai';
const headers = { 'Authorization': `Bearer ${API_KEY}`, 'Content-Type': 'application/json' };

// Sora 2 Video Generation
async function generateWithSora(prompt, options = {}) {
  const { data } = await axios.post(`${BASE_URL}/sora/generate`, {
    prompt, duration: options.duration || 5, resolution: options.resolution || '1080p', ...options
  }, { headers });
  return data;
}

// Veo 3 Video Generation
async function generateWithVeo(prompt, options = {}) {
  const { data } = await axios.post(`${BASE_URL}/veo/generate`, {
    prompt, model: options.model || 'veo-3', duration: options.duration || 5, ...options
  }, { headers });
  return data;
}

// Poll for result
async function waitForResult(endpoint, taskId) {
  while (true) {
    const { data } = await axios.get(`${BASE_URL}/${endpoint}/task`, {
      headers, params: { taskId }
    });
    if (data.status === 'completed') return data;
    if (data.status === 'failed') throw new Error(data.error);
    console.log(`Status: ${data.status}...`);
    await new Promise(r => setTimeout(r, 10000));
  }
}

// Usage
(async () => {
  // Generate with Sora 2
  const soraTask = await generateWithSora('A timelapse of a flower blooming in sunlight');
  console.log('Sora Task:', soraTask.taskId);
  const soraResult = await waitForResult('sora', soraTask.taskId);
  console.log('Sora Video:', soraResult.videoUrl);

  // Generate with Veo 3 (50% OFF!)
  const veoTask = await generateWithVeo('An astronaut floating in space with Earth in the background');
  console.log('Veo Task:', veoTask.taskId);
  const veoResult = await waitForResult('veo', veoTask.taskId);
  console.log('Veo Video:', veoResult.videoUrl);
})();
```

### Go

```go
package main

import (
    "bytes"
    "encoding/json"
    "fmt"
    "net/http"
)

func main() {
    apiKey := "your-api-key"
    baseURL := "https://api.mountsea.ai"

    // Sora 2 Generation
    payload, _ := json.Marshal(map[string]interface{}{
        "prompt":     "A golden retriever playing in autumn leaves, cinematic 4K",
        "duration":   5,
        "resolution": "1080p",
    })

    req, _ := http.NewRequest("POST", baseURL+"/sora/generate", bytes.NewBuffer(payload))
    req.Header.Set("Authorization", "Bearer "+apiKey)
    req.Header.Set("Content-Type", "application/json")

    client := &http.Client{}
    resp, _ := client.Do(req)
    defer resp.Body.Close()

    var result map[string]interface{}
    json.NewDecoder(resp.Body).Decode(&result)
    fmt.Printf("Task ID: %s\n", result["taskId"])
}
```

### cURL

```bash
# ===== Sora 2 =====
# Text-to-Video
curl -X POST https://api.mountsea.ai/sora/generate \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"prompt": "A timelapse of a flower blooming", "duration": 5, "resolution": "1080p"}'

# Image-to-Video
curl -X POST https://api.mountsea.ai/sora/generate \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"prompt": "The person slowly turns and smiles", "imageUrl": "https://example.com/photo.jpg", "duration": 5}'

# ===== Veo 3 (50% OFF!) =====
# Text-to-Video
curl -X POST https://api.mountsea.ai/veo/generate \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"prompt": "Ocean waves crashing on rocks at sunset, 4K", "model": "veo-3", "duration": 5}'

# Veo 3 Fast
curl -X POST https://api.mountsea.ai/veo/generate \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"prompt": "A cat playing with yarn", "model": "veo-3-fast", "duration": 3}'

# ===== Check Task Status =====
curl -X GET "https://api.mountsea.ai/sora/task?taskId=YOUR_TASK_ID" \
  -H "Authorization: Bearer YOUR_API_KEY"
```

---

## 📖 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/sora/generate` | POST | Generate video with Sora 2 (text-to-video or image-to-video) |
| `/sora/task` | GET | Get Sora task status and video result URL |
| `/veo/generate` | POST | Generate video with Veo 3 / Veo 3 Fast / Veo 3.1 |
| `/veo/task` | GET | Get Veo task status and video result URL |

### Request Parameters

| Parameter | Type | Required | Description |
|-----------|------|----------|-------------|
| `prompt` | string | ✅ | Text description of the video to generate |
| `model` | string | ❌ | Model to use (e.g. `veo-3`, `veo-3-fast`, `veo-3.1`) |
| `duration` | number | ❌ | Video duration in seconds (default: 5) |
| `resolution` | string | ❌ | Output resolution (`1080p`, `720p`) |
| `imageUrl` | string | ❌ | Source image URL for image-to-video generation |

### Response Format

```json
{
  "taskId": "task_abc123",
  "status": "processing",
  "videoUrl": "https://cdn.mountsea.ai/videos/output.mp4",
  "duration": 5,
  "model": "sora-2"
}
```

---

## 🎯 Use Cases

| Use Case | Recommended Model | Why |
|----------|------------------|-----|
| 🎬 Marketing Videos | Sora 2 or Veo 3 | Highest quality, cinematic output |
| 📱 Social Media Content (TikTok, Reels) | Veo 3 Fast | Quick generation, good quality |
| 🎨 Artistic & Abstract Creations | Runway Gen-3 | Best for creative and abstract styles |
| 🏢 Product Demos & Explainers | Sora 2 | Precise motion control |
| ⚡ Quick Prototypes & Storyboards | Veo 3 Fast | Fastest generation speed |
| 🎥 High-Quality Film Production | Veo 3 | Best visual realism |
| 📚 Educational & Training Content | Kling AI or Sora 2 | Clear and descriptive |
| 🛒 E-commerce Product Videos | Sora 2 or Kling AI | Product-focused motion |
| 🎮 Game Trailers & Cutscenes | Veo 3 | Cinematic realism |

---

## 🆚 Why Mountsea AI vs Other Providers?

| Feature | Mountsea AI | Fal.ai | Replicate | Direct API |
|---------|-------------|--------|-----------|------------|
| **Models** | ✅ Sora + Veo + Kling + more | Limited | Limited | One only |
| **Pricing** | ✅ Cheapest (Veo 50% OFF) | ❌ Expensive | ❌ Expensive | ❌ Varies |
| **Unified API** | ✅ One key, all models | ❌ Per-model | ❌ Per-model | ❌ N/A |
| **Python SDK** | ✅ Available | ✅ | ✅ | ❌ Varies |
| **Node.js SDK** | ✅ Available | ✅ | ❌ | ❌ Varies |
| **Setup Time** | ✅ 2 minutes | 5 min | 5 min | 30+ min |
| **Pay-as-you-go** | ✅ Credit system | ❌ Complex | ❌ Per-second | ❌ Varies |
| **Support** | ✅ 24/7 | Limited | Community | Varies |

---

## ❓ FAQ

### Is there a free trial for AI video generation?
Yes! Sign up at [Mountsea AI](https://shanhaiapi.com/zh/) and get free credits to test all models including Sora 2, Veo 3, and Kling AI.

### Which AI video generator is the best in 2026?
It depends on your use case. **Sora 2** and **Veo 3** are currently the best for general-purpose AI video generation. See our [model comparison](#-model-comparison--which-ai-video-generator-should-you-choose) above for a detailed breakdown.

### Sora 2 vs Veo 3 – which should I use?
- **Sora 2**: Better for creative motion, artistic videos, and precise camera control
- **Veo 3**: Better for photorealistic scenes and faster generation (with Veo 3 Fast)
- Both are available through our API. Try both and see which fits your project!

### Is this cheaper than Fal.ai or Replicate?
Yes! Mountsea AI offers the most competitive pricing for AI video generation, especially with Veo 3 at 50% off. [Compare pricing →](https://shanhaiapi.com/zh/)

### Can I use generated AI videos commercially?
Yes! All videos generated through Mountsea AI can be used for commercial purposes under the MIT license.

### What video resolutions are supported?
Most models support up to **1080p** (Full HD). Veo 3 Fast supports up to 720p for faster generation.

### How long can AI-generated videos be?
Currently Sora 2 and Kling support up to **10 seconds**, Veo 3 up to **8 seconds**, and Veo 3 Fast up to **5 seconds**. Longer durations are on the roadmap.

### Do you support image-to-video generation?
Yes! Both Sora 2 and Veo 3 support animating static images into video. Pass an `imageUrl` parameter along with your text prompt.

### What programming languages are supported?
We provide official **Python** and **Node.js** SDKs. The REST API works with any language — see our Go and cURL examples above.

### How fast is AI video generation?
Generation time varies by model: **Veo 3 Fast** takes ~30 seconds, while **Sora 2** and **Veo 3** take 1–3 minutes depending on duration and resolution.

### Is there a rate limit?
Yes, rate limits depend on your plan. Free tier allows 5 concurrent generations; paid plans support higher concurrency.

### Can I generate videos with audio?
Currently, the API generates silent video. Audio can be added using our [Suno API](https://github.com/mountsea-ai/suno-api) or [Producer API](https://github.com/mountsea-ai/producer-api) for AI-generated music.

---

## 💰 Pricing

**Best prices in the market! Cheaper than Fal.ai and Replicate.**

| Package | Credits | Price | Per Credit |
|---------|---------|-------|------------|
| Starter | 10,000 | ¥100 | ¥0.010 |
| Basic | 50,000 | ¥500 | ¥0.010 |
| Pro | 200,000 | ¥2,000 | ¥0.010 |
| Business | 500,000 | ¥4,500 (10% OFF) | ¥0.009 |
| Enterprise | 1,000,000 | ¥8,000 (20% OFF) | ¥0.008 |

🔥 **Veo 3 credits up to 50% OFF!**

👉 [View Full Pricing & Get Started](https://shanhaiapi.com/zh/)

---

## 📚 Documentation

- 📘 [Sora API Documentation](https://docs.mountsea.ai/api-reference/sora/introduction) – Full Sora 2 API reference
- 📘 [Veo API Documentation](https://docs.mountsea.ai/api-reference/veo/introduction) – Full Veo 3 API reference
- 🏠 [Mountsea AI Platform](https://shanhaiapi.com/zh/) – Dashboard, billing, and API key management

---

## 🔗 Related Projects

- [Sora API](https://github.com/mountsea-ai/sora-api) - Dedicated OpenAI Sora 2 API SDK
- [Veo API](https://github.com/mountsea-ai/veo-api) - Dedicated Google Veo 3 API SDK
- [Nano Banana API](https://github.com/mountsea-ai/nano-banana-api) - AI Image Generation API (Gemini)
- [Suno API](https://github.com/mountsea-ai/suno-api) - AI Music Generation API
- [Producer API](https://github.com/mountsea-ai/producer-api) - AI Music Production API
- [Gemini API](https://github.com/mountsea-ai/gemini-api) - Google Gemini Chat API
- [OpenAI Compatible API](https://github.com/mountsea-ai/openai-compatible-api) - OpenAI-compatible Chat API
- [Awesome AI API](https://github.com/mountsea-ai/awesome-ai-api) - Curated AI API List

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions, bug reports, or want to add examples:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

<a name="中文"></a>

## 🇨🇳 中文文档

# 🎬 AI 视频生成器 API – Sora 2 | Veo 3 | Kling AI | Runway | Hailuo | 文本转视频 | 图片转视频

> **一个 API 密钥，所有顶级 AI 视频模型。** 通过一个实惠的 API 访问 **Sora 2**、**Veo 3**、**Kling AI**、**Runway**、**Hailuo AI**。最便宜的 AI 视频生成 API — 比 Fal.ai、Replicate 和官方 API 更便宜。

---

## 📑 目录

- [这是什么？](#-这是什么)
- [最新动态](#-最新动态)
- [支持的模型](#-支持的模型)
- [工作原理](#-工作原理)
- [核心特性](#-核心特性)
- [模型对比](#-模型对比--哪个-ai-视频生成器最好)
- [快速开始](#-快速开始-1)
- [为什么选择 Mountsea AI？](#-为什么选择-mountsea-ai)
- [常见问题](#-常见问题)
- [价格](#-价格)
- [文档](#-文档)
- [相关项目](#-相关项目-1)

---

## 🤔 这是什么？

这是一个**统一的 AI 视频生成 API**，通过 [Mountsea AI](https://shanhaiapi.com/zh/) 的一个 API 密钥即可访问**所有顶级 AI 视频生成器**。

不再需要管理多个 API 密钥和计费系统。**一次集成，所有模型。**

无论你需要**文字生成视频**、**图片生成视频**还是 **AI 视频编辑**，这个 API 都能满足 — 包括 Sora 2、Veo 3、Kling AI、Runway Gen-3 和 Hailuo AI。

---

## 🆕 最新动态

| 日期 | 更新 |
|------|------|
| 2026-03 | **Veo 3.1** 上线 — Google DeepMind 下一代视频生成 |
| 2026-02 | 🔥 **Veo 3 & Veo 3 Fast** 5折优惠 |
| 2026-01 | **Hailuo AI** 模型上线 |
| 2025-12 | **Runway Gen-3 Alpha** 接入 |
| 2025-11 | Python & Node.js SDK 发布 |

---

## 🎯 支持的模型

| 模型 | 提供商 | 别名 | 类型 | 状态 |
|------|--------|------|------|------|
| **Sora 2** | OpenAI | Sora2, Sora-2, Sora Pro | 文本转视频、图片转视频 | ✅ 可用 |
| **Veo 3** | Google DeepMind | Veo3, Veo-3, Google Veo 3 | 文本转视频、图片转视频 | ✅ 可用（🔥5折！） |
| **Veo 3 Fast** | Google DeepMind | Veo3-Fast | 快速视频生成 | ✅ 可用（🔥5折！） |
| **Veo 3.1** | Google DeepMind | Veo3.1 | 下一代视频生成 | ✅ 可用 |
| **Kling AI** | 快手 | Kling, 可灵 | 文本转视频、图片转视频 | ✅ 可用 |
| **Runway Gen-3** | Runway | Runway-ML, Gen-3 Alpha | 创意视频生成 | ✅ 可用 |
| **Hailuo AI** | MiniMax | 海螺AI, MiniMax Video | AI 视频生成 | ✅ 可用 |

---

## 🔧 工作原理

```
┌─────────────────┐       ┌──────────────────────┐       ┌─────────────────────┐
│   你的应用       │       │   Mountsea AI API    │       │   AI 视频模型        │
│                 │ ───►  │                      │ ───►  │                     │
│  一个 API Key   │ POST  │  统一网关             │       │  Sora 2  │ Veo 3   │
│  一套 SDK       │ ◄───  │  负载均衡             │ ◄───  │  Kling   │ Runway  │
│                 │ JSON  │  积分计费             │       │  Hailuo  │ ...     │
└─────────────────┘       └──────────────────────┘       └─────────────────────┘

流程：
  1. 发送提示词 + 模型选择  ──► Mountsea AI
  2. 接收 taskId           ◄── Mountsea AI
  3. 轮询任务状态           ──► Mountsea AI
  4. 获取视频 URL           ◄── Mountsea AI
```

---

## ✨ 核心特性

- 🎥 **文字生成视频** – 输入描述，AI 生成视频
- 🖼️ **图片生成视频** – 让静态图片动起来
- 🎬 **7+ AI 视频模型** – Sora 2, Veo 3, Kling, Runway, Hailuo 等
- ⚡ **快速生成** – Veo 3 Fast 快速出片
- 💰 **最便宜的 AI 视频 API** – 比 Fal.ai、Replicate 和直接 API 更便宜
- 🔄 **统一 API** – 一个密钥，一次集成，所有模型
- 🐍 **Python SDK** – `pip install mountsea-sora` / `pip install mountsea-veo`
- 📦 **Node.js SDK** – `npm install mountsea-sora` / `npm install mountsea-veo`
- 🔒 **生产可用** – 稳定运行、限流保护、完善的错误处理
- 📊 **用量仪表盘** – 追踪积分、查看生成记录

---

## 🆚 模型对比 – 哪个 AI 视频生成器最好？

| 特性 | Sora 2 | Veo 3 | Veo 3 Fast | Kling AI | Runway | Hailuo |
|------|--------|-------|------------|----------|--------|--------|
| **画质** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| **速度** | 中等 | 中等 | ⚡快 | 中等 | 中等 | 快 |
| **最长时长** | 10秒 | 8秒 | 5秒 | 10秒 | 10秒 | 6秒 |
| **文字转视频** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **图片转视频** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **分辨率** | 1080p | 1080p | 720p | 1080p | 1080p | 720p |
| **最佳用途** | 创意运动 | 真实感 | 快速草稿 | 中文场景 | 艺术风格 | 通用 |
| **折扣** | — | 🔥5折 | 🔥5折 | — | — | — |

### 如何选择模型？

- **最高画质**：Sora 2 或 Veo 3
- **最快速度**：Veo 3 Fast
- **最高性价比**：Veo 3（5折优惠）
- **艺术/抽象风格**：Runway Gen-3
- **中文提示词**：Kling AI
- **通用场景**：Hailuo AI

---

## 🚀 快速开始

1. 访问 [Mountsea AI 平台](https://shanhaiapi.com/zh/)
2. 注册账号获取 API 密钥
3. 选择模型开始生成！

### 安装 SDK

```bash
# Python
pip install mountsea-sora  # Sora 2
pip install mountsea-veo   # Veo 3

# Node.js
npm install mountsea-sora  # Sora 2
npm install mountsea-veo   # Veo 3
```

### 示例 – Sora 2 文字生成视频

```python
import requests
import time

API_KEY = "your-api-key"
BASE_URL = "https://api.mountsea.ai"
headers = {"Authorization": f"Bearer {API_KEY}", "Content-Type": "application/json"}

# 使用 Sora 2 生成视频
response = requests.post(f"{BASE_URL}/sora/generate",
    headers=headers,
    json={
        "prompt": "无人机拍摄热带岛屿，水晶般清澈的海水，电影级4K画质",
        "duration": 5,
        "resolution": "1080p"
    })

task = response.json()
task_id = task['taskId']
print(f"任务 ID: {task_id}")

# 轮询结果
while True:
    status = requests.get(f"{BASE_URL}/sora/task",
        headers=headers, params={"taskId": task_id}).json()
    if status['status'] == 'completed':
        print(f"视频 URL: {status['videoUrl']}")
        break
    elif status['status'] == 'failed':
        print(f"错误: {status['error']}")
        break
    print(f"状态: {status['status']}...")
    time.sleep(10)
```

### 示例 – Veo 3（5折优惠！）

```python
# 使用 Veo 3 生成视频
response = requests.post(f"{BASE_URL}/veo/generate",
    headers=headers,
    json={
        "prompt": "未来城市中飞行汽车穿梭在霓虹灯间，赛博朋克风格",
        "model": "veo-3",
        "duration": 5,
        "resolution": "1080p"
    })

print(response.json())
```

### 示例 – 图片生成视频

```python
# 用 Sora 2 让图片动起来
response = requests.post(f"{BASE_URL}/sora/generate",
    headers=headers,
    json={
        "prompt": "花朵在微风中轻轻摇摆，花瓣缓缓飘落",
        "imageUrl": "https://example.com/flowers.jpg",
        "duration": 5
    })

# 或用 Veo 3
response = requests.post(f"{BASE_URL}/veo/generate",
    headers=headers,
    json={
        "prompt": "风景缓缓移动，云朵飘过天空",
        "imageUrl": "https://example.com/landscape.jpg",
        "model": "veo-3",
        "duration": 5
    })
```

---

## 🆚 为什么选择 Mountsea AI？

| 特性 | Mountsea AI | Fal.ai | Replicate | 官方 API |
|------|-------------|--------|-----------|----------|
| **模型数量** | ✅ Sora + Veo + Kling + 更多 | 有限 | 有限 | 仅一个 |
| **价格** | ✅ 最便宜（Veo 5折） | ❌ 贵 | ❌ 贵 | ❌ 不一定 |
| **统一 API** | ✅ 一个密钥，所有模型 | ❌ 按模型 | ❌ 按模型 | ❌ N/A |
| **Python SDK** | ✅ 有 | ✅ | ✅ | ❌ 不一定 |
| **Node.js SDK** | ✅ 有 | ✅ | ❌ | ❌ 不一定 |
| **接入时间** | ✅ 2分钟 | 5分钟 | 5分钟 | 30分钟+ |
| **技术支持** | ✅ 7×24 | 有限 | 社区 | 不一定 |

---

## ❓ 常见问题

### 有免费试用吗？
有！注册 [Mountsea AI](https://shanhaiapi.com/zh/) 即送免费积分，可测试所有模型，包括 Sora 2、Veo 3 和 Kling AI。

### 2026年最好的 AI 视频生成器是哪个？
取决于用途。**Sora 2** 和 **Veo 3** 目前是最佳通用选择。详见上方[模型对比表](#-模型对比--哪个-ai-视频生成器最好)。

### Sora 2 和 Veo 3 选哪个？
- **Sora 2**：创意运动和艺术视频更强，镜头控制更精确
- **Veo 3**：真实场景和快速生成更强（Veo 3 Fast）
- 我们的 API 两个都支持，可以都试试！

### 比 Fal.ai 和 Replicate 便宜吗？
是的！尤其 Veo 3 享5折优惠。[查看价格对比 →](https://shanhaiapi.com/zh/)

### 能用于商业项目吗？
可以！通过 Mountsea AI 生成的所有视频均可用于商业用途。

### 支持哪些分辨率？
大部分模型支持 **1080p**（全高清），Veo 3 Fast 支持 720p。

### AI 生成的视频最长多久？
Sora 2 和 Kling 最长 **10秒**，Veo 3 最长 **8秒**，Veo 3 Fast 最长 **5秒**。更长时长正在规划中。

### 支持图片转视频吗？
支持！Sora 2 和 Veo 3 都支持将静态图片转为视频。传入 `imageUrl` 参数加上提示词即可。

### 支持哪些编程语言？
官方提供 **Python** 和 **Node.js** SDK。REST API 支持任何编程语言 — 参见上方 Go 和 cURL 示例。

### 视频生成需要多长时间？
取决于模型：**Veo 3 Fast** 约30秒，**Sora 2** 和 **Veo 3** 约1-3分钟（取决于时长和分辨率）。

### 有速率限制吗？
有，取决于套餐。免费版支持5个并发生成；付费版支持更高并发。

### 可以生成带音频的视频吗？
目前 API 生成无声视频。可以使用 [Suno API](https://github.com/mountsea-ai/suno-api) 或 [Producer API](https://github.com/mountsea-ai/producer-api) 生成 AI 音乐配音。

---

## 💰 价格

**市场最低价！比 Fal.ai 和 Replicate 更便宜。**

| 套餐 | 积分 | 价格 | 单价 |
|------|------|------|------|
| 入门版 | 10,000 | ¥100 | ¥0.010 |
| 基础版 | 50,000 | ¥500 | ¥0.010 |
| 专业版 | 200,000 | ¥2,000 | ¥0.010 |
| 商务版 | 500,000 | ¥4,500 (9折) | ¥0.009 |
| 企业版 | 1,000,000 | ¥8,000 (8折) | ¥0.008 |

🔥 **Veo 3 积分最高5折优惠！**

👉 [查看完整价格 & 立即开始](https://shanhaiapi.com/zh/)

---

## 📚 文档

- 📘 [Sora API 文档](https://docs.mountsea.ai/api-reference/sora/introduction) – 完整 Sora 2 API 参考
- 📘 [Veo API 文档](https://docs.mountsea.ai/api-reference/veo/introduction) – 完整 Veo 3 API 参考
- 🏠 [Mountsea AI 官网](https://shanhaiapi.com/zh/) – 控制台、计费、API Key 管理

---

## 🔗 相关项目

- [Sora API](https://github.com/mountsea-ai/sora-api) - OpenAI Sora 2 视频生成 API SDK
- [Veo API](https://github.com/mountsea-ai/veo-api) - Google Veo 3 视频生成 API SDK
- [Nano Banana API](https://github.com/mountsea-ai/nano-banana-api) - AI 图片生成 API
- [Suno API](https://github.com/mountsea-ai/suno-api) - AI 音乐生成 API
- [Producer API](https://github.com/mountsea-ai/producer-api) - AI 音乐制作 API
- [Gemini API](https://github.com/mountsea-ai/gemini-api) - Google Gemini 对话 API
- [OpenAI Compatible API](https://github.com/mountsea-ai/openai-compatible-api) - OpenAI 兼容对话 API
- [Awesome AI API](https://github.com/mountsea-ai/awesome-ai-api) - 精选 AI API 列表

---

## ⭐ Star History

如果这个项目对你有帮助，请给我们一个 Star ⭐

---

## 📄 License

[MIT License](LICENSE)

---

**Powered by [Mountsea AI](https://shanhaiapi.com/zh/) – Your All-in-One AI API Platform for Video, Music, Image & Chat Generation**
