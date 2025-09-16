<!-- Carte profil pour README.md — coller dans une balise HTML -->
<section class="profile-card" aria-label="Profil de Raouf Bouras">
  <div class="card">
    <div class="avatar" aria-hidden="true">
      <!-- simple avatar SVG (pas besoin d'image externe) -->
      <svg viewBox="0 0 120 120" class="avatar-svg" role="img" xmlns="http://www.w3.org/2000/svg">
        <rect width="100%" height="100%" rx="16" />
        <g transform="translate(16,14)" fill="#fff">
          <circle cx="44" cy="36" r="20"/>
          <rect x="10" y="68" width="68" height="22" rx="8"/>
        </g>
      </svg>
    </div>

    <div class="info">
      <h2>Raouf <span class="family">Bouras</span></h2>
      <p class="role">Étudiant — Collège Boréal</p>
      <ul class="meta">
        <li><strong>Numéro étudiant :</strong> 300151833</li>
        <li><strong>Statut :</strong> Étudiant actif</li>
      </ul>

      <p class="cta">Bienvenue sur mon projet — regarde le README pour les détails.</p>

      <div class="links">
        <!-- Remplace les # par des liens si tu veux -->
        <a href="#" class="btn">Projets</a>
        <a href="#" class="btn btn-outline">Contact</a>
      </div>
    </div>
  </div>

  <style>
    /* Styles encapsulés pour README (éviter de casser le reste) */
    .profile-card { font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; max-width: 760px; margin: 0.6rem auto; padding: 0.6rem; }
    .card { display: flex; gap: 16px; align-items: center; background: linear-gradient(135deg, rgba(0,0,0,0.03), rgba(0,0,0,0.01)); border-radius: 14px; padding: 16px; box-shadow: 0 6px 18px rgba(11,22,40,0.06); }
    .avatar { flex: 0 0 96px; width: 96px; height: 96px; border-radius: 12px; overflow: hidden; display: grid; place-items: center; background: linear-gradient(180deg,#6b8cff,#3aa6ff); }
    .avatar-svg { width: 78px; height: 78px; opacity: 0.95; }
    .info { flex: 1 1 auto; min-width: 0; }
    h2 { margin: 0 0 6px 0; font-size: 1.25rem; line-height: 1.1; }
    .family { font-weight: 700; color: #0b63d6; }
    .role { margin: 0 0 10px 0; color: #2e3440; font-size: 0.95rem; }
    .meta { list-style: none; padding: 0; margin: 0 0 10px 0; display: inline-block; color: #475569; font-size: 0.9rem; }
    .meta li { margin-bottom: 4px; }
    .cta { margin: 8px 0 10px 0; color:#384155; font-size:0.9rem; }
    .links { display: flex; gap: 8px; flex-wrap: wrap; }
    .btn { text-decoration: none; padding: 8px 12px; border-radius: 10px; font-size: 0.85rem; background: #0b63d6; color: #fff; box-shadow: 0 2px 6px rgba(11,99,214,0.18); }
    .btn-outline { background: transparent; color: #0b63d6; border: 1px solid rgba(11,99,214,0.16); box-shadow: none; }
    @media (max-width: 520px) {
      .card { flex-direction: row; gap: 10px; padding: 12px; }
      .avatar { width: 72px; height: 72px; }
      h2 { font-size: 1.05rem; }
    }
  </style>
</section>
