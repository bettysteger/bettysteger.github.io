---
permalink: /netcup/
layout: page
title: netcup Gutscheine
description: "netcup Gutscheincodes: 5 € Rabatt für Neukunden (unbegrenzt gültig) und 30 % Rabatt auf Webhosting 2000, 4000 und 8000 für Neukunden. Code kopieren und bei netcup.com einlösen."
netcup_products:
  - name: Webhosting 2000
    url: https://www.netcup.com/de/hosting/webhosting/webhosting-2000-nue
    description: >-
      ist der Einsteigertarif für den Betrieb von <strong>bis zu drei Domains</strong>
      für kleine, private Webseiten und den Einsatz eines <strong>CMS Systems</strong>
      wie z.B. WordPress.
    codes:
      - 5207nc178516725614
      - 5207nc178516725613
      - 5207nc178516725612
      - 5207nc178516725611
      - 5207nc178516725610
      - 5207nc17851672569
      - 5207nc17851672568
      - 5207nc17851672567
      - 5207nc17851672566
      - 5207nc17851672565
      - 5207nc17851672564
      - 5207nc17851672563
      - 5207nc17851672562
      - 5207nc17851672561
      - 5207nc17851672560
  - name: Webhosting 4000
    url: https://www.netcup.com/de/hosting/webhosting/webhosting-4000-nue
    description: >-
      ist ein leistungsstarkes Webhosting für <strong>mehrere mittelgroße Webseiten</strong>,
      die neben dem Einsatz eines <strong>CMS Systems</strong> wie z.B. WordPress auch
      mittelgroße Mediengalerien enthalten.
    codes:
      - 5208nc17851748459
      - 5208nc17851748458
      - 5208nc17851748457
      - 5208nc17851748456
      - 5208nc17851748455
      - 5208nc17851748454
      - 5208nc17851748453
      - 5208nc17851748452
      - 5208nc17851748451
      - 5208nc17851748450
  - name: Webhosting 8000
    url: https://www.netcup.com/de/hosting/webhosting/webhosting-8000-nue
    description: >-
      ist der leistungsstärkste Webhosting Tarif für <strong>bis zu zwölf Domains</strong>
      und mit dem <strong>größten Speicherplatz</strong>. Dieser Tarif eignet sich besonders
      für den Betrieb von <strong>großen Webseiten, die Bildergalerien oder Videos</strong>
      enthalten oder für den Einsatz einer <strong>Cloud Storage Lösung</strong>.
    codes:
      - 5209nc17851748499
      - 5209nc17851748498
      - 5209nc17851748497
      - 5209nc17851748496
      - 5209nc17851748495
      - 5209nc17851748494
      - 5209nc17851748493
      - 5209nc17851748492
      - 5209nc17851748491
      - 5209nc17851748490
---

<style>
  .netcup-hero {
    background: #f5f5f5;
    border: 2px solid #49e2d6;
    border-radius: 8px;
    padding: 30px;
    margin-bottom: 40px;
    text-align: center;
  }
  .netcup-hero-label {
    display: inline-block;
    background: #49e2d6;
    color: #fff;
    font-weight: 700;
    font-size: 12px;
    letter-spacing: 1px;
    text-transform: uppercase;
    border-radius: 20px;
    padding: 4px 14px;
    margin-bottom: 15px;
  }
  .netcup-hero h3 {
    margin: 0 0 20px;
  }
  .netcup-code {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    background: #fff;
    border: 1px dashed #5b5963;
    border-radius: 6px;
    padding: 6px 6px 6px 14px;
    margin: 3px 0;
  }
  .netcup-code code {
    background: none;
    color: #5b5963;
    font-size: 15px;
    padding: 0;
  }
  .netcup-hero .netcup-code {
    padding: 10px 10px 10px 20px;
  }
  .netcup-hero .netcup-code code {
    font-size: 22px;
    font-weight: 700;
  }
  .netcup-copy {
    background: #fa1f55;
    color: #fff;
    border: 0;
    border-radius: 4px;
    padding: 8px 14px;
    cursor: pointer;
    font-size: 13px;
    transition: background 0.2s;
  }
  .netcup-copy:hover {
    background: #fd735a;
  }
  .netcup-copy.copied {
    background: #49e2d6;
  }
  .netcup-cta {
    display: inline-block;
    margin-top: 20px;
    font-weight: 700;
  }
  .netcup-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    max-height: 420px;
    overflow-y: auto;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 15px;
    margin: 20px 0;
  }
</style>

<div class="netcup-hero">
  <span class="netcup-hero-label">⭐ Für Neukunden · unbegrenzt gültig</span>
  <h3>5 € Rabatt auf deine erste Bestellung bei netcup</h3>
  <div class="netcup-code">
    <code>36nc17851671270</code>
    <button class="netcup-copy" data-code="36nc17851671270">Kopieren</button>
  </div>
  <p style="margin-top: 15px;">Gültig für alle Produkte (ausgenommen Domains) - einfach bei der Bestellung im Gutschein-Feld eingeben.</p>
  <a class="netcup-cta" href="https://www.netcup.com/de?ref=189769" target="_blank" rel="noopener">Jetzt bei netcup.com einlösen →</a>
</div>

{% for product in page.netcup_products %}
<h3>30 % Rabatt auf {{ product.name }}</h3>

<p>
  <a href="{{ product.url }}?ref=189769" target="_blank" rel="noopener">{{ product.name }}</a>
  {{ product.description }}
</p>

<p>
  Jeder dieser Gutscheine ist <strong>nur einmal einlösbar</strong> und gilt <strong>für Neukunden</strong>.
  Kopiere dir einen Code - falls er schon eingelöst wurde, probiere einfach den nächsten.
</p>

<div class="netcup-grid">
  {% for code in product.codes %}
  <div class="netcup-code">
    <code>{{ code }}</code>
    <button class="netcup-copy" data-code="{{ code }}">Kopieren</button>
  </div>
  {% endfor %}
</div>
{% endfor %}

<h3>So löst du einen Gutschein ein</h3>

<ol>
  <li>Gewünschtes Produkt auf <a href="https://www.netcup.com/de?ref=189769" target="_blank" rel="noopener">netcup.com</a> in den Warenkorb legen.</li>
  <li>Im Bestellvorgang den Gutscheincode in das Feld „Gutschein" eintragen.</li>
  <li>Der Rabatt wird direkt abgezogen - fertig! 🎉</li>
</ol>

<script>
  document.querySelectorAll('.netcup-copy').forEach(function (btn) {
    btn.addEventListener('click', function () {
      navigator.clipboard.writeText(btn.dataset.code).then(function () {
        btn.textContent = '✓ Kopiert';
        btn.classList.add('copied');
        setTimeout(function () {
          btn.textContent = 'Kopieren';
          btn.classList.remove('copied');
        }, 2000);
      });
    });
  });
</script>
