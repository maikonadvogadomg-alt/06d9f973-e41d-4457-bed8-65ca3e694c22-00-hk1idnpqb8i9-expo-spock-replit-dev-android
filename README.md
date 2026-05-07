# 06d9f973-e41d-4457-bed8-65ca3e694c22-00-hk1idnpqb8i9.expo.spock.replit.dev — Projeto Android (Capacitor)

## Origem
URL: https://06d9f973-e41d-4457-bed8-65ca3e694c22-00-hk1idnpqb8i9.expo.spock.replit.dev/

## Estrutura
```
├── dist/           ← Arquivos do PWA (já embutidos)
├── android/        ← Projeto Android Studio
│   ├── app/
│   │   └── src/main/
│   ├── build.gradle
│   └── settings.gradle
├── capacitor.config.ts
└── README.md
```

## Como compilar o APK

### Requisitos
- Android Studio (https://developer.android.com/studio)
- Java 17+
- Android SDK 34

### Passo a passo
1. Extraia este ZIP
2. Abra o Android Studio → File → Open → pasta `android/`
3. Aguarde Gradle sync (~5 min na primeira vez)
4. **Build → Build Bundle(s)/APK(s) → Build APK(s)**
5. APK gerado: `android/app/build/outputs/apk/debug/app-debug.apk`

### Para instalar no celular
- Configurações → Segurança → Fontes desconhecidas ✓
- Transfira o .apk e abra para instalar

### Para assinar (Google Play)
- Build → Generate Signed Bundle/APK
- Crie um keystore e guarde em segurança

## Configuração
- **Package:** `com.06d9f973.e41d.4457.bed8.65ca3e694c22.00.hk1idnpqb8i9.expo.spock.replit.dev`
- **Versão:** 1.0.0 (code: 1)
- **Min SDK:** Android 22+
- **Orientação:** portrait
