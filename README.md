# Team Onboarding & Collaboration Site

An interactive onboarding tool that helps a distributed team get set up, understand
how each person works best, and collaborate with more awareness and empathy.

## How to view it

Open `index.html` in any web browser. All pages link to each other, so you can
click through the whole site from there.

## Pages

- **index.html / onboarding-hub.html** — the landing page ("Start here"): welcome,
  a 3-step journey, and a first-weeks checklist.
- **teammate-intake.html** — an AI-style conversation that builds a personal
  "how to work with me" profile. Ask about hours, communication, feedback style,
  meeting comfort, strengths, stressors, growth goals, and what helps someone feel
  supported. The finished profile is fully editable, then downloadable.
- **team-roster.html** — the team directory, linking to each person's profile.
- **team-agreements.html** — the team's shared working agreements (editable in-page).
- **playbook.html** — copy-paste templates for meetings and async communication.
- **dashboard.html** — a manager view: timezone overlap, feedback preferences,
  meeting comfort, and where the team's strengths cluster.
- **\*-profile.html** — five example teammate profiles (Maya, Diego, Priya, Sam, Tariq).

## About the intake's "demo mode"

The intake is designed to run a live AI conversation via Claude's API. When it's
hosted as plain files (with no server-side API key), it automatically runs a
scripted version of the same conversation instead — same look, same editable
profile, no API key or cost required. This makes the site safe to share and demo
anywhere.

## How to put it online (free)

1. Keep all these files together in one folder.
2. Go to https://app.netlify.com/drop
3. Drag this whole folder onto the page.
4. You'll get a public URL to share. `index.html` opens automatically.

(GitHub Pages and Cloudflare Pages work too — any static host.)

## Adding a real teammate later

When someone completes the intake and downloads their `name-profile.html` file,
save it in this folder and add a link to it on `team-roster.html` (copy one of the
existing member blocks and update the name, role, and href).
