
<h2 class="sr-only">Freelance Agency CRM — manage contacts, deals, tasks, notes, outreach, and finances in one place.</h2>

<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: var(--font-sans); }
.crm { display: flex; height: 620px; border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); overflow: hidden; background: var(--color-background-primary); }
.sidebar { width: 200px; border-right: 0.5px solid var(--color-border-tertiary); background: var(--color-background-secondary); display: flex; flex-direction: column; flex-shrink: 0; }
.sidebar-logo { padding: 16px; font-size: 15px; font-weight: 500; border-bottom: 0.5px solid var(--color-border-tertiary); color: var(--color-text-primary); }
.sidebar-logo span { color: #1D9E75; }
.nav-item { padding: 10px 16px; font-size: 13px; cursor: pointer; color: var(--color-text-secondary); display: flex; align-items: center; gap: 8px; border-left: 2px solid transparent; transition: all 0.15s; }
.nav-item:hover { background: var(--color-background-primary); color: var(--color-text-primary); }
.nav-item.active { background: var(--color-background-primary); color: var(--color-text-primary); border-left: 2px solid #1D9E75; font-weight: 500; }
.nav-icon { font-size: 14px; width: 16px; }
.main { flex: 1; display: flex; flex-direction: column; overflow: hidden; }
.topbar { padding: 12px 20px; border-bottom: 0.5px solid var(--color-border-tertiary); display: flex; align-items: center; justify-content: space-between; flex-shrink: 0; }
.topbar h1 { font-size: 15px; font-weight: 500; color: var(--color-text-primary); }
.btn-add { background: #1D9E75; color: white; border: none; padding: 7px 14px; border-radius: var(--border-radius-md); font-size: 12px; cursor: pointer; font-weight: 500; }
.content { flex: 1; overflow-y: auto; padding: 16px 20px; }

.view { display: none; }
.view.active { display: block; }

.stat-row { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; margin-bottom: 16px; }
.stat { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 12px; }
.stat-label { font-size: 11px; color: var(--color-text-secondary); margin-bottom: 4px; text-transform: uppercase; letter-spacing: 0.04em; }
.stat-val { font-size: 20px; font-weight: 500; color: var(--color-text-primary); }
.stat-val.green { color: #1D9E75; }
.stat-val.amber { color: #BA7517; }

.section-title { font-size: 12px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 8px; margin-top: 16px; }
.section-title:first-child { margin-top: 0; }

.card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 12px 14px; margin-bottom: 8px; cursor: pointer; transition: border-color 0.15s; }
.card:hover { border-color: var(--color-border-secondary); }
.card-row { display: flex; align-items: center; justify-content: space-between; }
.card-name { font-size: 13px; font-weight: 500; color: var(--color-text-primary); }
.card-sub { font-size: 12px; color: var(--color-text-secondary); margin-top: 2px; }
.badge { font-size: 11px; padding: 2px 8px; border-radius: 99px; font-weight: 500; }
.badge.green { background: #E1F5EE; color: #0F6E56; }
.badge.amber { background: #FAEEDA; color: #854F0B; }
.badge.blue { background: #E6F1FB; color: #185FA5; }
.badge.gray { background: #F1EFE8; color: #5F5E5A; }
.badge.red { background: #FCEBEB; color: #A32D2D; }
.badge.purple { background: #EEEDFE; color: #534AB7; }
.avatar { width: 32px; height: 32px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 11px; font-weight: 500; flex-shrink: 0; }
.av-teal { background: #E1F5EE; color: #0F6E56; }
.av-blue { background: #E6F1FB; color: #185FA5; }
.av-purple { background: #EEEDFE; color: #534AB7; }
.av-amber { background: #FAEEDA; color: #854F0B; }
.av-coral { background: #FAECE7; color: #993C1D; }

.pipeline { display: flex; gap: 10px; overflow-x: auto; padding-bottom: 8px; }
.pipeline-col { min-width: 175px; flex-shrink: 0; }
.pipeline-head { font-size: 11px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.05em; padding: 6px 0; display: flex; justify-content: space-between; }
.pipeline-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 10px 12px; margin-bottom: 6px; cursor: pointer; }
.pipeline-card:hover { border-color: var(--color-border-secondary); }
.deal-name { font-size: 12px; font-weight: 500; color: var(--color-text-primary); }
.deal-client { font-size: 11px; color: var(--color-text-secondary); margin-top: 2px; }
.deal-val { font-size: 12px; font-weight: 500; color: #1D9E75; margin-top: 6px; }

.task-row { display: flex; align-items: flex-start; gap: 10px; padding: 10px 0; border-bottom: 0.5px solid var(--color-border-tertiary); }
.task-row:last-child { border-bottom: none; }
.checkbox { width: 16px; height: 16px; border: 1.5px solid var(--color-border-secondary); border-radius: 4px; cursor: pointer; flex-shrink: 0; margin-top: 1px; display: flex; align-items: center; justify-content: center; font-size: 10px; }
.checkbox.done { background: #1D9E75; border-color: #1D9E75; color: white; }
.task-text { font-size: 13px; color: var(--color-text-primary); flex: 1; }
.task-text.done { text-decoration: line-through; color: var(--color-text-secondary); }
.task-due { font-size: 11px; color: var(--color-text-secondary); flex-shrink: 0; }
.task-due.overdue { color: #A32D2D; }

.note { border-left: 2px solid #1D9E75; padding: 8px 12px; margin-bottom: 8px; background: var(--color-background-secondary); border-radius: 0 var(--border-radius-md) var(--border-radius-md) 0; }
.note-text { font-size: 13px; color: var(--color-text-primary); }
.note-meta { font-size: 11px; color: var(--color-text-secondary); margin-top: 4px; }

.outreach-row { display: flex; align-items: center; gap: 12px; padding: 10px 0; border-bottom: 0.5px solid var(--color-border-tertiary); }
.outreach-row:last-child { border-bottom: none; }
.or-name { font-size: 13px; font-weight: 500; color: var(--color-text-primary); flex: 1; }
.or-sub { font-size: 11px; color: var(--color-text-secondary); }
.or-action { font-size: 12px; padding: 4px 10px; border-radius: var(--border-radius-md); background: var(--color-background-secondary); border: 0.5px solid var(--color-border-secondary); cursor: pointer; color: var(--color-text-secondary); }
.or-action:hover { color: var(--color-text-primary); }

.money-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 16px; }
.money-card { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); padding: 14px; }
.money-label { font-size: 11px; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.04em; margin-bottom: 6px; }
.money-val { font-size: 22px; font-weight: 500; }
.invoice-row { display: flex; align-items: center; justify-content: space-between; padding: 8px 0; border-bottom: 0.5px solid var(--color-border-tertiary); font-size: 13px; }
.invoice-row:last-child { border-bottom: none; }
.invoice-client { color: var(--color-text-primary); font-weight: 500; }
.invoice-detail { color: var(--color-text-secondary); font-size: 11px; margin-top: 2px; }
</style>

<div class="crm">
  <div class="sidebar">
    <div class="sidebar-logo">Agency<span>CRM</span></div>
    <nav id="nav">
      <div class="nav-item active" data-view="dashboard"><span class="nav-icon">◈</span> Dashboard</div>
      <div class="nav-item" data-view="contacts"><span class="nav-icon">◉</span> Contacts</div>
      <div class="nav-item" data-view="pipeline"><span class="nav-icon">▤</span> Pipeline</div>
      <div class="nav-item" data-view="tasks"><span class="nav-icon">✓</span> Tasks</div>
      <div class="nav-item" data-view="notes"><span class="nav-icon">◧</span> Notes</div>
      <div class="nav-item" data-view="outreach"><span class="nav-icon">◎</span> Cold Outreach</div>
      <div class="nav-item" data-view="money"><span class="nav-icon">$</span> Money</div>
    </nav>
  </div>

  <div class="main">
    <div class="topbar">
      <h1 id="topbar-title">Dashboard</h1>
      <button class="btn-add" id="add-btn">+ Add</button>
    </div>
    <div class="content">

      <div class="view active" id="view-dashboard">
        <div class="stat-row">
          <div class="stat"><div class="stat-label">Total Clients</div><div class="stat-val">12</div></div>
          <div class="stat"><div class="stat-label">Open Deals</div><div class="stat-val amber">5</div></div>
          <div class="stat"><div class="stat-label">Revenue (MTD)</div><div class="stat-val green">$8,400</div></div>
          <div class="stat"><div class="stat-label">Tasks Due</div><div class="stat-val">3</div></div>
        </div>
        <div class="section-title">Recent activity</div>
        <div class="card"><div class="card-row"><span class="card-name">Sent proposal — Brimstone Agency</span><span class="badge blue">Deal</span></div><div class="card-sub">Today, 10:42am</div></div>
        <div class="card"><div class="card-row"><span class="card-name">Invoice paid — Lumex Studios</span><span class="badge green">Paid</span></div><div class="card-sub">Yesterday</div></div>
        <div class="card"><div class="card-row"><span class="card-name">Follow-up call — Zara Osei</span><span class="badge amber">Task</span></div><div class="card-sub">Yesterday</div></div>
        <div class="card"><div class="card-row"><span class="card-name">New lead — Petra Holdings</span><span class="badge purple">Outreach</span></div><div class="card-sub">2 days ago</div></div>
        <div class="section-title">Tasks due today</div>
        <div class="card">
          <div class="task-row" style="padding:0;border:none;"><div class="checkbox done">✓</div><div><div class="task-text done">Send revised deck to Brimstone</div></div><div class="task-due">Today</div></div>
        </div>
        <div class="card">
          <div class="task-row" style="padding:0;border:none;"><div class="checkbox"></div><div><div class="task-text">Follow up with Petra Holdings</div></div><div class="task-due overdue">Overdue</div></div>
        </div>
      </div>

      <div class="view" id="view-contacts">
        <div id="contacts-list">
          <div class="section-title">All contacts</div>
          <div class="card" onclick="openContact('Zara Osei','Lumex Studios','zara@lumex.com','+234 803 111 2233','Active Client')">
            <div class="card-row"><div style="display:flex;align-items:center;gap:10px;"><div class="avatar av-teal">ZO</div><div><div class="card-name">Zara Osei</div><div class="card-sub">Lumex Studios · zara@lumex.com</div></div></div><span class="badge green">Active</span></div>
          </div>
          <div class="card" onclick="openContact('Kofi Mensah','Brimstone Agency','kofi@brimstone.io','+233 244 567 890','In Negotiation')">
            <div class="card-row"><div style="display:flex;align-items:center;gap:10px;"><div class="avatar av-amber">KM</div><div><div class="card-name">Kofi Mensah</div><div class="card-sub">Brimstone Agency · kofi@brimstone.io</div></div></div><span class="badge amber">Negotiating</span></div>
          </div>
          <div class="card" onclick="openContact('Ada Nwosu','Petra Holdings','ada@petra.com','+234 701 445 6789','Lead')">
            <div class="card-row"><div style="display:flex;align-items:center;gap:10px;"><div class="avatar av-blue">AN</div><div><div class="card-name">Ada Nwosu</div><div class="card-sub">Petra Holdings · ada@petra.com</div></div></div><span class="badge blue">Lead</span></div>
          </div>
          <div class="card" onclick="openContact('James Olu','Vortex Media','james@vortex.ng','+234 802 334 5566','Past Client')">
            <div class="card-row"><div style="display:flex;align-items:center;gap:10px;"><div class="avatar av-purple">JO</div><div><div class="card-name">James Olu</div><div class="card-sub">Vortex Media · james@vortex.ng</div></div></div><span class="badge gray">Past</span></div>
          </div>
          <div class="card" onclick="openContact('Chidi Eze','Apex Digital','chidi@apex.com','+234 805 222 1100','Active Client')">
            <div class="card-row"><div style="display:flex;align-items:center;gap:10px;"><div class="avatar av-coral">CE</div><div><div class="card-name">Chidi Eze</div><div class="card-sub">Apex Digital · chidi@apex.com</div></div></div><span class="badge green">Active</span></div>
          </div>
        </div>
        <div id="contact-detail" style="display:none;">
          <div style="display:flex;align-items:center;gap:10px;margin-bottom:14px;cursor:pointer;" onclick="closeContact()"><span style="font-size:13px;color:var(--color-text-secondary);">← Back</span></div>
          <div class="card" style="margin-bottom:12px;">
            <div style="display:flex;align-items:center;gap:12px;margin-bottom:12px;">
              <div class="avatar av-teal" id="det-av" style="width:44px;height:44px;font-size:14px;"></div>
              <div><div class="card-name" id="det-name" style="font-size:15px;"></div><div class="card-sub" id="det-co"></div></div>
            </div>
            <div style="border-top:0.5px solid var(--color-border-tertiary);padding-top:10px;">
              <div style="display:flex;justify-content:space-between;padding:5px 0;font-size:13px;"><span style="color:var(--color-text-secondary);">Email</span><span id="det-email" style="color:var(--color-text-primary);"></span></div>
              <div style="display:flex;justify-content:space-between;padding:5px 0;font-size:13px;"><span style="color:var(--color-text-secondary);">Phone</span><span id="det-phone" style="color:var(--color-text-primary);"></span></div>
              <div style="display:flex;justify-content:space-between;padding:5px 0;font-size:13px;"><span style="color:var(--color-text-secondary);">Status</span><span id="det-status" class="badge green"></span></div>
            </div>
          </div>
          <div class="section-title">Notes</div>
          <div class="note"><div class="note-text">Interested in brand refresh + social content package. Budget ~$3k.</div><div class="note-meta">Added Apr 25</div></div>
          <div class="section-title">Activity</div>
          <div class="card-sub" style="font-size:12px;color:var(--color-text-secondary);padding:6px 0;">Email sent · Apr 27 · Proposal follow-up</div>
          <div class="card-sub" style="font-size:12px;color:var(--color-text-secondary);padding:6px 0;">Call · Apr 22 · Discovery call (30 min)</div>
        </div>
      </div>

      <div class="view" id="view-pipeline">
        <div class="pipeline">
          <div class="pipeline-col">
            <div class="pipeline-head"><span>Lead</span><span class="badge gray">2</span></div>
            <div class="pipeline-card"><div class="deal-name">Brand Identity</div><div class="deal-client">Petra Holdings</div><div class="deal-val">$2,500</div></div>
            <div class="pipeline-card"><div class="deal-name">Social Strategy</div><div class="deal-client">Nile Media</div><div class="deal-val">$1,200</div></div>
          </div>
          <div class="pipeline-col">
            <div class="pipeline-head"><span>Proposal</span><span class="badge blue">2</span></div>
            <div class="pipeline-card"><div class="deal-name">Web Redesign</div><div class="deal-client">Brimstone Agency</div><div class="deal-val">$5,000</div></div>
            <div class="pipeline-card"><div class="deal-name">Content Package</div><div class="deal-client">Apex Digital</div><div class="deal-val">$1,800</div></div>
          </div>
          <div class="pipeline-col">
            <div class="pipeline-head"><span>Negotiating</span><span class="badge amber">1</span></div>
            <div class="pipeline-card"><div class="deal-name">Annual Retainer</div><div class="deal-client">Lumex Studios</div><div class="deal-val">$12,000/yr</div></div>
          </div>
          <div class="pipeline-col">
            <div class="pipeline-head"><span>Won</span><span class="badge green">3</span></div>
            <div class="pipeline-card"><div class="deal-name">Logo & Brand Kit</div><div class="deal-client">Vortex Media</div><div class="deal-val">$2,200</div></div>
            <div class="pipeline-card"><div class="deal-name">Campaign Design</div><div class="deal-client">Lumex Studios</div><div class="deal-val">$3,400</div></div>
            <div class="pipeline-card"><div class="deal-name">SEO + Blog</div><div class="deal-client">Apex Digital</div><div class="deal-val">$1,800</div></div>
          </div>
          <div class="pipeline-col">
            <div class="pipeline-head"><span>Lost</span><span class="badge red">1</span></div>
            <div class="pipeline-card"><div class="deal-name">Rebrand Project</div><div class="deal-client">Kola & Sons</div><div class="deal-val">$4,000</div></div>
          </div>
        </div>
      </div>

      <div class="view" id="view-tasks">
        <div class="section-title">Overdue</div>
        <div class="task-row" onclick="toggleTask(this)"><div class="checkbox"></div><div style="flex:1"><div class="task-text">Follow up with Ada Nwosu (Petra Holdings)</div><div class="card-sub">Contact</div></div><div class="task-due overdue">Apr 27</div></div>
        <div class="section-title">Today</div>
        <div class="task-row" onclick="toggleTask(this)"><div class="checkbox done">✓</div><div style="flex:1"><div class="task-text done">Send revised proposal deck to Kofi</div><div class="card-sub">Deal</div></div><div class="task-due">Apr 29</div></div>
        <div class="task-row" onclick="toggleTask(this)"><div class="checkbox"></div><div style="flex:1"><div class="task-text">Review Lumex contract terms</div><div class="card-sub">Deal</div></div><div class="task-due">Apr 29</div></div>
        <div class="section-title">Upcoming</div>
        <div class="task-row" onclick="toggleTask(this)"><div class="checkbox"></div><div style="flex:1"><div class="task-text">Monthly invoice — Lumex Studios</div><div class="card-sub">Finance</div></div><div class="task-due">May 1</div></div>
        <div class="task-row" onclick="toggleTask(this)"><div class="checkbox"></div><div style="flex:1"><div class="task-text">Discovery call with Nile Media</div><div class="card-sub">Contact</div></div><div class="task-due">May 3</div></div>
        <div class="task-row" onclick="toggleTask(this)"><div class="checkbox"></div><div style="flex:1"><div class="task-text">Deliver final brand assets — Vortex Media</div><div class="card-sub">Deal</div></div><div class="task-due">May 5</div></div>
      </div>

      <div class="view" id="view-notes">
        <div class="section-title">All notes</div>
        <div class="note"><div style="display:flex;justify-content:space-between;margin-bottom:4px;"><span style="font-size:12px;font-weight:500;color:var(--color-text-primary);">Lumex Studios — Retainer call</span><span class="badge green">Active</span></div><div class="note-text">Zara wants to lock in 6-month retainer covering social content, strategy, monthly report. She's okay with $1,000/mo but wants a deliverables list first.</div><div class="note-meta">Apr 26 · Call</div></div>
        <div class="note"><div style="display:flex;justify-content:space-between;margin-bottom:4px;"><span style="font-size:12px;font-weight:500;color:var(--color-text-primary);">Brimstone — Proposal feedback</span><span class="badge amber">Negotiating</span></div><div class="note-text">Kofi liked the design approach but wants to reduce scope by removing the mobile prototype. Quoted revised price: $3,800. Awaiting sign-off.</div><div class="note-meta">Apr 25 · Email</div></div>
        <div class="note"><div style="display:flex;justify-content:space-between;margin-bottom:4px;"><span style="font-size:12px;font-weight:500;color:var(--color-text-primary);">Petra Holdings — Intro call</span><span class="badge blue">Lead</span></div><div class="note-text">Ada reached out via referral from James. Early stage — needs brand strategy + website. Budget not confirmed yet. Follow up end of week.</div><div class="note-meta">Apr 24 · Call</div></div>
        <div class="note"><div style="display:flex;justify-content:space-between;margin-bottom:4px;"><span style="font-size:12px;font-weight:500;color:var(--color-text-primary);">Apex Digital — Kick-off</span><span class="badge green">Active</span></div><div class="note-text">Chidi wants weekly check-ins. First deliverable due May 10. Content calendar to be shared by May 2.</div><div class="note-meta">Apr 22 · Meeting</div></div>
      </div>

      <div class="view" id="view-outreach">
        <div class="stat-row" style="grid-template-columns:repeat(3,1fr);">
          <div class="stat"><div class="stat-label">Leads Contacted</div><div class="stat-val">24</div></div>
          <div class="stat"><div class="stat-label">Replied</div><div class="stat-val green">9</div></div>
          <div class="stat"><div class="stat-label">Converted</div><div class="stat-val amber">3</div></div>
        </div>
        <div class="section-title">Active outreach</div>
        <div class="outreach-row"><div class="avatar av-blue" style="flex-shrink:0;">BN</div><div style="flex:1;"><div class="or-name">Bright Nwofor</div><div class="or-sub">CEO · Clearpath Consulting · LinkedIn</div></div><span class="badge amber">Followed up</span><button class="or-action" onclick="sendPrompt('Draft a second follow-up cold outreach message to Bright Nwofor at Clearpath Consulting')">Draft msg ↗</button></div>
        <div class="outreach-row"><div class="avatar av-coral" style="flex-shrink:0;">SO</div><div style="flex:1;"><div class="or-name">Sade Owolabi</div><div class="or-sub">Marketing Dir · Orbis Group · Email</div></div><span class="badge blue">Sent</span><button class="or-action" onclick="sendPrompt('Draft a follow-up cold outreach email to Sade Owolabi, Marketing Director at Orbis Group')">Draft msg ↗</button></div>
        <div class="outreach-row"><div class="avatar av-teal" style="flex-shrink:0;">EI</div><div style="flex:1;"><div class="or-name">Emeka Ibeh</div><div class="or-sub">Founder · IronLeaf Tech · Email</div></div><span class="badge green">Replied</span><button class="or-action" onclick="sendPrompt('Help me craft a response to a cold outreach reply from Emeka Ibeh at IronLeaf Tech who is interested in our services')">Reply ↗</button></div>
        <div class="outreach-row"><div class="avatar av-purple" style="flex-shrink:0;">TA</div><div style="flex:1;"><div class="or-name">Temi Adeyemi</div><div class="or-sub">Brand Mgr · Solis Foods · Instagram DM</div></div><span class="badge gray">No reply</span><button class="or-action" onclick="sendPrompt('Draft a cold outreach DM to Temi Adeyemi, Brand Manager at Solis Foods, about our agency services')">Draft msg ↗</button></div>
        <div class="section-title">Templates</div>
        <div class="card" onclick="sendPrompt('Write a cold outreach email template for a freelance agency targeting Nigerian startups')"><div class="card-row"><div class="card-name">Cold email — Startup founders ↗</div></div><div class="card-sub">Click to generate with AI</div></div>
        <div class="card" onclick="sendPrompt('Write a LinkedIn cold outreach message template for a creative agency targeting marketing directors')"><div class="card-row"><div class="card-name">LinkedIn DM — Marketing leads ↗</div></div><div class="card-sub">Click to generate with AI</div></div>
      </div>

      <div class="view" id="view-money">
        <div class="money-grid">
          <div class="money-card"><div class="money-label">Revenue (Apr)</div><div class="money-val" style="color:#1D9E75;">$8,400</div></div>
          <div class="money-card"><div class="money-label">Outstanding</div><div class="money-val" style="color:#BA7517;">$3,200</div></div>
          <div class="money-card"><div class="money-label">Expenses (Apr)</div><div class="money-val" style="color:#A32D2D;">$1,100</div></div>
          <div class="money-card"><div class="money-label">Profit (Apr)</div><div class="money-val" style="color:#1D9E75;">$7,300</div></div>
        </div>
        <div class="section-title">Invoices</div>
        <div class="invoice-row"><div><div class="invoice-client">Lumex Studios</div><div class="invoice-detail">INV-014 · Apr 1 · Content package</div></div><div style="text-align:right;"><div style="font-weight:500;color:var(--color-text-primary);">$2,800</div><span class="badge green">Paid</span></div></div>
        <div class="invoice-row"><div><div class="invoice-client">Apex Digital</div><div class="invoice-detail">INV-015 · Apr 10 · SEO + Blog</div></div><div style="text-align:right;"><div style="font-weight:500;color:var(--color-text-primary);">$1,800</div><span class="badge green">Paid</span></div></div>
        <div class="invoice-row"><div><div class="invoice-client">Vortex Media</div><div class="invoice-detail">INV-016 · Apr 15 · Logo & Brand Kit</div></div><div style="text-align:right;"><div style="font-weight:500;color:var(--color-text-primary);">$2,200</div><span class="badge green">Paid</span></div></div>
        <div class="invoice-row"><div><div class="invoice-client">Brimstone Agency</div><div class="invoice-detail">INV-017 · Apr 20 · Web Redesign deposit</div></div><div style="text-align:right;"><div style="font-weight:500;color:var(--color-text-primary);">$2,500</div><span class="badge amber">Pending</span></div></div>
        <div class="invoice-row"><div><div class="invoice-client">Petra Holdings</div><div class="invoice-detail">INV-018 · Apr 27 · Brand Strategy</div></div><div style="text-align:right;"><div style="font-weight:500;color:var(--color-text-primary);">$700</div><span class="badge red">Overdue</span></div></div>
        <div class="section-title">Expenses</div>
        <div class="invoice-row"><div><div class="invoice-client">Figma</div><div class="invoice-detail">Apr 1 · Design tool</div></div><div style="font-weight:500;color:#A32D2D;">-$45</div></div>
        <div class="invoice-row"><div><div class="invoice-client">Notion</div><div class="invoice-detail">Apr 1 · Workspace</div></div><div style="font-weight:500;color:#A32D2D;">-$16</div></div>
        <div class="invoice-row"><div><div class="invoice-client">Contractor — Copy</div><div class="invoice-detail">Apr 18 · Freelance help</div></div><div style="font-weight:500;color:#A32D2D;">-$400</div></div>
        <div class="invoice-row"><div><div class="invoice-client">Stock assets</div><div class="invoice-detail">Apr 22 · Client project</div></div><div style="font-weight:500;color:#A32D2D;">-$79</div></div>
      </div>

    </div>
  </div>
</div>

<script>
const views = ['dashboard','contacts','pipeline','tasks','notes','outreach','money'];
const titles = {dashboard:'Dashboard',contacts:'Contacts',pipeline:'Deal Pipeline',tasks:'Tasks',notes:'Notes',outreach:'Cold Outreach',money:'Money'};
const addLabels = {dashboard:'+ Add',contacts:'+ Contact',pipeline:'+ Deal',tasks:'+ Task',notes:'+ Note',outreach:'+ Lead',money:'+ Invoice'};

document.getElementById('nav').addEventListener('click', e => {
  const item = e.target.closest('.nav-item');
  if (!item) return;
  const view = item.dataset.view;
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
  item.classList.add('active');
  document.querySelectorAll('.view').forEach(v => v.classList.remove('active'));
  document.getElementById('view-' + view).classList.add('active');
  document.getElementById('topbar-title').textContent = titles[view];
  document.getElementById('add-btn').textContent = addLabels[view];
  closeContact();
});

function openContact(name, co, email, phone, status) {
  document.getElementById('contacts-list').style.display = 'none';
  document.getElementById('contact-detail').style.display = 'block';
  const initials = name.split(' ').map(w=>w[0]).join('');
  document.getElementById('det-av').textContent = initials;
  document.getElementById('det-name').textContent = name;
  document.getElementById('det-co').textContent = co;
  document.getElementById('det-email').textContent = email;
  document.getElementById('det-phone').textContent = phone;
  const s = document.getElementById('det-status');
  s.textContent = status;
  s.className = 'badge ' + (status==='Active Client'?'green':status==='In Negotiation'?'amber':status==='Lead'?'blue':'gray');
}
function closeContact() {
  document.getElementById('contacts-list').style.display = 'block';
  document.getElementById('contact-detail').style.display = 'none';
}
function toggleTask(row) {
  const cb = row.querySelector('.checkbox');
  const txt = row.querySelector('.task-text');
  if (cb.classList.contains('done')) { cb.classList.remove('done'); cb.textContent=''; txt.classList.remove('done'); }
  else { cb.classList.add('done'); cb.textContent='✓'; txt.classList.add('done'); }
}
</script>
