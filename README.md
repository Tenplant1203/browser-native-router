# Mini router

ブラウザ標準APIでSPAルーティングを再設計する、実験的なReact Routerです。

このプロジェクトは、React Routerを置き換えるproduction-readyなライブラリではありません。  
React + Vite + TypeScriptを使って小さなRouterを自作し、Navigation APIやView Transition APIをSPA Routerにどう接続できるかを検証するための技術実験です。

## Limitations

このプロジェクトはproduction-readyなRouterではありません。

現時点では、以下は未対応または簡易実装です。

- nested routes
- advanced route ranking
- cache invalidation
- SSR
- route pathからの高度な型推論
- production-grade accessibility
- full cross-browser testing
- npm package化
- scroll restoration
- form submission handling
- advanced Navigation API integration

## Future Work

今後試したいことは以下です。

- Navigation Inspectorの改善
- error boundary support
- loader cache
- nested routes
- React Activityとの連携
- React Canary ViewTransitionの検証
- Speculation Rules APIとの連携
- cross-browser behaviorの検証
- scroll restoration
- route-level cache invalidation
