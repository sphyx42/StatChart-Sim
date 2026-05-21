# __**StatChart-Sim**__

A set of self-contained web tools that lets EMS instructors quickly generate and print standardized, high-fidelity **clinical paperwork** for pre-hospital simulated scenarios. 

Instead of just abstract verbal briefings, **StatChart-Sim** allows you to populate training environments with the realistic, messy, and data-dense paper trails that paramedic students must navigate, review, and interpret in the field.

Each application is a **single HTML file** — no server, no database, no build step, and no internet connection required once loaded. It runs in any modern browser and prints (or saves to PDF) directly from the page.

> ⚠️ **Training use only.** Everything this tool produces is fictional and for simulation/education. It is **not** a real medical record system and must never be used for actual patient care or official documentation. See the disclaimer below.

---

## 🛠️ Simulated Patient Paperwork

The generator dynamically compiles data into several critical pre-hospital training documents:

* **[Discharge Summaries & After Visit Papers](./Discharge%Summary/):** Comprehensive hospital discharge paperwork detailing recent stays, specialized clinic follow-ups, and baseline patient histories.
* **[MARS Sheets (Medication Administration Record)](./MARS/):** *(Work-in-Progress)* Multi-page medication logs detailing scheduled doses, PRN medications, and administration histories—perfect for complex polypharmacy and reconciliation scenarios.
* **[Life-Sustaining Treatment & Legal Forms](./DNR/):** *(Work-in-Progress)* State-specific, highly realistic legal directives including:
  * **DNR** (Do Not Resuscitate) orders
  * **POLST** (Physician Orders for Life-Sustaining Treatment)
  * **MOLST** (Medical Orders for Life-Sustaining Treatment)

---

## ⚖️ Medical & Content Disclaimer

This software generates **fictional** medical documentation for the sole purpose of EMS education and simulation. It is **not** medical advice, **not** a clinical decision-support tool, and **not** a real medical record.

* Doses, vital-sign ranges, legal form text, and clinical summaries are plausible defaults created for training scenarios. They should be **reviewed against your own program's standards and local protocols** before classroom use.
* Some scenarios reference sensitive topics (e.g., behavioral health crises and substance withdrawal). These are written for professional clinical training and should be reviewed and used with appropriate care and alignment with current local crisis resources.

The authors and contributors assume no liability for any use of this tool outside of its intended simulation/educational context.

---

## 📜 License

The **source code** in this repository is licensed under the **GNU General Public License v3.0** — see the [`LICENSE`](LICENSE) file for the full text.

**Trademark / branding notice:** The MATC EMS logo and any Milwaukee Area Technical College names, marks, and branding are the property of Milwaukee Area Technical College and are **not** covered by the GPL-3.0 license. They are included here for use within this institution's simulation program and may not be reused, modified, or redistributed without permission from the College. If you fork this project for your own program, please replace the logo with your own institution's branding.

---

## 🤝 Acknowledgments

Built for the Milwaukee Area Technical College EMS / Paramedic Program to support high-fidelity pre-hospital simulation training.
