# Netherlands-trees# 🌳 Holenderskie Drzewka

Nowoczesny responsywny Landing Page dla firmy zajmującej się sprzedażą i importem drzewek holenderskich.

Projekt został przygotowany jako ćwiczenie frontendowe z wykorzystaniem HTML5, CSS3 oraz Responsive Web Design.

---

## 🎯 Cel projektu

Celem projektu jest stworzenie profesjonalnej strony internetowej prezentującej ofertę drzewek holenderskich wraz z nowoczesnym interfejsem użytkownika oraz pełną responsywnością.

Projekt bazuje na przygotowanym projekcie UI/UX i odwzorowuje rzeczywisty proces współpracy Frontend Developera z Grafikiem (UI Designerem).

---

## 🖥️ Widoki

### Desktop

Rozdzielczość projektowa:

1280px+

### Tablet

Breakpoint:

992px

### Mobile

Breakpoint:

768px

---

## 🏗️ Struktura projektu

```text
holenderskie-drzewka/

│
├── index.html
│
├── css/
│   ├── reset.css
│   ├── variables.css
│   ├── layout.css
│   ├── components.css
│   ├── sections.css
│   └── responsive.css
│
├── assets/
│   ├── images/
│   ├── icons/
│   └── logo/
│
├── js/
│   └── main.js
│
└── README.md
```

---

## 📐 Layout strony

Kolejność sekcji:

```text
Navbar

Hero

Statystyki

O Nas

Oferta

Galeria

Proces Współpracy

Opinie Klientów

CTA

Footer
```

---

## 🎨 Design System

### Font

Poppins

Wagi:

```text
300
400
500
600
700
```

### Kolory

```css
--primary: #2e7d32;
--primary-dark: #1b5e20;
--secondary: #8bc34a;

--text: #1f2937;
--text-light: #6b7280;

--background: #ffffff;
--background-light: #f8faf8;

--border: #e5e7eb;
```

---

## 🔠 Typografia

### H1

```css
font-size: 64px;
font-weight: 700;
line-height: 1.1;
```

Użycie:

Hero Section

---

### H2

```css
font-size: 42px;
font-weight: 700;
line-height: 1.2;
```

Użycie:

Nagłówki sekcji

---

### H3

```css
font-size: 24px;
font-weight: 600;
```

Użycie:

Nagłówki kart

---

### Body Large

```css
font-size: 18px;
font-weight: 400;
```

Użycie:

Opisy sekcji

---

### Body

```css
font-size: 16px;
font-weight: 400;
```

Użycie:

Standardowa treść

---

## 📦 Container

```css
max-width: 1280px;
margin: 0 auto;
padding-inline: 32px;
```

---

## 📏 Spacing System

W projekcie używamy wyłącznie:

```text
4px
8px
12px
16px
24px
32px
48px
64px
80px
120px
```

---

## 🔘 Przyciski

### Primary Button

```css
padding: 16px 32px;
border-radius: 12px;

background: #2e7d32;
color: #ffffff;

font-size: 16px;
font-weight: 600;
```

Hover:

```css
background: #1b5e20;
transform: translateY(-2px);
```

---

## 🃏 Karty

### Border Radius

```css
20px
```

### Shadow

```css
0 10px 30px rgba(0,0,0,.08);
```

### Padding

```css
24px
```

---

## 📱 Responsywność

### Tablet

```css
@media (max-width: 992px);
```

Zmiany:

- Hero → 1 kolumna
- Oferta → 2 kolumny
- Statystyki → 2 kolumny
- Footer → 2 kolumny

---

### Mobile

```css
@media (max-width: 768px);
```

Zmiany:

- Hero → 1 kolumna
- Oferta → 1 kolumna
- Statystyki → 1 kolumna
- Proces → 1 kolumna
- Galeria → 1 kolumna

---

## 🚀 Technologie

Projekt należy wykonać przy użyciu:

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Mobile First
- JavaScript (opcjonalnie)

---

## 📚 Zadania do wykonania

### Etap 1

- [ ] Stworzenie struktury HTML
- [ ] Przygotowanie folderów projektu
- [ ] Implementacja Design System

### Etap 2

- [ ] Navbar
- [ ] Hero Section
- [ ] Statystyki
- [ ] O nas

### Etap 3

- [ ] Oferta
- [ ] Galeria
- [ ] Proces współpracy

### Etap 4

- [ ] Opinie klientów
- [ ] CTA
- [ ] Footer

### Etap 5

- [ ] Responsywność
- [ ] Animacje
- [ ] Optymalizacja

---

## 🏁 Efekt końcowy

Po ukończeniu projektu użytkownik powinien otrzymać:

- Profesjonalny Landing Page
- Wynik Google Lighthouse powyżej 90
- Pełną responsywność
- Semantyczny HTML
- Czysty i skalowalny CSS
- Strukturę gotową do migracji na React / Next.js

```

```
