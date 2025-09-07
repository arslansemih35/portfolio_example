# 3D Portfolio Website

Modern, responsive ve interaktif 3D portfolyo websitesi. Glassmorphism tasarım trendi, dinamik animasyonlar ve gelişmiş kullanıcı deneyimi sunar.

## 🎨 Özellikler

### Tasarım
- **Modern Glassmorphism UI** - Cam efekti ve backdrop blur
- **Gradient Renk Paleti** - Cyan, Magenta ve Yellow vurguları
- **Responsive Tasarım** - Mobil, tablet ve masaüstü uyumlu
- **Dark Theme** - Göz yormayan koyu tema

### Animasyonlar & Etkileşimler
- **Smooth Scrolling** - Yumuşak sayfa geçişleri
- **Hover Efektleri** - Interactive hover animasyonları
- **Loading Animation** - Sayfa yükleme animasyonu
- **Parallax Effects** - Derinlik hissi yaratan efektler
- **Custom Cursor** - Masaüstü için özel imleç (1024px+)
- **Ripple Animations** - Tıklama dalgaları

### İçerik Bölümleri
- **Hero Section** - Ana başlık ve CTA butonu
- **Portfolio Grid** - 6 farklı proje kategorisi
- **About Section** - Kişisel hikaye ve yetenekler
- **Contact Form** - İletişim formu ve sosyal medya
- **Footer** - Sosyal medya linkleri

### Teknik Özellikler
- **Vanilla JavaScript** - Framework kullanmadan
- **CSS Grid & Flexbox** - Modern layout sistemleri
- **CSS Custom Properties** - Dinamik renk yönetimi
- **Intersection Observer** - Performanslı scroll animasyonları
- **RequestAnimationFrame** - Smooth animasyonlar

## 📱 Responsive Breakpoints

```css
/* Mobil */
@media (max-width: 768px)

/* Tablet */
@media (min-width: 768px) and (max-width: 1024px)

/* Masaüstü */
@media (min-width: 1024px)

/* Küçük telefonlar */
@media (max-width: 480px)

/* Büyük ekranlar */
@media (min-width: 1400px)
```

## 🎯 Portfolyo Kategorileri

1. **Mimari Görselleştirme** - 3ds Max, V-Ray, AutoCAD, Lumion
2. **Oyun Karakterleri** - Blender, ZBrush, Substance Painter, Maya
3. **Ürün Tasarımı** - SolidWorks, KeyShot, Fusion 360, Rhino
4. **VFX & Animasyon** - Cinema 4D, After Effects, Houdini, Nuke
5. **Sanat & Heykel** - ZBrush, Mudbox, Blender, Marvelous Designer
6. **AR/VR Deneyimleri** - Unity, Unreal Engine, Oculus SDK, WebXR

## 🚀 Kurulum

1. **Dosyaları İndirin**
   ```bash
   git clone https://github.com/kullaniciadi/3d-portfolio-website.git
   cd 3d-portfolio-website
   ```

2. **Tarayıcıda Açın**
   - `3d_portfolio_site.html` dosyasını çift tıklayın
   - Veya live server kullanın (VS Code Live Server, Python SimpleHTTPServer vb.)

3. **Özelleştirme**
   - CSS değişkenlerini düzenleyerek renkleri değiştirin
   - İçeriği kendi bilgilerinizle güncelleyin
   - Portfolyo projelerini ekleyin/çıkarın

## 🎨 Renk Paleti

```css
:root {
    --primary-cyan: #00ffff;
    --primary-magenta: #ff00ff;
    --primary-yellow: #ffff00;
    --bg-dark: #0c0c0c;
    --bg-secondary: #1a1a2e;
    --bg-tertiary: #16213e;
    --text-primary: #ffffff;
    --text-secondary: #cccccc;
    --text-muted: #888888;
}
```

## 📝 Özelleştirme

### İçerik Değiştirme
1. **Kişisel Bilgiler** - Hero section'daki başlık ve açıklamayı güncelleyin
2. **Portfolyo Projeleri** - `.portfolio-item` elementlerini düzenleyin
3. **Yetenekler** - About section'daki skill kartlarını güncelleyin
4. **İletişim** - Footer'daki sosyal medya linklerini ekleyin

### Renk Teması
```css
/* Yeni renk teması örneği */
:root {
    --primary-cyan: #00d4aa;
    --primary-magenta: #ff6b9d;
    --primary-yellow: #feca57;
}
```

### Animasyon Hızı
```css
:root {
    --transition-smooth: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    --transition-bounce: all 0.5s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}
```

## 🔧 JavaScript Özellikleri

- **Mobil Menü** - Hamburger menü ve overlay
- **Smooth Scrolling** - Navbar linkleri için
- **Form Handling** - İletişim formu gönderimi
- **Parçacık Sistemi** - Arka plan animasyonları
- **Performance Optimizasyonu** - Düşük performanslı cihazlar için

## 📊 Performance

- **Lighthouse Skoru**: 90+ (Performance, Accessibility, Best Practices)
- **Mobil Uyumlu**: ✅
- **SEO Optimized**: ✅
- **Accessibility**: ✅

## 🌐 Tarayıcı Desteği

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+
- Mobile Safari iOS 12+
- Chrome Mobile 70+

## 📱 Mobil Özellikler

- Touch-friendly interface
- Optimized animations
- Reduced particle count
- Simplified interactions
- Portrait/landscape support

## 🎭 Animasyon Detayları

### CSS Keyframes
```css
@keyframes float {
    0%, 100% { transform: translate(0, 0) rotate(0deg); }
    33% { transform: translate(30px, -30px) rotate(1deg); }
    66% { transform: translate(-20px, 20px) rotate(-1deg); }
}

@keyframes gradientShift {
    0%, 100% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
}
```

### JavaScript Animasyonları
- RequestAnimationFrame kullanımı
- Intersection Observer API
- Custom easing functions
- Performance optimizations

## 🔍 SEO & Accessibility

- Semantic HTML5 elements
- ARIA labels
- Alt text for images
- Keyboard navigation
- Focus management
- Screen reader support

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Kendi projelerinizde özgürce kullanabilirsiniz.

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Commit yapın (`git commit -m 'Add amazing feature'`)
4. Branch'i push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

## 📞 İletişim

- **Email**: contact@3dportfolio.com
- **LinkedIn**: [Profile Link]
- **Portfolio**: [Website Link]

## 🎯 TODO

- [ ] Dark/Light mode toggle
- [ ] Çoklu dil desteği (TR/EN)
- [ ] Blog section ekleme
- [ ] CMS entegrasyonu
- [ ] PWA support
- [ ] WebGL 3D elements

---

**Not**: Bu bir demo/template projesidir. Gerçek bir portfolyo için içerik ve iletişim bilgileri güncellenmelidir.