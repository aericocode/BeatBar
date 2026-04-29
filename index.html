<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Beat Bar — Video Beat Visualizer</title>
<style>
/* ─── toolkit.css (inlined) ────────────────────────────── */
:root,[data-tk-theme="dark"]{--tk-bg:#1e1f22;--tk-bg-alt:#2b2d31;--tk-surface:#313338;--tk-surface-hover:#3a3c42;--tk-surface-active:#43454b;--tk-text:#dbdee1;--tk-text-muted:#949ba4;--tk-text-faint:#6d6f78;--tk-border:#3f4147;--tk-border-strong:#4e5058;--tk-accent:#5385f1;--tk-accent-hover:#4077EF;--tk-accent-subtle:rgba(122,162,247,0.12);--tk-green:#9ece6a;--tk-green-hover:#8ab85a;--tk-green-subtle:rgba(158,206,106,0.12);--tk-teal:#73daca;--tk-yellow:#F0CF64;--tk-red:#F44666;--tk-purple:#bb9af7;--tk-orange:#ff9e64;--tk-success:var(--tk-green);--tk-warning:var(--tk-yellow);--tk-error:var(--tk-red);--tk-info:var(--tk-teal);--tk-radius:5px;--tk-radius-lg:9px;--tk-radius-sm:3px;--tk-sp-xs:4px;--tk-sp-sm:8px;--tk-sp-md:14px;--tk-sp-lg:20px;--tk-sp-xl:28px;--tk-font:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,sans-serif;--tk-font-mono:ui-monospace,"JetBrains Mono",Menlo,Consolas,monospace;--tk-shadow:0 2px 8px rgba(0,0,0,0.35);--tk-shadow-lg:0 8px 24px rgba(0,0,0,0.45)}
.tk-root,.tk-root *{box-sizing:border-box}
.tk-h1{font-size:20px;font-weight:600;margin:0;color:var(--tk-text)}
.tk-label-section{font-size:11px;font-weight:600;letter-spacing:0.08em;text-transform:uppercase;color:var(--tk-text-muted)}
.tk-muted{color:var(--tk-text-muted)}.tk-faint{color:var(--tk-text-faint)}
.tk-mono{font-family:var(--tk-font-mono)}
.tk-text-sm{font-size:12px}.tk-text-xs{font-size:11px}
.tk-btn{display:inline-flex;align-items:center;justify-content:center;gap:6px;padding:6px 12px;font-family:inherit;font-size:13px;font-weight:500;color:var(--tk-text);background:var(--tk-surface);border:1px solid var(--tk-border);border-radius:var(--tk-radius);cursor:pointer;transition:background .12s,border-color .12s,color .12s;white-space:nowrap}
.tk-btn:hover{background:var(--tk-surface-hover)}
.tk-btn:disabled{opacity:.5;cursor:not-allowed}
.tk-btn--primary{background:var(--tk-accent);border-color:var(--tk-accent);color:#fff}
.tk-btn--primary:hover{background:var(--tk-accent-hover);border-color:var(--tk-accent-hover)}
.tk-btn--ghost{background:transparent;border-color:transparent;color:var(--tk-text-muted)}
.tk-btn--ghost:hover{background:var(--tk-surface);color:var(--tk-text)}
.tk-btn--sm{padding:4px 8px;font-size:12px}
.tk-btn--icon{padding:6px 8px;min-width:32px}
.tk-input,.tk-select{width:100%;padding:6px 10px;font-family:inherit;font-size:13px;color:var(--tk-text);background:var(--tk-bg-alt);border:1px solid var(--tk-border);border-radius:var(--tk-radius);outline:none}
.tk-input:focus,.tk-select:focus{border-color:var(--tk-accent)}
.tk-field{display:flex;flex-direction:column;gap:4px;margin-bottom:var(--tk-sp-sm)}
.tk-label{font-size:12px;font-weight:500;color:var(--tk-text-muted)}
.tk-hint{font-size:11px;color:var(--tk-text-faint)}
.tk-flex{display:flex;align-items:center;gap:var(--tk-sp-sm)}
.tk-flex-between{justify-content:space-between}
.tk-flex-col{display:flex;flex-direction:column;gap:var(--tk-sp-sm)}
.tk-flex-1{flex:1}
.tk-card{background:var(--tk-bg-alt);border:1px solid var(--tk-border);border-radius:var(--tk-radius-lg);padding:var(--tk-sp-md)}
.tk-progress{width:100%;height:6px;background:var(--tk-bg-alt);border-radius:999px;overflow:hidden}
.tk-progress__bar{height:100%;background:var(--tk-accent);transition:width .15s}
.tk-toggle{position:relative;display:inline-block;width:32px;height:18px;flex-shrink:0}
.tk-toggle input{opacity:0;width:0;height:0}
.tk-toggle .slider{position:absolute;inset:0;background:var(--tk-surface);border:1px solid var(--tk-border);border-radius:999px;cursor:pointer;transition:.15s}
.tk-toggle .slider::before{content:"";position:absolute;left:2px;top:1px;width:12px;height:12px;background:var(--tk-text-muted);border-radius:50%;transition:.15s}
.tk-toggle input:checked+.slider{background:var(--tk-accent);border-color:var(--tk-accent)}
.tk-toggle input:checked+.slider::before{transform:translateX(14px);background:#fff}

/* ─── App ─────────────────────────────────────────────── */
body{margin:0;background:var(--tk-bg);color:var(--tk-text);font-family:var(--tk-font);font-size:13px}
.app{max-width:1600px;margin:0 auto;padding:var(--tk-sp-lg);display:flex;flex-direction:column;gap:var(--tk-sp-md)}
.drop-zone{border:2px dashed var(--tk-border-strong);border-radius:var(--tk-radius-lg);padding:var(--tk-sp-xl);text-align:center;cursor:pointer;transition:border-color .12s,background .12s}
.drop-zone:hover,.drop-zone.drag{border-color:var(--tk-accent);background:var(--tk-accent-subtle)}
.drop-zone input{display:none}

.video-wrap{position:relative;background:#000;border-radius:var(--tk-radius-lg);overflow:hidden;width:100%;max-height:75vh;display:flex;align-items:center;justify-content:center}
.video-wrap video{width:100%;height:100%;max-height:75vh;display:block;object-fit:contain}
/* Beat overlay covers full width of video, pinned to bottom, above video but below controls */
.beat-overlay{position:absolute;left:0;right:0;bottom:0;width:100%;height:110px;pointer-events:none;transition:opacity .15s;z-index:2}
.beat-overlay.off{display:none}
/* External beat canvas shown below video when overlay is off */
.beat-canvas{width:100%;height:130px;background:var(--tk-bg-alt);border:1px solid var(--tk-border);border-radius:var(--tk-radius);display:block}
.beat-canvas.off{display:none}

.video-wrap:fullscreen{width:100vw;height:100vh;max-height:none;border-radius:0;background:#000}
.video-wrap:fullscreen video{max-height:100vh;height:100vh;width:100vw}
.video-wrap:fullscreen .beat-overlay{height:130px}
.video-wrap:-webkit-full-screen{width:100vw;height:100vh;max-height:none}
.video-wrap:-webkit-full-screen video{max-height:100vh;height:100vh;width:100vw}

/* Fullscreen controls sit ABOVE the overlay (higher bottom offset, higher z-index) */
.fs-controls{position:absolute;bottom:140px;left:0;right:0;padding:var(--tk-sp-md);display:none;opacity:0;transition:opacity .2s;z-index:20;background:linear-gradient(to top,rgba(0,0,0,.75),transparent);align-items:center;gap:var(--tk-sp-md)}
.video-wrap:fullscreen .fs-controls{display:flex}
.video-wrap:fullscreen.show-controls .fs-controls{opacity:1}

.controls{display:flex;align-items:center;gap:var(--tk-sp-md);flex-wrap:wrap}
.controls .group{display:flex;align-items:center;gap:8px}
.time{font-family:var(--tk-font-mono);font-size:12px;color:var(--tk-text-muted);min-width:110px}
.status{font-size:12px;color:var(--tk-text-muted)}
.status.err{color:var(--tk-red)}
.stats{display:flex;gap:var(--tk-sp-md);font-size:12px;color:var(--tk-text-muted);flex-wrap:wrap}
.stats b{color:var(--tk-text);font-weight:600}

.seekbar{flex:1;min-width:150px;height:6px;background:var(--tk-bg-alt);border-radius:999px;cursor:pointer;position:relative;overflow:hidden}
.seekbar__fill{height:100%;background:var(--tk-accent);width:0%;pointer-events:none}

.vol-wrap{display:flex;align-items:center;gap:6px}
.vol-slider{-webkit-appearance:none;appearance:none;width:80px;height:4px;background:var(--tk-bg-alt);border-radius:999px;outline:none;cursor:pointer}
.vol-slider::-webkit-slider-thumb{-webkit-appearance:none;appearance:none;width:12px;height:12px;background:var(--tk-accent);border-radius:50%;cursor:pointer;border:none}
.vol-slider::-moz-range-thumb{width:12px;height:12px;background:var(--tk-accent);border-radius:50%;cursor:pointer;border:none}
.video-wrap:fullscreen .vol-slider{width:100px;background:rgba(255,255,255,0.2)}
.video-wrap:fullscreen .time{color:#ddd}
.video-wrap:fullscreen .seekbar{background:rgba(255,255,255,0.2)}

.hidden{display:none !important}
h1.title{font-family:var(--tk-font-mono);font-size:22px;font-weight:600;margin:0;letter-spacing:-0.02em}
h1.title span{color:var(--tk-accent)}
.sub{color:var(--tk-text-muted);font-size:12px;margin-top:-6px}
details.advanced{background:var(--tk-bg-alt);border:1px solid var(--tk-border);border-radius:var(--tk-radius);padding:var(--tk-sp-sm) var(--tk-sp-md)}
details.advanced summary{cursor:pointer;font-size:12px;color:var(--tk-text-muted);user-select:none}
details.advanced summary:hover{color:var(--tk-text)}
.advanced-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:var(--tk-sp-sm);margin-top:var(--tk-sp-sm)}
.num-input{width:100%;padding:4px 8px;font-family:var(--tk-font-mono);font-size:12px;color:var(--tk-text);background:var(--tk-bg);border:1px solid var(--tk-border);border-radius:var(--tk-radius);outline:none}
.num-input:focus{border-color:var(--tk-accent)}
.preset-row{display:flex;align-items:center;gap:6px;flex-wrap:wrap;margin-bottom:var(--tk-sp-sm)}
.preset.active{background:var(--tk-accent);border-color:var(--tk-accent);color:#fff}
.info-i{display:inline-flex;align-items:center;justify-content:center;width:14px;height:14px;border-radius:50%;background:var(--tk-surface);color:var(--tk-text-muted);font-size:10px;font-weight:600;margin-left:4px;cursor:help;user-select:none;vertical-align:middle;border:1px solid var(--tk-border)}
.info-i:hover{background:var(--tk-accent-subtle);color:var(--tk-accent);border-color:var(--tk-accent)}
</style>
</head>
<body class="tk-root">
<div class="app">
  <div>
    <h1 class="title">beat<span>·</span>bar</h1>
    <div class="sub">Drop a video, see its beats.</div>
  </div>

  <label class="drop-zone" id="dropZone">
    <input type="file" id="fileInput" accept="video/*,audio/*">
    <div class="tk-label-section" style="margin-bottom:6px">Drop video here</div>
    <div class="tk-muted tk-text-sm">or click to browse · .mp4 .webm .mov .mkv · audio files also work</div>
  </label>

  <details class="advanced" open>
    <summary>Detection settings <span class="tk-faint tk-text-xs" style="margin-left:8px">adjust &amp; click Re-analyze</span></summary>

    <div class="preset-row">
      <span class="tk-label-section" style="margin-right:6px">Preset:</span>
      <button class="tk-btn tk-btn--sm preset" data-preset="kick">Kick (steady pulse)</button>
      <button class="tk-btn tk-btn--sm preset" data-preset="snare">Snare / backbeat</button>
      <button class="tk-btn tk-btn--sm preset" data-preset="broad">Broad (all onsets)</button>
      <button class="tk-btn tk-btn--sm preset" data-preset="custom">Custom</button>
    </div>

    <div class="advanced-grid">
      <div class="tk-field">
        <label class="tk-label">Band low (Hz) <span class="info-i" title="Lower edge of the frequency band to analyze. Kick drums live at ~40–100 Hz. Raise this to ignore sub-bass rumble.">ⓘ</span></label>
        <input type="number" id="optBandLow" class="num-input" value="40" min="20" max="500" step="5">
      </div>
      <div class="tk-field">
        <label class="tk-label">Band high (Hz) <span class="info-i" title="Upper edge of the band. 100–150 Hz = kick only. 200–400 Hz = kick + lower toms. 500+ starts including snare body. Narrower band = cleaner kick detection.">ⓘ</span></label>
        <input type="number" id="optBandHigh" class="num-input" value="120" min="50" max="8000" step="10">
      </div>
      <div class="tk-field">
        <label class="tk-label">Min BPM <span class="info-i" title="Slowest beat you expect. Sets a minimum gap between detected beats — a min of 90 BPM means beats must be ≥ 666 ms apart, which prevents fast hats/snare hits from sneaking in between kicks.">ⓘ</span></label>
        <input type="number" id="optMinBpm" class="num-input" value="80" min="30" max="240" step="5">
      </div>
      <div class="tk-field">
        <label class="tk-label">Max BPM <span class="info-i" title="Fastest beat you expect. Rarely needs changing from 200 unless you're analyzing double-time/drum&amp;bass kick patterns.">ⓘ</span></label>
        <input type="number" id="optMaxBpm" class="num-input" value="200" min="80" max="400" step="5">
      </div>
      <div class="tk-field">
        <label class="tk-label">Sensitivity <span class="info-i" title="How much louder than the surrounding average a peak must be to count as a beat. 1.0 = everything is a beat. 1.5 = moderate. 2.0+ = only strong kicks. Lower this if you're missing beats; raise it if you're getting false positives.">ⓘ</span></label>
        <input type="number" id="optSensitivity" class="num-input" value="1.5" min="1.01" max="4" step="0.05">
      </div>
      <div class="tk-field">
        <label class="tk-label">Avg window (sec) <span class="info-i" title="The moving-average window used to compute the 'typical' energy level. SHORTER (0.2–0.4s) adapts fast — good for tracks with dynamics, but flaky on busy fast-hat sections. LONGER (1–2s) is stable and locks onto the dominant steady kick, ignoring fast transients. Use 1.0+ for rock/pop with steady kicks.">ⓘ</span></label>
        <input type="number" id="optAvgWindow" class="num-input" value="1.0" min="0.1" max="3" step="0.1">
      </div>
      <div class="tk-field">
        <label class="tk-label">Filter Q <span class="info-i" title="Sharpness of the bandpass filter. Higher Q = steeper, narrower filter (more isolation but can ring). 1 is safe; 2–3 is tighter.">ⓘ</span></label>
        <input type="number" id="optQ" class="num-input" value="1.5" min="0.3" max="5" step="0.1">
      </div>
      <div class="tk-field">
        <label class="tk-label">Lookahead (sec) <span class="info-i" title="How far ahead of the playhead the beat bar shows upcoming beats. Purely a display setting — does not affect detection.">ⓘ</span></label>
        <input type="number" id="optLookahead" class="num-input" value="3" min="1" max="8" step="0.5">
      </div>
    </div>

    <div class="tk-flex" style="margin-top:10px;gap:8px">
      <button id="reanalyzeBtn" class="tk-btn tk-btn--sm tk-btn--primary">Re-analyze</button>
      <span class="tk-hint" id="detectHint">Band 40–120 Hz targets kick drums. Raise 'Min BPM' if fast hats still register.</span>
    </div>
  </details>

  <div id="videoSection" class="hidden tk-flex-col" style="gap:var(--tk-sp-md)">
    <div class="video-wrap" id="videoWrap">
      <video id="video" playsinline></video>
      <canvas class="beat-overlay" id="beatOverlay"></canvas>

      <div class="fs-controls" id="fsControls">
        <button id="fsPlayBtn" class="tk-btn tk-btn--icon tk-btn--primary">▶</button>
        <span class="time" id="fsTimeLabel">0:00.00 / 0:00.00</span>
        <div class="seekbar" id="fsSeekbar"><div class="seekbar__fill" id="fsSeekFill"></div></div>
        <div class="vol-wrap">
          <button id="fsMuteBtn" class="tk-btn tk-btn--icon tk-btn--ghost" style="color:#fff">🔊</button>
          <input type="range" id="fsVolSlider" class="vol-slider" min="0" max="1" step="0.01" value="1">
        </div>
        <button id="fsExitBtn" class="tk-btn tk-btn--icon tk-btn--ghost" style="color:#fff" title="Exit fullscreen">⤓</button>
      </div>
    </div>

    <canvas id="beatCanvas" class="beat-canvas"></canvas>

    <div class="controls">
      <button id="playBtn" class="tk-btn tk-btn--primary">▶ Play</button>
      <span class="time" id="timeLabel">0:00.00 / 0:00.00</span>
      <div class="seekbar" id="seekbar"><div class="seekbar__fill" id="seekFill"></div></div>

      <div class="group vol-wrap">
        <button id="muteBtn" class="tk-btn tk-btn--icon tk-btn--ghost" title="Mute">🔊</button>
        <input type="range" id="volSlider" class="vol-slider" min="0" max="1" step="0.01" value="1">
      </div>

      <div class="group">
        <button id="fsBtn" class="tk-btn tk-btn--sm" title="Fullscreen (f)">⛶ Fullscreen</button>
      </div>

      <div class="group">
        <label class="tk-flex" style="gap:6px" title="Play a click on each beat">
          <span class="tk-text-sm tk-muted">Tick</span>
          <span class="tk-toggle"><input type="checkbox" id="tickToggle" checked><span class="slider"></span></span>
        </label>
        <label class="tk-flex" style="gap:6px" title="On: beat bar is drawn on the video. Off: shown in a separate panel below.">
          <span class="tk-text-sm tk-muted">Bar on video</span>
          <span class="tk-toggle"><input type="checkbox" id="overlayToggle" checked><span class="slider"></span></span>
        </label>
      </div>

      <button id="clearBtn" class="tk-btn tk-btn--sm tk-btn--ghost">Clear</button>
    </div>

    <div class="stats" id="stats"></div>
    <div class="tk-faint tk-text-xs">Shortcuts: space play/pause · f fullscreen · m mute · ←/→ seek · ↑/↓ volume</div>
  </div>

  <div id="progressCard" class="tk-card hidden">
    <div class="tk-flex tk-flex-between" style="margin-bottom:8px">
      <span class="tk-label-section" id="progressLabel">Analyzing audio</span>
      <span class="tk-mono tk-text-xs tk-muted" id="progressPct">0%</span>
    </div>
    <div class="tk-progress"><div class="tk-progress__bar" id="progressBar" style="width:0%"></div></div>
  </div>

  <div class="status" id="status"></div>
</div>

<script>
'use strict';

const state = {
  videoUrl: null,
  videoFile: null,
  beats: [],
  bpmEstimate: 0,
  duration: 0,
  lastBeatIdx: -1,
  tickEnabled: true,
  overlayEnabled: true,
  audioCtx: null,
  lastVideoTime: 0,
  lastVideoTimeAt: 0,
  smoothTime: 0,
  lastMute: 1,
};

const dom = {
  drop: document.getElementById('dropZone'),
  file: document.getElementById('fileInput'),
  video: document.getElementById('video'),
  wrap: document.getElementById('videoWrap'),
  canvas: document.getElementById('beatCanvas'),
  overlay: document.getElementById('beatOverlay'),
  section: document.getElementById('videoSection'),
  playBtn: document.getElementById('playBtn'),
  fsPlayBtn: document.getElementById('fsPlayBtn'),
  time: document.getElementById('timeLabel'),
  fsTime: document.getElementById('fsTimeLabel'),
  seekbar: document.getElementById('seekbar'),
  seekFill: document.getElementById('seekFill'),
  fsSeekbar: document.getElementById('fsSeekbar'),
  fsSeekFill: document.getElementById('fsSeekFill'),
  muteBtn: document.getElementById('muteBtn'),
  fsMuteBtn: document.getElementById('fsMuteBtn'),
  volSlider: document.getElementById('volSlider'),
  fsVolSlider: document.getElementById('fsVolSlider'),
  fsBtn: document.getElementById('fsBtn'),
  fsExitBtn: document.getElementById('fsExitBtn'),
  fsControls: document.getElementById('fsControls'),
  tickToggle: document.getElementById('tickToggle'),
  overlayToggle: document.getElementById('overlayToggle'),
  reanalyzeBtn: document.getElementById('reanalyzeBtn'),
  clearBtn: document.getElementById('clearBtn'),
  progressCard: document.getElementById('progressCard'),
  progressBar: document.getElementById('progressBar'),
  progressPct: document.getElementById('progressPct'),
  progressLabel: document.getElementById('progressLabel'),
  status: document.getElementById('status'),
  stats: document.getElementById('stats'),
  detectHint: document.getElementById('detectHint'),
  optBandLow: document.getElementById('optBandLow'),
  optBandHigh: document.getElementById('optBandHigh'),
  optMinBpm: document.getElementById('optMinBpm'),
  optMaxBpm: document.getElementById('optMaxBpm'),
  optSensitivity: document.getElementById('optSensitivity'),
  optAvgWindow: document.getElementById('optAvgWindow'),
  optQ: document.getElementById('optQ'),
  optLookahead: document.getElementById('optLookahead'),
  presetBtns: document.querySelectorAll('.preset'),
};

const fmt = (t) => {
  if (!isFinite(t)) t = 0;
  const m = Math.floor(t / 60);
  const s = t - m * 60;
  return `${m}:${s.toFixed(2).padStart(5, '0')}`;
};
const setStatus = (msg, isErr = false) => {
  dom.status.textContent = msg || '';
  dom.status.classList.toggle('err', !!isErr);
};
const setProgress = (label, pct) => {
  dom.progressCard.classList.remove('hidden');
  dom.progressLabel.textContent = label;
  dom.progressBar.style.width = pct + '%';
  dom.progressPct.textContent = Math.round(pct) + '%';
};
const hideProgress = () => dom.progressCard.classList.add('hidden');
const getCssVar = (n) => getComputedStyle(document.documentElement).getPropertyValue(n).trim();

// ── File input ──────────────────────────────────────────
dom.drop.addEventListener('click', () => dom.file.click());
dom.file.addEventListener('change', (e) => { const f = e.target.files[0]; if (f) loadFile(f); });
['dragenter', 'dragover'].forEach(ev =>
  dom.drop.addEventListener(ev, (e) => { e.preventDefault(); dom.drop.classList.add('drag'); })
);
['dragleave', 'drop'].forEach(ev =>
  dom.drop.addEventListener(ev, (e) => { e.preventDefault(); dom.drop.classList.remove('drag'); })
);
dom.drop.addEventListener('drop', (e) => { const f = e.dataTransfer.files[0]; if (f) loadFile(f); });

async function loadFile(file) {
  if (state.videoUrl) URL.revokeObjectURL(state.videoUrl);
  state.videoFile = file;
  state.videoUrl = URL.createObjectURL(file);
  state.beats = [];
  state.lastBeatIdx = -1;

  dom.video.src = state.videoUrl;
  dom.section.classList.remove('hidden');
  setStatus(`Loaded: ${file.name}`);

  await new Promise((res, rej) => {
    dom.video.onloadedmetadata = res;
    dom.video.onerror = () => rej(new Error('Failed to load media'));
  }).catch(err => { setStatus(err.message, true); throw err; });

  state.duration = dom.video.duration;
  await analyze(file);
}

// ── Beat detection ──────────────────────────────────────
async function analyze(file) {
  try {
    setProgress('Decoding audio…', 5);
    const buf = await file.arrayBuffer();
    const ctx = new (window.AudioContext || window.webkitAudioContext)();
    const decoded = await ctx.decodeAudioData(buf.slice(0));
    ctx.close();

    setProgress('Filtering & analyzing…', 30);
    const bandLow = parseFloat(dom.optBandLow.value) || 40;
    const bandHigh = parseFloat(dom.optBandHigh.value) || 120;
    const sens = parseFloat(dom.optSensitivity.value) || 1.5;
    const minBpm = parseFloat(dom.optMinBpm.value) || 80;
    const maxBpm = parseFloat(dom.optMaxBpm.value) || 200;
    const avgWin = parseFloat(dom.optAvgWindow.value) || 1.0;
    const filterQ = parseFloat(dom.optQ.value) || 1.5;

    // Build filter chain: cascaded HP + LP biquads (24 dB/oct per side).
    // Two stages each gives a tight bandpass that kills mids when tuned narrow.
    const offline = new OfflineAudioContext(1, decoded.length, decoded.sampleRate);
    const src = offline.createBufferSource();
    src.buffer = decoded;

    const hp1 = offline.createBiquadFilter();
    hp1.type = 'highpass'; hp1.frequency.value = bandLow; hp1.Q.value = filterQ;
    const hp2 = offline.createBiquadFilter();
    hp2.type = 'highpass'; hp2.frequency.value = bandLow; hp2.Q.value = filterQ;
    const lp1 = offline.createBiquadFilter();
    lp1.type = 'lowpass'; lp1.frequency.value = bandHigh; lp1.Q.value = filterQ;
    const lp2 = offline.createBiquadFilter();
    lp2.type = 'lowpass'; lp2.frequency.value = bandHigh; lp2.Q.value = filterQ;

    src.connect(hp1).connect(hp2).connect(lp1).connect(lp2).connect(offline.destination);
    src.start(0);
    const filtered = await offline.startRendering();

    setProgress('Finding onsets…', 65);
    const minGapMs = (60 / maxBpm) * 1000;
    const maxGapGuide = (60 / minBpm) * 1000; // not enforced, but informs detection
    const beats = detectBeats(filtered, {
      sensitivity: sens,
      minGapMs,
      maxGapMs: maxGapGuide,
      avgWindowSec: avgWin,
    });
    state.beats = beats;
    state.bpmEstimate = estimateBpm(beats);

    setProgress('Done', 100);
    setTimeout(hideProgress, 400);
    updateStats();
    setStatus(`Found ${beats.length} beats · ~${state.bpmEstimate.toFixed(1)} BPM avg (band ${bandLow}–${bandHigh} Hz)`);
  } catch (err) {
    hideProgress();
    setStatus('Analysis failed: ' + err.message, true);
    console.error(err);
  }
}

function detectBeats(audioBuffer, opts) {
  const { sensitivity, minGapMs, avgWindowSec } = opts;
  const sr = audioBuffer.sampleRate;
  const data = audioBuffer.getChannelData(0);
  const frameSize = 1024, hop = 512;
  const numFrames = Math.floor((data.length - frameSize) / hop);
  const energy = new Float32Array(numFrames);

  for (let i = 0; i < numFrames; i++) {
    let sum = 0;
    const start = i * hop;
    for (let j = 0; j < frameSize; j++) {
      const v = data[start + j];
      sum += v * v;
    }
    energy[i] = Math.sqrt(sum / frameSize);
  }

  // Onset function: positive-going difference (half-wave rectified derivative)
  // This is more selective for sharp transients than raw energy
  const onset = new Float32Array(numFrames);
  for (let i = 1; i < numFrames; i++) {
    const d = energy[i] - energy[i - 1];
    onset[i] = d > 0 ? d : 0;
  }

  // Moving-average threshold on ENERGY (not onset) for stability
  const windowFrames = Math.round((sr / hop) * avgWindowSec);
  const minGapFrames = Math.round((minGapMs / 1000) * (sr / hop));
  const beats = [];
  let lastBeat = -Infinity;

  // Running sum for efficient mean
  // Use a trailing window so detection doesn't "see the future" too much
  for (let i = 1; i < numFrames - 1; i++) {
    const w0 = Math.max(0, i - windowFrames);
    const w1 = Math.min(numFrames, i + windowFrames);
    let avg = 0;
    for (let k = w0; k < w1; k++) avg += energy[k];
    avg /= (w1 - w0);

    const e = energy[i];
    // Require: above adaptive threshold, local max in energy, positive onset,
    // and far enough from last beat
    if (
      e > avg * sensitivity &&
      e > energy[i - 1] &&
      e >= energy[i + 1] &&
      onset[i] > 0 &&
      i - lastBeat > minGapFrames
    ) {
      beats.push((i * hop) / sr);
      lastBeat = i;
    }
  }
  return beats;
}

function estimateBpm(beats) {
  if (beats.length < 4) return 0;
  const ivs = [];
  for (let i = 1; i < beats.length; i++) ivs.push(beats[i] - beats[i - 1]);
  ivs.sort((a, b) => a - b);
  const med = ivs[Math.floor(ivs.length / 2)];
  return med ? 60 / med : 0;
}

function updateStats() {
  dom.stats.innerHTML = `
    <span>Beats: <b>${state.beats.length}</b></span>
    <span>Avg BPM: <b>${state.bpmEstimate ? state.bpmEstimate.toFixed(1) : '—'}</b></span>
    <span>Duration: <b>${fmt(state.duration)}</b></span>
  `;
}

// ── Canvas sizing ───────────────────────────────────────
const ctxMain = dom.canvas.getContext('2d');
const ctxOverlay = dom.overlay.getContext('2d');

function resizeCanvases() {
  for (const c of [dom.canvas, dom.overlay]) {
    const dpr = window.devicePixelRatio || 1;
    const rect = c.getBoundingClientRect();
    if (rect.width === 0 || rect.height === 0) continue;
    c.width = Math.round(rect.width * dpr);
    c.height = Math.round(rect.height * dpr);
    c.getContext('2d').setTransform(dpr, 0, 0, dpr, 0, 0);
  }
}
window.addEventListener('resize', resizeCanvases);
const resizeObs = new ResizeObserver(resizeCanvases);
resizeObs.observe(dom.canvas);
resizeObs.observe(dom.overlay);

// ── Drawing ─────────────────────────────────────────────
const PLAYHEAD_X_FRAC = 0.2;
const pulses = new Map();

function drawBar(ctx, canvas, now, opts) {
  const w = canvas.clientWidth;
  const h = canvas.clientHeight;
  if (w === 0 || h === 0) return;

  ctx.clearRect(0, 0, w, h);
  if (opts.overlay) {
    const grad = ctx.createLinearGradient(0, 0, 0, h);
    grad.addColorStop(0, 'rgba(0,0,0,0)');
    grad.addColorStop(1, 'rgba(0,0,0,0.6)');
    ctx.fillStyle = grad;
    ctx.fillRect(0, 0, w, h);
  }

  ctx.strokeStyle = opts.overlay ? 'rgba(255,255,255,0.12)' : 'rgba(255,255,255,0.05)';
  ctx.lineWidth = 1;
  ctx.beginPath();
  ctx.moveTo(0, h / 2);
  ctx.lineTo(w, h / 2);
  ctx.stroke();

  if (!state.beats.length) {
    if (!opts.overlay) {
      ctx.fillStyle = 'rgba(148,155,164,0.7)';
      ctx.font = '12px ' + getComputedStyle(document.body).fontFamily;
      ctx.textAlign = 'center';
      ctx.textBaseline = 'middle';
      ctx.fillText('No beats detected — try adjusting sensitivity', w / 2, h / 2);
    }
    return;
  }

  const t = state.smoothTime;
  const lookahead = parseFloat(dom.optLookahead.value) || 3;
  const playheadX = w * PLAYHEAD_X_FRAC;
  const lookbehind = lookahead * (PLAYHEAD_X_FRAC / (1 - PLAYHEAD_X_FRAC));
  const pxPerSec = (w - playheadX) / lookahead;

  ctx.strokeStyle = opts.overlay ? 'rgba(255,255,255,0.6)' : 'rgba(83,133,241,0.45)';
  ctx.lineWidth = 2;
  ctx.beginPath();
  ctx.moveTo(playheadX, 6);
  ctx.lineTo(playheadX, h - 6);
  ctx.stroke();

  // Dot sizes scaled to canvas height; much bigger than before
  const baseR = Math.max(8, Math.min(14, h * 0.1));
  const pulseR = baseR + 14;

  const accent = getCssVar('--tk-accent') || '#5385f1';
  const teal = getCssVar('--tk-teal') || '#73daca';
  const futureCol = opts.overlay ? '#7aa8ff' : accent;
  const pastCol = opts.overlay ? '#9ef0df' : teal;

  // Binary search for first visible beat
  const firstT = t - lookbehind - 0.2;
  let lo = 0, hi = state.beats.length;
  while (lo < hi) {
    const mid = (lo + hi) >> 1;
    if (state.beats[mid] < firstT) lo = mid + 1; else hi = mid;
  }

  for (let i = lo; i < state.beats.length; i++) {
    const bt = state.beats[i];
    const dt = bt - t;
    if (dt > lookahead + 0.2) break;

    const x = playheadX + dt * pxPerSec;
    const y = h / 2;

    const pulse = pulses.get(i);
    let radius = baseR;
    let glow = 0;
    if (pulse) {
      const age = (now - pulse.startTime) / 1000;
      const LIFE = 0.4;
      if (age > LIFE) {
        pulses.delete(i);
      } else {
        const k = 1 - (age / LIFE);
        radius = baseR + k * (pulseR - baseR);
        glow = k;
      }
    }

    if (glow > 0) {
      const g = ctx.createRadialGradient(x, y, 0, x, y, radius + 22);
      g.addColorStop(0, `rgba(83,133,241,${glow * 0.6})`);
      g.addColorStop(1, 'rgba(83,133,241,0)');
      ctx.fillStyle = g;
      ctx.beginPath();
      ctx.arc(x, y, radius + 22, 0, Math.PI * 2);
      ctx.fill();
    }

    const isPast = dt < -0.02;

    if (opts.overlay) {
      ctx.fillStyle = 'rgba(0,0,0,0.55)';
      ctx.beginPath();
      ctx.arc(x, y, radius + 2, 0, Math.PI * 2);
      ctx.fill();
    }
    ctx.fillStyle = isPast ? pastCol : futureCol;
    ctx.beginPath();
    ctx.arc(x, y, radius, 0, Math.PI * 2);
    ctx.fill();

    ctx.strokeStyle = isPast
      ? (opts.overlay ? 'rgba(158,240,223,0.4)' : 'rgba(115,218,202,0.3)')
      : (opts.overlay ? 'rgba(122,168,255,0.45)' : 'rgba(83,133,241,0.3)');
    ctx.lineWidth = 1.5;
    ctx.beginPath();
    ctx.moveTo(x, y + radius + 3);
    ctx.lineTo(x, h - 8);
    ctx.stroke();
  }

  if (!opts.overlay) {
    const fade = ctx.createLinearGradient(w - 50, 0, w, 0);
    fade.addColorStop(0, 'rgba(43,45,49,0)');
    fade.addColorStop(1, 'rgba(43,45,49,1)');
    ctx.fillStyle = fade;
    ctx.fillRect(w - 50, 0, 50, h);
  }
}

// ── Beat firing ─────────────────────────────────────────
function checkBeatsPassed() {
  const t = state.smoothTime;
  if (state.lastBeatIdx >= 0 && state.beats[state.lastBeatIdx] > t + 0.1) {
    let lo = 0, hi = state.beats.length;
    while (lo < hi) {
      const mid = (lo + hi) >> 1;
      if (state.beats[mid] <= t) lo = mid + 1; else hi = mid;
    }
    state.lastBeatIdx = lo - 1;
  }
  let idx = state.lastBeatIdx + 1;
  while (idx < state.beats.length && state.beats[idx] <= t) {
    fireBeat(idx);
    idx++;
  }
  state.lastBeatIdx = idx - 1;
}

function fireBeat(idx) {
  pulses.set(idx, { startTime: performance.now() });
  if (state.tickEnabled && !dom.video.paused) playTick();
}

function playTick() {
  if (!state.audioCtx) state.audioCtx = new (window.AudioContext || window.webkitAudioContext)();
  const ac = state.audioCtx;
  const now = ac.currentTime;
  const osc = ac.createOscillator();
  const gain = ac.createGain();
  osc.type = 'square';
  osc.frequency.setValueAtTime(1800, now);
  osc.frequency.exponentialRampToValueAtTime(800, now + 0.04);
  gain.gain.setValueAtTime(0.0001, now);
  gain.gain.exponentialRampToValueAtTime(0.15, now + 0.005);
  gain.gain.exponentialRampToValueAtTime(0.0001, now + 0.06);
  osc.connect(gain).connect(ac.destination);
  osc.start(now);
  osc.stop(now + 0.08);
}

// ── Smooth time interpolation ───────────────────────────
// Fixes jitter: video.currentTime only ticks ~30Hz; we interp with perf.now()
dom.video.addEventListener('timeupdate', () => {
  state.lastVideoTime = dom.video.currentTime;
  state.lastVideoTimeAt = performance.now();
});

function updateSmoothTime(nowPerf) {
  if (dom.video.paused || dom.video.seeking || !dom.video.src) {
    state.smoothTime = dom.video.currentTime;
    state.lastVideoTime = dom.video.currentTime;
    state.lastVideoTimeAt = nowPerf;
    return;
  }
  if (dom.video.currentTime !== state.lastVideoTime) {
    state.lastVideoTime = dom.video.currentTime;
    state.lastVideoTimeAt = nowPerf;
  }
  const dt = (nowPerf - state.lastVideoTimeAt) / 1000;
  const rate = dom.video.playbackRate || 1;
  state.smoothTime = state.lastVideoTime + dt * rate;
  if (state.smoothTime > state.duration) state.smoothTime = state.duration;
}

// ── Main loop ───────────────────────────────────────────
function loop(now) {
  updateSmoothTime(now);
  checkBeatsPassed();
  drawBar(ctxMain, dom.canvas, now, { overlay: false });
  if (state.overlayEnabled) {
    drawBar(ctxOverlay, dom.overlay, now, { overlay: true });
  } else {
    ctxOverlay.clearRect(0, 0, dom.overlay.clientWidth, dom.overlay.clientHeight);
  }
  updateTimeUi();
  requestAnimationFrame(loop);
}
requestAnimationFrame(loop);

function updateTimeUi() {
  const txt = `${fmt(state.smoothTime)} / ${fmt(state.duration)}`;
  dom.time.textContent = txt;
  dom.fsTime.textContent = txt;
  const pct = state.duration ? (state.smoothTime / state.duration) * 100 : 0;
  dom.seekFill.style.width = pct + '%';
  dom.fsSeekFill.style.width = pct + '%';
}

// ── Playback & seek ─────────────────────────────────────
async function togglePlay() {
  if (dom.video.paused) {
    if (state.audioCtx && state.audioCtx.state === 'suspended') await state.audioCtx.resume();
    dom.video.play();
  } else {
    dom.video.pause();
  }
}
dom.playBtn.addEventListener('click', togglePlay);
dom.fsPlayBtn.addEventListener('click', togglePlay);
dom.video.addEventListener('play', () => { dom.playBtn.textContent = '❚❚ Pause'; dom.fsPlayBtn.textContent = '❚❚'; });
dom.video.addEventListener('pause', () => { dom.playBtn.textContent = '▶ Play'; dom.fsPlayBtn.textContent = '▶'; });
dom.video.addEventListener('seeking', () => { state.lastBeatIdx = -1; pulses.clear(); });
dom.video.addEventListener('click', togglePlay);

function attachSeek(bar) {
  bar.addEventListener('click', (e) => {
    const rect = bar.getBoundingClientRect();
    const pct = (e.clientX - rect.left) / rect.width;
    dom.video.currentTime = Math.max(0, Math.min(state.duration, pct * state.duration));
  });
}
attachSeek(dom.seekbar);
attachSeek(dom.fsSeekbar);

// ── Volume / mute ───────────────────────────────────────
function applyVolume(v) {
  v = Math.max(0, Math.min(1, v));
  dom.video.volume = v;
  dom.video.muted = (v === 0);
  dom.volSlider.value = v;
  dom.fsVolSlider.value = v;
  const icon = v === 0 ? '🔇' : (v < 0.5 ? '🔉' : '🔊');
  dom.muteBtn.textContent = icon;
  dom.fsMuteBtn.textContent = icon;
}
[dom.volSlider, dom.fsVolSlider].forEach(s => {
  s.addEventListener('input', (e) => {
    const v = parseFloat(e.target.value);
    if (v > 0) state.lastMute = v;
    applyVolume(v);
  });
});
function toggleMute() {
  if (dom.video.volume === 0) applyVolume(state.lastMute || 1);
  else { state.lastMute = dom.video.volume; applyVolume(0); }
}
dom.muteBtn.addEventListener('click', toggleMute);
dom.fsMuteBtn.addEventListener('click', toggleMute);

// ── Fullscreen ──────────────────────────────────────────
async function toggleFullscreen() {
  if (!document.fullscreenElement) {
    const el = dom.wrap;
    const req = el.requestFullscreen || el.webkitRequestFullscreen || el.msRequestFullscreen;
    if (req) await req.call(el);
  } else {
    const exit = document.exitFullscreen || document.webkitExitFullscreen || document.msExitFullscreen;
    if (exit) await exit.call(document);
  }
}
dom.fsBtn.addEventListener('click', toggleFullscreen);
dom.fsExitBtn.addEventListener('click', toggleFullscreen);
document.addEventListener('fullscreenchange', () => {
  requestAnimationFrame(resizeCanvases);
  requestAnimationFrame(() => requestAnimationFrame(resizeCanvases));
});

let fsHideTimer = null;
dom.wrap.addEventListener('mousemove', () => {
  if (!document.fullscreenElement) return;
  dom.wrap.classList.add('show-controls');
  clearTimeout(fsHideTimer);
  fsHideTimer = setTimeout(() => dom.wrap.classList.remove('show-controls'), 2000);
});

// ── Keyboard shortcuts ──────────────────────────────────
document.addEventListener('keydown', (e) => {
  if (e.target.tagName === 'INPUT' || e.target.tagName === 'TEXTAREA') return;
  if (!state.videoUrl) return;
  switch (e.key) {
    case ' ': e.preventDefault(); togglePlay(); break;
    case 'f': case 'F': toggleFullscreen(); break;
    case 'm': case 'M': toggleMute(); break;
    case 'ArrowLeft': dom.video.currentTime = Math.max(0, dom.video.currentTime - 5); break;
    case 'ArrowRight': dom.video.currentTime = Math.min(state.duration, dom.video.currentTime + 5); break;
    case 'ArrowUp': e.preventDefault(); applyVolume(dom.video.volume + 0.05); break;
    case 'ArrowDown': e.preventDefault(); applyVolume(dom.video.volume - 0.05); break;
    case 'Escape': if (document.fullscreenElement) toggleFullscreen(); break;
  }
});

// ── Toggles & actions ───────────────────────────────────
dom.tickToggle.addEventListener('change', (e) => { state.tickEnabled = e.target.checked; });
function applyBarMode() {
  // Only ONE bar visible at a time
  if (state.overlayEnabled) {
    dom.overlay.classList.remove('off');
    dom.canvas.classList.add('off');
  } else {
    dom.overlay.classList.add('off');
    dom.canvas.classList.remove('off');
  }
  // Force resize after DOM visibility change
  requestAnimationFrame(resizeCanvases);
}
dom.overlayToggle.addEventListener('change', (e) => {
  state.overlayEnabled = e.target.checked;
  applyBarMode();
});
dom.reanalyzeBtn.addEventListener('click', () => { if (state.videoFile) analyze(state.videoFile); });
dom.clearBtn.addEventListener('click', () => {
  if (state.videoUrl) URL.revokeObjectURL(state.videoUrl);
  state.videoUrl = null; state.videoFile = null; state.beats = [];
  dom.video.src = ''; dom.section.classList.add('hidden');
  dom.stats.innerHTML = ''; setStatus('');
});

// ── Detection presets ───────────────────────────────────
const PRESETS = {
  kick: {
    bandLow: 40, bandHigh: 120, minBpm: 80, maxBpm: 180,
    sensitivity: 1.5, avgWindow: 1.0, q: 1.5,
    hint: 'Kick drum / steady pulse. Wide avg window locks onto the dominant kick pattern, ignoring fast hats.'
  },
  snare: {
    bandLow: 150, bandHigh: 300, minBpm: 60, maxBpm: 160,
    sensitivity: 1.6, avgWindow: 0.8, q: 1.5,
    hint: 'Snare / backbeat. Mid-range band catches snare body; slow BPM range targets 2 & 4.'
  },
  broad: {
    bandLow: 30, bandHigh: 500, minBpm: 100, maxBpm: 280,
    sensitivity: 1.35, avgWindow: 0.4, q: 1.0,
    hint: 'Broad onset detection. Catches more events including fast hats and snare — use if kick-only feels sparse.'
  },
  custom: { hint: 'Custom settings — tweak freely.' }
};

function applyPreset(name) {
  const p = PRESETS[name];
  if (!p) return;
  if (name !== 'custom') {
    dom.optBandLow.value = p.bandLow;
    dom.optBandHigh.value = p.bandHigh;
    dom.optMinBpm.value = p.minBpm;
    dom.optMaxBpm.value = p.maxBpm;
    dom.optSensitivity.value = p.sensitivity;
    dom.optAvgWindow.value = p.avgWindow;
    dom.optQ.value = p.q;
  }
  dom.detectHint.textContent = p.hint;
  dom.presetBtns.forEach(b => b.classList.toggle('active', b.dataset.preset === name));
}
dom.presetBtns.forEach(btn => {
  btn.addEventListener('click', () => applyPreset(btn.dataset.preset));
});
// Mark any setting change as "custom"
['optBandLow','optBandHigh','optMinBpm','optMaxBpm','optSensitivity','optAvgWindow','optQ'].forEach(k => {
  dom[k].addEventListener('input', () => {
    dom.presetBtns.forEach(b => b.classList.toggle('active', b.dataset.preset === 'custom'));
    dom.detectHint.textContent = PRESETS.custom.hint;
  });
});

// Init
applyPreset('kick');
applyBarMode();
applyVolume(1);
resizeCanvases();
</script>
</body>
</html>
