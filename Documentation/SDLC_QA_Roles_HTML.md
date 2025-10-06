# 🧩 QA Role in SDLC (HTML Tables Version)

This document presents QA responsibilities and artifacts across **Waterfall, V-Model, and Agile (Scrum)** using HTML tables for crisp column alignment on GitHub.

---

## 🔹 1. SDLC Overview

<table>
  <thead>
    <tr>
      <th>Phase</th>
      <th>Description</th>
      <th>QA Focus</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Requirements</td>
      <td>Define goals and user needs</td>
      <td>Review for clarity & testability</td>
    </tr>
    <tr>
      <td>Design</td>
      <td>System & component architecture</td>
      <td>Plan test strategy, data, environments</td>
    </tr>
    <tr>
      <td>Implementation</td>
      <td>Code development</td>
      <td>Support unit tests, write test cases</td>
    </tr>
    <tr>
      <td>Testing</td>
      <td>Verification & validation</td>
      <td>Execute functional / regression / NFR</td>
    </tr>
    <tr>
      <td>Deployment</td>
      <td>Release to production</td>
      <td>Smoke/sanity, environment validation</td>
    </tr>
    <tr>
      <td>Maintenance</td>
      <td>Support & fixes</td>
      <td>Regression, impact analysis</td>
    </tr>
  </tbody>
</table>

---

## 🔹 2. QA in Waterfall Model

<p><strong>Key idea:</strong> Sequential phases. <strong>QA involvement:</strong> mainly after development.</p>

<table>
  <thead>
    <tr>
      <th>Phase</th>
      <th>QA Responsibilities</th>
      <th>Artifacts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Requirements</td>
      <td>Review for testability & completeness</td>
      <td>Comments, clarified requirements</td>
    </tr>
    <tr>
      <td>Design</td>
      <td>Outline high-level test plan</td>
      <td>Test plan draft</td>
    </tr>
    <tr>
      <td>Implementation</td>
      <td>Support devs, prepare test cases</td>
      <td>Test cases, checklists</td>
    </tr>
    <tr>
      <td>Testing</td>
      <td>System & regression execution</td>
      <td>Bug reports, test reports</td>
    </tr>
    <tr>
      <td>Maintenance</td>
      <td>Verify fixes, run regression</td>
      <td>Regression suite, reports</td>
    </tr>
  </tbody>
</table>

---

## 🔹 3. QA in V-Model

<p><strong>Key idea:</strong> Each dev phase maps to a specific test level (traceability).</p>

<table>
  <thead>
    <tr>
      <th>Development Phase</th>
      <th>Test Level</th>
      <th>QA Responsibilities</th>
      <th>Artifacts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Requirements</td>
      <td>Acceptance Testing</td>
      <td>Define acceptance criteria, support UAT</td>
      <td>UAT checklist, sign‑off notes</td>
    </tr>
    <tr>
      <td>System Design</td>
      <td>System Testing</td>
      <td>Define end‑to‑end & non‑functional tests</td>
      <td>System test plan & report</td>
    </tr>
    <tr>
      <td>Detailed Design</td>
      <td>Integration Testing</td>
      <td>Validate interfaces, data flow, errors</td>
      <td>Integration test cases, API logs</td>
    </tr>
    <tr>
      <td>Coding</td>
      <td>Unit Testing</td>
      <td>Support & review unit tests</td>
      <td>Unit test checklist, code review notes</td>
    </tr>
  </tbody>
</table>

---

## 🔹 4. QA in Agile (Scrum)

<p><strong>Key idea:</strong> QA is part of the team; testing occurs within each sprint.</p>

<table>
  <thead>
    <tr>
      <th>Sprint Stage</th>
      <th>QA Responsibilities</th>
      <th>Artifacts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Backlog Grooming</td>
      <td>Clarify acceptance criteria, identify risks</td>
      <td>Updated user stories, notes</td>
    </tr>
    <tr>
      <td>Sprint Planning</td>
      <td>Define test scope, envs, data</td>
      <td>Board tasks, data checklist</td>
    </tr>
    <tr>
      <td>Development</td>
      <td>Write test cases; API/UI exploratory</td>
      <td>Test cases, Postman collections</td>
    </tr>
    <tr>
      <td>Build / CI</td>
      <td>Smoke, monitor build health</td>
      <td>Build verification report</td>
    </tr>
    <tr>
      <td>Testing</td>
      <td>Functional, regression, NFR; triage</td>
      <td>Bug reports, screenshots, logs</td>
    </tr>
    <tr>
      <td>Review / Retro</td>
      <td>Demo flows; analyze metrics</td>
      <td>Feedback log, improvements</td>
    </tr>
  </tbody>
</table>

---

## 🔹 5. Summary

<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>QA Involvement</th>
      <th>Advantage</th>
      <th>Risk</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Waterfall</td>
      <td>After development</td>
      <td>Clear structure</td>
      <td>Late bug discovery</td>
    </tr>
    <tr>
      <td>V-Model</td>
      <td>Parallel to dev phases</td>
      <td>Strong traceability</td>
      <td>Requires solid planning</td>
    </tr>
    <tr>
      <td>Agile</td>
      <td>Continuous (each sprint)</td>
      <td>Fast feedback, flexibility</td>
      <td>High communication & automation</td>
    </tr>
  </tbody>
</table>

---

<p>📌 <em>Created by Hanna Spivachuk as part of ISTQB FL Week 1 Practice (SDLC & QA Roles).</em></p>
