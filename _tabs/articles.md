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
      <img src="/assets/img/farewell.jpg?w=400&q=80" alt="Welcome party"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Welcome From our seniors</span>
          <span class="card-date">20 Mar 2026</span>
        </div>
        <div class="card-title">Visualizing the UET Spirit</div>
        <div class="card-excerpt">My journey of first week in which i learned different things about my life.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">6 min read</span>
        <a href="/posts/my-first-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/second.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Programming fundamentals</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">The Geometry of Victory: Engineering the Win</div>
        <div class="card-excerpt">My second week in which i learn about python programming and diff subjects and i attended a fiesta in my uet.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-second-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/third_week.png?w=400&q=80" alt="JavaScript"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Machine learning project</span>
          <span class="card-date">01 Apr 2026</span>
        </div>
        <div class="card-title">My project outputs of graphs</div>
        <div class="card-excerpt">Encoding categorical data and converting them into numerical and many more like this by which we use different libraries.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">5 min read</span>
        <a href="/posts/my-third-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/graphs.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Graphs</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">The Machine learnig outcomes of our project</div>
        <div class="card-excerpt">The bar chart ,pie chart,line and many more other charts and outputs that are given by our model.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-4-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/forest.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Random forest</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">The Machine learnig models of our project</div>
        <div class="card-excerpt">The models in machine learnig which we used for prediction and mean absolute error.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-5-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/confusion.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Confusion Matrix</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">Confusion matrix and mean absolute eror</div>
        <div class="card-excerpt">A confusion matrix is a tabular layout that visualizes the correct and incorrect predictions across actual and predicted classes.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-6-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/7.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">SQL and Database</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">Begining of 2nd semester</div>
        <div class="card-excerpt">We start our semester with a beatufil begining and the knowledge of sql and the project of sql.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-7-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/8.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Database Systems</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">Querying the Core: Structured Retrieval</div>
        <div class="card-excerpt">Structured Retrieval is a search method that finds information by querying organized, highly defined data schemas (like SQL databases or tagged metadata) rather than searching through raw, unstructured text.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-8-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>
  
  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/9.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Database Systems</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">Normalization: Eliminating the Chaos</div>
        <div class="card-excerpt">Overcoming mid-semester stress, systematically moving from 1NF to 3NF to eliminate anomalies, and drawing parallels between database normalization and preprocessing datasets for predictive models.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-9-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/10.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Database Systems</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">Relationships and Joins</div>
        <div class="card-excerpt">Hostel group study collaborations, mastering INNER, LEFT, and RIGHT SQL joins, and mapping entity-relationship interconnections across databases and machine learning workflows.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-10-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>

  <div class="article-card">
    <div class="card-thumb">
      <img src="/assets/img/11.png?w=400&q=80" alt="CSS Practice"/>
    </div>
    <div class="card-body">
      <div>
        <div class="card-meta-top">
          <span class="badge">Database Systems</span>
          <span class="card-date">25 Mar 2026</span>
        </div>
        <div class="card-title">Aggregating the Big Picture</div>
        <div class="card-excerpt">Analyzing mid-semester academic performance, mastering SQL aggregation functions, and leveraging statistical analysis to uncover overarching data trends.</div>
      </div>
      <div class="card-meta-bottom">
        <span class="read-time">4 min read</span>
        <a href="/posts/my-11-week/" class="btn-read">Read More</a>
      </div>
    </div>
  </div>


</div>
