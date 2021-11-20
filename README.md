# try-pnpm

Try pnpm

## tl;dr

    pnpm install
    pnpm start

## Installing pnpm

If you don't have pnpm installed locally then following [installation
guide](https://pnpm.io/installation). You may need to clean out previous
installs

    brew uninstall yarn
    npm uninstall -g yarn pnpm

And then install with corepack

    npm install -g corepack
    corepack enable
    corepack prepare pnpm@6.22.2 --activate
