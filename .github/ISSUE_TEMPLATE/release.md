---
name: 📅 Release
about: Release checklist
labels:
---

# 📅 Checklist

## 🔶 Staging 

### Dev Tag
 - [ ] [supertokens-core:X.Y](https://github.com/supertokens/supertokens-core/tree/X.Y)
 - [ ] [supertokens-node:X.Y](https://github.com/supertokens/supertokens-node/tree/X.Y)
 - [ ] [supertokens-website:X.Y](https://github.com/supertokens/supertokens-website/X.Y)
 - [ ] [supertokens-auth-react:X.Y](https://github.com/supertokens/supertokens-auth-react/tree/X.Y)
    - [ ] Updated dependencies to use supertokens-website from npm registry
    - [ ] Various browsers - Safari, Firefox, Chrome, Edge
    - [ ] Mobile responsiveness
    - [ ] Make sure using with-typescript example that types are correct for every new configs exposed to users

### Others

 - [supertokens-demo-react](https://github.com/supertokens/supertokens-demo-react/tree/master)
     - [ ] In progress
     - [ ] [PR]() Ready using `supertokens/supertokens-auth-react#X.Y` and `supertokens/supertokens-node#X.Y` github repositories in `package.json`
     - [ ] Make changes to add demo site branches

### 📚 Documentation

- [ ] All recipe main documentation update
   - [ ] If UI changes, make sure to update the themes netlify link.
   - [ ] In progress [PR]()
   - [ ] Deployed on test site

- [ ] nodejs documentation update
   - [ ] In progress [PR]()
   - [ ] Deployed on [test site](https://test.supertokens.io/docs/nodejs/installation)

- [ ] auth-react documentation update
   - [ ] In progress [PR]()
   - [ ] Deployed on [test site](https://test.supertokens.io/docs/auth-react/introduction)

- [ ] supertokens-website documentation update
   - [ ] In progress [PR]()
   - [ ] Deployed to [test site](https://test.supertokens.io/docs/website/introduction)

- [ ] community documentation update
   - [ ] In progress [PR]()
   - [ ] Deployed to test site

- [ ] website changes (test.supertokens.io)
   - [ ] homepage
   - [ ] pricing page feature list
   - [ ] comparison chart in the pricing page

- [ ] Checked for broken links


## 🔥 Production 

### 💻 NPM and core release

 - [ ] [supertokens-core:X.Y](https://github.com/supertokens/supertokens-core/tree/X.Y)
    - Docker update
       - [ ] MySQL
       - [ ] Postgres
       - [ ] MongoDB
    - [ ] try.supertokens.io
    - [ ] Update SaaS config
 - [ ] [supertokens-node:X.Y](https://github.com/supertokens/supertokens-node/tree/X.Y)
 - [ ] [supertokens-website:X.Y](https://github.com/supertokens/supertokens-website/tree/X.Y)
 - [ ] [supertokens-auth-react:X.Y](https://github.com/supertokens/supertokens-auth-react/tree/X.Y)

### 🔀 Others

- [supertokens-demo-react:master](https://github.com/supertokens/supertokens-demo-react/tree/master)
   - [ ] Updated [PR]()
   - [ ] Deployed to actual demo sites

- [supertokens-auth-react:master](https://github.com/supertokens/supertokens-auth-react/tree/master)
   - [ ] Update examples to use latest `supertokens-node` and `supertokens-auth-react`

- [next.js:canary](https://github.com/vercel/next.js/tree/canary)
   - [ ] Update `with-supertokens` examples to use latest `supertokens-node` and `supertokens-auth-react`

- RedwoodJS
   - [ ] Update `redwood core` to use latest `supertokens-node` and `supertokens-auth-react`
   - [ ] Update `playground-auth` to use latest `supertokens-node` and `supertokens-auth-react`

### 📚 Documentation

- [ ] Pushed to production