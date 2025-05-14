# How to Download and Run the Space Shooter Game

## English Instructions

### Option 1: Using Git
1. Open terminal/command prompt
2. Run the following commands:
```bash
git clone <repository-url>
cd space-shooter
npm install
npm run dev
```
3. Open http://localhost:3000 in your browser

### Option 2: Manual Download
1. Download all project files and maintain the following structure:
```
space-shooter/
├── public/
├── src/
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   └── tailwind.css
│   ├── components/
│   │   ├── GameCanvas.tsx
│   │   └── GameMenu.tsx
│   └── lib/
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── tsconfig.json
```
2. Open terminal in the project folder
3. Run:
```bash
npm install
npm run dev
```
4. Open http://localhost:3000 in your browser

## Polish Instructions (Instrukcje po polsku)

### Opcja 1: Używając Git
1. Otwórz terminal/wiersz poleceń
2. Wykonaj następujące polecenia:
```bash
git clone <repository-url>
cd space-shooter
npm install
npm run dev
```
3. Otwórz http://localhost:3000 w przeglądarce

### Opcja 2: Pobieranie ręczne
1. Pobierz wszystkie pliki projektu i zachowaj następującą strukturę:
```
space-shooter/
├── public/
├── src/
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   └── tailwind.css
│   ├── components/
│   │   ├── GameCanvas.tsx
│   │   └── GameMenu.tsx
│   └── lib/
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── tsconfig.json
```
2. Otwórz terminal w folderze projektu
3. Wykonaj:
```bash
npm install
npm run dev
```
4. Otwórz http://localhost:3000 w przeglądarce

## Required Dependencies / Wymagane zależności
All dependencies are listed in package.json and will be installed automatically when running `npm install`.
Wszystkie zależności są wymienione w package.json i zostaną zainstalowane automatycznie po uruchomieniu `npm install`.
