# nextjs-tailwind-turborepo-setting

## How to start

```shell
git clone https://github.com/brightchul/nextjs-tailwind-turborepo-setting.git
cd nextjs-tailwind-turborepo-setting

yarn install
turbo build
turbo dev
```

## Directories

- apps/admin
- apps/web
- apps/workshop : storybook
- packages/eslint-config-custom
- packages/tailwind-config : tailwind 관련 설정 및 DS 색상 설정 등
- packages/tsconfig
- packages/ui
```
.
├── README.md
├── apps
│   ├── admin
│   ├── web
│   └── workshop
├── node_modules
├── package.json
├── packages
│   ├── eslint-config-custom
│   ├── tailwind-config
│   ├── tsconfig
│   └── ui
├── turbo.json
└── yarn.lock
```