# AI Microvideos — Tech Storytelling (Gemini + Grok)

[![Status](https://img.shields.io/badge/status-experiment-blue)](#)
[![Format](https://img.shields.io/badge/format-9:16%20(Reels%2FShorts)-purple)](#)
[![Focus](https://img.shields.io/badge/focus-IT%20%7C%20DevOps%20%7C%20CI%2FCD-black)](#)

**PT-BR:** Microvídeos criados com IA para comunicar conceitos de TI de forma rápida, visual e memorável — com estética de Reels/Shorts e humor “tech”.  
**EN:** AI-generated microvideos to explain tech concepts in a fast, visual, and memorable way — Reels/Shorts style with a light “tech meme” tone.

> **PT-BR:** Este repositório registra o processo real (testes, prompts, ajustes e aprendizados).  
> **EN:** This repo documents the real process (tests, prompts, tweaks, and learnings).

---

## 🎬 Featured Project — Deploy Cebola (CI/CD)

**PT-BR (ideia):** retratar a jornada clássica em TI: ✅ Build → ✅ Testes → ❌ Deploy  
**EN (idea):** portray the classic tech journey: ✅ Build → ✅ Tests → ❌ Deploy

**PT-BR (objetivo):** testar image-to-video + storytelling em poucos segundos, mantendo consistência do personagem e clareza.  
**EN (goal):** test image-to-video storytelling in a few seconds, keeping character consistency and message clarity.

### Preview
> Add a short GIF here to make the README more visual (`assets/preview.gif`).

![Preview](assets/preview.gif)

### 📥 Full video
- **MP4 (Release):** add your GitHub Release link here  
- **Post (LinkedIn/Instagram):** optional

---

## 🧰 Tools / Stack

**PT-BR**
- **Gemini:** apoio na ideação e refinamento de roteiro/prompts  
- **Grok:** geração do vídeo (image-to-video) e variações do prompt  
- **Editor (opcional):** CapCut/Canva para texto, capa, timing e export final

**EN**
- **Gemini:** ideation + prompt/script refinement  
- **Grok:** video generation (image-to-video) + prompt variations  
- **Editor (optional):** CapCut/Canva for overlays, cover, timing and final export

---

## ✅ What I’m testing / O que estou avaliando

**PT-BR**
- Consistência do personagem (identidade visual)
- Timing do texto na tela (clareza em 6–10s)
- Movimento de câmera (push-in, tremor leve no “fail”)
- Qualidade do cenário (tech vibe sem poluição visual)
- Próximos passos: versão PT-BR completa + variações do conceito

**EN**
- Character consistency (visual identity)
- On-screen text timing (clarity in 6–10s)
- Camera motion (push-in, subtle shake on “fail”)
- Scene quality (tech vibe, clean background)
- Next steps: full PT-BR version + concept variations

---

## 📁 Repository Structure

```bash
ai-microvideos-ti/
├─ README.md
├─ assets/
│  ├─ cover.png
│  └─ preview.gif
└─ projects/
   └─ deploy-cebola/
      ├─ prompt-ptbr.md
      └─ notes.md
```

## ✍️ Prompts & Notes

- Prompt: ```bash projects/deploy-cebola/prompt-ptbr.md ```

- Notes: ```bash projects/deploy-cebola/notes.md ```

---

## 🗺️ Roadmap

- “Funciona na minha máquina” / “Works on my machine”

- “Erro 500” / “HTTP 500”

- “Timeout”

- “Merge conflict”

- Narração PT-BR (voiceover) + auto captions

- Padronização visual (capas + tipografia + ritmo) / Visual system (covers + typography + rhythm)

---

## 📌 Hosting the MP4 (recommended)

**PT-BR:** evite commitar MP4 pesado no repositório. Use **GitHub Releases**.
**EN:** avoid committing large MP4 files into the repo. Use **GitHub Releases**.

**Steps**

**1.** Go to **Releases → Draft a new release**

**2.** Suggested tag: v0.1-deploy-cebola

**3.** Attach: deploy-cebola.mp4

**4.** Publish and paste the download link in the Full video section above

---

## 📜 License

PT-BR: Conteúdo para estudo e portfólio. Se reutilizar, mantenha créditos.
EN: Portfolio/study content. If you reuse it, keep credits.

---

### `projects/deploy-cebola/notes.md`

# Notes — Deploy Cebola

## ✅ O que funcionou bem / What worked
- Narrativa simples e reconhecível (Build/Testes/Deploy)
- Emoção do personagem comunica a ideia mesmo sem narração
- Bom “hook” para Reels/Shorts

## 🔧 Pontos a melhorar / Improvements
- Texto 100% PT-BR (Build/Testes/Deploy e “Permissão negada”)
- Punchline final (“Era só permissão.”)
- Reduzir deformação em close (baixar motion strength)
- Melhorar legibilidade do texto (tamanho/contraste)

## 💡 Próximas variações / Next variations
- “Funciona na minha máquina” / “Works on my machine”
- “Erro 500”
- “Timeout”
- “Merge conflict”
