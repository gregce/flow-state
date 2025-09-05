---
theme: the-unnamed
layout: cover
background: '#161C2C'
title: 'Flow State: Non-Coding AI Workflows'
info: |
  Interactive demo session exploring powerful AI workflows without traditional programming.
  Learn how to leverage AI for creative production, data processing, and content creation.
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-up
mdc: true
themeConfig:
  color: "#F3EFF5"
  background: "#161C2C"
  
  code-background: "#0F131E"
  code-border: "#242d34"

  accents-teal: "#44FFD2"
  accents-yellow: "#FFE45E"
  accents-red: "#FE4A49"
  accents-lightblue: "#15C2CB"
  accents-blue: "#5EADF2"
  accents-vulcan: "#0E131F"
---

<style>
/* Make title font smaller on cover slide */
.cover h1 {
  font-size: 2.5em !important;
}

.cover h2 {
  font-size: 1.5em !important;
}

/* Custom styles for code blocks */
.shiki {
  background: #0F131E !important;
  border: 1px solid #242d34 !important;
}

/* Accent colors */
.text-accent-teal { color: #44FFD2; }
.text-accent-yellow { color: #FFE45E; }
.text-accent-red { color: #FE4A49; }
.text-accent-blue { color: #5EADF2; }
.bg-accent-blue { background-color: #5EADF2; }
.bg-vulcan { background-color: #0E131F; }
.bg-code-background { background-color: #0F131E; }
.border-code-border { border-color: #242d34; }

/* Demo indicator styles */
.demo-indicator {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.5rem 1rem;
  background: rgba(68, 255, 210, 0.1);
  border: 1px solid #44FFD2;
  border-radius: 0.5rem;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  animation: pulse 2s infinite;
}

@keyframes pulse {
  0%, 100% { opacity: 0.8; }
  50% { opacity: 1; }
}
</style>

# Flow State: Non-Coding AI Workflows

<div class="text-2xl mt-8 text-accent-teal">Interactive Demo Session</div>

<div class="absolute bottom-5 right-5 text-sm opacity-70">
  Lighthaven • Berkeley • 2025
</div>

---
layout: center
---

# Get These Slides

<div class="flex flex-col items-center gap-8 mt-8">
  <img src="/qr-code.png" class="w-48 h-48" alt="QR Code for slides" />
  
  <div class="text-center">
    <p class="text-2xl text-accent-teal mb-4">Scan to access slides</p>
    <a href="https://github.com/gregce/flow-state" 
       target="_blank"
       class="text-xl text-accent-yellow hover:text-accent-blue transition-colors">
      github.com/gregce/flow-state
    </a>
  </div>
</div>

---
layout: about-me
helloMsg: Hello!
name: I'm Greg
imageSrc: /greg.png
position: left
job: Co-founder of SpecStory
line2: Previously CPO at Pluralsight and Data at Dropbox, GitHub, Google
social1: "X: @gregce10"
social2: "greg@specstory.com"
---

---
layout: default
---

# My Non-Coding AI Landscape

<div class="flex flex-col items-center mt-8">
  <h2 v-click class="text-lg font-bold text-accent-yellow mb-4">
    Every novel use of AI shrinks the fear of "I don't know how".
  </h2>
  
  <div v-click class="grid grid-cols-3 gap-6 w-full max-w-5xl">
    <div class="bg-code-background p-6 rounded-lg border border-code-border">
      <div class="text-4xl mb-4">🎬</div>
      <h3 class="text-xl font-bold text-accent-blue mb-2">Creative Production</h3>
      <p class="text-gray-300">Video generation & editing with AI</p>
    </div>
    
  <div class="bg-code-background p-6 rounded-lg border border-code-border">
      <div class="text-4xl mb-4">📊</div>
      <h3 class="text-xl font-bold text-accent-teal mb-2">Data Processing</h3>
      <p class="text-gray-300">Classification at scale</p>
    </div>
    
  <div class="bg-code-background p-6 rounded-lg border border-code-border">
      <div class="text-4xl mb-4">✍️</div>
      <h3 class="text-xl font-bold text-accent-yellow mb-2">Content Creation</h3>
      <p class="text-gray-300">AI-assisted writing workflows</p>
    </div>
  </div>
  
</div>

---
layout: default
---

# Workflow 1A: Creative AI Video Production

<div class="demo-indicator mb-6">
  <span>🔴</span> LIVE DEMO: Veo 3 + CapCut Pipeline
</div>

<div class="grid grid-cols-2 gap-8">
  <div v-click>
    <h3 class="text-2xl mb-4 text-accent-blue">AI Generation Process</h3>
    <ul class="space-y-3">
      <li class="flex items-start gap-2">
        <span class="text-accent-teal">→</span>
        <span>Environment prompting</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-accent-teal">→</span>
        <span>Character models</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-accent-teal">→</span>
        <span>Lighting & Style guides</span>
      </li>
    </ul>
  </div>
  
  <div v-click>
    <h3 class="text-2xl mb-4 text-accent-yellow">Production Pipeline</h3>
    <ul class="space-y-3">
      <li class="flex items-start gap-2">
        <span class="text-accent-yellow">→</span>
        <span>Storyboarding with AI components</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-accent-yellow">→</span>
        <span>CapCut editing + Suno music</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-accent-yellow">→</span>
        <span>Prompt engineering for consistency</span>
      </li>
    </ul>
  </div>
</div>

<div v-click class="mt-8 bg-code-background p-6 rounded-lg border border-code-border">
  <p class="text-xl text-center font-bold text-accent-teal">
    Biggest Challenge: Storytelling & Visual Coherence
  </p>
</div>

---
layout: default
---

# Workflow 1B: Programmatic Video Creation

<div class="demo-indicator mb-6">
  <span>🔴</span> LIVE DEMO: Maven Lightning Lesson Redux
</div>

<div class="grid grid-cols-2 gap-8">
  <div>
    <div v-click>
      <h3 class="text-2xl mb-4 text-accent-blue">Remotion Approach</h3>
      <div class="bg-code-background p-4 rounded-lg border border-code-border">

```jsx
// React components for video
const frame = useCurrentFrame();
const opacity = interpolate(
  frame, [0, 30], [0, 1]
);

// Frame 0: opacity = 0 (invisible)
// Frame 15: opacity = 0.5 (half visible)  
// Frame 30: opacity = 1 (fully visible)

return React.createElement('div', 
  { style: { opacity } },
  'Your content here'
);
```

  </div>
    </div>
  </div>
  
  <div>
    <div v-click>
      <h3 class="text-2xl mb-4 text-accent-yellow">Decision Matrix</h3>
      <div class="space-y-3">
        <div class="bg-code-background p-3 rounded">
          <span class="font-bold text-accent-teal">Go Manual:</span> One-off creative videos
        </div>
        <div class="bg-code-background p-3 rounded">
          <span class="font-bold text-accent-teal">Go Programmatic:</span> Repeatable, data-driven
        </div>
      </div>
    </div>
  </div>  
</div>

---
layout: default
---

# Workflow 2: AI CLIs for Data Classification

<div class="demo-indicator mb-6">
  <span>🔴</span> LIVE DEMO: Classification System
</div>

<div class="flex flex-col gap-6">
  <div v-click class="bg-code-background p-6 rounded-lg border border-code-border">
    <h3 class="text-xl font-bold text-accent-blue mb-3">Parallel Processing Architecture</h3>
    <ul class="space-y-2">
      <li>Claude Code/Codex for concurrent classification</li>
      <li>Batch processing with progress monitoring</li>
      <li>Results aggregation and visualization</li>
    </ul>
  </div>
  
  <div v-click class="grid grid-cols-2 gap-6">
    <div class="bg-vulcan p-4 rounded-lg">
      <h4 class="font-bold text-accent-teal mb-2">💰 Cost Optimization</h4>
      <p class="text-sm">Leveraging subscription tokens vs. API costs</p>
    </div>
    
  <div class="bg-vulcan p-4 rounded-lg">
      <h4 class="font-bold text-accent-yellow mb-2">📈 Performance</h4>
      <p class="text-sm">Real-world applications and benchmarks</p>
    </div>
  </div>
  
  <div v-click class="mt-6 text-center">
    <p class="text-2xl font-bold text-accent-teal">
      Scaling classification without code
    </p>
  </div>
</div>

---
layout: default
---

# Workflow 3: AI-Assisted Writing & Meta-Analysis

<div class="demo-indicator mb-4">
  <span>🔴</span> LIVE DEMO: Substack Workflow
</div>

<div class="grid grid-cols-2 gap-4 mt-4 text-sm">
  <div v-click>
    <h3 class="text-lg mb-3 text-accent-blue">Multi-Stage Writing Pipeline</h3>
    <div class="space-y-2">
      <div class="bg-code-background p-2 rounded-lg border border-code-border">
        <p class="font-bold text-sm">1. Divergent Ideation</p>
        <ul class="text-xs text-gray-300 ml-3">
          <li>ChatGPT: 10+ title variations</li>
          <li>Claude: Contrarian perspectives</li>
        </ul>
      </div>
      <div class="bg-code-background p-2 rounded-lg border border-code-border">
        <p class="font-bold text-sm">2. Structural Development</p>
        <ul class="text-xs text-gray-300 ml-3">
          <li>Outline generation & critique loops</li>
          <li>Section-by-section expansion</li>
        </ul>
      </div>
    </div>
  </div>
  
  <div v-click>
    <h3 class="text-lg mb-3 text-accent-yellow">Meta-Analysis Tools</h3>
    <div class="space-y-2">
      <div class="bg-code-background p-2 rounded-lg border border-code-border">
        <p class="font-bold text-sm">📚 Corpus Analysis</p>
        <ul class="text-xs text-gray-300 ml-3">
          <li>70+ posts from meditationsontech.com</li>
          <li>Extracted: themes, vocabulary, cadence</li>
        </ul>
      </div>
      <div class="bg-code-background p-2 rounded-lg border border-code-border">
        <p class="font-bold text-sm">🎯 Custom Prompts</p>
        <ul class="text-xs text-gray-300 ml-3">
          <li>Style matching against corpus</li>
          <li>Tone consistency checks</li>
        </ul>
      </div>
    </div>
  </div>
</div>
---
layout: default
---

# Patterns & Insights

<div class="mt-4">
  
  <div v-click class="grid grid-cols-3 gap-4 mb-6">
    <div class="bg-code-background p-4 rounded-lg border border-code-border text-center">
      <div class="text-2xl mb-2">🎯</div>
      <h3 class="text-lg font-bold text-accent-blue mb-1">Prompt Engineering</h3>
      <p class="text-xs">Core skill across all AI tools</p>
    </div>
    
  <div class="bg-code-background p-4 rounded-lg border border-code-border text-center">
      <div class="text-2xl mb-2">🔄</div>
      <h3 class="text-lg font-bold text-accent-teal mb-1">Iterative Refinement</h3>
      <p class="text-xs">Continuous improvement</p>
    </div>
    
  <div class="bg-code-background p-4 rounded-lg border border-code-border text-center">
      <div class="text-2xl mb-2">🤝</div>
      <h3 class="text-lg font-bold text-accent-yellow mb-1">Human-AI Collaboration</h3>
      <p class="text-xs">Hybrid workflows win</p>
    </div>
  </div>
  
  <div v-click class="text-center mt-8">
    <p class="text-xl font-bold text-accent-teal mb-2">✨ The Bottom Line</p>
    <p class="text-lg">AI handles the <span class="text-accent-yellow">heavy lifting</span> • We provide the <span class="text-accent-blue">soul</span></p>
  </div>
</div>

---
layout: center
---

# Go deeper

<div class="flex flex-col items-center justify-center h-full">
  <div v-click class="grid grid-cols-3 gap-6 max-w-6xl w-full mt-8">
    <a href="https://www.gregceccarelli.com/writing/creating-film-with-ai" target="_blank" class="bg-code-background p-8 rounded-lg border border-code-border hover:border-accent-blue transition-all group flex flex-col items-center justify-between text-center h-64">
      <div class="text-5xl mb-4 group-hover:scale-110 transition-transform">🎬</div>
      <div class="flex-grow flex flex-col justify-center">
        <h3 class="text-lg font-bold text-accent-blue mb-2">Creating Film with AI</h3>
        <p class="text-xs text-gray-400">AI-powered filmmaking</p>
      </div>
      <div class="h-4"></div>
    </a>
    <a href="https://www.gregceccarelli.com/writing/build-product-video-with-ai" target="_blank" class="bg-code-background p-8 rounded-lg border border-code-border hover:border-accent-yellow transition-all group flex flex-col items-center justify-between text-center h-64">
      <div class="text-5xl mb-4 group-hover:scale-110 transition-transform">🚀</div>
      <div class="flex-grow flex flex-col justify-center">
        <h3 class="text-lg font-bold text-accent-yellow mb-2">Build Product Videos</h3>
        <p class="text-xs text-gray-400">Step-by-step production guide</p>
      </div>
      <div class="h-4"></div>
    </a>
    <a href="https://www.meditationsontech.com/p/claude-and-i" target="_blank" class="bg-code-background p-8 rounded-lg border border-code-border hover:border-accent-red transition-all group flex flex-col items-center justify-between text-center h-64">
      <div class="text-5xl mb-4 group-hover:scale-110 transition-transform">🤖</div>
      <div class="flex-grow flex flex-col justify-center">
        <h3 class="text-lg font-bold text-accent-red mb-2">Claude and I</h3>
        <p class="text-xs text-gray-400">Reflections on a year with AI</p>
      </div>
      <div class="h-4"></div>
    </a>
  </div>
  
  <div v-click class="mt-12 text-center">
    <p class="text-2xl font-bold text-accent-teal">Shoot me an email: greg@specstory.com</p>
  </div>
</div>