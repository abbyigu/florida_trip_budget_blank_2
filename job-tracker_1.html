<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ariel Blouin — Job Tracker 2026</title>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet"/>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'DM Sans', 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #f0f9f9 0%, #e8f4f5 40%, #f5f0ff 100%);
      min-height: 100vh;
      color: #1a1a1a;
    }
    /* HEADER */
    .header {
      background: linear-gradient(135deg, #0D7377 0%, #14a8ad 100%);
      padding: 32px 40px 28px;
      position: relative;
      overflow: hidden;
    }
    .header::before {
      content: ''; position: absolute; top: -40px; right: -40px;
      width: 200px; height: 200px; border-radius: 50%;
      background: rgba(255,255,255,0.06);
    }
    .header::after {
      content: ''; position: absolute; bottom: -60px; right: 80px;
      width: 140px; height: 140px; border-radius: 50%;
      background: rgba(255,255,255,0.04);
    }
    .header-inner { position: relative; z-index: 1; }
    .header-label { color: rgba(255,255,255,0.7); font-size: 12px; letter-spacing: 0.08em; text-transform: uppercase; margin-bottom: 4px; }
    .header h1 { color: #fff; font-size: 28px; font-weight: 700; letter-spacing: -0.5px; margin-bottom: 20px; }
    .stats-row { display: flex; gap: 12px; flex-wrap: wrap; }
    .stat-pill {
      background: rgba(255,255,255,0.15); border-radius: 10px;
      padding: 8px 16px; color: #fff; display: flex; align-items: center; gap: 8px;
    }
    .stat-pill.highlight { background: rgba(255,255,255,0.22); }
    .stat-num { font-size: 20px; font-weight: 700; }
    .stat-label { font-size: 12px; opacity: 0.85; }

    /* MAIN */
    .main { padding: 28px 40px; max-width: 1100px; margin: 0 auto; }

    /* CONTROLS */
    .controls { display: flex; gap: 12px; margin-bottom: 20px; flex-wrap: wrap; align-items: center; }
    .search-input {
      flex: 1; min-width: 200px; padding: 10px 16px; border-radius: 10px;
      border: 1.5px solid #d1e8e9; background: #fff; font-size: 14px;
      outline: none; font-family: inherit;
    }
    .sort-select {
      padding: 10px 14px; border-radius: 10px; border: 1.5px solid #d1e8e9;
      background: #fff; font-size: 14px; color: #444; outline: none; font-family: inherit; cursor: pointer;
    }
    .btn-add {
      background: #0D7377; color: #fff; border: none; border-radius: 10px;
      padding: 10px 20px; font-size: 14px; font-weight: 600; cursor: pointer;
      font-family: inherit;
    }
    .btn-add:hover { background: #0a5e62; }

    /* FILTER TABS */
    .filter-tabs { display: flex; gap: 8px; margin-bottom: 24px; flex-wrap: wrap; }
    .filter-tab {
      padding: 6px 14px; border-radius: 20px; border: 1.5px solid #e2e8f0;
      background: #fff; color: #555; font-size: 13px; cursor: pointer;
      font-family: inherit; transition: all 0.15s;
    }
    .filter-tab.active { background: #0D7377; color: #fff; border-color: #0D7377; font-weight: 600; }

    /* CARDS */
    .cards { display: flex; flex-direction: column; gap: 12px; }
    .card {
      background: #fff; border-radius: 14px; overflow: hidden;
      border: 1.5px solid #e8f0f1; box-shadow: 0 2px 8px rgba(0,0,0,0.04);
      transition: box-shadow 0.2s;
    }
    .card.expanded { box-shadow: 0 4px 24px rgba(13,115,119,0.10); }
    .card-top {
      padding: 16px 20px; display: flex; align-items: center;
      gap: 14px; cursor: pointer;
    }
    .priority-dot { width: 10px; height: 10px; border-radius: 50%; flex-shrink: 0; }
    .card-info { flex: 1; min-width: 0; }
    .card-title { display: flex; align-items: center; gap: 10px; flex-wrap: wrap; }
    .card-company { font-weight: 700; font-size: 15px; }
    .card-role { color: #444; font-size: 14px; }
    .card-meta { color: #94A3B8; font-size: 12px; margin-top: 3px; }
    .status-badge {
      border-radius: 20px; padding: 4px 12px; font-size: 12px; font-weight: 600;
      white-space: nowrap; flex-shrink: 0; border: 1px solid;
    }
    .priority-label { font-size: 12px; font-weight: 500; flex-shrink: 0; min-width: 80px; }
    .chevron { color: #ccc; font-size: 18px; transition: transform 0.2s; flex-shrink: 0; }
    .chevron.open { transform: rotate(180deg); }

    /* EXPANDED */
    .card-body {
      border-top: 1px solid #f0f4f5; padding: 16px 20px; background: #fafefe;
      display: none;
    }
    .card-body.visible { display: block; }
    .section-label {
      font-size: 11px; color: #888; text-transform: uppercase;
      letter-spacing: 0.06em; font-weight: 600; margin-bottom: 8px;
    }
    .status-buttons { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 14px; }
    .status-btn {
      padding: 5px 12px; border-radius: 16px; font-size: 12px; font-weight: 500;
      cursor: pointer; transition: all 0.15s; font-family: inherit; border: 1.5px solid #e2e8f0;
      background: #fff; color: #888;
    }
    .salary-row { display: flex; gap: 12px; margin-bottom: 14px; flex-wrap: wrap; }
    .salary-box {
      flex: 1; min-width: 150px; background: #f0f9f9; border-radius: 10px;
      padding: 10px 14px; border: 1px solid #d1e8e9;
    }
    .salary-box-label { font-size: 11px; color: #0D7377; text-transform: uppercase; letter-spacing: 0.06em; font-weight: 600; margin-bottom: 4px; }
    .salary-box-value { font-size: 14px; color: #1a1a1a; font-weight: 600; }
    .salary-box-value.empty { color: #bbb; font-weight: 400; }
    .notes-section { margin-bottom: 14px; }
    .notes-text { font-size: 14px; color: #444; line-height: 1.6; }
    .card-actions { display: flex; gap: 10px; }
    .btn-edit {
      padding: 7px 16px; border-radius: 8px; border: 1.5px solid #0D7377;
      color: #0D7377; background: #fff; font-size: 13px; cursor: pointer;
      font-weight: 500; font-family: inherit;
    }
    .btn-edit:hover { background: #f0f9f9; }
    .btn-remove {
      padding: 7px 16px; border-radius: 8px; border: 1.5px solid #fecdd3;
      color: #E11D48; background: #fff; font-size: 13px; cursor: pointer; font-family: inherit;
    }
    .btn-remove:hover { background: #fff1f2; }
    .empty-state { text-align: center; padding: 60px; color: #94A3B8; font-size: 15px; }

    /* MODAL */
    .modal-overlay {
      display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.35);
      align-items: center; justify-content: center; z-index: 100; padding: 20px;
    }
    .modal-overlay.visible { display: flex; }
    .modal {
      background: #fff; border-radius: 18px; padding: 32px;
      width: 100%; max-width: 520px; max-height: 90vh; overflow-y: auto;
      box-shadow: 0 20px 60px rgba(0,0,0,0.2);
    }
    .modal h2 { font-size: 20px; font-weight: 700; color: #1a1a1a; margin-bottom: 24px; }
    .form-group { margin-bottom: 16px; }
    .form-label {
      font-size: 12px; color: #888; text-transform: uppercase;
      letter-spacing: 0.06em; display: block; margin-bottom: 6px;
    }
    .form-input, .form-select, .form-textarea {
      width: 100%; padding: 10px 14px; border-radius: 10px;
      border: 1.5px solid #e2e8f0; font-size: 14px; color: #1a1a1a;
      outline: none; font-family: inherit;
    }
    .form-textarea { resize: vertical; }
    .form-row { display: flex; gap: 16px; margin-bottom: 16px; }
    .form-row > div { flex: 1; }
    .modal-actions { display: flex; gap: 12px; }
    .btn-save {
      flex: 1; background: #0D7377; color: #fff; border: none;
      border-radius: 10px; padding: 12px; font-size: 14px; font-weight: 600;
      cursor: pointer; font-family: inherit;
    }
    .btn-save:hover { background: #0a5e62; }
    .btn-cancel {
      padding: 12px 20px; border-radius: 10px; border: 1.5px solid #e2e8f0;
      background: #fff; font-size: 14px; color: #666; cursor: pointer; font-family: inherit;
    }
  </style>
</head>
<body>

<!-- HEADER -->
<div class="header">
  <div class="header-inner">
    <p class="header-label">Ariel Blouin · Job Search 2026</p>
    <h1>Application Tracker</h1>
    <div class="stats-row">
      <div class="stat-pill"><span class="stat-num" id="stat-total">0</span><span class="stat-label">Total</span></div>
      <div class="stat-pill"><span class="stat-num" id="stat-applied">0</span><span class="stat-label">Applied</span></div>
      <div class="stat-pill"><span class="stat-num" id="stat-interview">0</span><span class="stat-label">Interviews</span></div>
      <div class="stat-pill highlight"><span class="stat-num" id="stat-offer">0</span><span class="stat-label">Offers</span></div>
    </div>
  </div>
</div>

<!-- MAIN -->
<div class="main">
  <div class="controls">
    <input class="search-input" id="search" placeholder="Search company, role, location..." oninput="render()" />
    <select class="sort-select" id="sortBy" onchange="render()">
      <option value="date">Sort: Date</option>
      <option value="company">Sort: Company</option>
      <option value="priority">Sort: Priority</option>
    </select>
    <button class="btn-add" onclick="openAdd()">+ Add Job</button>
  </div>

  <div class="filter-tabs" id="filterTabs"></div>
  <div class="cards" id="cards"></div>
</div>

<!-- MODAL -->
<div class="modal-overlay" id="modal">
  <div class="modal">
    <h2 id="modalTitle">Add New Application</h2>
    <div class="form-group"><label class="form-label">Company *</label><input class="form-input" id="f-company" placeholder="e.g. Enso Connect" /></div>
    <div class="form-group"><label class="form-label">Role *</label><input class="form-input" id="f-role" placeholder="e.g. Customer Success Manager" /></div>
    <div class="form-group"><label class="form-label">Location</label><input class="form-input" id="f-location" placeholder="e.g. Quebec, Canada (Remote)" /></div>
    <div class="form-group"><label class="form-label">Job Posting URL</label><input class="form-input" id="f-link" placeholder="https://..." /></div>
    <div class="form-group"><label class="form-label">Posted Salary / Range</label><input class="form-input" id="f-salary" placeholder="e.g. $55K–$70K" /></div>
    <div class="form-group"><label class="form-label">My Salary Expectation</label><input class="form-input" id="f-salaryExpected" placeholder="e.g. $58,000–$65,000 CAD" /></div>
    <div class="form-row">
      <div>
        <label class="form-label">Status</label>
        <select class="form-select" id="f-status">
          <option>Wishlist</option><option selected>Applied</option><option>Interview</option>
          <option>Offer</option><option>Rejected</option><option>Withdrawn</option>
        </select>
      </div>
      <div>
        <label class="form-label">Priority</label>
        <select class="form-select" id="f-priority">
          <option value="high">⭐ Top Choice</option>
          <option value="medium" selected>✦ Interested</option>
          <option value="low">· Exploring</option>
        </select>
      </div>
    </div>
    <div class="form-group"><label class="form-label">Date Applied</label><input class="form-input" type="date" id="f-date" /></div>
    <div class="form-group"><label class="form-label">Notes</label><textarea class="form-textarea" id="f-notes" rows="3" placeholder="Why this role? Interview notes, contacts, follow-up dates..."></textarea></div>
    <div class="modal-actions">
      <button class="btn-save" onclick="saveJob()">Save</button>
      <button class="btn-cancel" onclick="closeModal()">Cancel</button>
    </div>
  </div>
</div>

<script>
  const STATUS_COLORS = {
    Wishlist:  { bg: "#F0F4FF", text: "#4A6CF7", border: "#C7D2FE" },
    Applied:   { bg: "#ECFDF5", text: "#059669", border: "#A7F3D0" },
    Interview: { bg: "#FFFBEB", text: "#D97706", border: "#FDE68A" },
    Offer:     { bg: "#F0FDF4", text: "#16A34A", border: "#86EFAC" },
    Rejected:  { bg: "#FFF1F2", text: "#E11D48", border: "#FECDD3" },
    Withdrawn: { bg: "#F8FAFC", text: "#94A3B8", border: "#E2E8F0" },
  };
  const PRIORITY = {
    high:   { label: "⭐ Top Choice", color: "#0D7377" },
    medium: { label: "✦ Interested",  color: "#D97706" },
    low:    { label: "· Exploring",   color: "#94A3B8" },
  };
  const STATUSES = ["Wishlist","Applied","Interview","Offer","Rejected","Withdrawn"];

  let jobs = JSON.parse(localStorage.getItem("ariel_jobs") || "null") || [
    { id: 1, company: "Enso Connect", role: "Bilingual Customer Success Manager", location: "Quebec, Canada (Remote)", status: "Applied", date: "2026-03-05", salary: "$55K–$70K", salaryExpected: "$58,000–$65,000 CAD", notes: "Top choice! Hospitality + SaaS + bilingual — perfect fit. Resume tailored, standout statement added.", link: "", priority: "high" },
    { id: 2, company: "Engage2Excel", role: "Program Manager", location: "Quebec, Canada (Remote)", status: "Applied", date: "2026-03-05", salary: "", salaryExpected: "$58,000–$63,000 CAD", notes: "Temp-to-permanent (6 months). Day-to-day account management, invoice accuracy, bilingual client contact. Good bridge role.", link: "", priority: "medium" },
    { id: 3, company: "Les Prétentieux", role: "Chargée de projets", location: "Lévis, QC (Hybride)", status: "Applied", date: "2026-03-05", salary: "Salaire compétitif", salaryExpected: "$58,000–$63,000 CAD", notes: "Agence marketing créative en croissance. Coordination de mandats clients — identités de marque, campagnes, vidéo, outils graphiques. OBNL, événementiel, PMEs. Vendredis après-midi libres. CV + email en français envoyés. Anglais = atout seulement.", link: "", priority: "medium" }
  ];

  let filter = "All";
  let expandedId = null;
  let editingId = null;

  function save() { localStorage.setItem("ariel_jobs", JSON.stringify(jobs)); }

  function render() {
    const search = document.getElementById("search").value.toLowerCase();
    const sortBy = document.getElementById("sortBy").value;

    // Stats
    document.getElementById("stat-total").textContent = jobs.length;
    document.getElementById("stat-applied").textContent = jobs.filter(j => j.status === "Applied").length;
    document.getElementById("stat-interview").textContent = jobs.filter(j => j.status === "Interview").length;
    document.getElementById("stat-offer").textContent = jobs.filter(j => j.status === "Offer").length;

    // Filter tabs
    const tabsEl = document.getElementById("filterTabs");
    tabsEl.innerHTML = ["All", ...STATUSES].map(s => {
      const count = s !== "All" ? jobs.filter(j => j.status === s).length : null;
      const active = filter === s;
      return `<button class="filter-tab ${active ? "active" : ""}" onclick="setFilter('${s}')">${s}${count ? ` (${count})` : ""}</button>`;
    }).join("");

    // Filter + sort
    let filtered = jobs
      .filter(j => filter === "All" || j.status === filter)
      .filter(j => !search || j.company.toLowerCase().includes(search) || j.role.toLowerCase().includes(search) || j.location.toLowerCase().includes(search));

    if (sortBy === "date") filtered.sort((a, b) => new Date(b.date) - new Date(a.date));
    else if (sortBy === "company") filtered.sort((a, b) => a.company.localeCompare(b.company));
    else if (sortBy === "priority") { const o = {high:0,medium:1,low:2}; filtered.sort((a,b) => o[a.priority] - o[b.priority]); }

    const cardsEl = document.getElementById("cards");
    if (filtered.length === 0) {
      cardsEl.innerHTML = `<div class="empty-state">No applications yet. Add your first one! ✨</div>`;
      return;
    }

    cardsEl.innerHTML = filtered.map(job => {
      const sc = STATUS_COLORS[job.status] || STATUS_COLORS.Applied;
      const pc = PRIORITY[job.priority] || PRIORITY.medium;
      const expanded = expandedId === job.id;

      const statusBtns = STATUSES.map(s => {
        const c = STATUS_COLORS[s];
        const active = job.status === s;
        const style = active
          ? `background:${c.bg};color:${c.text};border-color:${c.border};`
          : "";
        return `<button class="status-btn" style="${style}" onclick="updateStatus(${job.id},'${s}')">${s}</button>`;
      }).join("");

      return `
        <div class="card ${expanded ? "expanded" : ""}" id="card-${job.id}">
          <div class="card-top" onclick="toggleExpand(${job.id})">
            <div class="priority-dot" style="background:${pc.color}"></div>
            <div class="card-info">
              <div class="card-title">
                <span class="card-company">${job.company}</span>
                <span style="color:#666">·</span>
                <span class="card-role">${job.role}</span>
              </div>
              <div class="card-meta">${job.location}${job.salary ? " · " + job.salary : ""} · Applied ${job.date}</div>
            </div>
            <div class="status-badge" style="background:${sc.bg};color:${sc.text};border-color:${sc.border}">${job.status}</div>
            <div class="priority-label" style="color:${pc.color}">${pc.label}</div>
            <div class="chevron ${expanded ? "open" : ""}">▾</div>
          </div>
          <div class="card-body ${expanded ? "visible" : ""}">
            <div class="section-label">Update Status</div>
            <div class="status-buttons">${statusBtns}</div>
            <div class="salary-row">
              <div class="salary-box">
                <div class="salary-box-label">Posted Salary</div>
                <div class="salary-box-value ${job.salary ? "" : "empty"}">${job.salary || "Not listed"}</div>
              </div>
              <div class="salary-box">
                <div class="salary-box-label">My Expectation</div>
                <div class="salary-box-value ${job.salaryExpected ? "" : "empty"}">${job.salaryExpected || "Not set"}</div>
              </div>
            </div>
            ${job.notes ? `<div class="notes-section"><div class="section-label">Notes</div><div class="notes-text">${job.notes}</div></div>` : ""}
            ${job.link ? `<div style="margin-bottom:14px"><a href="${job.link}" target="_blank" style="color:#0D7377;font-size:13px">🔗 View Job Posting</a></div>` : ""}
            <div class="card-actions">
              <button class="btn-edit" onclick="openEdit(${job.id})">Edit</button>
              <button class="btn-remove" onclick="removeJob(${job.id})">Remove</button>
            </div>
          </div>
        </div>`;
    }).join("");
  }

  function setFilter(f) { filter = f; render(); }
  function toggleExpand(id) { expandedId = expandedId === id ? null : id; render(); }
  function updateStatus(id, status) { jobs = jobs.map(j => j.id === id ? {...j, status} : j); save(); render(); }
  function removeJob(id) { if (confirm("Remove this application?")) { jobs = jobs.filter(j => j.id !== id); save(); render(); } }

  function openAdd() {
    editingId = null;
    document.getElementById("modalTitle").textContent = "Add New Application";
    ["company","role","location","link","salary","salaryExpected","notes"].forEach(k => document.getElementById("f-"+k).value = "");
    document.getElementById("f-status").value = "Applied";
    document.getElementById("f-priority").value = "medium";
    document.getElementById("f-date").value = new Date().toISOString().slice(0,10);
    document.getElementById("modal").classList.add("visible");
  }

  function openEdit(id) {
    const job = jobs.find(j => j.id === id);
    editingId = id;
    document.getElementById("modalTitle").textContent = "Edit Application";
    ["company","role","location","link","salary","salaryExpected","notes","status","priority","date"].forEach(k => {
      document.getElementById("f-"+k).value = job[k] || "";
    });
    document.getElementById("modal").classList.add("visible");
  }

  function closeModal() { document.getElementById("modal").classList.remove("visible"); }

  function saveJob() {
    const company = document.getElementById("f-company").value.trim();
    const role = document.getElementById("f-role").value.trim();
    if (!company || !role) { alert("Company and Role are required."); return; }
    const job = {
      company, role,
      location: document.getElementById("f-location").value,
      link: document.getElementById("f-link").value,
      salary: document.getElementById("f-salary").value,
      salaryExpected: document.getElementById("f-salaryExpected").value,
      notes: document.getElementById("f-notes").value,
      status: document.getElementById("f-status").value,
      priority: document.getElementById("f-priority").value,
      date: document.getElementById("f-date").value,
    };
    if (editingId) {
      jobs = jobs.map(j => j.id === editingId ? {...job, id: editingId} : j);
    } else {
      jobs = [...jobs, {...job, id: Date.now()}];
    }
    save(); closeModal(); render();
  }

  render();
</script>
</body>
</html>
