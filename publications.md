---
layout: page
title: "Publications"
tagline : ""
use_math: true
lang: en
---

{% include JB/setup %}

{% assign posts_collate = site.categories.projects %}
{% include JB/posts_collate %}

<div class="pub-intro">
  <p>
    This page lists selected peer-reviewed publications, preprints, benchmark contributions,
    and manuscripts under review. A more complete and regularly updated list is available on
    <a href="https://scholar.google.com/citations?user=q7dQio4AAAAJ" target="_blank">Google Scholar</a>.
  </p>
</div>

---

# Peer-Reviewed Publications

<div class="pub-section">

  <div class="pub-card featured">
    <div class="pub-year">2026</div>
    <div class="pub-content">
      <div class="pub-badge nature">Nature</div>

      <h3>
        A benchmark of expert-level academic questions to assess AI capabilities
      </h3>

      <p class="pub-authors">
        Center for AI Safety, Scale AI, and HLE Contributors Consortium
        (<strong>Ariel Ghislain Kemogne Kamdoum</strong>).
      </p>

      <p class="pub-venue">
        <strong>Nature</strong> 649, 1139–1146 (2026).
      </p>

      <p class="pub-links">
        <a href="https://doi.org/10.1038/s41586-025-09962-4" target="_blank">DOI</a>
      </p>
    </div>
  </div>

  <div class="pub-card">
    <div class="pub-year">2026</div>
    <div class="pub-content">
      <div class="pub-badge journal">Journal Article</div>

      <h3>
        MOKA: a pipeline for multiomics bridged SNP-set kernel association test
      </h3>

      <p class="pub-authors">
        David Enoma, Dinghao Wang, <strong>Ariel Ghislain Kemogne Kamdoum</strong>,
        Rodrigo Ortega Polo, Quan Long, Jingni He.
      </p>

      <p class="pub-venue">
        <strong>G3: Genes | Genomes | Genetics</strong>, Volume 16, Issue 2,
        February 2026, jkaf296.
      </p>

      <p class="pub-links">
        <a href="https://doi.org/10.1093/g3journal/jkaf296" target="_blank">DOI</a>
      </p>
    </div>
  </div>

</div>

---

# Preprints and Benchmark Contributions

<div class="pub-section">

  <div class="pub-card">
    <div class="pub-year">2026</div>
    <div class="pub-content">
      <div class="pub-badge preprint">Preprint</div>

      <h3>
        COMPOSITE-Stem
      </h3>

      <p class="pub-authors">
        Waters, K., Nuzzi, L., Looram, T., Tomasiello, A.,
        <strong>Kemogne Kamdoum, A. G.</strong>, Li, B., Sileo, D.,
        Kretov, E., Fournier-Facio, F., Soloupis, G., Kassahun, H.,
        Wolff, H., Cai, J., Li, L., Roth, M., Naiya, M., Guo, N.,
        Tang, Q., Wheeler, R., Sala, S., Popov, S., Dillman, S., and Li, Y.
      </p>

      <p class="pub-venue">
        arXiv preprint arXiv:2604.09836.
      </p>

      <p class="pub-links">
        <a href="https://doi.org/10.48550/arXiv.2604.09836" target="_blank">arXiv DOI</a>
      </p>
    </div>
  </div>

  <div class="pub-card">
    <div class="pub-year">2025</div>
    <div class="pub-content">
      <div class="pub-badge preprint">Preprint</div>

      <h3>
        Humanity's Last Exam
      </h3>

      <p class="pub-authors">
        Phan, L., Gatti, A., Han, Z., Li, N., Hu, J., Zhang, H.,
        ... <strong>Ariel Ghislain Kemogne Kamdoum</strong> ... and Wykowski, J.
      </p>

      <p class="pub-venue">
        arXiv preprint arXiv:2501.14249.
      </p>
    </div>
  </div>

</div>

---

# Manuscripts Under Review

