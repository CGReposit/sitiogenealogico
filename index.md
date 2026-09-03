---
layout: default
title: Archivo Genealógico Guerra Martín
---

<style>
  :root {
    --ink: #4a2f2a;
    --wine: #8e2f3f;
    --terracotta: #b75a3c;
    --cream: #f8f0df;
    --paper: #fffaf0;
    --gold: #c89543;
  }

  body {
    background: var(--cream);
    color: var(--ink);
  }

  h1, h2, h3 {
    color: var(--wine);
  }

  a {
    color: var(--wine);
  }

  .hero-image {
    width: 100%;
    max-height: 430px;
    object-fit: cover;
    object-position: center;
    border: 7px solid var(--paper);
    box-shadow: 0 10px 28px rgba(74, 47, 42, .18);
    margin: 1rem 0 1.6rem;
  }

  .intro {
    font-size: 1.08rem;
    line-height: 1.75;
  }

  .registry-card {
    max-width: 560px;
    margin: 2rem auto;
    padding: 1.75rem;
    text-align: center;
    background: var(--paper);
    border: 1px solid rgba(142, 47, 63, .2);
    border-top: 5px solid var(--gold);
    border-radius: 8px;
    box-shadow: 0 8px 22px rgba(74, 47, 42, .12);
  }

  .registry-card h3 {
    margin-top: 0;
  }

  .registry-button {
    display: inline-block;
    margin-top: .65rem;
    padding: .8rem 1.25rem;
    color: #fff !important;
    background: var(--wine);
    border-radius: 5px;
    font-weight: 700;
    text-decoration: none;
  }

  .registry-button:hover {
    background: var(--terracotta);
    text-decoration: none;
  }

  .purpose {
    margin-top: 2.2rem;
    padding: 1.25rem 1.4rem;
    background: rgba(200, 149, 67, .14);
    border-left: 4px solid var(--gold);
  }
</style>

<p style="text-align:center; font-style:italic;">Cada nombre conserva una historia; cada documento nos ayuda a reconstruirla.</p>

<img class="hero-image" src="{{ '/images/castilla.jpg' | relative_url }}" alt="Paisaje de Castilla pintado al óleo">

<div class="intro">
  <p>Este archivo digital reúne la genealogía de la familia <strong>Guerra Martín</strong>. Su propósito es conservar y organizar nombres, fechas, lugares, fotografías, documentos y recuerdos familiares para que puedan consultarse y ampliarse con el paso del tiempo.</p>

  <p>El proyecto sigue el modelo del archivo genealógico de la rama paterna, pero está dedicado a la familia materna y a sus raíces en España. La información se irá incorporando de forma gradual a medida que aparezcan nuevas fuentes y testimonios.</p>
</div>

## Índice

<div class="registry-card">
  <h3>Registro familiar</h3>
  <p>Consulta el directorio de familiares y accede a las fichas individuales que se incorporen al archivo.</p>
  <a class="registry-button" href="{{ '/family-directory.html' | relative_url }}">Abrir el registro familiar</a>
</div>

<div class="purpose">
  <strong>Un archivo en construcción.</strong> Esta página crecerá con nuevas personas, documentos y relatos. Cuando existan versiones contradictorias de una fecha o un parentesco, se conservarán las fuentes para distinguir lo comprobado de lo pendiente de investigación.
</div>
