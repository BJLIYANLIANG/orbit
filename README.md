# Planet Express

**WIP branch for a Twitter-like demo using Orbit and IPFS**

## Run

```
git clone -b tests https://github.com/haadcode/orbit.git
cd orbit/
npm install
rm -rf node_modules/ipfs/node_modules/ipfs-api/
rm -rf node_modules/ipfsd-ctl/node_modules/ipfs-api/
npm run electron
```

## Development

#### Requirements

- Node.js v6.x.x
- npm v3.x.x
- g++, gcc, make (for building native modules)
- python 2 (for building, some native modules need it, node-fibers perhaps?)

First start the Electron app:
```
rm -rf client/node_modules/ipfs/node_modules/ipfs-api/
npm run dev:electron
```

Then run the UI development environment:

```
cd client/
npm install
grunt serve
```
