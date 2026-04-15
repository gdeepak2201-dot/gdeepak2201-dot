<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600&family=Fira+Code:wght@400;500&display=swap');
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:'Space Grotesk',sans-serif;color:var(--color-text-primary);background:transparent;}
.wrap{background:#0d1117;border-radius:14px;padding:28px;max-width:780px;margin:0 auto;border:1px solid #21262d;}
.header{display:flex;gap:18px;align-items:flex-start;margin-bottom:24px;}
.avatar{width:68px;height:68px;border-radius:50%;background:linear-gradient(135deg,#2ea043,#1f6feb);display:flex;align-items:center;justify-content:center;font-size:24px;font-weight:600;color:#fff;flex-shrink:0;font-family:'Fira Code',monospace;border:2px solid #30363d;}
.info{flex:1;}
.name{font-size:20px;font-weight:600;color:#e6edf3;letter-spacing:-.3px;}
.handle{font-size:12px;color:#8b949e;margin-top:2px;font-family:'Fira Code',monospace;}
.bio{font-size:13px;color:#c9d1d9;margin-top:6px;line-height:1.6;max-width:480px;}
.tags{display:flex;gap:6px;flex-wrap:wrap;margin-top:10px;}
.tag{font-size:10px;padding:3px 10px;border-radius:20px;font-family:'Fira Code',monospace;border:1px solid;letter-spacing:.02em;}
.tag.green{color:#3fb950;border-color:#2ea043;background:rgba(46,160,67,.1);}
.tag.blue{color:#58a6ff;border-color:#1f6feb;background:rgba(31,111,235,.1);}
.tag.orange{color:#ffa657;border-color:#d1791f;background:rgba(209,121,31,.1);}
.sec-label{font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:#8b949e;margin-bottom:12px;font-family:'Fira Code',monospace;}
.projects{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:24px;}
.proj{background:#161b22;border:1px solid #21262d;border-radius:10px;padding:14px 16px;transition:border-color .2s;}
.proj:hover{border-color:#388bfd;}
.proj-top{display:flex;align-items:center;gap:8px;margin-bottom:6px;}
.proj-icon{font-size:14px;width:26px;height:26px;border-radius:6px;display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.proj-name{font-size:13px;font-weight:500;color:#58a6ff;font-family:'Fira Code',monospace;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.proj-desc{font-size:11px;color:#8b949e;line-height:1.6;margin-bottom:10px;}
.proj-footer{display:flex;gap:10px;align-items:center;}
.lang-dot{width:9px;height:9px;border-radius:50%;flex-shrink:0;}
.lang-name{font-size:10px;color:#8b949e;}
.proj-link{margin-left:auto;font-size:10px;color:#58a6ff;text-decoration:none;font-family:'Fira Code',monospace;opacity:.7;}
.proj-link:hover{opacity:1;}
.stack-grid{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:24px;}
.stack-item{display:flex;align-items:center;gap:7px;background:#161b22;border:1px solid #21262d;border-radius:8px;padding:6px 12px;}
.stack-logo{font-size:14px;width:20px;text-align:center;}
.stack-name{font-size:12px;color:#c9d1d9;font-family:'Fira Code',monospace;}
.divider{border:none;border-top:1px solid #21262d;margin:20px 0;}
.bottom{display:grid;grid-template-columns:1fr 1fr;gap:16px;}
.stat-box{background:#161b22;border:1px solid #21262d;border-radius:8px;padding:14px;}
.stat-row{display:flex;justify-content:space-between;padding:4px 0;border-bottom:1px solid #21262d;}
.stat-row:last-child{border:none;}
.stat-k{font-size:11px;color:#8b949e;}
.stat-v{font-size:11px;color:#e6edf3;font-family:'Fira Code',monospace;}
.badge-strip{display:flex;flex-direction:column;gap:8px;}
.badge-row{display:flex;align-items:center;gap:10px;background:#161b22;border:1px solid #21262d;border-radius:8px;padding:10px 14px;}
.badge-icon{font-size:18px;width:30px;text-align:center;}
.badge-info .bl{font-size:12px;font-weight:500;color:#e6edf3;}
.badge-info .bs{font-size:10px;color:#8b949e;margin-top:1px;}
</style>

<div class="wrap">
  <div class="header">
    <div class="avatar">DG</div>
    <div class="info">
      <div class="name">Deepak G</div>
      <div class="handle">@gdeepak2201-dot</div>
      <div class="bio">Electronics & Communication Engineering student with a passion for building scalable software applications. Clean, reliable code in agile environments.</div>
      <div class="tags">
        <span class="tag green">Open to opportunities</span>
        <span class="tag blue">Java · Full Stack</span>
        <span class="tag orange">ECE Student</span>
      </div>
    </div>
  </div>

  <div class="sec-label">Pinned projects</div>
  <div class="projects">
    <div class="proj">
      <div class="proj-top">
        <div class="proj-icon" style="background:#0d419d20;">📚</div>
        <div class="proj-name">collegemanagement</div>
      </div>
      <div class="proj-desc">Full-featured college management system handling student records, faculty, departments and academic workflows.</div>
      <div class="proj-footer">
        <div class="lang-dot" style="background:#b07219;"></div>
        <span class="lang-name">Java</span>
        <a class="proj-link" href="https://github.com/gdeepak2201-dot/collegemanagement" target="_blank">↗ View</a>
      </div>
    </div>
    <div class="proj">
      <div class="proj-top">
        <div class="proj-icon" style="background:#2ea04320;">🎓</div>
        <div class="proj-name">studentmanagementjdbc</div>
      </div>
      <div class="proj-desc">Student management system built with Java and JDBC — handles enrollment, grades and database operations.</div>
      <div class="proj-footer">
        <div class="lang-dot" style="background:#b07219;"></div>
        <span class="lang-name">Java · JDBC</span>
        <a class="proj-link" href="https://github.com/gdeepak2201-dot/studentmanagementjdbc" target="_blank">↗ View</a>
      </div>
    </div>
    <div class="proj">
      <div class="proj-top">
        <div class="proj-icon" style="background:#1f6feb20;">🧾</div>
        <div class="proj-name">receipebookingsystem</div>
      </div>
      <div class="proj-desc">Receipt and booking management system — streamlines transaction records and booking confirmations.</div>
      <div class="proj-footer">
        <div class="lang-dot" style="background:#b07219;"></div>
        <span class="lang-name">Java</span>
        <a class="proj-link" href="https://github.com/gdeepak2201-dot/receipebookingsystem" target="_blank">↗ View</a>
      </div>
    </div>
    <div class="proj">
      <div class="proj-top">
        <div class="proj-icon" style="background:#d1791f20;">✈️</div>
        <div class="proj-name">flightbooking</div>
      </div>
      <div class="proj-desc">Flight booking application with seat selection, scheduling and passenger management features.</div>
      <div class="proj-footer">
        <div class="lang-dot" style="background:#b07219;"></div>
        <span class="lang-name">Java</span>
        <a class="proj-link" href="https://github.com/gdeepak2201-dot/flightbooking" target="_blank">↗ View</a>
      </div>
    </div>
    <div class="proj">
      <div class="proj-top">
        <div class="proj-icon" style="background:#8957e520;">🏨</div>
        <div class="proj-name">hotelmanagement</div>
      </div>
      <div class="proj-desc">Hotel management system covering room booking, check-in/out, billing and guest record tracking.</div>
      <div class="proj-footer">
        <div class="lang-dot" style="background:#b07219;"></div>
        <span class="lang-name">Java</span>
        <a class="proj-link" href="https://github.com/gdeepak2201-dot/hotelmanagement" target="_blank">↗ View</a>
      </div>
    </div>
    <div class="proj" style="border-style:dashed;display:flex;align-items:center;justify-content:center;flex-direction:column;gap:6px;min-height:100px;">
      <span style="font-size:22px;">+</span>
      <span style="font-size:11px;color:#8b949e;">More repos on GitHub</span>
      <a href="https://github.com/gdeepak2201-dot" target="_blank" style="font-size:10px;color:#58a6ff;font-family:'Fira Code',monospace;">View all ↗</a>
    </div>
  </div>

  <div class="sec-label">Tech stack</div>
  <div class="stack-grid">
    <div class="stack-item"><span class="stack-logo">☕</span><span class="stack-name">Java</span></div>
    <div class="stack-item"><span class="stack-logo">🗄️</span><span class="stack-name">JDBC</span></div>
    <div class="stack-item"><span class="stack-logo">🛢️</span><span class="stack-name">MySQL</span></div>
    <div class="stack-item"><span class="stack-logo">🌐</span><span class="stack-name">HTML / CSS</span></div>
    <div class="stack-item"><span class="stack-logo">⚡</span><span class="stack-name">JavaScript</span></div>
    <div class="stack-item"><span class="stack-logo">🔧</span><span class="stack-name">Git</span></div>
    <div class="stack-item"><span class="stack-logo">🐙</span><span class="stack-name">GitHub</span></div>
    <div class="stack-item"><span class="stack-logo">🧩</span><span class="stack-name">OOP</span></div>
    <div class="stack-item"><span class="stack-logo">📦</span><span class="stack-name">Maven</span></div>
    <div class="stack-item"><span class="stack-logo">🖥️</span><span class="stack-name">VS Code</span></div>
    <div class="stack-item"><span class="stack-logo">☁️</span><span class="stack-name">GitHub Pages</span></div>
  </div>

  <div class="divider"></div>

  <div class="bottom">
    <div class="stat-box">
      <div class="sec-label" style="margin-bottom:10px;">Profile stats</div>
      <div class="stat-row"><span class="stat-k">Repositories</span><span class="stat-v">5+</span></div>
      <div class="stat-row"><span class="stat-k">Primary language</span><span class="stat-v">Java</span></div>
      <div class="stat-row"><span class="stat-k">Profile</span><span class="stat-v">gdeepak2201-dot</span></div>
      <div class="stat-row"><span class="stat-k">Portfolio</span><span class="stat-v">live ✓</span></div>
      <div class="stat-row"><span class="stat-k">Status</span><span class="stat-v">Open to work</span></div>
    </div>
    <div>
      <div class="sec-label" style="margin-bottom:10px;">Highlights</div>
      <div class="badge-strip">
        <div class="badge-row">
          <div class="badge-icon">🏗️</div>
          <div class="badge-info"><div class="bl">System builder</div><div class="bs">College, hotel, flight, student systems</div></div>
        </div>
        <div class="badge-row">
          <div class="badge-icon">🗃️</div>
          <div class="badge-info"><div class="bl">Database-first</div><div class="bs">JDBC + MySQL across all projects</div></div>
        </div>
        <div class="badge-row">
          <div class="badge-icon">🚀</div>
          <div class="badge-info"><div class="bl">Portfolio deployed</div><div class="bs">GitHub Pages — live portfolio</div></div>
        </div>
      </div>
    </div>
  </div>
</div>
