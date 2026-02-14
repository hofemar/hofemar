# Hi, I'm Mario

I build mixed reality applications with a focus on practical, real-world use cases.

## AgilityAR

A VR application that brings dog agility course designs into mixed reality. Handlers and trainers can import their course maps from [SmarterAgility](https://smarteragility.com) and walk them life-sized on Meta Quest headsets — with hand tracking, no controllers needed.

### What it does

- Imports course designs from SmarterAgility cloud
- Renders 10 obstacle types (jumps, tunnels, weave poles, A-frame, dogwalk, and more) as 3D objects at real-world scale
- Hand-tracked interaction: grab, move, and rotate obstacles or the entire course
- Bezier-curve course path visualization with numbered markers

### Tech

| Layer | Stack |
|-------|-------|
| VR App | Unity 2022.3 LTS, C#, Meta XR SDK |
| Backend | Python, FastAPI, SQLite |
| Target | Meta Quest 2 / 3 / Pro |
| CI/CD | GitHub Actions, Azure Container Apps |

### Numbers

- 10 obstacle types with procedural mesh generation
- 275+ automated tests (Unity EditMode + pytest)
- Cloud sync with SmarterAgility API