<div class="pub-section">

  <div class="pub-card under-review">
    <div class="pub-year">2026+</div>
    <div class="pub-content">
      <div class="pub-badge review">Under Review</div>

      <h3>
        gVAE: Stable and interpretable representation learning for high-dimensional genomic cohorts with moderate sample sizes
      </h3>

      <p class="pub-authors">
        <strong>Kemogne A.</strong>, Weeraman J., Wang D., Enoma D., Li C.,
        Ganeshiny S., Chernenkoff S., Chekouo T., Zhang Q., Long Q.
      </p>

      <p class="pub-venue">
        Manuscript under review.
      </p>
    </div>
  </div>

  <div class="pub-card under-review">
    <div class="pub-year">2026+</div>
    <div class="pub-content">
      <div class="pub-badge review">Under Review</div>

      <h3>
        Representation learning-based genome-wide association mapping discovers genes underlying complex traits
      </h3>

      <p class="pub-authors">
        David O. Enoma, Hongjiang Chu, Dinghao Wang, Li Shu,
        <strong>Ariel Ghislain Kemogne Kamdoum</strong>, Janith Weeraman,
        Lang Wu, Paul M. K. Gordon, A. P. Jason de Koning, Paul D. Arnold,
        M. Ethan MacDonald, Weijia Cai, Linzhi Cai, Rodrigo Ortega Polo,
        Quan Long, and Chen Cao.
      </p>

      <p class="pub-venue">
        Manuscript under review.
      </p>
    </div>
  </div>

</div>

---

<div class="scholar-box">
  <p>
    More publications and citation updates are available on
    <a href="https://scholar.google.com/citations?user=q7dQio4AAAAJ" target="_blank">
      Google Scholar
    </a>.
  </p>
</div>
<style type="text/css">

/* Intro text */
.pub-intro {
  margin: 1.2rem 0 2rem 0;
  font-size: 1.03rem;
  line-height: 1.65;
  color: #333;
}

/* Publication section */
.pub-section {
  display: flex;
  flex-direction: column;
  gap: 1.15rem;
  margin-top: 1.2rem;
  margin-bottom: 2.4rem;
}

/* Publication card */
.pub-card {
  display: grid;
  grid-template-columns: 82px 1fr;
  gap: 1.15rem;
  padding: 1.15rem 1.25rem;
  border: 1px solid #e5e8ec;
  border-radius: 14px;
  background: #ffffff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.035);
}

/* Featured publication */
.pub-card.featured {
  border-left: 5px solid #1f4e79;
  background: #fbfdff;
}

/* Under-review manuscripts */
.pub-card.under-review {
  background: #fffdf8;
}

/* Year column */
.pub-year {
  font-size: 1rem;
  font-weight: 700;
  color: #1f4e79;
  padding-top: 0.15rem;
}

/* Publication content */
.pub-content {
  line-height: 1.58;
}

.pub-content h3 {
  margin: 0.3rem 0 0.45rem 0;
  font-size: 1.08rem;
  line-height: 1.38;
  color: #1f2933;
}

.pub-content p {
  margin: 0.35rem 0;
}

/* Authors */
.pub-authors {
  color: #333;
}

/* Venue */
.pub-venue {
  color: #4b5563;
}

/* Links */
.pub-links {
  margin-top: 0.55rem;
}

.pub-links a {
  display: inline-block;
  padding: 0.22rem 0.55rem;
  border-radius: 6px;
  border: 1px solid #d7e2ec;
  background: #f5f9fc;
  color: #1f4e79;
  font-weight: 600;
  text-decoration: none;
  font-size: 0.88rem;
}

.pub-links a:hover {
  background: #eaf2f8;
  text-decoration: none;
}

/* Badges */
.pub-badge {
  display: inline-block;
  padding: 0.22rem 0.55rem;
  border-radius: 999px;
  font-size: 0.78rem;
  font-weight: 700;
  margin-bottom: 0.25rem;
  letter-spacing: 0.01em;
}

.pub-badge.nature {
  background: #f2e8e8;
  color: #8b1e1e;
}

.pub-badge.journal {
  background: #eef4fa;
  color: #1f4e79;
}

.pub-badge.preprint {
  background: #f0f4f8;
  color: #455a64;
}

.pub-badge.review {
  background: #fff3cd;
  color: #8a5a00;
}

/* Scholar box */
.scholar-box {
  margin: 2.5rem 0 1rem 0;
  padding: 1rem 1.2rem;
  border-radius: 12px;
  background: #f8fafc;
  border: 1px solid #e5e8ec;
  line-height: 1.6;
}

/* Cleaner headings */
h1 {
  margin-top: 2.2rem;
  margin-bottom: 1rem;
  border-bottom: 2px solid #e5e8ec;
  padding-bottom: 0.35rem;
}

/* Mobile layout */
@media screen and (max-width: 760px) {
  .pub-card {
    grid-template-columns: 1fr;
  }

  .pub-year {
    padding-top: 0;
  }
}

</style>
