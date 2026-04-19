<style>
.prof-card{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1.25rem;margin-bottom:12px}
.avatar{width:52px;height:52px;border-radius:50%;background:var(--color-background-success);display:flex;align-items:center;justify-content:center;font-weight:500;font-size:16px;color:var(--color-text-success);flex-shrink:0}
.badge{display:inline-flex;align-items:center;gap:4px;font-size:11px;font-weight:500;padding:3px 8px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);background:var(--color-background-secondary);color:var(--color-text-secondary);margin:3px 2px}
.badge.teal{background:#E1F5EE;color:#085041;border-color:#5DCAA5}
.badge.blue{background:#E6F1FB;color:#0C447C;border-color:#85B7EB}
.badge.purple{background:#EEEDFE;color:#3C3489;border-color:#AFA9EC}
.badge.gray{background:#F1EFE8;color:#444441;border-color:#B4B2A9}
.badge.green{background:#EAF3DE;color:#27500A;border-color:#97C459}
.sec-label{font-size:11px;font-weight:500;color:var(--color-text-tertiary);text-transform:uppercase;letter-spacing:.06em;margin-bottom:6px}
.divider{border:none;border-top:0.5px solid var(--color-border-tertiary);margin:12px 0}
.social-btn{display:inline-flex;align-items:center;gap:6px;font-size:12px;font-weight:500;padding:5px 12px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);background:var(--color-background-secondary);color:var(--color-text-secondary);text-decoration:none;margin-right:6px;cursor:pointer}
.social-btn:hover{background:var(--color-background-tertiary)}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.grid3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px}
.stat-card{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:.75rem 1rem}
.stat-num{font-size:18px;font-weight:500;color:var(--color-text-primary)}
.stat-lbl{font-size:12px;color:var(--color-text-secondary);margin-top:2px}
.dot{display:inline-block;width:5px;height:5px;border-radius:50%;background:var(--color-text-success);margin-right:6px;vertical-align:middle}
</style>

<h2 class="sr-only">Gamal Tolan — .NET Backend Developer profile card</h2>

<div class="prof-card">
  <div style="display:flex;align-items:center;gap:14px">
    <div class="avatar">GT</div>
    <div style="flex:1">
      <p style="margin:0;font-size:17px;font-weight:500;color:var(--color-text-primary)">Gamal Tolan</p>
      <p style="margin:2px 0 6px;font-size:13px;color:var(--color-text-secondary)"><span class="dot"></span>.NET Backend Developer · Software Engineer</p>
      <div>
        <a class="social-btn" href="https://www.linkedin.com/in/GamalTolan">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
          LinkedIn
        </a>
        <a class="social-btn" href="mailto:gamaltolan4@gmail.com">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
          Email
        </a>
      </div>
    </div>
  </div>
</div>

<div class="grid2">
  <div>
    <div class="prof-card" style="height:100%;box-sizing:border-box">
      <div class="sec-label">Core languages</div>
      <div>
        <span class="badge purple">C#</span>
        <span class="badge blue">C++</span>
        <span class="badge teal">Python</span>
      </div>
      <hr class="divider">
      <div class="sec-label">Backend (.NET)</div>
      <div>
        <span class="badge teal">ASP.NET Core MVC</span>
        <span class="badge teal">Web API</span>
        <span class="badge teal">EF Core</span>
        <span class="badge teal">LINQ</span>
        <span class="badge teal">JWT Auth</span>
        <span class="badge teal">SignalR</span>
      </div>
      <hr class="divider">
      <div class="sec-label">Database</div>
      <span class="badge blue">SQL Server</span>
      <hr class="divider">
      <div class="sec-label">Frontend</div>
      <span class="badge gray">HTML5</span>
      <span class="badge gray">CSS3</span>
      <span class="badge gray">Bootstrap</span>
    </div>
  </div>

  <div style="display:flex;flex-direction:column;gap:12px">
    <div class="prof-card">
      <div class="sec-label">Architecture & design</div>
      <div>
        <span class="badge green">SOLID</span>
        <span class="badge green">Design Patterns</span>
        <span class="badge green">Onion Arch</span>
        <span class="badge green">N-tier</span>
      </div>
    </div>
    <div class="prof-card">
      <div class="sec-label">Methodologies</div>
      <span class="badge purple">Agile / Scrum</span>
      <span class="badge purple">SDLC</span>
    </div>
    <div class="prof-card" style="flex:1">
      <div class="sec-label">About me</div>
      <ul style="margin:0;padding-left:16px;color:var(--color-text-secondary);font-size:13px;line-height:1.9">
        <li>Focused on backend with .NET</li>
        <li>Passionate about system design & problem solving</li>
        <li>Building scalable backend systems</li>
        <li>Always learning new tech</li>
      </ul>
    </div>
  </div>
</div>

<div class="prof-card" style="margin-top:0">
  <div class="sec-label">GitHub stats</div>
  <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:10px">
    <img src="https://github-readme-stats.shion.dev/api?username=GamalTolan&theme=shadow_green&hide_border=true&include_all_commits=true&count_private=true&hide_title=true" style="width:100%;border-radius:var(--border-radius-md)" alt="GitHub stats">
    <img src="https://streak-stats.demolab.com/?user=GamalTolan&theme=shadow_green&hide_border=true" style="width:100%;border-radius:var(--border-radius-md)" alt="Streak stats">
    <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=GamalTolan&theme=shadow_green&hide_border=true&layout=compact" style="width:100%;border-radius:var(--border-radius-md)" alt="Top languages">
  </div>
</div>

