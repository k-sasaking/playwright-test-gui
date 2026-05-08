## testファイル作成
tests/template.spect.tsというファイルを作成する例
```
npx playwright codegen --target=playwright-test -o tests/template.spec.ts
```

## testの実行
```
npx playwright test
```

# ブラウザ表示ありで実行
```
npx playwright test --headed
```

# PlaywrightのGUI画面で実行
```
npx playwright test --ui
```
