### Hi, I'm William Christie 👋

I build small, useful software and take it all the way from the data model to the last screen. I like picking a real problem, shipping something that actually works, and keeping it simple enough that someone non-technical can pick it up and use it.

### 🩺 Pulse, the project I'm proudest of

A WHOOP-style recovery dashboard for Apple Watch data, built native in SwiftUI (iOS 17+, no dependencies).

It reads HealthKit and works out recovery, strain, and sleep scores entirely on the device. No account, no backend, nothing leaves the phone. I wrote the scoring math (z-scores against your own rolling baselines), the data layer, and the interface.

- 📊 Live overview: https://william-t-christie.github.io/pulse/
- 💻 Code: https://github.com/William-T-Christie/pulse

### A few things I've built

| Project | What it is | Built with |
|---|---|---|
| [pulse](https://github.com/William-T-Christie/pulse) | On-device Apple Watch recovery dashboard | Swift, SwiftUI, HealthKit |
| [meal-prep-tool](https://github.com/William-T-Christie/meal-prep-tool) | Meal planner that turns a dietary profile into a week of meals, scaled recipes, and a shopping list | Next.js, TypeScript, Claude API, Prisma |
| [n-equals-one](https://github.com/William-T-Christie/n-equals-one) | Local-first personal fitness data tracker (feeds Pulse's next phase) | TypeScript, Node |
| [personal-site](https://william-t-christie.github.io/personal-site/) | Portfolio site with a few small apps and my resume | HTML, CSS, JS |

A couple of older projects are being cleaned up and will be back soon.

### How I work

I'd rather build the whole thin slice (data, logic, and interface) than one piece in isolation. I try to make things you can actually trust: in Pulse, every score can be traced back to the numbers behind it. And I use what I build. Pulse runs on my own phone every day.
