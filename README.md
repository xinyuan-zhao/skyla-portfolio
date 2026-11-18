# Data Analytics & Reporting Portfolio

Four-project React + TypeScript + Vite portfolio with Tailwind CSS and Lucide icons. Independent candidate portfolio with a white, charcoal and restrained red design. No Scotiabank assets or affiliation claims.

## Run locally

Use Node.js 22+ with npm: `npm install`, then `npm run dev`. Open the printed local URL. Build with `npm run build`; serve the built files with `npm run preview`. Once dependencies are installed the portfolio runs without internet, external fonts or runtime APIs. Do not open index.html directly from disk.

## Edit content

`src/content.ts` contains project titles, purpose statements, technologies, technical topic lists, workflow steps, Project 04 descriptions and media references. `src/main.tsx` contains reusable project, diagram and media layouts; `src/styles.css` defines the responsive design.

No existing source, project evidence or screenshots were supplied. The first three projects retain the brief's titles and technology categories; all actual methodology, results and impact need confirmation. Project 04 tools, architectures and controls are candidates or proposals, not assertions of implementation. Its input is synthetic and its output is explicitly manually authored. No AI endpoint is connected.

Before interview use, replace pending content with verified professional examples. Confirm implementation, deployment status, validation controls and measured efficiency gains. If measurements are unavailable, say so. Do not turn a proposed architecture into a claimed delivered system.

Add approved media in `public/assets/`, then populate a project's `media` array or `automation.media`, for example `{src:'assets/project04-demo.png', caption:'Approved synthetic demonstration', kind:'image'}`. For video use `kind:'video'` and a local MP4. Images open in a keyboard-accessible native dialog; Escape closes it and returns focus. Videos use browser controls. No blank asset is represented as a real screenshot.

## Interview route

Overview 1 minute; Projects 01–03 5 minutes combined; Project 04 2 minutes (one minute per subsection); close 1 minute. Use expandable technical details only for follow-up questions. Project 04 follows problem → process → implementation → controls → evidence, with a separate AI use case, architecture, review boundary and limitations.

## GitHub Pages

Push this folder's contents to a repository with a `main` branch. In Settings → Pages select GitHub Actions. The included workflow builds and deploys `dist`. Vite's relative base supports a repository subpath. No deployment or repository creation has been performed here.

## Review checks

Build checks TypeScript and creates a production bundle. Manually check all five navigation links, active section tracking, small-screen layouts, technical accordions and reduced motion. After adding approved media check image expansion, Escape, focus return and video playback. No real screenshot/video is supplied, so those media paths need validation with actual assets.

Validation completed: TypeScript check and production Vite build passed. Browser check confirmed Automation & AI navigation, active navigation styling and workflow-controls expansion in the production preview. Media behavior remains untested because approved assets were not supplied. The host development optimizer encountered a Windows sandbox path restriction; production preview runs successfully.
