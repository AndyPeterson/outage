<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Service Status — Microsoft 365 & Office Outage</title>
  <style>
    :root {
      --bg-color: #f8fafc;
      --card-bg: #ffffff;
      --text-main: #0f172a;
      --text-muted: #64748b;
      --border-color: #e2e8f0;
      --alert-red: #dc2626;
      --alert-red-bg: #fef2f2;
      --alert-amber: #d97706;
      --alert-amber-bg: #fffbeb;
      --status-green: #16a34a;
      --accent-blue: #2563eb;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-main);
      line-height: 1.6;
      padding: 2rem 1rem;
    }

    .container {
      max-width: 780px;
      margin: 0 auto;
    }

    /* Header */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 1.75rem;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }

    .brand-icon {
      width: 36px;
      height: 36px;
      background: var(--text-main);
      color: #fff;
      border-radius: 8px;
      display: grid;
      place-items: center;
      font-weight: 700;
      font-size: 1.1rem;
    }

    .brand h1 {
      font-size: 1.25rem;
      font-weight: 700;
      letter-spacing: -0.02em;
    }

    .refresh-box {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      font-size: 0.875rem;
      color: var(--text-muted);
    }

    .btn-refresh {
      background: var(--card-bg);
      border: 1px solid var(--border-color);
      color: var(--text-main);
      padding: 0.45rem 0.85rem;
      border-radius: 6px;
      font-size: 0.875rem;
      font-weight: 500;
      cursor: pointer;
      transition: all 0.15s ease;
    }

    .btn-refresh:hover {
      background: #f1f5f9;
      border-color: #cbd5e1;
    }

    /* Main Outage Banner */
    .banner {
      background: var(--alert-red);
      color: #ffffff;
      padding: 1.5rem;
      border-radius: 12px;
      margin-bottom: 1.75rem;
      box-shadow: 0 4px 12px rgba(220, 38, 38, 0.15);
      display: flex;
      align-items: flex-start;
      gap: 1rem;
    }

    .pulse-dot {
      width: 14px;
      height: 14px;
      background-color: #ffffff;
      border-radius: 50%;
      margin-top: 0.35rem;
      flex-shrink: 0;
      box-shadow: 0 0 0 0 rgba(255, 255, 255, 0.7);
      animation: pulse 1.8s infinite;
    }

    @keyframes pulse {
      0% { box-shadow: 0 0 0 0 rgba(255, 255, 255, 0.7); }
      70% { box-shadow: 0 0 0 10px rgba(255, 255, 255, 0); }
      100% { box-shadow: 0 0 0 0 rgba(255, 255, 255, 0); }
    }

    .banner-content h2 {
      font-size: 1.25rem;
      font-weight: 700;
      margin-bottom: 0.35rem;
    }

    .banner-content p {
      font-size: 0.95rem;
      opacity: 0.95;
    }

    /* Card Containers */
    .card {
      background: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 12px;
      padding: 1.5rem;
      margin-bottom: 1.75rem;
      box-shadow: 0 1px 3px rgba(0, 0, 0, 0.03);
    }

    .card-title {
      font-size: 1rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.04em;
      color: var(--text-muted);
      margin-bottom: 1rem;
    }

    /* Service List */
    .service-list {
      list-style: none;
    }

    .service-item {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0.85rem 0;
      border-bottom: 1px solid var(--border-color);
    }

    .service-item:last-child {
      border-bottom: none;
      padding-bottom: 0;
    }

    .service-item:first-child {
      padding-top: 0;
    }

    .service-name {
      font-weight: 600;
      font-size: 0.98rem;
    }

    .badge {
      font-size: 0.8rem;
      font-weight: 600;
      padding: 0.25rem 0.65rem;
      border-radius: 999px;
    }

    .badge-outage {
      background: var(--alert-red-bg);
      color: var(--alert-red);
    }

    .badge-degraded {
      background: var(--alert-amber-bg);
      color: var(--alert-amber);
    }

    /* Incident Timeline */
    .timeline {
      position: relative;
      padding-left: 1.5rem;
      border-left: 2px solid var(--border-color);
    }

    .timeline-item {
      position: relative;
      margin-bottom: 1.5rem;
    }

    .timeline-item:last-child {
      margin-bottom: 0;
    }

    .timeline-item::before {
      content: "";
      position: absolute;
      left: -1.85rem;
      top: 0.35rem;
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background: var(--accent-blue);
      border: 2px solid var(--card-bg);
    }

    .timeline-status {
      font-weight: 700;
      font-size: 0.95rem;
      margin-bottom: 0.2rem;
    }

    .timeline-time {
      font-size: 0.8rem;
      color: var(--text-muted);
      margin-bottom: 0.4rem;
    }

    .timeline-body {
      font-size: 0.92rem;
      color: #334155;
    }

    /* Footer */
    footer {
      text-align: center;
      font-size: 0.85rem;
      color: var(--text-muted);
      margin-top: 2rem;
    }

    footer a {
      color: var(--accent-blue);
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Top Header -->
    <header>
      <div class="brand">
        <div class="brand-icon">IT</div>
        <h1>System Status &amp; Alerts</h1>
      </div>
      <div class="refresh-box">
        <span id="last-checked">Updated just now</span>
        <button class="btn-refresh" onclick="manualRefresh()">↻ Refresh Now</button>
      </div>
    </header>

    <!-- Primary Outage Alert -->
    <section class="banner" role="alert">
      <div class="pulse-dot"></div>
      <div class="banner-content">
        <h2>Active Outage: Microsoft Office &amp; 365 Tools</h2>
        <p>
          Microsoft is currently experiencing a widespread service disruption affecting email, file access, and collaboration apps. 
          <strong>Please bookmark and check back on this page for live updates.</strong>
        </p>
      </div>
    </section>

    <!-- Affected Services Breakdown -->
    <section class="card">
      <h3 class="card-title">Affected Microsoft Services</h3>
      <ul class="service-list">
        <li class="service-item">
          <span class="service-name">Microsoft Outlook &amp; Exchange Online</span>
          <span class="badge badge-outage">Major Outage</span>
        </li>
        <li class="service-item">
          <span class="service-name">Microsoft 365 Web Apps (Word, Excel, PowerPoint)</span>
          <span class="badge badge-outage">Major Outage</span>
        </li>
        <li class="service-item">
          <span class="service-name">Microsoft Teams</span>
          <span class="badge badge-degraded">Degraded Performance</span>
        </li>
        <li class="service-item">
          <span class="service-name">OneDrive &amp; SharePoint Online</span>
          <span class="badge badge-degraded">Degraded Performance</span>
        </li>
        <li class="service-item">
          <span class="service-name">Microsoft 365 Copilot</span>
          <span class="badge badge-outage">Major Outage</span>
        </li>
      </ul>
    </section>

    <!-- Incident Updates Log -->
    <section class="card">
      <h3 class="card-title">Incident Updates</h3>
      <div class="timeline">
        <div class="timeline-item">
          <div class="timeline-status">Mitigation Underway</div>
          <div class="timeline-time">Today — Latest Update</div>
          <p class="timeline-body">
            Microsoft engineers have paused configuration changes and are actively repairing affected infrastructure to restore capacity. Desktop versions of Word and Excel may still work offline for local files.
          </p>
        </div>
        <div class="timeline-item">
          <div class="timeline-status">Investigating Connectivity Errors</div>
          <div class="timeline-time">Today — Initial Report</div>
          <p class="timeline-body">
            Users are reporting errors signing in, sending/receiving emails in Outlook, and loading cloud documents. Our IT team is monitoring the situation and will post updates here as soon as service stabilizes.
          </p>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <p>This page automatically checks for updates every 60 seconds. For urgent local hardware issues, contact the IT Help Desk.</p>
    </footer>
  </div>

  <script>
    let secondsAgo = 0;
    const statusLabel = document.getElementById('last-checked');

    // Update the "last checked" counter every second
    setInterval(() => {
      secondsAgo++;
      if (secondsAgo >= 60) {
        location.reload(); // Auto-reloads page every 60s to pull new edits you publish
      } else {
        statusLabel.textContent = `Checked ${secondsAgo}s ago`;
      }
    }, 1000);

    function manualRefresh() {
      statusLabel.textContent = 'Refreshing...';
      setTimeout(() => {
        location.reload();
      }, 250);
    }
  </script>

</body>
</html>