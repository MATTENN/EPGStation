# これはなに

- 宗教上の理由でどうしてもWindowsでEPGStationを使いたいケースに対応するためのフォークです
- Windows Server 2025 + Node.js v18.20.5 での動作確認をしています
```
> git clone https://github.com/MATTENN/EPGStation
> cd ./EPGStation
> npm run all-install
> set NODE_OPTIONS=--openssl-legacy-provider
> npm run build

```