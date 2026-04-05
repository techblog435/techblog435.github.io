---
layout: page
title: Articles
icon: fas fa-newspaper
order: 1
---

<style>
  .section-header {
    margin-bottom: 32px;
  }
  .section-header h2 {
    font-size: 1.7rem;
    font-weight: 700;
    color: #f0f0f0;
    margin-bottom: 6px;
  }
  .section-header p {
    font-size: 0.95rem;
    color: #9ca3af;
  }

  .cards-list {
    display: flex;
    flex-direction: column;
    gap: 18px;
    max-width: 860px;
  }

  .article-card {
    display: flex;
    background: #1e2535;
    border-radius: 16px;
    overflow: hidden;
    box-shadow: 0 2px 12px rgba(0, 0, 0, 0.3);
    transition: transform 0.22s ease, box-shadow 0.22s ease;
  }
  .article-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 28px rgba(0, 0, 0, 0.4);
  }

  .card-thumb {
    width: 200px;
    min-width: 200px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .card-thumb img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: transform 0.35s ease;
  }
  .article-card:hover .card-thumb img {
    transform: scale(1.05);
  }

  .card-body {
    padding: 20px 24px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    flex: 1;
  }

  .card-meta-top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 10px;
  }
  .badge {
    font-size: 0.75rem;
    font-weight: 600;
    padding: 4px 12px;
    border-radius: 999px;
    background: #2a3550;
    color: #c9aa71;
    letter-spacing: 0.02em;
  }
  .card-date {
    font-size: 0.8rem;
    color: #9ca3af;
  }

  .card-title {
    font-size: 1.05rem;
    font-weight: 700;
    color: #f0f0f0;
    margin-bottom: 8px;
    line-height: 1.4;
  }

  .card-excerpt {
    font-size: 0.875rem;
    color: #9ca3af;
    line-height: 1.6;
    margin-bottom: 16px;
  }

  .card-meta-bottom {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .read-time {
    font-size: 0.8rem;
    color: #9ca3af;
  }
  .btn-read {
    font-size: 0.82rem;
    font-weight: 600;
    padding: 7px 18px;
    border-radius: 10px;
    border: none;
    background: #2a3550;
    color: #c9aa71;
    cursor: pointer;
    transition: background 0.18s, color 0.18s;
    text-decoration: none;
  }
  .btn-read:hover {
    background: #c9aa71;
    color: #0f1629;
  }

  @media (max-width: 600px) {
    .article-card { flex-direction: column; }
    .card-thumb { width: 100%; min-width: unset; height: 180px; }
  }
</style>

<div class="section-header">
  <h2>Latest Practice Articles</h2>
  <p>Simple notes from my weekly learning and university lab tasks.</p>
</div>

<div class="cards-list">

  <div class="article-card">
    <div class="card-thumb">
      <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=400&q=80" alt="Lab Project"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Lab Project</span>
          <span class="card-date">20 Mar 2026</span>
        </div>
        <div class="card-title">Building My First Lab Website</div>
        <div class="card-excerpt">My first complete website submission using HTML, CSS, and a little JavaScript with responsive design.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">6 min read</span>
        <a href="/posts/my-first-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="https://images.unsplash.com/photo-1507721999472-8ed4421c4af2?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">CSS Practice</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">What I Learned from CSS Layout Practice</div>
        <div class="card-excerpt">A simple note on using Flexbox and spacing rules to make beginner websites look cleaner and easier to read.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-second-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?w=400&q=80" alt="JavaScript"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">JavaScript</span>
          <span class="card-date">01 Apr 2026</span>
        </div>
        <div class="card-title">My First JavaScript DOM Exercise</div>
        <div class="card-excerpt">Notes from practicing DOM manipulation — changing text, hiding elements, and responding to button clicks.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">5 min read</span>
        <a href="#" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

</div>
