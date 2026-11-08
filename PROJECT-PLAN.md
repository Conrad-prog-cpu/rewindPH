# Rewind.PH — Project Plan and Rubric Alignment

## Project identity

**Main tagline:** Living the Filipino 2000s  
**Supporting line:** Log in. Look back. See what shaped us.

## SMART project goal

Within 15 working days from project approval, the team will design, build, test, and publish a responsive virtual museum containing 3 curated exhibition rooms, at least 15 past-to-present artifact comparisons, and captions plus alternative text for 100% of displayed photographs. The museum will be tested with at least 20 users, targeting at least 90% successful task completion and an average visitor satisfaction rating of 4.0/5 or higher.

## Execution plan

| Sequence | Timeframe | Tasks | Output / checkpoint | Lead roles |
|---|---:|---|---|---|
| 1 | Days 1–2 | Confirm scope; validate names, dates, descriptions, historical context, and permissions; finalize the 15 comparisons | Approved content inventory and source/permission checklist | Project lead, researchers/curators, adviser |
| 2 | Days 3–4 | Sort uploaded ZIP files; identify duplicates; convert/optimize image assets; write captions and alt text | Organized, optimized and captioned asset library | Media editor, curators |
| 3 | Days 5–7 | Map visitor journey; create visual identity; design room layout, wireframes, and artifact viewer | Approved UI design and gallery floor plan | UI designer, project lead |
| 4 | Days 8–11 | Develop responsive interface, 3D room, navigation, artifact modal, search, filters, and project blueprint | Functional beta website | Web developer, designer |
| 5 | Days 12–13 | Test mobile/desktop layouts, browser compatibility, keyboard access, captions, links, loading, and fallback behavior | QA checklist and corrected release candidate | QA testers, developer, curators |
| 6 | Day 14 | Conduct usability testing with at least 20 visitors; collect task-completion and satisfaction data | User-test summary and prioritized fixes | Project lead, QA team |
| 7 | Day 15 | Apply final fixes; publish through GitHub Pages; document repository, URL, roles, and results | Published museum and final project documentation | Developer, project lead |

## Resource plan

| Task | Tools / materials | Human resources |
|---|---|---|
| Research and curation | Project brief, historical references, artifact inventory, source/permission tracker | Project lead, content researchers, adviser |
| Asset preparation | Supplied ZIP files, image editor, WebP converter, caption/alt-text checklist, storage | Media editor, curators |
| Interface design | Wireframe tool, color/type system, layout references, laptop | UI designer, project lead |
| Development | Laptop/desktop, code editor, HTML, CSS, JavaScript, Three.js CDN, browser developer tools | Web developer, UI designer |
| Testing | Desktop, Android/iOS phones, browsers, accessibility checklist, user feedback form | QA testers, at least 20 test visitors |
| Deployment | Git, GitHub account/repository, GitHub Pages, README and documentation | Developer, project lead |

## Success indicators

- All 3 exhibition rooms are accessible and clearly labeled.
- All 15 selected comparisons appear in the archive and in the relevant 3D room.
- Every displayed image has a visible caption and meaningful alternative text.
- All artifact cards open the correct expanded gallery.
- The site works at common desktop, tablet, and mobile widths.
- If 3D rendering is unavailable, visitors can still browse the full artifact archive.
- At least 90% of test users complete the assigned navigation task without assistance.
- Average visitor satisfaction is at least 4.0/5.
- Initial landing content is optimized for practical loading on typical broadband/mobile connections.

## Monitoring and adjustment

Use a simple Kanban board with **To Do / In Progress / Review / Done** columns. Review progress at the end of each workday. The project lead checks the critical path (content approval → asset readiness → interface build → QA → deployment). If a task slips, prioritize the core deliverables: three rooms, 15 pairings, captions, responsive archive, and working deployment. The 3D walkthrough is an enhancement; the accessible artifact archive remains the continuity plan.

## Risk register

| Risk | Mitigation |
|---|---|
| Large image or video files slow the site | Optimize still images, lazy-load detail galleries, and keep optional video out of the first-release package. |
| Historical dates or claims are inaccurate | Use a source-checking pass; distinguish pre-2000 roots from 2000s influence; verify present-day product claims. |
| Image copyright / permission concerns | Maintain a source and permission log; use only materials approved for the intended educational publication. |
| 3D engine or WebGL unavailable | Keep the full searchable artifact archive as a non-3D fallback. |
| Mobile controls are difficult | Test on actual phones and retain standard archive browsing and room shortcuts. |

## Rubric alignment

- **SMART goal:** The goal specifies the product, quantity, quality requirements, test group, success thresholds, and deadline.
- **Ordered tasks and timeframe:** Seven sequential work packages identify dependencies, deliverables, and a logical 15-day schedule.
- **Resources:** Each work package identifies tools/materials and responsible human roles.
- **Delivery and metrics:** Daily Kanban reviews, user testing, measurable success indicators, and risk mitigations support timely delivery and adjustment.
- **Innovation:** The project combines a first-person 3D exhibition, interactive then/now artifact panels, searchable captioned galleries, a cultural timeline, and a fallback experience.


## Group 2 team assignments

| Member | Assigned role | Core contribution |
|---|---|---|
| Conrad Santos | Leader / Software Developer | Coordinates delivery; develops the website, 3D walkthrough, interaction logic, and deployment. |
| Christian Borja | Artifacts Researcher | Researches artifact history, dates, context, and then-and-now comparisons. |
| Carl Josef Buizon | Artifacts Researcher | Researches and validates artifact details and cultural connections. |
| Charlene Padua | Artifacts Researcher | Researches cultural references and prepares exhibit descriptions. |
| Clarence Joy Garcia | Graphic Designer | Develops the visual identity, exhibit graphics, and presentation consistency. |
| Clark Maverick Olinares | Artifacts Researcher | Checks historical context, names, dates, and artifact relevance. |
| Connie Yadao | Artifacts Researcher | Supports artifact research, captions, and exhibit interpretation. |

## Updated immersive experience features

- A one-line **REWIND.PH** wordmark in the landing-page feature card and 3D museum header.
- A high-ceiling exhibition hall with recessed ceiling panels and soft warm spotlights.
- A double-glass entrance that automatically slides open on entry and can be toggled by clicking the glass panels or the on-screen door control.
- Group 2 names and roles shown on the landing page, in the About / Meet the Team section, and on a navigable 3D credits wall.
