# Happy New Year 2026

M?t trang web chúc m?ng n?m m?i 2026 ???c xây d?ng b?ng HTML, CSS, JS thu?n.

## Tính n?ng

- Giao di?n T?t
- Phát nh?c
- Hi?u ?ng hoa r?i
- Phát lì xì
- Xin lì xì qua QR

## Tùy ch?nh

### 1. Thay tin nh?n chúc T?t và lì xì

```javascript
const chucMungMessages = [
  'Chúc m?ng n?m m?i 2026! Chúc b?n m?t n?m tràn ??y ni?m vui.',
  'T?t ??n xuân v?, chúc b?n v?n s? nh? ý, h?nh phúc viên mãn.',
];

const lixiMessages = [
  'Mình xin lì xì nhé.',
  'Xin 10k nhé.',
];
```

### 2. C?u hình QR Code xin lì xì

```javascript
const filePathQR = './assets/qr/qr.jpg';
const showQR = true;
const hasQR = showQR ? Math.random() < 0.4 : false;
```

### 3. Thay nh?c n?n

Trong file `index.html`, b?n có th? thay ???ng d?n file nh?c:

```html
<source src="./assets/audio/nhuhoamuaxuan-wrenEvans.mp3" type="audio/mp3" />
```

## Deploy web

Có th? deploy web b?ng nhi?u cách khác nhau nh? GitHub Pages, Netlify, Vercel, Render,...

# tet
# tet2026
# 2026tet

