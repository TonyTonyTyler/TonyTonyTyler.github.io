<style>
  .nav-bar { display:flex; flex-wrap:wrap; align-items:center; gap:16px; padding:12px 0; }
  .nav-links { display:flex; gap:16px; align-items:center; }
  .nav-dropdown { position:relative; }
  .nav-menu { display:none; position:absolute; top:28px; left:0; background:#fff; border:1px solid #e5e7eb; border-radius:8px; padding:8px 12px; min-width:200px; box-shadow:0 8px 18px rgba(0,0,0,0.08); }
  .nav-dropdown:hover .nav-menu { display:block; }
</style>
<nav class="nav-bar">
  <div class="nav-links">
    <a href="/" style="text-decoration:none;">Home</a>
    <div class="nav-dropdown">
      <span style="cursor:pointer;">Projects ▾</span>
      <div class="nav-menu">
        <div><a href="/projects" style="text-decoration:none; display:block; padding:4px 0;">All Projects</a></div>
        <div><a href="/projects/materials-research" style="text-decoration:none; display:block; padding:4px 0;">Materials Research</a></div>
        <div><a href="/projects/thermal-system" style="text-decoration:none; display:block; padding:4px 0;">Thermal System Design</a></div>
        <div><a href="/projects/mechatronics-build" style="text-decoration:none; display:block; padding:4px 0;">Mechatronics Build</a></div>
      </div>
    </div>
    <a href="/about" style="text-decoration:none;">About</a>
  </div>
</nav>

---

# Projects

Browse a selection of engineering work. Each project card links to a dedicated page with more detail.

<div style="display:grid; gap:24px; grid-template-columns:repeat(auto-fit, minmax(260px, 1fr));">
  <div style="border:1px solid #e5e7eb; border-radius:12px; overflow:hidden; background:#fff; box-shadow:0 2px 6px rgba(0,0,0,0.05);">
    <a href="/projects/materials-research" style="text-decoration:none; color:inherit; display:block;">
      <img src="/images/materials-thumb.jpg" alt="Materials research thumbnail" style="width:100%; height:190px; object-fit:cover;">
      <div style="padding:16px;">
        <h3 style="margin-top:0;">Materials Research (Navy-Funded)</h3>
        <p>Lab-based testing and data analysis supporting advanced materials research.</p>
        <p style="margin-bottom:0; color:#2563eb;">View project details →</p>
      </div>
    </a>
  </div>

  <div style="border:1px solid #e5e7eb; border-radius:12px; overflow:hidden; background:#fff; box-shadow:0 2px 6px rgba(0,0,0,0.05);">
    <a href="/projects/thermal-system" style="text-decoration:none; color:inherit; display:block;">
      <img src="/images/thermal-thumb.jpg" alt="Thermal system thumbnail" style="width:100%; height:190px; object-fit:cover;">
      <div style="padding:16px;">
        <h3 style="margin-top:0;">Thermal System Design</h3>
        <p>Simulation-driven design for performance and integration requirements.</p>
        <p style="margin-bottom:0; color:#2563eb;">View project details →</p>
      </div>
    </a>
  </div>

  <div style="border:1px solid #e5e7eb; border-radius:12px; overflow:hidden; background:#fff; box-shadow:0 2px 6px rgba(0,0,0,0.05);">
    <a href="/projects/mechatronics-build" style="text-decoration:none; color:inherit; display:block;">
      <img src="/images/placeholder-project.svg" alt="Mechatronics project placeholder thumbnail" style="width:100%; height:190px; object-fit:cover; background:#f8fafc;">
      <div style="padding:16px;">
        <h3 style="margin-top:0;">Mechatronics Build</h3>
        <p>Prototype integrating mechanical, electrical, and control systems.</p>
        <p style="margin-bottom:0; color:#2563eb;">View project details →</p>
      </div>
    </a>
  </div>
</div>
