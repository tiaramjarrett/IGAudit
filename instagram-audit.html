<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Instagram Audit</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #ffffff;
    --bg-secondary: #f7f7f5;
    --bg-tertiary: #f0efec;
    --text: #1a1a18;
    --text-secondary: #6b6b66;
    --text-muted: #9b9b96;
    --border: #e2e2dc;
    --border-strong: #c8c8c0;
    --accent: #2d6a4f;
    --accent-light: #e8f4ee;
    --amber: #b45309;
    --amber-light: #fef3c7;
    --red: #b91c1c;
    --red-light: #fee2e2;
    --green: #166534;
    --green-light: #dcfce7;
    --radius: 10px;
    --radius-sm: 6px;
    --shadow: 0 1px 3px rgba(0,0,0,0.06), 0 1px 2px rgba(0,0,0,0.04);
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif;
    background: var(--bg-secondary);
    color: var(--text);
    font-size: 15px;
    line-height: 1.6;
    min-height: 100vh;
  }

  .page {
    max-width: 760px;
    margin: 0 auto;
    padding: 2rem 1.25rem 4rem;
  }

  /* Header */
  .header {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 1rem;
    margin-bottom: 2rem;
    padding-bottom: 1.5rem;
    border-bottom: 1px solid var(--border);
  }
  .header-left h1 {
    font-size: 22px;
    font-weight: 600;
    color: var(--text);
    letter-spacing: -0.3px;
  }
  .header-left p {
    font-size: 13px;
    color: var(--text-secondary);
    margin-top: 3px;
  }
  .logo-mark {
    width: 40px;
    height: 40px;
    background: var(--text);
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
  }
  .logo-mark svg { width: 20px; height: 20px; fill: white; }

  /* Score bar */
  .score-bar {
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 1.25rem 1.5rem;
    margin-bottom: 1.5rem;
    box-shadow: var(--shadow);
  }
  .score-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
    gap: 1rem;
    margin-bottom: 1rem;
  }
  .metric {
    text-align: center;
    padding: 0.75rem;
    background: var(--bg-secondary);
    border-radius: var(--radius-sm);
  }
  .metric-num {
    font-size: 26px;
    font-weight: 600;
    color: var(--text);
    line-height: 1;
  }
  .metric-label {
    font-size: 11px;
    color: var(--text-secondary);
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-top: 4px;
  }
  .progress-track {
    height: 5px;
    background: var(--bg-tertiary);
    border-radius: 3px;
    margin-top: 10px;
    overflow: hidden;
  }
  .progress-fill {
    height: 100%;
    border-radius: 3px;
    transition: width 0.5s ease;
    background: var(--accent);
  }
  .tag-row { display: flex; flex-wrap: wrap; gap: 6px; }
  .tag {
    font-size: 12px;
    padding: 3px 10px;
    border-radius: 20px;
    font-weight: 500;
  }
  .tag-red { background: var(--red-light); color: var(--red); }
  .tag-amber { background: var(--amber-light); color: var(--amber); }
  .tag-green { background: var(--green-light); color: var(--green); }

  /* Sections */
  .section {
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 1.5rem;
    margin-bottom: 1rem;
    box-shadow: var(--shadow);
  }
  .section-header {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 1.25rem;
    padding-bottom: 1rem;
    border-bottom: 1px solid var(--border);
  }
  .section-icon {
    width: 32px;
    height: 32px;
    background: var(--bg-secondary);
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 16px;
    flex-shrink: 0;
  }
  .section-title {
    font-size: 15px;
    font-weight: 600;
    color: var(--text);
  }

  /* Form elements */
  .field { margin-bottom: 1rem; }
  .field:last-of-type { margin-bottom: 0; }
  label.field-label {
    display: block;
    font-size: 12px;
    font-weight: 500;
    color: var(--text-secondary);
    text-transform: uppercase;
    letter-spacing: 0.4px;
    margin-bottom: 5px;
  }
  input[type=text], input[type=number], select, textarea {
    width: 100%;
    font-size: 14px;
    color: var(--text);
    background: var(--bg-secondary);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 8px 12px;
    font-family: inherit;
    outline: none;
    transition: border-color 0.15s;
    appearance: none;
    -webkit-appearance: none;
  }
  input[type=text]:focus, input[type=number]:focus, select:focus, textarea:focus {
    border-color: var(--border-strong);
    background: var(--bg);
    box-shadow: 0 0 0 3px rgba(45,106,79,0.08);
  }
  textarea { resize: vertical; min-height: 72px; line-height: 1.5; }
  select {
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'%3E%3Cpath fill='%236b6b66' d='M6 8L1 3h10z'/%3E%3C/svg%3E");
    background-repeat: no-repeat;
    background-position: right 10px center;
    padding-right: 30px;
  }

  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
  .three-col { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 12px; }

  /* Checkboxes */
  .checkbox-group { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 4px; }
  .checkbox-label {
    display: flex;
    align-items: center;
    gap: 6px;
    font-size: 13px;
    color: var(--text);
    cursor: pointer;
    padding: 5px 10px;
    background: var(--bg-secondary);
    border: 1px solid var(--border);
    border-radius: 20px;
    transition: all 0.15s;
    user-select: none;
  }
  .checkbox-label:hover { border-color: var(--border-strong); }
  .checkbox-label input { width: 14px; height: 14px; accent-color: var(--accent); }

  /* Rating */
  .ratings-block {
    background: var(--bg-secondary);
    border-radius: var(--radius-sm);
    padding: 1rem;
    margin-top: 1.25rem;
  }
  .ratings-title {
    font-size: 11px;
    font-weight: 500;
    color: var(--text-muted);
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 10px;
  }
  .rating-row {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 6px 0;
    border-bottom: 1px solid var(--border);
  }
  .rating-row:last-child { border-bottom: none; padding-bottom: 0; }
  .rating-label { flex: 1; font-size: 13px; color: var(--text); }
  .rating-btns { display: flex; gap: 4px; }
  .rbtn {
    width: 30px;
    height: 30px;
    border-radius: 50%;
    border: 1px solid var(--border);
    background: var(--bg);
    font-size: 12px;
    font-weight: 500;
    cursor: pointer;
    color: var(--text-secondary);
    transition: all 0.15s;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .rbtn:hover { border-color: var(--border-strong); background: var(--bg-tertiary); }
  .rbtn.sel-1 { background: var(--red-light); border-color: var(--red); color: var(--red); font-weight: 600; }
  .rbtn.sel-2 { background: var(--amber-light); border-color: var(--amber); color: var(--amber); font-weight: 600; }
  .rbtn.sel-3 { background: var(--green-light); border-color: var(--green); color: var(--green); font-weight: 600; }

  /* Checklist */
  .checklist-item {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    padding: 10px 0;
    border-bottom: 1px solid var(--border);
  }
  .checklist-item:last-of-type { border-bottom: none; }
  .checklist-item input[type=checkbox] {
    width: 16px;
    height: 16px;
    margin-top: 2px;
    flex-shrink: 0;
    accent-color: var(--accent);
    cursor: pointer;
  }
  .checklist-text { font-size: 13px; color: var(--text); }

  /* Buttons */
  .btn-primary {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    width: 100%;
    padding: 12px;
    background: var(--text);
    color: white;
    border: none;
    border-radius: var(--radius-sm);
    font-size: 14px;
    font-weight: 500;
    cursor: pointer;
    font-family: inherit;
    transition: opacity 0.15s;
    margin-top: 0.5rem;
  }
  .btn-primary:hover { opacity: 0.85; }
  .btn-secondary {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    width: 100%;
    padding: 10px;
    background: var(--bg);
    color: var(--text);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    font-size: 14px;
    font-weight: 500;
    cursor: pointer;
    font-family: inherit;
    transition: background 0.15s;
    margin-top: 0.5rem;
  }
  .btn-secondary:hover { background: var(--bg-secondary); }

  /* Rating legend */
  .legend {
    display: flex;
    gap: 1rem;
    font-size: 12px;
    color: var(--text-secondary);
    margin-bottom: 8px;
    flex-wrap: wrap;
  }
  .legend span { display: flex; align-items: center; gap: 5px; }
  .dot {
    width: 8px; height: 8px; border-radius: 50%; display: inline-block;
  }

  /* Print */
  @media print {
    body { background: white; }
    .btn-primary, .btn-secondary { display: none; }
    .section { break-inside: avoid; }
  }

  @media (max-width: 540px) {
    .two-col, .three-col { grid-template-columns: 1fr; }
    .score-grid { grid-template-columns: repeat(3, 1fr); }
  }
</style>
</head>
<body>
<div class="page">

  <!-- Header -->
  <div class="header">
    <div class="header-left">
      <h1>Instagram audit</h1>
      <p>Viewer access — no insights dashboard required</p>
    </div>
    <div class="logo-mark">
      <svg viewBox="0 0 20 20"><path d="M10 2a8 8 0 1 0 0 16A8 8 0 0 0 10 2zm0 14.5a6.5 6.5 0 1 1 0-13 6.5 6.5 0 0 1 0 13zm0-10a1 1 0 1 0 0 2 1 1 0 0 0 0-2zm-1 4h2v4H9v-4z"/></svg>
    </div>
  </div>

  <!-- Client info bar -->
  <div class="section" style="margin-bottom:1rem">
    <div class="section-header" style="margin-bottom:1rem">
      <div class="section-icon">📋</div>
      <span class="section-title">Audit details</span>
    </div>
    <div class="three-col">
      <div class="field">
        <label class="field-label">Client / brand name</label>
        <input type="text" id="client-name" placeholder="e.g. Timberholm Inn">
      </div>
      <div class="field">
        <label class="field-label">Auditor name</label>
        <input type="text" id="auditor-name" placeholder="Your name">
      </div>
      <div class="field">
        <label class="field-label">Audit date</label>
        <input type="text" id="audit-date" placeholder="e.g. June 2026">
      </div>
    </div>
  </div>

  <!-- Score summary -->
  <div class="score-bar">
    <div class="score-grid">
      <div class="metric">
        <div class="metric-num" id="total-score">—</div>
        <div class="metric-label">Overall score</div>
        <div class="progress-track">
          <div class="progress-fill" id="score-fill" style="width:0%"></div>
        </div>
      </div>
      <div class="metric">
        <div class="metric-num" id="sections-done">0 / 5</div>
        <div class="metric-label">Sections rated</div>
      </div>
      <div class="metric">
        <div class="metric-num" id="grade">—</div>
        <div class="metric-label">Grade</div>
      </div>
    </div>
    <div class="tag-row" id="tag-area"></div>
  </div>

  <!-- Section 1: Profile -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">👤</div>
      <span class="section-title">1 — Profile setup</span>
    </div>

    <div class="field">
      <label class="field-label">Instagram username</label>
      <input type="text" id="username" placeholder="@handle">
    </div>

    <div class="two-col">
      <div class="field">
        <label class="field-label">Account type</label>
        <select id="acct-type">
          <option value="">Select...</option>
          <option>Business</option>
          <option>Creator</option>
          <option>Personal</option>
          <option>Unknown</option>
        </select>
      </div>
      <div class="field">
        <label class="field-label">Category shown on profile</label>
        <input type="text" id="category" placeholder="e.g. Bed and breakfast">
      </div>
    </div>

    <div class="three-col">
      <div class="field">
        <label class="field-label">Followers</label>
        <input type="number" id="followers" placeholder="e.g. 1240">
      </div>
      <div class="field">
        <label class="field-label">Following</label>
        <input type="number" id="following" placeholder="e.g. 380">
      </div>
      <div class="field">
        <label class="field-label">Total posts</label>
        <input type="number" id="total-posts" placeholder="e.g. 95">
      </div>
    </div>

    <div class="field">
      <label class="field-label">Bio (paste or summarize)</label>
      <textarea id="bio" placeholder="Paste the current bio here..."></textarea>
    </div>

    <div class="two-col">
      <div class="field">
        <label class="field-label">Link in bio</label>
        <input type="text" id="link-bio" placeholder="URL or 'none'">
      </div>
      <div class="field">
        <label class="field-label">Story highlights count</label>
        <input type="number" id="highlights-count" placeholder="e.g. 5">
      </div>
    </div>

    <div class="field">
      <label class="field-label">Highlight topics (list them)</label>
      <input type="text" id="highlight-topics" placeholder="e.g. Rooms, Reviews, Local tips, Events">
    </div>

    <div class="ratings-block">
      <div class="ratings-title">Rate this section</div>
      <div class="legend">
        <span><span class="dot" style="background:var(--red)"></span>1 = Needs work</span>
        <span><span class="dot" style="background:var(--amber)"></span>2 = Okay</span>
        <span><span class="dot" style="background:var(--green)"></span>3 = Strong</span>
      </div>
      <div class="rating-row"><span class="rating-label">Profile photo quality</span><div class="rating-btns" data-key="photo"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Bio clarity & keyword use</span><div class="rating-btns" data-key="bio-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Link in bio / call to action</span><div class="rating-btns" data-key="link-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Story highlights — present & labeled</span><div class="rating-btns" data-key="highlights-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
    </div>
  </div>

  <!-- Section 2: Content -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">🖼</div>
      <span class="section-title">2 — Content & visual quality</span>
    </div>

    <div class="field">
      <label class="field-label">Content types visible (check all)</label>
      <div class="checkbox-group">
        <label class="checkbox-label"><input type="checkbox" class="content-type" value="Photos"> Photos</label>
        <label class="checkbox-label"><input type="checkbox" class="content-type" value="Reels"> Reels</label>
        <label class="checkbox-label"><input type="checkbox" class="content-type" value="Carousels"> Carousels</label>
        <label class="checkbox-label"><input type="checkbox" class="content-type" value="Stories"> Stories</label>
        <label class="checkbox-label"><input type="checkbox" class="content-type" value="Graphics"> Graphics / text slides</label>
        <label class="checkbox-label"><input type="checkbox" class="content-type" value="Video"> Video (non-Reel)</label>
      </div>
    </div>

    <div class="field">
      <label class="field-label">Grid observation (last 9 posts)</label>
      <textarea id="grid-obs" placeholder="Consistent color palette? Variety of content types? Seasonal? Mix of UGC and original?"></textarea>
    </div>

    <div class="two-col">
      <div class="field">
        <label class="field-label">Est. posts per week (last 4 wks)</label>
        <input type="number" id="post-freq" placeholder="e.g. 3" step="0.5" min="0">
      </div>
      <div class="field">
        <label class="field-label">Reels present?</label>
        <select id="reels-present">
          <option value="">Select...</option>
          <option>Yes — frequently (weekly+)</option>
          <option>Yes — occasionally</option>
          <option>No</option>
        </select>
      </div>
    </div>

    <div class="field">
      <label class="field-label">Pinned posts? (what are they)</label>
      <input type="text" id="pinned" placeholder="e.g. Welcome video, seasonal promo — or 'none'">
    </div>

    <div class="ratings-block">
      <div class="ratings-title">Rate this section</div>
      <div class="rating-row"><span class="rating-label">Visual consistency / brand feel</span><div class="rating-btns" data-key="visual"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Content variety (formats used)</span><div class="rating-btns" data-key="variety"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Posting frequency</span><div class="rating-btns" data-key="freq-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Use of Reels</span><div class="rating-btns" data-key="reels-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
    </div>
  </div>

  <!-- Section 3: Captions -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">✏️</div>
      <span class="section-title">3 — Captions & hashtags</span>
    </div>

    <div class="two-col">
      <div class="field">
        <label class="field-label">Caption length trend</label>
        <select id="caption-len">
          <option value="">Select...</option>
          <option>Very short (1–2 lines)</option>
          <option>Medium (3–5 lines)</option>
          <option>Long / storytelling</option>
          <option>Inconsistent</option>
        </select>
      </div>
      <div class="field">
        <label class="field-label">Hashtag usage</label>
        <select id="hashtags">
          <option value="">Select...</option>
          <option>Consistent & relevant (5–15)</option>
          <option>Overloaded (15–30+)</option>
          <option>Minimal or none</option>
          <option>Inconsistent</option>
        </select>
      </div>
    </div>

    <div class="field">
      <label class="field-label">CTAs visible in captions?</label>
      <select id="ctas">
        <option value="">Select...</option>
        <option>Yes — consistently</option>
        <option>Occasionally</option>
        <option>Rarely or never</option>
      </select>
    </div>

    <div class="field">
      <label class="field-label">Example caption (paste one or note what's working / missing)</label>
      <textarea id="caption-notes" placeholder="Paste an example or describe tone, voice, what's missing..."></textarea>
    </div>

    <div class="field">
      <label class="field-label">Hashtags used (note common ones)</label>
      <input type="text" id="hashtag-list" placeholder="e.g. #stowe #vermontbnb #bedandbreakfast">
    </div>

    <div class="ratings-block">
      <div class="ratings-title">Rate this section</div>
      <div class="rating-row"><span class="rating-label">Caption quality & brand voice</span><div class="rating-btns" data-key="caption-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Hashtag strategy</span><div class="rating-btns" data-key="hashtag-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">CTAs & engagement prompts</span><div class="rating-btns" data-key="cta-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
    </div>
  </div>

  <!-- Section 4: Engagement -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">❤️</div>
      <span class="section-title">4 — Visible engagement</span>
    </div>
    <p style="font-size:12px;color:var(--text-secondary);margin-bottom:1rem;">Estimate from the last 9–12 posts visible on the grid.</p>

    <div class="two-col">
      <div class="field">
        <label class="field-label">Avg. likes per post (estimate)</label>
        <input type="number" id="avg-likes" placeholder="e.g. 45">
      </div>
      <div class="field">
        <label class="field-label">Avg. comments per post (estimate)</label>
        <input type="number" id="avg-comments" placeholder="e.g. 3">
      </div>
    </div>

    <div class="two-col">
      <div class="field">
        <label class="field-label">Brand replies to comments?</label>
        <select id="reply-comments">
          <option value="">Select...</option>
          <option>Yes — most comments get replies</option>
          <option>Sometimes</option>
          <option>Rarely or never</option>
        </select>
      </div>
      <div class="field">
        <label class="field-label">Tagged / UGC content visible?</label>
        <select id="ugc">
          <option value="">Select...</option>
          <option>Yes — regularly reposted</option>
          <option>Occasionally</option>
          <option>No</option>
        </select>
      </div>
    </div>

    <div class="field">
      <label class="field-label">Standout post (high engagement) — describe it</label>
      <textarea id="top-post" placeholder="What type of post got the most likes/comments? What made it work?"></textarea>
    </div>

    <div class="field">
      <label class="field-label">Engagement notes</label>
      <textarea id="eng-notes" placeholder="Overall vibe of comments — community feel? Bot-like? Lots of questions? Mostly emoji?"></textarea>
    </div>

    <div class="ratings-block">
      <div class="ratings-title">Rate this section</div>
      <div class="rating-row"><span class="rating-label">Visible likes / comment level</span><div class="rating-btns" data-key="eng-level"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Community management (replies)</span><div class="rating-btns" data-key="community"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">UGC & tagging activity</span><div class="rating-btns" data-key="ugc-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
    </div>
  </div>

  <!-- Section 5: Strategy -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">🎯</div>
      <span class="section-title">5 — Strategy & content pillars</span>
    </div>

    <div class="field">
      <label class="field-label">Content themes / pillars you can identify</label>
      <textarea id="pillars-obs" placeholder="e.g. Rooms & amenities, local Stowe activities, food & dining, guest experiences, seasonal content..."></textarea>
    </div>

    <div class="two-col">
      <div class="field">
        <label class="field-label">Local / community content</label>
        <select id="local-content">
          <option value="">Select...</option>
          <option>Yes — regularly</option>
          <option>Occasionally</option>
          <option>Rarely</option>
          <option>No</option>
        </select>
      </div>
      <div class="field">
        <label class="field-label">Seasonal / timely content</label>
        <select id="seasonal">
          <option value="">Select...</option>
          <option>Yes — well timed</option>
          <option>Some</option>
          <option>No</option>
        </select>
      </div>
    </div>

    <div class="field">
      <label class="field-label">Partner / collab tags visible</label>
      <input type="text" id="collabs" placeholder="e.g. @thealchemistbeer, @stowemountain, @stowefarmersmarket">
    </div>

    <div class="field">
      <label class="field-label">Promotional / sales content frequency</label>
      <select id="promo-freq">
        <option value="">Select...</option>
        <option>Rare — mostly value/lifestyle content</option>
        <option>Balanced mix</option>
        <option>Heavy — mostly promotional</option>
      </select>
    </div>

    <div class="ratings-block">
      <div class="ratings-title">Rate this section</div>
      <div class="rating-row"><span class="rating-label">Clarity of content strategy</span><div class="rating-btns" data-key="strategy-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Local & seasonal relevance</span><div class="rating-btns" data-key="local-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
      <div class="rating-row"><span class="rating-label">Partnership / collab use</span><div class="rating-btns" data-key="collab-q"><button class="rbtn" data-val="1">1</button><button class="rbtn" data-val="2">2</button><button class="rbtn" data-val="3">3</button></div></div>
    </div>
  </div>

  <!-- Checklist -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">✅</div>
      <span class="section-title">Quick checklist</span>
    </div>

    <div class="checklist-item"><input type="checkbox" id="c1"><span class="checklist-text">Account is verified or has a check badge</span></div>
    <div class="checklist-item"><input type="checkbox" id="c2"><span class="checklist-text">Pinned posts present and strategic</span></div>
    <div class="checklist-item"><input type="checkbox" id="c3"><span class="checklist-text">Story highlights cover key topics (rooms, location, amenities, reviews)</span></div>
    <div class="checklist-item"><input type="checkbox" id="c4"><span class="checklist-text">Contact button or booking link accessible from profile</span></div>
    <div class="checklist-item"><input type="checkbox" id="c5"><span class="checklist-text">Consistent branding visible across all posts</span></div>
    <div class="checklist-item"><input type="checkbox" id="c6"><span class="checklist-text">Location tags on posts</span></div>
    <div class="checklist-item"><input type="checkbox" id="c7"><span class="checklist-text">Posted within last 7 days</span></div>
    <div class="checklist-item"><input type="checkbox" id="c8"><span class="checklist-text">Alt text or accessibility features used</span></div>
    <div class="checklist-item"><input type="checkbox" id="c9"><span class="checklist-text">Bio includes relevant keywords for discoverability</span></div>
    <div class="checklist-item"><input type="checkbox" id="c10"><span class="checklist-text">Profile category is set correctly</span></div>

    <div class="field" style="margin-top:1rem">
      <label class="field-label">Checklist notes</label>
      <textarea id="checklist-notes" placeholder="Any other observations, red flags, or quick wins spotted here..."></textarea>
    </div>
  </div>

  <!-- Recommendations -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">💡</div>
      <span class="section-title">Recommendations</span>
    </div>

    <div class="field">
      <label class="field-label">Top 3 priorities to improve</label>
      <textarea id="priorities" placeholder="Based on your audit, what needs attention first? Think biggest impact areas."></textarea>
    </div>

    <div class="field">
      <label class="field-label">Quick wins (low effort, high impact)</label>
      <textarea id="quick-wins" placeholder="e.g. Add link in bio, reply to existing comments, add location tags, pin a top post..."></textarea>
    </div>

    <div class="field">
      <label class="field-label">Longer-term recommendations</label>
      <textarea id="longterm" placeholder="e.g. Build a Reels strategy, partner with local businesses, create branded highlight covers, establish a posting cadence..."></textarea>
    </div>

    <div class="field">
      <label class="field-label">Overall assessment</label>
      <textarea id="overall" placeholder="1–2 sentence summary of where the account stands and what the focus should be..."></textarea>
    </div>
  </div>

  <!-- Buttons -->
  <button class="btn-primary" onclick="exportText()">
    ⬇ Download audit summary (.txt)
  </button>
  <button class="btn-secondary" onclick="window.print()">
    🖨 Print / save as PDF
  </button>

</div>

<script>
const scores = {};

// Rating buttons
document.querySelectorAll('.rating-btns').forEach(group => {
  const key = group.dataset.key;
  group.querySelectorAll('.rbtn').forEach(btn => {
    btn.addEventListener('click', () => {
      group.querySelectorAll('.rbtn').forEach(b => b.className = 'rbtn');
      const val = parseInt(btn.dataset.val);
      btn.classList.add('sel-' + val);
      scores[key] = val;
      updateSummary();
    });
  });
});

function updateSummary() {
  const sectionKeys = {
    profile: ['photo','bio-q','link-q','highlights-q'],
    content: ['visual','variety','freq-q','reels-q'],
    captions: ['caption-q','hashtag-q','cta-q'],
    engagement: ['eng-level','community','ugc-q'],
    strategy: ['strategy-q','local-q','collab-q']
  };

  let sectionsComplete = 0;
  for (const keys of Object.values(sectionKeys)) {
    if (keys.every(k => scores[k])) sectionsComplete++;
  }
  document.getElementById('sections-done').textContent = sectionsComplete + ' / 5';

  const vals = Object.values(scores);
  if (vals.length === 0) return;

  const total = vals.reduce((a, b) => a + b, 0);
  const max = vals.length * 3;
  const pct = Math.round((total / max) * 100);

  document.getElementById('total-score').textContent = pct + '%';
  const fill = document.getElementById('score-fill');
  fill.style.width = pct + '%';
  fill.style.background = pct >= 70 ? '#166534' : pct >= 45 ? '#b45309' : '#b91c1c';

  let grade = '—';
  if (vals.length >= 5) {
    if (pct >= 80) grade = 'A';
    else if (pct >= 65) grade = 'B';
    else if (pct >= 50) grade = 'C';
    else grade = 'D';
  }
  document.getElementById('grade').textContent = grade;

  const tags = [];
  if (scores['photo'] === 1 || scores['bio-q'] === 1) tags.push({t:'Profile needs work', c:'tag-red'});
  if (scores['reels-q'] === 1) tags.push({t:'No Reels strategy', c:'tag-red'});
  if (scores['freq-q'] === 1) tags.push({t:'Posting too infrequently', c:'tag-red'});
  if (scores['community'] === 1) tags.push({t:'Not replying to comments', c:'tag-amber'});
  if (scores['hashtag-q'] === 1) tags.push({t:'Hashtag strategy weak', c:'tag-amber'});
  if (scores['cta-q'] === 1) tags.push({t:'No CTAs in captions', c:'tag-amber'});
  if (scores['local-q'] === 3) tags.push({t:'Strong local content', c:'tag-green'});
  if (scores['visual'] === 3) tags.push({t:'Great visual consistency', c:'tag-green'});
  if (scores['community'] === 3) tags.push({t:'Strong community management', c:'tag-green'});

  document.getElementById('tag-area').innerHTML = tags.map(t =>
    `<span class="tag ${t.c}">${t.t}</span>`
  ).join('');
}

function v(id) { return document.getElementById(id)?.value?.trim() || '—'; }

function exportText() {
  const client = v('client-name');
  const auditor = v('auditor-name');
  const date = v('audit-date');
  const pct = document.getElementById('total-score').textContent;
  const grade = document.getElementById('grade').textContent;
  const sections = document.getElementById('sections-done').textContent;

  const contentTypes = Array.from(document.querySelectorAll('.content-type:checked')).map(c => c.value).join(', ') || '—';

  const checklist = [
    ['c1','Verified / check badge'],
    ['c2','Pinned posts present'],
    ['c3','Story highlights set up'],
    ['c4','Contact/booking link accessible'],
    ['c5','Consistent branding'],
    ['c6','Location tags on posts'],
    ['c7','Posted within last 7 days'],
    ['c8','Alt text / accessibility'],
    ['c9','Bio keywords for discoverability'],
    ['c10','Profile category set correctly'],
  ].map(([id,label]) => `  [${document.getElementById(id).checked ? 'x' : ' '}] ${label}`).join('\n');

  const ratingLabels = {
    'photo':'Profile photo quality','bio-q':'Bio clarity & keyword use','link-q':'Link in bio / CTA',
    'highlights-q':'Story highlights','visual':'Visual consistency','variety':'Content variety',
    'freq-q':'Posting frequency','reels-q':'Reels use','caption-q':'Caption quality',
    'hashtag-q':'Hashtag strategy','cta-q':'CTAs in captions','eng-level':'Visible engagement level',
    'community':'Community management','ugc-q':'UGC & tagging','strategy-q':'Content strategy clarity',
    'local-q':'Local & seasonal relevance','collab-q':'Partnership use'
  };
  const ratingsLines = Object.entries(scores).map(([k,v]) =>
    `  ${ratingLabels[k] || k}: ${v}/3`
  ).join('\n');

  const out = `INSTAGRAM AUDIT
================================
Client: ${client}
Auditor: ${auditor}
Date: ${date}
Overall score: ${pct} (Grade: ${grade}) — ${sections} sections rated

RATINGS
${ratingsLines || '  (none recorded)'}

PROFILE
Username: ${v('username')}
Account type: ${v('acct-type')} | Category: ${v('category')}
Followers: ${v('followers')} | Following: ${v('following')} | Posts: ${v('total-posts')}
Bio: ${v('bio')}
Link in bio: ${v('link-bio')}
Story highlights: ${v('highlights-count')} — topics: ${v('highlight-topics')}

CONTENT & VISUALS
Content types seen: ${contentTypes}
Posting frequency (est.): ${v('post-freq')} per week
Reels: ${v('reels-present')}
Pinned posts: ${v('pinned')}
Grid observation: ${v('grid-obs')}

CAPTIONS & HASHTAGS
Caption length: ${v('caption-len')}
Hashtags: ${v('hashtags')}
Common hashtags: ${v('hashtag-list')}
CTAs in captions: ${v('ctas')}
Caption notes: ${v('caption-notes')}

VISIBLE ENGAGEMENT
Avg. likes/post: ${v('avg-likes')} | Avg. comments/post: ${v('avg-comments')}
Replies to comments: ${v('reply-comments')}
UGC / tagged content: ${v('ugc')}
Standout post: ${v('top-post')}
Engagement notes: ${v('eng-notes')}

STRATEGY
Pillars observed: ${v('pillars-obs')}
Local content: ${v('local-content')} | Seasonal content: ${v('seasonal')}
Partner tags: ${v('collabs')}
Promo content frequency: ${v('promo-freq')}

CHECKLIST
${checklist}
Checklist notes: ${v('checklist-notes')}

RECOMMENDATIONS
Top priorities:
${v('priorities')}

Quick wins:
${v('quick-wins')}

Longer-term:
${v('longterm')}

Overall assessment:
${v('overall')}
================================
Generated with Instagram Audit Tool
`;

  const blob = new Blob([out], {type: 'text/plain'});
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a');
  a.href = url;
  const filename = client !== '—' ? `instagram-audit-${client.toLowerCase().replace(/\s+/g,'-')}.txt` : 'instagram-audit.txt';
  a.download = filename;
  a.click();
  URL.revokeObjectURL(url);
}
</script>
</body>
</html>
