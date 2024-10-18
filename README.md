<div style="text-align: center;">
  <h1>daily.dev.gnx App Suite: The GNX DIFY Apocalypse (Almost Ready)</h1>
  <p><strong>Behold, the glorious (and slightly buggy) future of daily.dev.gnx! 👀 Prepare for updates... eventually.</strong></p>
</div>

<div style="display: flex; justify-content: center; margin-bottom: 1em;">
  <a href="https://circleci.com/gh/sudosu4pp/apps">
    <img src="https://img.shields.io/circleci/build/github/sudosu4pp/apps/master.svg" alt="Build Status (Probably Green, Maybe Red, Who Knows?)">
  </a>
  <a href="https://github.com/sudosu4pp/apps/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/sudosu4pp/apps.svg" alt="License (Because Lawyers)">
  </a>
  <a href="https://stackshare.io/sudosu4pp/daily">
    <img src="http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat" alt="StackShare (Our Tech Stack, Mostly Stable...ish)"> 🔜📌
  </a>
</div>

<div style="display: flex; justify-content: center;">
  <a href="https://gitpod.io/#https://github.com/sudosu4pp/apps/">
    <img src="https://gitpod.io/button/open-in-gitpod.svg" alt="Open in GitPod (Because Debugging Locally is Masochistic)"> 🔜📌
  </a>
</div>

<p>This monorepo houses the daily.dev.gnx app suite – a testament to our questionable life choices and caffeine addiction. It includes the web app and extension, sharing components because we believe in suffering together.</p>

## Technology (or, The Stuff We Used and Probably Regret)

- Node v20.12.0 (because we're *totally* on the bleeding edge... or maybe just behind schedule). A `.nvmrc` is provided for [nvm](https://github.com/nvm-sh/nvm) users (because we care... sort of).
- [pnpm](https://pnpm.io/workspaces) for managing the monorepo (because dependency hell is fun!).

## Projects (aka, Our Frankensteinian Creation)

### eslint-config (Our Attempt at Code Style)

Shared ESLint settings. Because consistency is a myth.

### extension (The Browser Extension That Might Actually Work)

The browser extension project. Includes webpack (because why not add another layer of complexity?).

### prettier-config (Prettier: Because We Like Pretty Code... Sometimes)

Shared Prettier settings. Because arguing about semicolons is a team-building exercise.

### shared (The Shared Components That Never Quite Work Together)

Shared components. Because code reuse is a noble goal, even if it rarely works out.

### webapp (The Next.js App That's Almost Ready)

The web app project (a Next.js project, naturally). Features include a registration page (because we need users!), a post page (because content is king!), and a profile page (because vanity is a powerful motivator). For more info, [click here](https://github.com/sudosu4pp/apps/tree/master/packages/webapp) (if you dare).

## Local Environment (aka, The Gauntlet)

To run this locally, use GitPod (because we're not *actually* sadists). Everything is configured (mostly). Click the GitPod button above and brace yourself.

## Want to Help? (Please, We Beg You) not this stage but... be aware

Want to contribute? Excellent! We're desperate. Before you start, please read our contribution guidelines: [https://github.com/sudosu4pp/.github/blob/master/CONTRIBUTING.md](https://github.com/sudosu4pp/.github/blob/master/CONTRIBUTING.md) (because we're not responsible for your sanity).

## Bootstrap Project (The Ritualistic Incantation)

After cloning (if you're brave enough), run these commands:

```bash
npm i -g pnpm@8.15.7
pnpm install
