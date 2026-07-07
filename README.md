# Kunle Owolabi

**Engineer building data-intensive software for energy & industrial systems.**
Backend, data platforms, and IIoT telemetry. Electrical/electronics background.

---

I build the software layer that sits on top of physical infrastructure — turning
high-volume telemetry and messy operational data into systems people can rely on to
make decisions. My route here is unusual: I started in power systems and industrial
automation (thermal generation, DCS platforms, IIoT), then moved into building the
data pipelines, backends, and full-stack applications that make that data useful.

That background shows up in the work — I've analysed 100k+ telemetry points per day
across 30+ utility and industrial sites, deployed Industrial IoT across live
facilities, and shipped AI-assisted enterprise applications to 1,000+ users. I care
about correctness, data-quality flags, and systems that hold up in production, not
just demos.

**Focus:** data platforms · backend systems · IIoT / telemetry · the energy transition

**Stack:** Python · SQL / PostgreSQL · FastAPI · React · AWS · geospatial / PostGIS

---

## Selected public projects

These are the projects whose code I can share openly. Each links to source; some
of my professional and client work lives in private repositories under NDA (see below).

**[Arrhen](https://github.com/kunleowolabi/arrhen) — GHG emissions accounting platform for energy & industrial organisations**
Full-stack platform to track carbon emissions across multi-site operations and
generate audit-ready, geospatial reports. Built on the GHG Protocol, with a
seven-gas calculation engine (per-compound GWP resolution, AR5/AR6), field-data
ingestion (CSV, ODK/KoboToolbox), materiality screening, and multi-site mapping.
*Python · FastAPI · SQLAlchemy · Alembic · React · PostGIS*

**[Owen](https://github.com/kunleowolabi/owen) — multi-tenant back-office platform for cooperative financial organisations**
A structured data platform for contribution tracking, cycle management, and
compliance oversight. Security is enforced at the database: PostgreSQL row-level
security, JWT-claim tenant isolation, role-gated financial policies, append-only
audit logs, and DB-side status derivation.
*React · Supabase / PostgreSQL · Row-Level Security · JWT*

**[Rubeeq](https://github.com/kunleowolabi/rubeeq) — AI-powered document extraction engine**
Converts unstructured exam PDFs into structured, database-ready data. Detects
native vs. scanned pages, routes each to text or vision extraction, identifies the
document type automatically, and emits a SQL schema, JSON bundle, and insert script.
A pluggable profile system handles new formats; a platform layer adds jobs,
per-page billing, and a test suite.
*Python · pdfplumber · Claude vision · Pydantic · FastAPI · pytest*

**[Rubeeq ETL](https://github.com/kunleowolabi/rubeeq-etl) — PDF-to-structured-data pipeline (prototype)**
The design sketch behind Rubeeq: a page-level detect → extract → schema-infer →
load pipeline that ends in a queryable DuckDB database. Demonstrates
schema-inference-over-enforcement across three document types.
*Python · pdfplumber · DuckDB · Jupyter*

---

## Beyond what's public

Some of my strongest work isn't on GitHub. In professional and contract roles I've
built and deployed AI-driven enterprise applications for B2B SaaS platforms, designed
Python data/automation backends on PostgreSQL, and built real-time monitoring
infrastructure for industrial and utility sites. Those repositories are private or
covered by contractual agreements — my CV covers them, and I'm happy to talk through
the work in more detail.

## Currently building

Working toward an end-to-end energy-demand intelligence platform for Nigeria's grid —
combining satellite (nighttime-lights) demand modelling, a spatial backend, custom
IIoT reference probes for ground-truth voltage/telemetry, and time-series forecasting.
It's the kind of project this whole profile has been building toward: hardware, data, and
software in one system.

---

📫 kunleowolabi77@gmail.com · [LinkedIn](https://www.linkedin.com/in/kunleowolabi)
