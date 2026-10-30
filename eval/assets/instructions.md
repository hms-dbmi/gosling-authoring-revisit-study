# How to Rate

Your task is to evaluate one question: **how useful is this visualization for the request shown?**

Each page shows:

* **The request.** Treat it as correct. Judge only the visualization made for it.
* **The input data.** A preview of the dataset.
* **The visualization.** Live and interactive. Pan, zoom and hover before you decide.

There is no reference answer.

## The scale

| Score | Label | What it means |
|---|---|---|
| **5** | Use as-is | No changes needed. |
| **4** | Minor tweaks | Cosmetic fixes only (labels, colours, sizing). |
| **3** | Borderline | Could go either way. Use this when you are genuinely undecided. |
| **2** | Major rework | Substantial work needed before it could be used. |
| **1** | Unusable | Does not render, or is fundamentally wrong (wrong data, wrong encoding, misleading). |

* **3** is for when you are genuinely undecided. If you lean one way, pick that side.
* **Cannot evaluate** is not a rating. Use it only if the page itself failed to load. A
  visualization that shows an error or stays blank gets a **1**.

## If you rate 3 or below

A follow-up asks what went wrong. It looks like this:

| | Wrong | Cannot assess |
|---|:-:|:-:|
| <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" style="vertical-align:-3px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" > <path d="M11 12a1 1 0 1 0 2 0a1 1 0 1 0 -2 0" /> <path d="M7 12a5 5 0 1 0 10 0a5 5 0 1 0 -10 0" /> <path d="M3 12a9 9 0 1 0 18 0a9 9 0 1 0 -18 0" /> </svg> Does not do what was asked | ☐ | ☐ |
| <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" style="vertical-align:-3px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" > <path d="M4 6a8 3 0 1 0 16 0a8 3 0 1 0 -16 0" /> <path d="M4 6v6a8 3 0 0 0 16 0v-6" /> <path d="M4 12v6a8 3 0 0 0 16 0v-6" /> </svg> Wrong or mishandled data | ☐ | ☐ |
| <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" style="vertical-align:-3px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" > <path d="M3 13a1 1 0 0 1 1 -1h4a1 1 0 0 1 1 1v6a1 1 0 0 1 -1 1h-4a1 1 0 0 1 -1 -1l0 -6" /> <path d="M15 9a1 1 0 0 1 1 -1h4a1 1 0 0 1 1 1v10a1 1 0 0 1 -1 1h-4a1 1 0 0 1 -1 -1l0 -10" /> <path d="M9 5a1 1 0 0 1 1 -1h4a1 1 0 0 1 1 1v14a1 1 0 0 1 -1 1h-4a1 1 0 0 1 -1 -1l0 -14" /> <path d="M4 20h14" /> </svg> Wrong mark or encoding | ☐ | ☐ |
| <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" style="vertical-align:-3px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" > <path d="M4 5a1 1 0 0 1 1 -1h4a1 1 0 0 1 1 1v4a1 1 0 0 1 -1 1h-4a1 1 0 0 1 -1 -1l0 -4" /> <path d="M14 5a1 1 0 0 1 1 -1h4a1 1 0 0 1 1 1v4a1 1 0 0 1 -1 1h-4a1 1 0 0 1 -1 -1l0 -4" /> <path d="M4 15a1 1 0 0 1 1 -1h4a1 1 0 0 1 1 1v4a1 1 0 0 1 -1 1h-4a1 1 0 0 1 -1 -1l0 -4" /> <path d="M14 15a1 1 0 0 1 1 -1h4a1 1 0 0 1 1 1v4a1 1 0 0 1 -1 1h-4a1 1 0 0 1 -1 -1l0 -4" /> </svg> Poor layout or composition | ☐ | ☐ |
| <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" style="vertical-align:-3px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" > <path d="M6.5 7.5a1 1 0 1 0 2 0a1 1 0 1 0 -2 0" /> <path d="M3 6v5.172a2 2 0 0 0 .586 1.414l7.71 7.71a2.41 2.41 0 0 0 3.408 0l5.592 -5.592a2.41 2.41 0 0 0 0 -3.408l-7.71 -7.71a2 2 0 0 0 -1.414 -.586h-5.172a3 3 0 0 0 -3 3" /> </svg> Missing or wrong axes, legends, or labels | ☐ | ☐ |
| <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" style="vertical-align:-3px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" > <path d="M12 21a9 9 0 0 1 0 -18c4.97 0 9 3.582 9 8c0 1.06 -.474 2.078 -1.318 2.828c-.844 .75 -1.989 1.172 -3.182 1.172h-2.5a2 2 0 0 0 -1 3.75a1.3 1.3 0 0 1 -1 2.25" /> <path d="M7.5 10.5a1 1 0 1 0 2 0a1 1 0 1 0 -2 0" /> <path d="M11.5 7.5a1 1 0 1 0 2 0a1 1 0 1 0 -2 0" /> <path d="M15.5 10.5a1 1 0 1 0 2 0a1 1 0 1 0 -2 0" /> </svg> Styling harms readability | ☐ | ☐ |
| <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" style="vertical-align:-3px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" > <path d="M9 12h6" /> <path d="M12 9v6" /> <path d="M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-14a2 2 0 0 1 -2 -2v-14" /> </svg> Unhelpful additions | ☐ | ☐ |
| <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" style="vertical-align:-3px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" > <path d="M7.904 17.563a1.2 1.2 0 0 0 2.228 .308l2.09 -3.093l4.907 4.907a1.067 1.067 0 0 0 1.509 0l1.047 -1.047a1.067 1.067 0 0 0 0 -1.509l-4.907 -4.907l3.113 -2.09a1.2 1.2 0 0 0 -.309 -2.228l-13.582 -3.904l3.904 13.563" /> </svg> Interaction broken or missing | ☐ | ☐ |

Tick every row that applies and leave rows that are fine blank. Use **Cannot assess** for
anything outside your expertise rather than guessing. Hover over an aspect for a description.

A rating of 4 or 5 goes straight to the next item.

## Tips

* Take about **3 minutes** per item.
* The data can take a few seconds to load. **Next** unlocks after
  30 seconds.
* Judge each item on its own.


